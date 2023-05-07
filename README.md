Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-3
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>A min-max problem.For <em>n </em>∈ N<sup>+</sup>, determine</li>

</ol>

<em>,</em>

where the minimum is taken over all <em>a<sub>i </sub></em>∈ R and <em>a</em><sub>0 </sub>6= 0.

<ol>

 <li>Imitate the proof of Chebyshev Theorem.</li>

</ol>

Let <em>a &gt; </em>1 and denote.

Define

<em>,</em>

where <em>T<sub>n </sub></em>is the Chebyshev polynomial of degree <em>n</em>. Clearly ˆ . Define the <em>max-norm </em>of a function <em>f </em>: R → R as

k<em>f</em>k<sub>∞ </sub>=        max |<em>f</em>(<em>x</em>)|<em>.</em>

<em>x</em>∈[−1<em>,</em>1] Prove

<em>,             </em>k<em>p</em>ˆ<em><sub>n</sub></em>(<em>x</em>)k<sub>∞ </sub>≤ k<em>p</em>k<sub>∞</sub><em>.</em>

Problems I and II weigh 4 and 6 points, respectively. There is no extra-credit problem for this homework.

The three programming assignments in the next section weigh 10, 5, and 5 points, respectively. The total number of points is thus 30.

<h1>2           C++ programming</h1>

<ul>

 <li>Implement the Newton formula in a subroutine thatproduces the value of the interpolation polynomial <em>p<sub>n</sub></em>(<em>f</em>;<em>x</em><sub>0</sub><em>,x</em><sub>1</sub><em>,…,x<sub>n</sub></em>;<em>x</em>) at any real <em>x</em>, where <em>n </em>∈ N<sup>+</sup>, <em>x</em><sup>0</sup><em><sub>i</sub>s </em>are distinct, and <em>f </em>is a function assumed to be available in the form of a subroutine.</li>

 <li>Run your routine on the function</li>

</ul>

for <em>x </em>∈ [−5<em>,</em>5] using, and <em>n </em>= 2<em>,</em>4<em>,</em>6<em>,</em>8. Plot the polynomials against the exact function to reproduce the plot in the notes that illustrate the Runge phenomenon.

<ul>

 <li>Reuse your subroutine of Newton interpolation to perform Chebyshev interpolation for the function</li>

</ul>

for <em>x </em>∈ [−1<em>,</em>1] on the zeros of Chebyshev polynomials <em>T<sub>n </sub></em>with <em>n </em>= 5<em>,</em>10<em>,</em>15<em>,</em>20. Clearly the Runge function <em>f</em>(<em>x</em>) is a scaled version of the function in (b). Plot the interpolating polynomials against the exact function to observe that the Chebyshev interpolation is free of the wide oscillations in the previous homework