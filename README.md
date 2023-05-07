Download Link: https://assignmentchef.com/product/solved-mast30025-lab-12
<br>
<ol>

 <li>The following data were collected, to compare two treatments. The treatments were randomlyassigned to test subjects.</li>

</ol>

<table width="246">

 <tbody>

  <tr>

   <td colspan="2" width="131">treatment 1</td>

   <td colspan="2" width="115">treatment 2</td>

  </tr>

  <tr>

   <td width="66">subject</td>

   <td width="65">response</td>

   <td width="58">subject</td>

   <td width="57">response</td>

  </tr>

  <tr>

   <td width="66">10</td>

   <td width="65">7.5</td>

   <td width="58">11</td>

   <td width="57">9.5</td>

  </tr>

  <tr>

   <td width="66">9</td>

   <td width="65">9.6</td>

   <td width="58">6</td>

   <td width="57">9.7</td>

  </tr>

  <tr>

   <td width="66">5</td>

   <td width="65">8.4</td>

   <td width="58">2</td>

   <td width="57">10.8</td>

  </tr>

  <tr>

   <td width="66">12</td>

   <td width="65">10.6</td>

   <td width="58">8</td>

   <td width="57">11.9</td>

  </tr>

  <tr>

   <td width="66">7</td>

   <td width="65">9.9</td>

   <td width="58">4</td>

   <td width="57">10.0</td>

  </tr>

  <tr>

   <td width="66">1</td>

   <td width="65">10.6</td>

   <td width="58">3</td>

   <td width="57">12.9</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Estimate the difference between treatment effects, and test if it is significantly different from</li>

</ul>

0.

<ul>

 <li>Now suppose that it is discovered that the response can be affected by the season, and thatthe data was collected over a period of six months, in the order given by the table. That is, a month was spent collecting each row of the table.</li>

</ul>

We re-express the experiment by blocking: each month (row of the table) is considered one block, and we model the data as an additive two-factor model (the factors being the treatment and the block). Using this model, repeat your analysis. Is the estimate different? Is the <em>p</em>-value different?

<ol start="2">

 <li>In lectures, we showed that for the (randomised) complete block design</li>

</ol>

<em>y</em><em>ij </em>= <em>µ </em>+ <em>β</em><em>i </em>+ <em>τ</em><em>j </em>+ <em>ε</em><em>ij,</em>

<ul>

 <li>solution to the reduced normal equations for <em>τ </em>= (<em>τ</em><sub>1</sub><em>,…,τ<sub>k</sub></em>)<em><sup>T </sup></em>is given by</li>

</ul>

(¯<em>y</em><sub>·1 </sub>− <em>y</em>¯<sub>··</sub><em>,…,y</em>¯<sub>·<em>k </em></sub>− <em>y</em>¯<sub>··</sub>)<em><sup>T</sup>.</em>

Here we suppose that we have <em>b </em>blocks and <em>k </em>treatments.

Consider now the completely randomised design, with <em>k </em>treatments and <em>b </em>replications of each treatment <em>y</em><em>ij </em>= <em>µ </em>+ <em>τ</em><em>i </em>+ <em>ε</em><em>ij.</em>

Treating <em>µ </em>as a nuisance parameter, obtain the reduced normal equations for <em>τ</em>, then show that they admit the solution

(¯<em>y</em><sub>1 </sub>− <em>y</em>¯<sub>·</sub><em>,…,y</em>¯<em><sub>k </sub></em>− <em>y</em>¯<sub>·</sub>)<em><sup>T</sup>.</em>

<ol start="3">

 <li>Suppose we have a (randomised) complete block design, <em>y<sub>ij </sub></em>= <em>µ </em>+ <em>β<sub>i </sub></em>+ <em>τ<sub>j </sub></em>+ <em>ε<sub>ij</sub></em>, with <em>b </em>blocks and <em>k </em></li>

</ol>

Let <strong>c</strong><em><sup>T </sup></em>be a treatment contrast, so that <strong>c</strong><em><sup>T</sup></em><em>τ </em>is estimable, in which case

<em>.</em>

