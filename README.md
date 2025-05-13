# cs-se4x03-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS-SE4X03 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs-se4x03-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92460&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS-SE4X03 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 1&nbsp; Solve the system

3 4 3x1 10 1 5 −1x2=7 637×3 15

using Gaussian elimination • without pivoting

• with partial pivoting

Show all steps. In your calculations, you can carry four digits after the decimal point, and

a nonzero digit before the decimal point.

Problem 2 [3 points] Consider the linear system

􏰀 1 1+ε􏰁􏰀x1􏰁 􏰀1+(1+ε)ε􏰁 1−ε1x=1.

The exact solution is x = [1,ε]T for any value of ε. Solve this system in Matlab with various values for ε, especially for values near √εmach.

• For each value of ε you try, compute the condition number of the matrix and the relative error in each component of the solution. Submit in the PDF results for 4 different values of ε in the form

ε |x1 − 1| |x2 − ε|/ε cond(A) .

• What conclusions can you draw from this experiment?

Problem 3

(a) [2,3,1 points] Implement in Matlab the following functions:

<pre>         function B = GE(A)
</pre>
performs LU factorization of an n × n matrix A without pivoting and stores the L and U factors in the output B. U is stored in the upper-triangular part of B. The diagonal of L is not stored, and the part of L below the main diagonal is stored below the main diagonal of B. For example, for a 3 × 3 matrix A, B is

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
u11 u12 l21 u22 l31 l32

2

</div>
<div class="column">
u13  u23 u33

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>         function [B, ipivot] = GEPP(A)
</pre>
performs LU factorization with partial pivoting. The L and U factors are stored in the output B as in GE. ipivot is permutation of the vector 1:n recording the row permutations. When computing the LU factorization you must not swap rows in memory.

function x = backward(B, b, ipivot)

performs backward substitution. B contains the L and U factors as computed by

GE or GEPP; ipivot is an index vector storing row permutations. b is an n-vector. Then you can solve a linear system Ax = b as

<pre>    [B,ipivot] = GEPP(A);
    x=backward(B,b,ipivot);
</pre>
Store these functions in files GE.m, GEPP.m, and backward.m. (b) [2 points] Write a main program main_ge.m that

<ul>
<li>generates an n × n random matrix A and vector x of ones</li>
<li>computes b = Ax</li>
<li>solves Ax = b using Gauss elimination with and without partial pivoting and with Matlab’s A\b</li>
<li>produces output in the format

A\b no pivoting pivoting cond(A)</li>
</ul>
1 7.3e-13 6.5e-11 6.2e-13 1.9e+04

The first column is experiment number, the next three columns are the relative errors in the solutions computed with A\b, Gauss elimination without pivoting, and with pivoting, respectively. The last column is the condition number of A.

(c) [2 points] Generate a table for 5 systems with matrices of size 2000 × 2000 each.

(d) [2 points] How do the condition numbers relate to the accuracy of the computed solu-

</div>
</div>
<div class="layoutArea">
<div class="column">
tions?

Submit

• PDF: the Matlab files, table, (d) • Avenue: the Matlab files

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 4 [4 points] You have to interpolate ex by a polynomial of degree five using equally spaced points in [0, 1]. What error would you expect if you use this polynomial?

Using equally spaced points, what degree polynomial would you use to achieve a maxi- mum error of 10−8?

Problem 5 [5 points] You are given the data points

xi 0 0.1 0.2 0.3

yi 1.0000 1.0488 1.0954 1.1402 whereyi ≈√xi +1,i=0,1,2,3.

√√

a. (2 points) Using these data calculate approximations for 0.05 and 0.15 b. (2 points) Derive a bound for the error in these approximations.

c. (1 point) How does it compare to the actual errors?

Problem 6 [4 points] Let f(x) = |x| where x ∈ [−1,1]. Use the polyfit function to interpolate f (x) at 21 equally spaced points −1 = x0 &lt; x1 &lt; · · · x20 = 1. Denote the interpolating polynomial by p(x).

(a) Plot on the same plot f(x) and p(x) versus x at 41 equally spaced points in [−1,1]. (b) Plot the error |f (x) − p(x)| versus x at these points.

(c) Repeat (a) and (b), but now use Chebyshev points for the interpolation.

Submit

• PDF: the four plots

Problem 7 [3 points] Redo Problem 6, with f(x) = sin(x) and interval [−π,π].

Explain the differences in the errors when interpolating |x| and sin(x).

</div>
</div>
</div>
</div>
