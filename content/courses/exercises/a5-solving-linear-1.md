---
title: Solving Linear Equations 1
description: Solving basic linear equations
slug: linear-equation-1

date: 2021-01-12 16:19:44.120 +0800
lastmod: 2021-01-12 16:19:44.120 +0800

toc: false
type: docs
math: true

tags:
  - algebra
  - polynomial
  - AC Year 8
  - AC Year 9

menu:
  exc:
    name: Linear Equations 1
    parent: Algebra
    weight: 51

weight: 51
---

In this exercise, you will practise how to solve simple linear equations; for example, $$ \text{solve}~2x + 1 = 9. $$

Use the panel below to create randomised questions. You can click each question to reveal its answer, or click "Reveal All Answers" button to see all answers.

{{< exercise-html >}}
<input type="checkbox" id="neg0" />
<label for="neg0">Allow negative numbers and roots [ex. $x - 5 = -7$] </label><br />
<input type="checkbox" id="frac0" />
<label for="frac0">Allow fractional roots [ex. $3x + 1 = 2$] </label><br />
<input type="checkbox" id="frac1" />
<label for="frac1">Allow fractional numbers and coefficients [ex. $\frac{1}{2}x + 1 = \frac{5}{2}$] </label><br />
<input type="checkbox" id="both" />
<label for="both">Allow the unknown to be on both sides [ex. $2x+3 = x+5$] </label><br />
<br>
{{< /exercise-html >}}

{{< exercise-script >}}

<script>
  function genQs() {
    // Question area
    const qbox = document.getElementById("questions");
    const qinst = document.getElementById("instructions");
    // Read value from the form
    const nq = document.getElementById("nq").value;
    let neg0,frac0,frac1,both;
    [neg0,frac0,frac1,both] = 
      ["neg0","frac0","frac1","both"].map(isChecked);
    // Sanity check
    nqIsNumber = /[\d+]/.test(nq);
    if (!nqIsNumber || nq<1 || nq>10 ) {
      qbox.innerHTML = "Error: Invalid number of questions!";
      return;
    }
    // Coefficients
    const maxCoeff = 9;
    const poolCoeff = arange(1, maxCoeff);
    const poolAns = arange(0, maxCoeff);
    if (neg0) {
      poolCoeff.push(...arange(-maxCoeff, -1));
      poolAns.push(...arange(-maxCoeff, -1));
    }
    const poolLett = 'abcdefghijkmnpqrstuvwxyz'.split('');
    // Make questions
    qinst.innerHTML = "Solve the following linear equations.";
    qbox.innerHTML = "";
    for (let i = 0; i < nq; i++) {
      const lett = choice(poolLett);
      const ans = new Frac(choice(poolAns), frac0? choice(poolAns,"z") : 1);
      let lhs = new Poly([0, ans.d], lett);
      let rhs = ans.mult(ans.d);
      const op1 = new Frac(choice(poolAns, "z"), frac1? choice(poolAns, "z") : 1);
      const op2 = new Frac(choice(poolAns), frac1? choice(poolAns, "z") : 1);

      lhs = lhs.mult(op1).add(op2);
      rhs = rhs.mult(op1).add(op2);

      if (both) {
        const generator = () => new Frac(choice(poolAns), frac1? choice(poolAns, "z") : 1);
        const poly2 = new Poly(genCoeffs(1, generator, 1), lett);
        lhs = lhs.add(poly2);
        rhs = poly2.add(rhs);
      }
      
      const qTex = `${lhs.tex()} = ${rhs.tex()}`;
      const aTex = `\\boldsymbol{\\iff ${lett}=${ans.tex()}}`;
      render(qTex, aTex).then((li) => {
        qbox.appendChild(li);
      });
    }
    return;
  }
</script>