<ul>

 <li>Give an approximate 100(1−<em>α</em>)% CI for <strong>c</strong><em><sup>T</sup></em><em>τ</em>, using the percentage point from a normal rather than the correct percentage point from a <em>t </em> (This is reasonable if the degrees of freedom are large.)</li>

 <li>Now suppose that you know <em>σ</em><sup>2 </sup>(perhaps you have an estimate from a pilot study), and that you think a plausible alternative to <strong>c</strong><em><sup>T</sup></em><em>τ </em>= 0 is given by some <strong>c</strong><em><sup>T</sup></em><em>τ</em><sup>∗ </sup>6= 0. How large should <em>b </em>be to give a power of 100(1 − <em>α</em>)% against this alternative (roughly)?</li>

</ul>

<ol start="4">

 <li>Consider the following data:</li>

</ol>

<table width="195">

 <tbody>

  <tr>

   <td width="70">Response</td>

   <td width="49">Block</td>

   <td width="76">Treatment</td>

  </tr>

  <tr>

   <td width="70">1.245</td>

   <td width="49">1</td>

   <td width="76">1</td>

  </tr>

  <tr>

   <td width="70">1.804</td>

   <td width="49">1</td>

   <td width="76">2</td>

  </tr>

  <tr>

   <td width="70">2.468</td>

   <td width="49">2</td>

   <td width="76">1</td>

  </tr>

  <tr>

   <td width="70">6.664</td>

   <td width="49">2</td>

   <td width="76">3</td>

  </tr>

  <tr>

   <td width="70">5.573</td>

   <td width="49">3</td>

   <td width="76">1</td>

  </tr>

  <tr>

   <td width="70">-0.560</td>

   <td width="49">3</td>

   <td width="76">4</td>

  </tr>

  <tr>

   <td width="70">7.880</td>

   <td width="49">4</td>

   <td width="76">2</td>

  </tr>

  <tr>

   <td width="70">10.469</td>

   <td width="49">4</td>

   <td width="76">3</td>

  </tr>

  <tr>

   <td width="70">0.457</td>

   <td width="49">5</td>

   <td width="76">2</td>

  </tr>

  <tr>

   <td width="70">-3.621</td>

   <td width="49">5</td>

   <td width="76">4</td>

  </tr>

  <tr>

   <td width="70">-4.291</td>

   <td width="49">6</td>

   <td width="76">3</td>

  </tr>

  <tr>

   <td width="70">-9.384</td>

   <td width="49">6</td>

   <td width="76">4</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Show that this data comes from a balanced incomplete block design, and give <em>t</em>, <em>b</em>, <em>k</em>, <em>r </em>and <em>λ</em>.</li>

 <li>Give the design matrix <em>X<sup>A </sup></em>for a model with block and treatment effects (and an overall</li>

</ul>

mean).

<ul>

 <li>Using this model, estimate <em>τ</em><sub>1 </sub>−<em>τ</em><sub>2</sub>, the difference between the first two treatment effects, and its variance. Write the variance estimate as <em>s</em><sup>2</sup><strong>c</strong><em><sup>T</sup></em>(<em>X<sup>AT</sup>X<sup>A</sup></em>)<em><sup>c</sup></em><strong>c </strong>for a suitable <strong>c</strong>.</li>

 <li>Give the design matrix <em>X<sup>B </sup></em>for a model with just treatment effects (and an overall mean).</li>

 <li>Using this model, estimate <em>τ</em><sub>1 </sub>−<em>τ</em><sub>2</sub>, the difference between the first two treatment effects, and its variance. Write the variance estimate as <em>s</em><sup>2</sup><strong>c</strong><em><sup>T</sup></em>(<em>X<sup>BT</sup>X<sup>B</sup></em>)<em><sup>c</sup></em><strong>c </strong>for a suitable <strong>c</strong>.</li>

 <li>Show that when going from model A (BIBD) to model B (CRD) the term <strong>c</strong><em><sup>T</sup></em>(<em>X<sup>T</sup>X</em>)<em><sup>c</sup></em><strong>c </strong>decreases, but <em>s</em><sup>2 </sup>increases markedly. What does this indicate?</li>

 <li>Is your estimate for <em>τ</em><sub>1 </sub>− <em>τ</em><sub>2 </sub>the same or different for the two models? Why?</li>

