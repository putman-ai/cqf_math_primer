# CQF
I've wanted to sit for the CQF since I first became aware of it in the mid-2000's.  
Something always got in the way though and I just never got around to it.  I was also a little  
concerned about the math portion and some of the programming requirments.  

Fast forward to 2023: I've spent many years in the Numerai Data Science competition and   
my coding and math skills are a lot better.

I have unfortunately had to put it on hold again for family reasons. But, I feel like I've got my foot  
in the door and who knows, maybe when I'm 60 I can hang this on the backside of my signature.

![Description of the image](https://github.com/putman-ai/cqf_math_primer/blob/main/cqf.png)

## CQF Math Primer (No Answers)

I know for many people this level of math is pretty easy. I'm not going to lie though, this test was difficult for me!  
At 57, it's been a long time since I worked on traditional math and I struggled to get through this.  
I spent a lot of time before and during the test brushing up and clarifying.  

Please note this doc is likely full of errors. I'm only fair with LaTeX to begin with (I'm not a doc writer),  
and what I had locally, did not want to render on Github in a web environment. 

Final score 22 of 26.

![Description of the image](https://github.com/putman-ai/cqf_math_primer/blob/main/cqf_math_primer.PNG)

## Question 1
### Second Order Derivative
The second order derivative $\frac{d^2 f}{dx^2} \text{ of } f(x) = x \exp(-x)$

Possible answers:
1. $e^{-x}(x^2 - 1)$
2. $e^{-x}(x - 1)$
3. $f(x) + 2e^{-x}$ 
4. $f(x) - 2e^{-x}$
5. $f(x) - e^{-x}$


## Question 2
### Combining First and Second Deriviatives.
Given $y = \ln |1-x|$ find an expression for $\frac{dy}{dx} + x\frac{d^2 y}{dx^2}$

Possible answers:
1. $\frac{1}{(1-x)}$
2. $-\frac{1}{(1-x)^2}$
3. $\frac{x}{(1-x)^2}$
4. $(1-x)$
5. $\frac{1}{(1-x^2)^2}$


## Question 3
### Limiting Problem: Cubic Derivative
What is the value of the limiting problem  
$$\lim_{h \to 0} \frac{{(x+h)^3 - x^3}}{{h}}$$

Possible answers:
1. $0$
2. $\infty$
3. $-\infty$
4. $3x^2$
5. None of these are correct


## Question 4
### Limiting Problem: Limit of function as x approaches 0 from the right side.
Calculate:  
$$\lim_{x > 0} \frac{{2x+\sin x}}{{x(x-1)}}$$

Possible answers:
1. $\infty$
2. $0$
3. $2$
4. $1$
5. $-3$


## Question 5
### Evaluating an improper integral with an exponential function.

Calculate:

If $I = \int_{0}^{\infty} x \exp(-x^2) \,dx$, then $I =$

Possible answers:
1. $0$
2. $\infty$
3. $-2$
4. $-\frac{1}{2}$
5. $\frac{1}{2}$


## Question 6

Evaluate the integral $\int_{0}^{1} \frac{dx}{x^2+3x+2}$

Possible answers:
1. $\ln \frac{2}{3}$
2. $\infty$
3. $0$
4. $-\ln \frac{3}{4}$
5. $\frac{3}{4}$


## Question 7

What is the $n^{th}$ order term in the Tayolr series expansion of the function $f(x) = \exp x$ about $x = -3$

Possible answers:
1. $\frac{e^{-3}}{n!}(x+3)^n$

2. $\frac{e^{-3}}{2^n} \frac{(x+3)^n}{n!}$

3. $\frac{e}{2^{n+1}} \frac{(x-3)^{n+1}}{(n+1)!}$

4. $\frac{e^{-3}}{2^{n}} \frac{(x+3)^{n-1}}{n!}$

5. $\frac{e^{-3}}{2^n} \frac{(x-3)^{n-1}}{(n-1)!}$


## Question 8
Given the Taylor series for  
$$\frac{1}{1+x} = 1 - x + x^2 - x^3 +... = \sum_{n=0}^{\infty} (-1)^n x^n$$  

Obtain the series for  
$\ln(1+x)$

Possible answers:
1. $$\sum_{n=0}^{\infty} n^2(-1)^{n-1} x^{n-1} $$
2. $$\sum_{n=0}^{\infty} (-1)^{n+1} (n+1)x $$
3. $$\sum_{n=0}^{\infty} (-1)^n \frac{x^{n+1}}{n+1} $$ 
4. $$\sum_{n=0}^{\infty} (-1)^{n-1} \frac{x^{n+1}}{n+1} $$
5. $$\sum_{n=0}^{\infty} (-1)^n \frac{x^{n-1}}{n-1} $$


## Question 9
 
Let $X$ be a continuous random variable with distribution:  
$$
p(x) =
\begin{cases} 
      k(1-x^3) & 0 \leq x \leq 1 \\
      0 & \text{otherwise}
\end{cases}
$$

Possible solutions:
1. $\frac{3}{4}$

2. $-\frac{4}{3}$

3. $\frac{4}{3}$

4. $\frac{3}{2}$

5. $2$


## Question 10

Consider the probability density function (PDF)
$$
p(x) =
\begin{cases} 
      \frac{3}{4}(1-x^2) & 0 \leq x \leq 1 \\
      0 & \text{otherwise}
\end{cases}
$$  

Which a random variable $X$ follows.  
Find the probability that $0 \leq X \leq \frac{1}{2}$


Possible solutions:
1. $\frac{3}{32}$

2. $\frac{9}{32}$

3. $\frac{12}{88}$

4. $\frac{1}{8}$

5. $\frac{11}{32}$


## Question 11

Let $X$ be a normally distributed random variable with mean $\mu = 4$ and standard deviation $\sigma = 2$. If $E[X]$ denotes the expectation of $X$, then the value of $E[X^2]$ is:

1. 16
2. 20
3. 4
4. 2
5. 3


## Question 12
A random variable is uniformly distributed over $[0;1]$: What is the skew?

Possible answers:
1. 3
2. None of those listed
3. 6
4. 2
5. 4


## Question 13
A normally distributed random variable with mean $\mu$ has a probability density function given by:

$$
\frac{\gamma}{\sqrt{2 \pi \sigma}} \exp \left( -\frac{\gamma^2}{\sigma} \frac{(x-\mu)^2}{2} \right)
$$

It's standard deviation is given by:

1. $\frac{\gamma^2}{\sigma}$

2. $\frac{\sigma}{\gamma}$

3. $\frac{\sqrt{\sigma}}{\gamma}$

4. $\frac{\gamma}{\sqrt{\sigma}}$

5. $\frac{\sqrt{\sigma}}{2\gamma}$


## Question 14
if $f(x,y) = x^2 - 4xy + y^3 + 4y$, the sum $fxx + fyy$ is given by:

Possible answers:
1. $2 - 6y$
2. $0$
3. $2x + 4$
4. $-4(x+y)$
5. None of the above


## Question 15
Obtain the solution to the differential equation:  
$\frac{dy}{dx} = \frac{1+y^2}{1+x^2}$

Possible answers:
1. $\frac{Cx}{1-Cx}$

2. $\frac{Cx}{1+Cx}$

3. $\frac{C-x}{1-Cx}$

4. $\frac{1-Cx}{x+C}$

5. $\frac{x+C}{1-Cx}$


## Question 16
Solve the first order differential equation:

$\frac{dy}{dx} - xy = x$

Possible answers:
1. $A\exp(-\frac{1}{2}x^2)$

2. $\exp(-\frac{1}{2}x^2) - 1$

3. $\exp(\frac{1}{2}x^2) - A$

4. $A\exp(\frac{1}{2}x^2) - 1$

5. $A\exp(\frac{1}{4}x^2) - 1$


# Question 17

Solve $y'' - 4y' + 13y = 0 \text{ to obtain } y =$

Possible answers:  

1. $e^{2x}(A \cos 3x + B \sin 3x)$
2. $e^{3x} \{A \cos 2x + B \sin 2x\}$
3. $Ae^{2x} + Be^{3x}$
4. $e^{3x}(A +Bx)$
5. $e^{2x}(A + Bx)$


# Question 18

Solve $x^2y'' - 4xy' + 6y = 0 \text{ to obtain } y =$

Possible solutions:
1. $e^{2x}(A \cos 3x + B \sin 3x)$
2. $Ax^2 + Bx^3$
3. $x^2(A + B\ln x)$
4. $x^3(A + B\ln x)$
5. $x^2(A \cos(3\ln x) + B\sin(3\ln x))$


## Question 19

Determine those values of $k$ for which

$$
\det\begin{bmatrix}
k & k \\
8 & 4k
\end{bmatrix} = 0
$$

Possible answers:
1. 0 &amp; 2
2. 2 &amp; 4
3. 0 &amp; -2
4. -2 &amp; 4
5. There is no solution.

## Question 20

Consider the following problem:  

$$
\begin{array}{lcl}
2x + y - z & = & 1 \\
x - 2z & = & -5 \\
x - 2y + 3z & = & 6
\end{array}
$$

What are the values of $x$, $y$ &amp; $z$ in turn?

1. A solution does not exist

2.
$$
\begin{bmatrix}
   \begin{aligned}
    x = 0\\
    y = 0\\
    z = 0
  \end{aligned}
\end{bmatrix}
$$

3.
$$
\begin{bmatrix}
   \begin{aligned}
   x = 1 \\
   y = 2 \\
   z = 3 \\
   \end{aligned}
\end{bmatrix}
$$

4.
$$
\begin{bmatrix}
   \begin{aligned}
   x = -1\\
   y = 0\\
   z = 2
   \end{aligned}
\end{bmatrix}
$$

6. There are seveal solutions.


## Question 21

Obtain the determinate of the matrix

$$
\begin{pmatrix}
   2 & 0 & 1\\
   3 & 2 & -3\\
   -1 & -3 & 5
\end{pmatrix}
$$

To refer specifically to the determinate of the matrix rewrite as:  

$$  
\det\begin{vmatrix}
      2 & 0 & 1\\
      3 & 2 & -3\\
      -1 & -3 & 5
\end{vmatrix}
$$

Possible solutions:
1. 0
2. -5
3. Does not exist
4. 10
5. 24


## Question 22
Consider the vectors  

$$
\mathbf{u} = (-1, 0, k), \quad \mathbf{v} = (6, -4, 2)
$$  

What is the value of $k$ for which the two vectors are orthogonal.

Possible answers:
1. 0
2. 2
3. 3
4. $\frac{1}{2}$

5. They can never be orthogonal


## Question 23

If $x = 2 -3i$ is a complex number, then its size is

1. $\sqrt{13}$
2. $\sqrt{5i}$
3. 3
4. 2
5. $\sqrt{\frac{2}{3}}$


## Question 24

Consider the function: 

$$ 
f(x,y) = x^2+y^2 \text{ where } x = \sin 2 \theta \text{ and } y = \cos 2 \theta \frac{df}{d\theta} 
$$ 

is given by:

1. 1
2. 0
3. 2
4. -1
5. None of those given


## Question 25
Givent the matrix 

$$  
\begin{pmatrix}
      2 & 2\\
      1 & 3
\end{pmatrix}
$$ 

the value of the largest eigenvalue is:

Possible answers:
1. 4
2. 1
3. -1
4. -4
5. The eigenvalues are complex


## Question 26

Evaluate
$\int_{-2}^{1} |x|dx$

Possible answers:
1. $\frac{1}{2}$

2. $-\frac{1}{2}$

3. $\frac{3}{2}$

4. $-\frac{5}{2}$

5. $\frac{5}{2}$