</ul>

<ol start="5">

 <li>Consider the BIBD model, with <em>t </em>treatments and <em>b </em>blocks of size <em>k</em>. Let <em>λ </em>be the number of times each pair appears, and write the design as</li>

</ol>

<strong>y</strong><em>.</em>

Show that for this model, contrasts in <em>τ </em>are estimable.

If <strong>c</strong><em><sup>T</sup></em><em>τ </em>is a contrast, show that an unbiased estimate is (<em>k/λt</em>)<strong>c</strong><em><sup>T</sup></em><strong>q</strong>, where

<strong>q</strong><strong>b</strong>

and <strong>t </strong>are the treatment totals and <strong>b </strong>the block totals.

<ol start="6">

 <li>An experimenter is tasked with designing an experiment to compare three treatment levels. Thereis a known confounding factor, so a blocked design is appropriate. Consider the following two designs, each using four blocks of size three:</li>

</ol>

block 1:      1      2      3

block 2:      2      1      3

Design 1

block 3:      1      3      2

block 4:      3      2      1

block 1:      1      1      2

block 2:      2      2      3

Design 2

block 3:      3      3      1

block 4:      1      2      3

<ul>

 <li>Which design is a complete block design?</li>

 <li>Write down the design matrix for each design. Hence show that <em>τ</em><sub>2 </sub>− <em>τ</em><sub>1 </sub>is estimable in each case.</li>

 <li>For each design, in terms of the unknown error variance <em>σ</em><sup>2</sup>, what is the variance of the estimator for <em>τ</em><sub>2 </sub>− <em>τ</em><sub>1</sub>, the difference between the first two treatment effects?</li>

</ul>

Based on this, which design is better?

<ol start="7">

 <li>In some situations, it is sensible to think of block effects as random. For example, experimentsperformed on a single day might be considered as a single block, subject to some effect for conditions on that day.</li>

</ol>

Consider the following model for an experiment with fixed treatment effects <em>τ </em>and random block effects <em>β </em>(independent of the error <em>ε</em>):

<strong>y </strong>= <em>X</em><sub>1</sub><em>β </em>+ <em>X</em><sub>2</sub><em>τ </em>+ <em>ε, </em>E<em>ε </em>= <strong>0</strong><em>,                      </em>Var <em>ε </em>= <em>σ</em><sup>2</sup><em>I, </em>E<em>β </em>= <em>µ</em><strong>1</strong><em>,               </em>Var <em>β </em>= <em>σ<sub>β</sub></em><sup>2</sup><em>I.</em>

<ul>

 <li>Find E<strong>y </strong>and <em>V </em>= Var <strong>y</strong>.</li>

 <li>Give a solution to the generalised least squares problem:</li>

</ul>

min(<strong>y </strong>− <em>X</em><sub>2</sub><strong>t</strong>)<em><sup>T</sup>V </em><sup>−1</sup>(<strong>y </strong>− <em>X</em><sub>2</sub><strong>t</strong>)<em>. </em><strong>t</strong>

<ul>

 <li>A problem with the generalised least squares above is that <em>µ </em>may not be zero, so that if we write <strong>y </strong>= <em>X</em><sub>2</sub><em>τ </em>+ <em>ε</em><sup>0</sup>, then <em>ε</em><sup>0 </sup>= <em>ε </em>+ <em>X</em><sub>1</sub><em>β </em>does not have a zero mean. To get around this, first suppose that each block is of size <em>k</em>, so</li>

</ul>

<em> ,</em>

then suppose that <em>U </em>is such that

Put <strong>y</strong><sub>1 </sub>= <em>U<sup>T</sup></em><strong>y </strong>and <strong>y</strong><strong>y</strong>, then show that we can write them as linear models whose errors have mean zero.

<ul>

 <li>Show that Cov(<strong>y</strong><sub>1</sub><em>,</em><strong>y</strong><sub>2</sub>) = E(<strong>y</strong><sub>1 </sub>− E<strong>y</strong><sub>1</sub>)(<strong>y</strong><sub>2 </sub>− E<strong>y</strong><sub>2</sub>)<em><sup>T </sup></em>= 0.</li>

</ul>