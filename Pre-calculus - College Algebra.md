## Introduction to Functions

What is a function?
	A function is a relationship that maps 1 input ($x$-values) to 1 output ($y$ or $f(x)$ values).

In a functional relationship, an input **NEVER** gives more than 1 output (this is so that we ca graph it easily).
$$y=f(x)$$
- $x$ or whatever you plug in the function is the *independent* variable (input = independent).
- $y$ or whatever come out of the function is the *dependent* variable (it depends on the input).

We can graph them as $(x,y)$ or $(x,f(x))$.

Let's look at an example, in a job, you get paid as much as you "work". In this case, we quantitatively look at "work" by the no. of hours you put in:
![[Pasted image 20240806121045.png]]
Work hrs. is the independent variable (no. of hours translate to pay)
- the set of our *input* (work hrs: $\{25,53,30,40\}$) is called a **Domain**.
- the set of our *output* (pay: $\{500, 310, 490\}$) is called a **Range**.

We can determine if this is a function, if for any $1$ input you can only get $1$ output from it. Thus, our example is a functional relationship.
	Don't get this confused with the [[#One-to-One Functions|one-to-one function]], which is when you input $1$ number and get out $1$ unique number. This example is not a *one-to-one* functional relationship as both $30$ hrs. and $40$ hrs. output $490$ dollars pay, which is not a unique output.

![[Pasted image 20240806121803.png]]
Say at 30 work hrs. and, depending on the boss' mood, you get either $490 or $310. That is not dependable. You don't know what you're gonna get for the amount of work. This is NOT a functional relationship (a non-function), since 1 input gives more than 1 outputs.

### Examples

Let's look at another example:$$S=\{(-2,16),(-1,4),(0,3),(1,4)\}$$This is a functional relationship:
- Each element in the domain (the $x$'s) are unique.
- There are some duplicate ($4$) in the range but that's okay.
$$R=\{(-2,5),(3,9),(5,0),(-2,6)\}$$This is not a functional relationship:
- There are duplicate elements in the domain ($-2$), and they give out different output $((-2,5),(-2,6))$.

Let's look at the example in algebraic form:
We can easily see that below equation is a function (1 input => 1 output)$$y=-7x+5$$Now, with things like $x^2$  or $\sqrt{x}$, suspicion may arise since we clearly are dealing with more than 1 $x$. The key question here is that if you plug in 1 input ($x$ or $-x$), do you get only 1 input? Looking at the below equation, let consider cases with $x=3$ and $x=-3$
$$y=2x^2$$
1. $x=3$
$$y=2(3)^2$$$$y=18$$
2. $x=-3$
$$y=2(-3)^2$$$$y=18$$
Now, it does not matter that both output equal $18$. The important thing here is that you plug in 1 thing and it output 1 thing. Thus, $y=2x^2$ is a function.

The above equations are conveniently arranged in a way that we can easily see if it is a function or not ($y = something$). 
$$2x-4y=8$$For this case, we might have to re-arrange a little bit.$$2x-8=4y$$$$y=\frac{2x-8}{4}$$$$y=\frac{1}{2}x-2$$
Below equation is NOT a function. Notice how the notation make it so that whatever 1 input you're plugging in, you will get 2 outputs.
$$y=\pm\sqrt{3-2x}$$

Consider this problem:$$y^2=x$$
Instinctively, I'd say we put a sqrt on both sides:$$y=\sqrt{x}$$And we're good to go! This is a function. **NO! THIS IS WRONG.**
When a sqrt (or other even roots) is given to you in a question, it is fine. But when you are solving it yourself you should put a $\pm$ sign to maintain the idea that when you square a number, whether it is positive or negative, you get a positive number out of it. So:$$y=\pm \sqrt{x}$$Now we can see that this is clearly NOT a function. So the point to rmb here is: whenever you put a sqrt on the paper **yourself**, put a $\pm$ sign.

Consider this:$$2x^2+3y^2=1$$Ask yourself this, for solving this $y$ will you have to take a sqrt? $$y=\pm \sqrt{-\frac{2}{3}x^2+\frac1{3}}$$YES, so this is not a function.

Next:$$xy+2y=3x-1$$Will we have to take a sqrt for this? $$y=\frac{3x-1}{x+2}$$No, so this is a function.

Next:
$$x^2-4y^2=1$$
Will we have to take a sqrt for this? $$y=\pm \sqrt{\frac{x^2}{4}-\frac{1}{4}}$$Yes, so this is a function.

## How to Evaluate Functions

$y=-7x+5$ or $f(x)=-7x+5$
- above refer to the same thing
- why we prefer the $f(x)$ notation?
	- there's no ambiguity (it's like having 2 guys named Jim)
	- it is more descriptive (tells you what is dependent and independent variable)

Evaluate for $x=2$ means to plug in $2$ as $x$ into the function:
$y=-7(2)+5$
$y=-9$
OR
$f(2)=-7(2)+5$
$f(2)=-9$
	See how, with the below notation, we don't lose the input value so we can easily write it as ordered pair very easily: $(2,-9)$.

Next example:$$h(x)=-2x^2+x-1$$Eval. $h(-1)$:
$h(-1)=-2(-1)^2+(-1)-1$
$h(-1)=-2-1-1=4$
As ordered pair: $(-1,4)$

Eval. $h(-x)$:
$h(-x)=-2(-x)^2+(-x)+1$
$h(-x)=-2x-x+1=-3x+1$
As ordered pair: $(-x, -3x+1)$
Note: Even functions and Odd functions ([[#Properties of Functions - Even vs Odd|we'll talk about this later]]). Refer to this expression $h(x)=-2x^2+x-1$
- if every signs is the same with $-x$ e.g. $f(-x)=-2x^2+x-1$, we have an **even function**
- if every signs is the opposite with $-x$ e.g. $f(-x)= 2x^2-x+1$, we have an **odd function**
- if it is a combination of the two, you have neither.

Eval. $h(x+1)$
$h(x+1)=-2(x+1)^2+(x+1)-1$
$h(x+1)=-2(x^2+2x+1)+(x+1)-1$
$h(x+1)=-2x^2-4x-2+x+1-1=-2x^2-3x-2$
As ordered pair: $(x+1, -2x^2+3x-2)$

Next example:$$f(x)=\sqrt{x^2-3x}$$Eval. $f(5)$
$f(5)=\sqrt{(5)^2-3(5)}$
$f(5)=\sqrt{10}$
As OP: $(5,\sqrt{10})$

Eval. $f(0)$
$f(0)=\sqrt{(0)^2-3(0)}$
$f(0)=0$
As OP: $(0,0)$

Eval $f(2x)$
$f(2x)=\sqrt{(2x)^2-3(2x)}$
$f(2x)=\sqrt{4x^2-6x}$
As OP: $(2x,\sqrt{4x^2-6x})$

Eval $f(x+h)$
$f(x+h)=\sqrt{(x+h)^2+3(x+h)}$
$f(x+h)=\sqrt{x^2+2xh+h^2+3x+3h}$
As OP: $(x+h,\sqrt{x^2+2xh+h^2+3x+3h})$

Eval $f(1)$
$f(1)=\sqrt{(1)^2-3(1)}$
$f(1)=\sqrt{-2}$
Now that is a problem. This is not possible over real number ($\sqrt{-2}$ is not a real number). This show that not every number is possible to plug in to every function. This is called a *domain issue*. 
- every number that output a negative sqrt (this issue would not hold with cubic root) is a problem number, since it falls outside of the domain.

Next example:$$g(x)=\frac{2x+1}{x-5}$$
Eval $g(0)$
$g(0)=\frac{2(0)+1}{(0)-5}$
$g(0)=\frac{1}{-5}$
As OP: $(0,\frac{1}{-5})$

Eval $g(x^2)$
$g(x^2)=\frac{2(x^2)+1}{(x^2)-5}$
As OP: $(x^{2}, \frac{2x^2+1}{x^2-5})$

Eval $g(5)$
$g(5)=\frac{2(5)+1}{5-5}$
$g(5)=\frac{11}{0}$
Division by 0, which is an undefined number. This is a *domain issue*.

Eval $-g(x)$
$-g(x)=-\frac{2x+1}{x-5}$
This is done. You can distribute the $-1$ to the numerator or denominator, but not both (since it would be $\frac{-1}{-1}$ which is just $1$).

### Difference Quotient

See this:$$f(x)=x^2+1$$$$\frac{f(x+h)-f(x)}{h}$$
- See here that there is a *difference* between $f(x+h)$ and $f(x)$ (which are just 2 output values)
- Quotient just means dividing one quantity by another (in this case by $h$, which is added to $x$ in the 1st term of numerator)

![[Pasted image 20240806170253.png]]
- notice how this is pretty much rise/run or the rate of change on a graph ($\frac{y_2-y_1}{x_2-x_1}$)
The $\frac{f(x+h)-f(x)}{h}$ just gives a relationship on a slope of a line.

Whenever we see this, our main goal is to find the output of $f(x+h)$, then $f(x)$, then try to get rid of the denominator ($h$).

Let's eval. $f(x+h)$:
$f(x+h)=(x+h)^2+1$
$f(x+h)=x^2+2xh+h^2+1$

We already know $f(x)$.

Now we can replace these in $\frac{f(x+h)-f(x)}{h}$:
$$\frac{(x^2+2xh+h^2+1)-(x^2+1)}{h}$$$$\frac{2xh+h^2}{h}$$$$\frac{h(2x+h)}{h}$$
$$2x+h$$

Now what does $2x+h$ even means?
- rmb that $\frac{f(x+h)-f(x)}{h}$ represents slope between 2 points, $h$ is the distance horizontally between this 2 point
- as $h$ get smaller and smaller (closer and closer to 0), $2x+h$ get closer to $2x$.

![[Pasted image 20240806172403.png]]
## Finding the Domain of Functions

Domain is the set of inputs ($x$) of a function that give a REAL number output (since we are working in $\mathbb{R}$ space).

3 Problems Areas:
1. **Sqrt** ($\sqrt{}$): Inside must be positive
2. **Denominators** ($\frac{}{not 0!}$): should not be zero
3. Logarithms: We'll add on to this later...

We'll focus on the first two:
1st example,
$f(x)=\sqrt{5-4x}$
Since inside should be positive to make sense...
$5-4x\geq 0$
$-4x\ge -5$
$x \le \frac{5}{4}$
	Note: that $\geq$ turned to $\leq$ in this bottom line since we are multiplying/dividing by a negative number on both sides ($-\frac{1}{4}$).
So we have our domain.

2 ways to write this:
- Set notations => $D:\{x|x \leq \frac{5}{4}\}$. This reads $x$ such that ($|$) $x$ is leq to $\frac{5}{4}$
- Interval notation => $(-\infty, \frac{5}{4}]$
	- note: always use bracket with infty
![[Pasted image 20240807230630.png]]

2nd example,
$g(t)=\frac{5t}{t^3-16t}$
We set the denominator to equal $0$
$t^3-16t=0$
Why? Because we want to identify the "bad numbers". In this case, a value of $t$ that would make the denominator equal to $0$.
$t(t^2-16)=0$
$t(t-4)(t+4)=0$
	note: factor $t^2-5$ => $(t-\sqrt{5})(t+\sqrt{5})$
If any of the 3 terms ($t, (t-4), (t+4)$) are equal to $0$, this will cause a true statement. So the number to exclude are $t=0$, $t=4$, $t=-4$.
	This mean that your function will have "holes" in its line.
![[Pasted image 20240807232554.png]]
	This is how the function looks. This introduces the concept of a *vertical asymptotes*. $g(t)$ lines cannot cross an 'invisible barrier' (in this case $4$ and $-4$) and just shoot up or down (in this case, both) to infinity, since at those values the function is not defined.
	**Note:** there are some graphical misrepresentation here as at $t=0$ the point is $(0, undefined)$. So there should be a very very very small hole at that point.

2 ways to write this:
- $D:\{t|$$ All real numbers except $t=0, t=-4, t=4\}$
- $(-\infty,-4)\cup(-4,0)\cup(0,4)\cup(4,\infty)$
	- remember that brackets exclude values.
![[Pasted image 20240807234208.png]]

Recap: notice that we use completely different approach for the two domain issues.
- sqrt: we assume that it wants to be a positive number (greater than 0)
- denominator: Conversely, for this, we look at what it cannot be ($0$). 
### Examples

$$f(x)=3x^2-2x+4$$
Notice that we don't have: sqrt, denominators, logarithm

We can conclude that our domain includes all real numbers. 
- $D:\{x|$ All real numbers $\}$ or
- $(-\infty,\infty)$

$$h(x)=\frac{\sqrt{3x-15}}{x-4}$$
Firstly, the denominator:
$x-4=0$
$x=4$
Note that $x$ can be anything but $4$.

Next, the sqrt:
$3x-15 \geq 0$
$3x \geq 15$
$x \geq 5$
Note that $x$ should be greater than equal to 5.

Since $4$ is already lessor than $5$:
- $D:\{x|x\geq 5\}$
- $[5,\infty)$
![[Pasted image 20240807235131.png]]
Additional example on the same problem:
![[Pasted image 20240807235702.png]]

$$g(x)=\frac{5}{\sqrt{x-8}}$$
Now, the sqrt is in the denominator so both logic must apply here to stay in the domain of real numbers.
$\sqrt{x-8}=0$
$x=8$
Note that $x$ cannot equal to $8$.

We also do not want negative sqrt:
$x-8\geq 0$
$x\geq 8$

So:
- $D:\{x|x\geq 8\}$
- $(8,\infty)$
![[Pasted image 20240807235528.png]]
## Operations of Functions

This section is about adding, subtracting, multiplying, dividing functions and the domain issues that may arise with these operations.

The first thing that we do, we find the domain for each of the function first.$$f(x)=\frac{2x+3}{3x-2}$$$$g(x)=\frac{4x}{3x-2}$$
so for $f(x)$, $x$ cannot equal to $\frac{2}{3}$ and for $g(x)$, x cannot equal to $\frac{2}{3}$.
- so for both functions $D:\{x|x\neq \frac{2}{3}\}$
$$(f+g)(x)=\frac{2x+3}{3x-2} + \frac{4x}{3x-2}$$$$(f+g)(x)=\frac{6x+3}{3x-2}$$ Notice how the very same domain issue would apply to $(f+g)(x)$ (even if we have different denominator, we would still have to find common denominator anyway). So $D:\{x|x\neq \frac{2}{3}\}$.

$$(f-g)(x)=\frac{2x+3}{3x-2}-\frac{4x}{3x-2}$$$$(f-g)(x)=\frac{-2x+3}{3x-2}$$Same thing here. $D:\{x|x\neq \frac{2}{3}\}$.
$$(f\cdot g)(x)=(\frac{2x+3}{3x-2})(\frac{4x}{3x-2})$$$$(f\cdot g)(x)=\frac{8x^2+12x}{(3x-2)^2}$$Once again, same domain issue: $D:\{x|x\neq \frac{2}{3}\}$. Note: Later on this will give us a vertical asymptotes at $\frac{2}{3}$.

If we divide functions, not only we're gonna get the same domain, we could add some new issues to the domain issue each function independently have. 
	Note: with division, it's going to look like we can cancel out stuff and remove the domain issue, but we actually can't. The issue will just be hidden, but it will still be there.
$$(\frac{f}{g})(x)=\frac{\frac{2x+3}{3x-2}}{\frac{4x}{3x-2}}$$$$(\frac{f}{g})(x)=\frac{2x+3}{3x-2} \cdot \frac{3x-2}{4x}$$We can cancel our denominator??? BOOM! BOOM! $$(\frac{f}{g})(x)=\frac{2x+3}{4x}$$So our domain issue($D:\{x|x\neq \frac{2}{3}\}$) is gone? No, not really. Based on our root functions, $x\neq \frac{2}{3}$ still, but it's just hidden (it is very important to rmb where we came from).
	Why? Let's take another look at this part: $(\frac{f}{g})(x)=\frac{2x+3}{3x-2} \cdot \frac{3x-2}{4x}$. If we replace $x$ with $\frac{2}{3}$ in the denominator we get: $(3(\frac{2}{3})-2) \cdot (4(\frac{2}{3}))$. Now we can clearly see that the first term is 0. This is why where we came from are very important.
However, there are new issues added ($4x=0$, so $x \neq 0$). So $D:\{x|x\neq \frac{2}{3} , x\neq 0\}$.
### Another example
$$f(x)=\sqrt{x+3}$$$$g(x)=\frac{5}{x}$$Firstly, we find our domain. 
- For $f(x)$, $x$ must be greater than or equal to $-3$ 
	- $D:\{x|x\geq -3\}$
- For $g(x)$, $x$ cannot be 0.
	- $D:\{x|x\neq 0\}$
- For any operations, we have the combined:
	- $D:\{x|x\geq -3, x\neq 0\}$

$$(f+g)(x)=\sqrt{x+3}+\frac{5}{x}$$
Same domain: $D:\{x|x\geq -3, x\neq 0\}$. $$(f-g)(x)=\sqrt{x+3}-\frac{5}{x}$$Same domain: $D:\{x|x\geq -3, x\neq 0\}$.$$(f\cdot g)(x)=\frac{5\cdot \sqrt{x+3}}{x}$$Same domain: $D:\{x|x\geq -3, x\neq 0\}$.$$(\frac{f}{g})(x)=\frac{\sqrt{x+3}}{\frac{5}{x}}$$$$(\frac{f}{g})(x)=\sqrt{x+3}\cdot\frac{x}{5}$$$$(\frac{f}{g})(x)=\frac{x\sqrt{x+3}}{5}$$Same domain: $D:\{x|x\geq -3, x\neq 0\}$. We may think that $x\neq 0$ no longer applies since $x$ is not in the denominator anymore, but both of our domain issues still apply (in respect to the originating functions).

## Using the Vertical Line Test

*Vertical line test* is used to determine whether the equation or expression is a function or not.
	Rmb: for functions, 1 input gives 1 output.
We can look at it from a graphical point of view with the x-axis being the input-axis and y-axis being the output-axis. ![[Pasted image 20240808124101.png]]
Example 1:
![[Pasted image 20240808124212.png]]
At any given input, we can clearly see that the function give exactly one output using the vertical line test (red dotted line).

Example 2:
![[Pasted image 20240808124326.png]]
Same thing here. There's never a case where we get more than one output for any given input.

Example 3:
![[Pasted image 20240808124420.png]]
For this one, clearly we see that we have 2 output for 1 input. Thus, this is NOT a function.

Example 4:
![[Pasted image 20240808124518.png]]
Same thing here. There's never a case where we get more than one output for any given input.

Example 5:
![[Pasted image 20240808124556.png]]
For this one, clearly we see that we have 2 output for 1 input. Thus, this is NOT a function.

Example 6:
![[Pasted image 20240808124740.png]]
There are infinite amount of output for 1 input. This is a non-function.
## Features of Graphs, Domain, Range

![[Pasted image 20240808172734.png]]
	This is really just about finding points in the graph.

**Find $f(0)$:**
See where $x=0$, and we'll notice that at point $x=0$, $y=5$. So $f(0)=5$

**Find $f(-6)$:**
$f(-6)=0$

**Is $f(3)$ positive or negative?** Ask yourself: is the line above or below the x-axis? Positive.![[Pasted image 20240808173106.png]]

**Is $f(8)$ positive or negative?** Same idea. Negative.

**For what $x$ is $f(x)=0$?** This is really asking: What are the points where the graph intercept the x-axis. From the graph, we can see at $x=-4,6,10$ is $f(x)=0$.

**For what is $x$ is $f(x)>0?$** This is really asking: what interval of x-axis is your graph ABOVE the x-axis? From this, we can see that at $x = (-4,6)\cup (10,11)$ or $-4<x<6$ & $10<x<11$, $f(x)$ is positive. (see the red line)
![[Pasted image 20240808174502.png]]

**For what is $x$ is $f(x)<0?$** Same thing in reverse. From this, we can see that at $x = (-6,-4)\cup (6,10)$ or $-6<x<-4$ & $6<x<10$, $f(x)$ is positive. (see the red line)
![[Pasted image 20240808174534.png]]

**Domain**: 
Graphically, the domain means: what section of the x-axis does my graph covers?
Our graph cover $[-6,11]$ or $\{x|-6\leq x \leq 11\}$
![[Pasted image 20240808174906.png]]
	note: there are some tails before $-6$ and after $11$ but that is purely due to my lack of artistic skills. 

**Range:**
This is a little harder than **Domain** because it doesn't have to be 1-to-1 like in the x-axis. But the same idea is applicable, what section of the y-axis does my graph covers? Our graph cover $[-3,5]$ or $\{y|-3\leq y \leq 5\}$
![[Pasted image 20240808175226.png]]
	Once again, forgive my drawing skills.

**x-intercepts:**
This is a redundant question. $(-4,0), (6,0), (10,0)$.

y-intercepts:
$(0,5)$

```
Note: 
Can a graph has multiple x-intercepts and still be a function? Yes.
Can a graph has multiple y-intercepts and still be a function? No. It will not pass the vertical line test.
```

**How many times does $y=2$ cross the graph?** 2 times.
![[Pasted image 20240808175617.png]]

For what $x$ does $f(x)=3$? At $x=-2,4$, $f(x)=3$.![[Pasted image 20240808175729.png]]

For what $x$ does $f(x)=-3$? At $x=-6,8$, $f(x)=-3$.
![[Pasted image 20240808175905.png]]

### More examples
![[Pasted image 20240808180124.png]]
$D: \{x|-\pi \leq x \leq \pi\}$ or $[-\pi,\pi]$
$R: \{y|-1 \leq x \leq 1\}$ or $[-1,1]$

![[Pasted image 20240808180326.png]]
Notice the arrowhead here. This graph is continuous, meaning that it is defined for all $x$.
$D: \{x|-\infty \leq x \leq \infty\}$ or $(-\infty,\infty)$
Now the lecturer himself say that there are some horizontal asymptotes at 0 (so that the range is not $(-\infty,\infty)$ and that y never reaches 0).
$R: \{y|0 < x \leq \infty\}$ or $(0,\infty)$

![[Pasted image 20240808180807.png]]
Notice the white head at $(4,5)$. This means that the represented point is not included. The domain include $0$ all the way up to $3.9999....$ but never $4$, and the same idea for range.
$D: \{x|0 \leq x < 4\}$ or $[0,4)$
$R: \{y|0 \leq y < 5\}$ or $[0,5)$

![[Pasted image 20240808181221.png]]
Notice the white head at $(7,12)$, arrow head downwards and the vertical asymptotes at 0.
$D: \{x|0 < x < 7\}$ or $(0,7)$
$R: \{y|-\infty < y < 12\}$ or $(-\infty,12)$

Next example:$$f(x)=\frac{x+2}{x-6}$$
1. $f(1)$
$f(1)=\frac{1+2}{1-6}=-\frac{3}{5}$
2. $f(x)=2$, find $x$.
$2=\frac{x+2}{x-6}$
$x=14$
3. **Domain:**
Look at the denominator: $x-6$, so $x$ cannot equal to 6 (to avoid the domain issue).
So $D:\{x|x\neq 6\}$ or $(-\infty,6)\cup (6,\infty)$.
4. **x-intercept**:
All points in this format $(x,0)$ or $f(x)=0$.
$0=\frac{x+2}{x-6}$
$0=x+2$
$x=-2$
So x-intercept(s) are point(s) at: $(-2,0)$
5. **y-intercept**:
All points in this format $(0,y)$ or $f(0)$.
$f(0)=\frac{2}{-6}$
$f(0)=-\frac{1}{3}$
So y-intercept(s) are point(s) at: $(0,-\frac{1}{3})$

Note: the 1st attempt you did this, you confused x-intercept as $f(0)$ and y-intercept $f(x)=0$. That's it, I just find it pleasing to point out your dumb mistakes.

## Properties of Functions - Even vs Odd

```
What even and add means, how it looks graphically, how it translate algebraically, and how to check if a function is even or odd.
```

When a graph is:
- **Even**: Symmetric about the **Y-axis**. It will has a mirror image about y-axis
![[Pasted image 20240809175255.png]]
	symmetric about y-axis
- **Odd**: Symmetric about the **ORIGIN**. If we rotate it 180 degrees, we will have a symmetry.
![[Pasted image 20240809175348.png]]
	If we rotate this 180 degrees, we will still have the same image.
	For more clarity (since odd is a bit harder than even), imagine mirroring about the y-axis once and mirror one more time about the x-axis.
	1. Mirror one side of the graph about the y-axis![[Pasted image 20240809180030.png]]
	2. Mirror that side one more time about the x-axis and we get the original graph, as desired.
	![[Pasted image 20240809180056.png]]
Another example of odd functions (rotate 180 degrees or mirror twice to see!):
![[Pasted image 20240809180316.png]]
 ^a2c181
- **Neither**: neither even nor odd
![[Pasted image 20240809180432.png]]

Why are we learning about this? When we get to graphing polynomials and ,especially, rational functions, even vs odd will tell us a lot about how they look e.g. how they begave with asymptotes, how they behave around x-intercepts.
	Note: I still don't really get why this is important. Learn more and come back to this later. #follow-up 

Now, it's really important to think about input vs output here also. Imagine what caused symmetry in *even* functions:
If our inputs ($x$) are opposites e.g. -1 and 1, -4 and 4, to make the graph symmetrical, both inputs would give the same output ($y$). Same output from opposite inputs.
![[Pasted image 20240809181708.png]]
	See? Opposite $x$s would give the same $y$
So for even functions:$$f(x)=f(-x)$$
Odd functions are different. Opposite inputs ($x$) would get out opposite outputs ($y$).
![[Pasted image 20240809181953.png]]
So for odd functions: $$-f(x)=f(-x)$$This is essentially saying that if we plug in opposite inputs ($x,-x$), we got out opposite outputs ($-y,y$)
	Note: This is also a valid definition: $f(x)=-f(-x)$, but the above equation gives clearer meaning(?)

This is how we check algebraically if the function is even vs odd.

### Examples
To solve these problems we simply evaluate the functions.
$$f(x)=2x^4-x^2$$
What if we input the opposite: $f(-x)=2(-x)^4-(-x)^2$
Since the power of both terms are even, $x$ cannot really end up being negative so: $f(-x)=2x^4-x^2$
So, $f(x)=f(-x)$, this is an *even* function.

$$g(x)=\frac{x}{x^2-1}$$
$g(-x)=\frac{-x}{(-x)^2-1}$
$g(-x)=-\frac{x}{x^2-1}$
$-g(-x)=\frac{x}{x^2-1}$
Just to be super clear and fit in our previous definition, what is $-g(x)$?:
$-g(x)=-\frac{x}{x^2-1}$
So, $-g(x)=g(-x)$ or $g(x)=-g(-x)$, this is an *odd* function.

$$h(x)=3x^3+5$$
$h(-x)=3(-x)^3+5$
$h(-x)=-3x^3+5$
To be super clear:
$-h(x)=-(3x^3+5)=-3x^3-5$
So this function would be *neither*, since neither $h(x)=h(-x)$ nor $-h(x)=h(-x)$ holds.

$$F(x)=\frac{x^2+3}{x^2-1}$$
$F(-x)=\frac{(-x)^2+3}{(-x)^2-1}=\frac{x^2+3}{x^2-1}$
So $F(x)=F(-x)$, this is an *even* function.

$$G(x)=\sqrt{x}$$
$G(-x)=\sqrt{(-x)}$
This is *undefined*, unless $x< 0$, but in that case $g(x)=\sqrt{x}$ would be *undefined* instead. The professor Leonard said that whenever we have a situation like this, it is *neither*, since either one side of $x$ is *undefined* which makes any sort of symmetry impossible.
![[Pasted image 20240809190337.png]]

$$h(x)=\frac{-x^3}{3x^2-9}$$
Let's rewrite $h(x)$ a little first, $h(x)=-\frac{x^3}{3x^2-9}$
$h(-x)=\frac{-(-x)^3}{3(-x)^2-9}=\frac{x^3}{3x^2-9}$
Since $h(-x)=-h(x)$, this is an *odd* function.

## Properties of Functions - Increasing vs Decreasing

Here's what we mean and what to look for: increasing vs decreasing:
- **Increase**: as we're moving from left-to-right, if our input ($x$) is growing, then our output ($y$) is also growing. So, for $x_{1}< x_2$, then $f(x_1)<f(x_2)$. Graphically, it is *climbing*.
- **Decrease**: is just the opposite of increase. So, for $x_{1}< x_2$, then $f(x_1)>f(x_2)$. Graphically, it is *falling*.
All of this is given by **open** intervals on $x$-axis.
	at any particular *endpoint* (e.g. the left-most and right-most black dot), we cannot say it is *climbing* or *falling* because there is no *next* value to compare with.
	![[Pasted image 20240809194751.png]]
Increasing says: tell me the part on x-axis, when you look from left-to-right, that it is *climbing*, and vice versa for decreasing.

Taking a look at some examples:
![[Pasted image 20240809195123.png]]
Inc.: In intervals: $(-2,0)\cup (2,4)$
Dec.: In intervals: $(-4,-2)\cup(0,2)$
Notice how we always use *open intervals* (the brackets notation "$()$") for the increasing and decreasing because *closed intervals* (the square bracket notation "$[]$") **stop** the continuity e.g. at point $x=0$ (called *local max*), the line is neither increasing or decreasing because there is some next point to compare to.

![[Pasted image 20240809195948.png]]
Inc.: $(-1,1)$
Dec.: $(-\infty, -1)\cup(1,\infty)$

![[Pasted image 20240809200155.png]]
Inc.: $(-2,0)\cup(2,\infty)$
Dec.:$(-\infty,-2)\cup(0,2)$

![[Pasted image 20240809200317.png]]
Inc.: $(0,\infty)$
Dec.: None
This graph never really decreases. Even if we keep going right along the x-axis, the rate of increase will slowing down but never stops.

## Properties of Functions - Extrema

What's extrema? What's local, relative, and absolute extrema? Now, we cannot go algebraic with this one until we've learned some calculus.
- **local or relative max**: are the little peak that occurs generally when function changes from *increase -> decrease*. On an *open interval*, $f(x)\leq f(c)$, $c$ is a local max.
- **local or relative min**: are the bottommost point that occur generally when the function changes from *decrease -> increase*. On an *open interval*, $f(x)\geq f(c)$, $c$ is a local min.
Note: local max or min is not "required" in a graph.
Note 2:  local max or min do not include *endpoints* because cannot be on an *open* interval, as it can only be on *closed* interval.

- **absolute max**: highest output on the graph
- **absolute min**: lowest output on the graph
Note: every *closed continuous interval* (notation: $[]$) will guarantee both absolute max and absolute min.

Note: the point itself is NOT local or absolute max or min, it's just where these things occur and it's value is what we're looking for.

Let's look at some examples:
![[Pasted image 20240809231535.png]]
L. Max: $4$ at $(2,4)$
L. Min: $2$ at $(-1,2)$
For absolute max and min, we mostly just compare the endpoints and local max or min and see which one is more extreme.
A. Max: $5$ at $(-4,5)$
A. Min: $1$ at $(5,1)$

![[Pasted image 20240809232124.png]]
L. Max: $5$ at $(3,5)$
L. Min: $-1$ at $(-1,-1)$
A. Max: $5$ at $(3,5)$
A. Min: $-1$ at $(1,-1)$
Here we can see that A.Max can be L.Max and A.Min can be L.Min.

![[Pasted image 20240809232609.png]]
L. Max: None (if point $(3,5)$ is available, it would have been a L.max but it's not.)
L. Min: None (there is no case where the graph go from decrease -> increase)
A. Max: None (if point $(3,5)$ is available, it would have also been an A.max but it's not)
A. Min: $-3$ at $(0,-3)$
This is a case of a discontinuous function.

![[Pasted image 20240809233201.png]]
L. Max: $4$ at $(2,4)$
L. Min: $1$ at $(-1,1)$
A. Max: $4$ at $(2,4)$
It may look like $-\infty$ is the A.min, but A.min has to be found in a point on the graph, which we do not see here.
A. Min: None

![[Pasted image 20240809232329.png]]
L. Max: $5$ at $(0,5)$
L. Min: $0$ at $(-2,0)$ and $1$ at $(3,1)$
A. Max: None
A. Min: $0$ at $(-2,0)$
This is the case where we have more than 1 L.Max and L.Min.

![[Pasted image 20240809233646.png]]
L. Max: None
L. Min: None
A. Max: None
A. Min: None

Let's switch it up a little:
![[Pasted image 20240809233933.png]]
L. Max: 5 at $(-4,5)$
L. Min: None
A. Max: 5 at $(-4,5)$ and $(5,5)$
A. Min: None
A. Max can occurs at 2 seperate (or more) $x$ values.
## Average Rate of Change of a Function

What the average rate of change looks for, is just the slope between 2 points on a curve.
![[Pasted image 20240810163545.png]]
Suppose that we have a curve (here it is $f(x)$), we cannot really find a slope of the curve. 
But we can find the slope *between* 2 points on that curve. This is represented by the red line below aka. *secant line*.
So:
```
the average rate of change of a function between two points is the slope of the secant line connecting those two points
```
![[Pasted image 20240810163822.png]]
The slope of this line is the *average* slope of the curve between those 2 points. So, somewhere between those two points, the slope of the curve between those 2 points will equal the slope of the secant line. 

Now this seems like a poor representation. But what if we keep on pushes back $b$ so that it is so close to $a$:
![[Pasted image 20240810164305.png]]
We can see that, as the interval between a and b get smaller and smaller, we can the *average* rate of change approaches the *instantaneous* rate of change.
```
*Average rate of change* gives a broad view of how the function behaves between two points, while the *instantaneous rate of change* (derivative) gives the exact rate at a specific point.
```

So, the average rate of change is:$$\frac{f(b)-f(a)}{b-a}$$ or (a more familiar one):$$\frac{y_2-y_1}{x_2-x_1}$$This is the same as the slope formula.
	So why do we call this average rate of change? This is to emphasizes that we are looking at **the change in the function's output (i.e., the change in $y$) over an interval of its input (i.e., the change in $x$)**. It's the *average* amount by which the function's value changes per unit increase in the input across that interval.
	...
	While *slope* is technically the same thing (change in $y$ over change in $x$), it is often associated with *straight lines*.

Example:
$f(x)=x^2-2x$ Find the average rate of change from $x=3$ to $x=5$.
So, at $x=3$, we have point $(3,3)$, and at $x=5$, we have point $(5,15)$.
$Avg. R.O.C.=\frac{y_2-y_1}{x_2-x_{1}}=\frac{15-3}{5-3}=6$
We can write the secant line in algebraic form:
$y-y_1=m(x-x_1)$
$y-(3)=6(x-(3))$
$y-3=6x-18$
$y=6x-15$
Let's try graphing this:
![[Pasted image 20240810170518.png]]
## How to Graph Piecewise Functions

What is a piecewise function? Important reminder: for functions, one input put out one output. *Piecewise functions* give you a function in *pieces*, you can only use one piece on certain interval of the x-axis.
$$
f(x) = \begin{cases}
x^3 \text{, } x<1 \\
3x-2\text{, } x\geq1 \\
\end{cases}
$$
See how this function tells you to use $x^3$ when $x < 1$ and use $3x-2$ when $x\geq1$.
Let's try evaluating this function:
$f(-1)$ since $-1<1$ it fits $x^3$, so:
$f(-1)=(-1)^3$ and we get point $(-1,-1)$

$f(0)=(0)^3$ and we get point $(0,0)$

$f(1)$, since $1\geq1$ is true, so:
$f(1)=3(1)-2=1$ and we get point $(1,1)$

$f(3)$, since $3\geq1$ is true, so:
$f(3)=3(3)-2=7$ and we get point $(3,7)$

Let's try drawing this graph:
First, we separate the piecewise function by pieces (separate the $x$ interval).
![[Pasted image 20240810173106.png]]
The blue line is just a visual aid for $x=1$ to see where the separation begins. 
$$
f(x) = \begin{cases}
x^2 \text{, } x<0 \\
2 \text{, } x=0 \\
2x+1 \text{, } x>0 \\
\end{cases}
$$
Evaluate:
$f(-2) = x^2$
$f(-2)=(-2)^2=4$ and we get point $(-2,4)$

$f(0) = 2$ and we get point $(0,2)$

$f(2) = 2x+1$
$f(2)=2(2)+1=5$ and we get point $(2,5)$

Drawing this graph
![[Pasted image 20240810175406.png]]
This is how it looks in Desmos, but this is not such an accurate representation. See at the y-axis, the interval $[1,2]$, this wouldn't be possible for a function where 1 output ($x=0$) must gives 1 input (in this case all values between 1 and 2). So the corrected version would be:
![[Pasted image 20240810175751.png]]
- the green line between 1 and 2 on the y-axis is gone
- added a black point on $x=0$ and white point on the other 2 pieces of the function.
We can see that this is not a *continuous* function (the line is broken).
$$
f(x)=\begin{cases}
x+3 \text{, } -4\leq x<2\\
-2x-3 \text{, } x\geq-2
\end{cases}
$$
Drawing the graph:
![[Pasted image 20240810180759.png]]
	Note: rmb, equal signs means closed point (black point) and no equal signs means open point (white point).
#### Notes on How to Graph Piecewise Functions in Desmos
Windows calculator does not support this, so we have to use Desmos.
For example:
```
f(x)={x<=0:2x+1, 4x-3}
```
This can be extended to additional pieces, where you have {condition 1:expression 1, condition 2:expression 2, … , “otherwise” expression}
## Graphs You Must Know

Memorize these graphs and understand why their shape look the way they do:
**Even Functions (symmetry about the y-axis)**
Characteristics of odd functions:
- Key points: Every even function is going to have $(1,1)$ and $(-1,1)$ in the graph (except for the constant function $f(x)=b$).
$$f(x)=b$$![[Pasted image 20240811123621.png]]
$$f(x)=x^2$$![[Pasted image 20240811131413.png]]
$$f(x)=|x|$$![[Pasted image 20240811131457.png]]
To summarize:
- The first graphs:
	- No $(0,0)$ unless $b=0$ and no $(1,1)$ unless $b=1$ (this is because the coefficient of $x$ is $0$, leaving only $b$, the y-intercept line)
	- Domain is all real number
	- Range is $b$ (one input still give only one output so this is a function)
- The the other two:
	- contains $(1,1)$, $(0,0)$, and $(-1,1)$, which is in line with the even functions characteristic of having symmetry over the y-axis
	- Domain is all real numbers
	- Range is $0$ and all positive numbers

**Neither Functions**
$$f(x)=\sqrt{x}$$![[Pasted image 20240811131741.png]]
We might be tempted to think that $f(x)=\sqrt{x}$ is an even function but since the outputs of all negative inputs would be in the complex number space, it is neither function. ^a26f85

**Odd Functions (Rotation)**
Characteristics of odd functions:
- Key points:
	- Every odd function is going to have $(1,1)$ and $(-1,-1)$ in the graph.
	- Almost all of them have $(0,0)$ (See $f(x)=\frac{1}{x}$, where $x=0$ is *undefined*)
$$f(x)=x$$
![[Pasted image 20240811124530.png]]
$$f(x)=x^3$$
![[Pasted image 20240811124753.png]]
$$f(x)=\sqrt[3]{x}$$
![[Pasted image 20240811125125.png]] ^ca506d
- See how this is a *rotation* of $f(x)=x^3$
$$f(x)=\frac{1}{x}$$
![[Pasted image 20240811125430.png]] ^06affe
- there is a *vertical asymptotes* here because $x=0$ is *undefined* and the factor $x$ (which is on the denominator) cannot be *cancelled out* or *simplified away* (otherwise, we can have an open circle (white point) aka. *removable discontinuity*).
- we also have a *horizontal asymptotes*. Notice how, regardless of our $x$, this function can never output a $0$. $1$ divided by something other than $0$ would never gives $0$.
- This is called a *rational* functions or *reciprocal* function.
	- The reciprocal of a number can be determined by dividing the variable by 1. Similarly, the reciprocal of a function is **determined by dividing 1 by the function's expression**.

To summarize:
- The first 3 graphs:
	- increasing functions
	- Domain is all real numbers
	- Range is all real numbers
- The last one:
	- decreasing functions
	- Domain is all real numbers except $0$
	- Range is all real numbers except $0$
## Introduction to Graph Transformation

What shifts the graph left and right, up and down? What stretches it, compresses it, horizontally and vertically? This section is for understanding how these operations work.

**Vertical**
- $f(x)+k$
	- Shift up: This is going to shift you graph *up* by $k$. 
- $f(x)-k$
	- Shift down: This is going to shift you graph *down* by $k$. 
Let's look at the example of $f(x)=x^2+3$:
- rmb that $x^2$ is a *Parabola*. The "$+3$" means shifting the parabola up along the y-axis by 3 (this $+3$ does not affect the $x$ value at all).
- This is an *even* function.
![[Pasted image 20240811135733.png]]
Now performing the operations $f(x)+k$ and $f(x)-k$. Say for now that $k=2$:
![[Pasted image 20240811135808.png]]

**Horizontal**
- $f(x+h)$
	- Shift left
		- Intuitively, this looks like a shift right since it is a plus sign. But it is not. Everything that happens inside the function's parentheses will be the *opposite* of what your intuition says. See this [[#Analogy for Horizontal Shifting]].
- $f(x-h)$
	- Shift right
Let's look at the example of $f(x)=|x+2|$:![[Pasted image 20240811151436.png]]

More examples:
$$f(x)=(x+1)^3-1$$
- Rmb the $x^3$ [[#^ca506d|graph]], $(x+1)$ means it is left-shifted by $1$
- $-1$ mean the graph is shifted down by $1$
![[Pasted image 20240811152437.png]]![[Pasted image 20240811152524.png]]
$$g(x)=\sqrt{x-2}+3$$
- rmb what the $\sqrt{x}$ graph [[#^a26f85|look like]]
- inside the sqrt, $x-2$ mean it is right shifted and the $+3$ means it is up-shifted by $3$
![[Pasted image 20240811153445.png]]
![[Pasted image 20240811153524.png]]

Next, we're going to talk about stretch & compression, both vertically and horizontally, and reflection:
**Vertical Stretch or Compression**
$$y=a\cdot f(x)$$
This is what stretching and compression means, taking your output value and multiplying it by a value $a$ (similar to *scalar multiplication* in linear algebra):
- stretching means $1 < a$
	- vertical stretch = horizontal compression (making the shape narrower)
- compression means $0<a<1$
	- horizontal stretch = vertical compression (making the shape wider)
For example:$$f(x)=2x^2$$![[Pasted image 20240811163611.png]]
- notice how the orange line is *narrower* (horizontal compressed)
$$f(x)=\frac{1}{2}x^2$$
![[Pasted image 20240811163625.png]]
- notice how the orange line is *wider* (horizontal stretch)

**Horizontal Stretch or Compression**
$$y=f(ax)$$Once again, anything inside of the parentheses is going to go against your intuition. ^9ec6e7
- with $a>1$, the shape is going to be *compressed*
- with $0<a<1$, the shape is going to be *stretched*

For example:$$f(x)=(3x)^2$$
- notice how this is essentially $f(x)=9x^2$, which is the same as vertical stretch (once again, vertical stretch = horizontal compress)
![[Pasted image 20240811163635.png]]
Let's think about our key points:
- $(1,1) \to (\frac{1}{3},1)$
- $(0,0)$
- $(-1,1) \to (-\frac{1}{3},1)$
Notice how for $x$, instead of multiplying by 3, we divide by 3 (the inverse of multiplying). 
	Why? Look at $(1,1) \to (\frac{1}{3},1)$, for example. Since we didn't do anything to $y$, it remains at $1$, but we know that the graph is horizontally compressed, we have to make $x$ reaches that that $y=1$ *faster*.

Here we have a horizontal stretch with the orange line representing $f(x)=(\frac{1}{2}x)^{2}$, and the blue dotted line representing $f(x)=x^{2}$:
![[Pasted image 20240828011746.png]]
Let's think about our key points:
- $(1,1) \to (\frac{1}{\frac{1}{2}},1)\to (2,1)$
- $(0,0)$
- $(-1,1) \to \left(-\frac{1}{\frac{1}{2}},1\right)\to (-2,1)$
Look at $(1,1) \to (\frac{1}{\frac{1}{2}},1)\to (2,1)$. Since we didn't do anything to $y$, it remains at $1$, but we know that the graph is horizontally stretched, we have to make $x$ reaches that that $y=1$ *slower*. 

It's a bit nuanced but that's just how dealing with transformations to input is. See [[#^{2475b3|here]] for a very valuable example in graphing logarithm with a bunch of transformation.

**Reflection**
$$y=-f(x)$$
- this is just changing the sign, making it reflect about the x-axis
 For example:$$f(x)=-\sqrt[3]{x}$$![[Pasted image 20240811163646.png]]
Key points:
- $(1,1) \implies (1,-1)$
- $(0,0) \implies (0,0)$

Next, this is reflection about the *y-axis*:$$y=f(-x)$$
For example:$$f(x)=\sqrt{-x}$$![[Pasted image 20240811163653.png]]
Key points:
- $(1,1) \implies (-1,1)$
- $(0,0) \implies (0,0)$
- $(-1,-1) \implies (1,-1)$

#### Analogy for Horizontal Shifting
Here is the general idea:
Imagine an original graph $f(x)$ of any shape.

We consider the new graph $f(x + 1)$. What new value of $x$ should I put in such that the output is the same? The new input should be $1$ less than the original to produce the same output,

For example:
Originally $x = 5, y = f(5)$
Now to get $f(5)$ with $f(x+1)$, we need $x = 4$
Hence, if you draw it out you can clearly see the graph moving leftwards!

Imagine you're sitting in a movie theater watching a film. The screen represents the function $f(x)$, and the point on the screen where you're currently looking represents the value of $x$.
![[Pasted image 20240811151009.png]]

#### Notes on Multiple-Line Graph Plotting in Python
```python
# plotting f(x)=x^2+3 and f(x)+k and f(x)-k where k=2
def f(x):
    return x**2+3

x_list = np.linspace(-10,10,100)
y_list = f(x_list)
k = 2
y_list_plus_k = f(x_list)+k
y_list_minus_k = f(x_list)-k
#######################################
plt.plot(x_list,y_list,label="f(x)")
plt.plot(x_list,y_list_plus_k,label="f(x)+k",linestyle="dashed")
plt.plot(x_list,y_list_minus_k,label="f(x)-k",linestyle="dashdot")
```
Line styles:
![[Pasted image 20240811135323.png]]
## How to Graph with Transformations

$$f(x)=-\frac{1}{2}|x-3|+2$$
- we know that $|x|$ has a v shape
- the $-3$ inside the absolute means right shifted by 3
- the $-\frac{1}{2}$ means vertical compression, and since it is *negative*, it reflect about the x-axis
- the $+2$ means it is shifted up by $2$

So, regarding our key points:
- $(1,1) \implies (1,-\frac{1}{2})$
	- notice how $x$ is unaffected here since it doesn't have a negative sign directly modifying $x$
- $(0,0) \implies (0,0)$
- $(-1,1) \implies (-1,- \frac{1}{2})$
![[Pasted image 20240811182808.png]]
![[Pasted image 20240811182815.png]]

Next example:$$g(x)=-\frac{1}{3}(x+1)^3-1$$
- rmb the $x^3$ graph
- $-1$ means shifted down by $1$ (vertical shift)
- $+1$ inside the parentheses mean left shifted by $1$ (horizontal shift)
- $-\frac{1}{3}$ means reflection about the x-axis and *vertical compression* or *horizontal stretch* since $0<a<1$ 

Key points:
- $(1,1) \implies (1, - \frac{1}{3})$
- $(0,0)\implies (0,0)$
- $(-1,-1) \implies (-1,\frac{1}{3})$
![[Pasted image 20240811183950.png]]
![[Pasted image 20240811184433.png]]
### Examples
Here's some of the more difficult examples:
$$f(x)=\frac{3}{x-2}+1$$
This is a bit harder to see if this has a shift up down left right, stretch & compression or not? Let's re-write it:
$f(x)=3\cdot \frac{1}{x-2}+1$
Now this is slightly clearer:
- rmb the $\frac{1}{x}$ [[#^06affe|graph]] that we had
- $+1$ means shift up
- $-2$ means shift right
- $3$ is *vertical stretch* or *horizontal compression*
Key points:
- $(1,1) \implies (1,3)$
- $(0,0)$ is *undefined*
- $(-1,-1) \implies (-1,-3)$

![[Pasted image 20240811190011.png]]
![[Pasted image 20240811190441.png]]

Another example:$$g(x)=2\sqrt{1-x}+3$$Rewriting this:
$g(x)=2\cdot \sqrt{-1(x-1)}+3$
- rmb the $\sqrt{x}$ graph
- $+3$ means shift up by $3$
- factor out the $-1$ and the $1$ in sqrt becomes $-1$
- $-1$ directly in front of $x$ would reflect the graph about y-axis (since all $x\implies -x$)
- $2$ means the graph is vertically stretched
Key points:
- $(1,1) \implies (-1,2)$
- $(0,0) \implies (0,0)$

![[Pasted image 20240811191215.png]]
![[Pasted image 20240811192248.png]]
## Introduction to Solving Quadratics

What are we doing? What are quadratics? How to solve quadratics?![[Pasted image 20240812132857.png]]

This is how a quadratic equation generally looks like:$$f(x)=ax^2+bx+c$$- *quadratic* (adj.) means involving the second and no higher power of an unknown quantity or variable.

Notice that $x^2$, which is a parabola. Next, we locate where the function cross the x-axis by setting $f(x)=0$. So:$$ax^2+bx+c=0$$
4 methods (by the order to look for them; easier to harder):
- [[#The Square Root Method in Solving Quadratics|square root method]]
- [[#Using Factoring to Solve Quadratics|factoring]]
- [[#Completing the Square Made Easy|completing the square]]
	- we rarely use this (it takes too much time) to solve quadratic equations but will be valuable in calculus.
- [[#Proving the Quadratic Formula|using the quadratic formula]]
	- $x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
The goal of these methods is to find the x-intercept aka. root of the function.

Let's examine 3 cases of the parabola:
![[Pasted image 20240812134736.png]]
- 2 solutions for $ax^2+bx+c=0$
- 2 REAL solutions (not *imaginary*)
- 2 real x-intercepts

![[Pasted image 20240812135006.png]]
- 1 REAL solution
- 1 x-intercept

![[Pasted image 20240812135122.png]]
- 0 REAL solution ([[#Plotting Complex Functions is Matlab|2 COMPLEX solutions]])
	- if from solving $ax^2+bx+c=0$, we get no real solutions, we've found this type
- No x-intercept
##### Plotting Complex Functions is Matlab
Say:$$f(x)=2x^2+2x+2$$![[Pasted image 20240813155950.png]]
We want to find the x-intercept, which clearly does not exist on the plane that we're looking at above $\mathbb{R}$:
$0=2x^2+2x+2$
$0=2(x^2+x+...)-...+2$
$0=2(x^{2}+x+ \frac{1}{4})- \frac{1}{2}+2$
$0=2(x+ \frac{1}{2})^{2}+ \frac{3}{2}$
$- \frac{3}{4}=(x+\frac{1}{2})^2$
Using the [[#The Square Root Method in Solving Quadratics|sqrt method]]:
$\pm\sqrt{- \frac{3}{4}}=\sqrt{(x+ \frac{1}{2})^{2}}$
$\pm\sqrt{\frac{3}{4}}i=(x+ \frac{1}{2})$
$\frac{1}{2}\pm\frac{\sqrt{3}}{2}i=x$
Now, can see that $x$ is a complex number or $x=a+bi$
![[Pasted image 20240813162220.png]]
- we can kind of see that there are 2 points touching the imaginary part of $x$ plane. $\frac{1}{2}+ \frac{\sqrt{3}}{2}\approx1.37$ and  $\frac{1}{2}- \frac{\sqrt{3}}{2}\approx-0.37$. 
![[Pasted image 20240813163019.png]]
For reference, this is the same graph on real plane with $xlim$ and $ylim$ similar to the 3D plot:
![[Pasted image 20240813162840.png]]
See this [video](https://\frac{www.youtube.com}{watch?v=f8CXG7dS-D0) for Euler's Formula for a great presentation on complex solutions.
## The Square Root Method in Solving Quadratics

Can I find the x-intercept by taking the square root of both sides?
Two important points:
1. Identify when and when we cannot use this method?
	1. Can we get something with a power of 2 on one side e.g. $x^{2}, (x+1)^2$ , and a constant on the other side (without any other $x$'s)? If yes, this method is applicable.
2. Rmb: when we put a square root, put a $\pm$ sign. This matters for our understanding of the graph we're working with (2 solutions instead of 1)

$$f(x)=x^2-18$$
Rearrange and set $f(x)=0$:
$x^2-18=0$
Can we get something with a power of 2 on one side and a constant on the other side? 
$x^2=18$
Yes. So we put a sqrt on both sides:
$\sqrt{x^2}=\pm\sqrt{18}$
$x=\pm3\sqrt{2}$
2 Solutions.
![[Pasted image 20240812140538.png]]

$$f(x)=3x^2-33$$
$3x^2-33=0$
$x^2=11$
The sqrt method is applicable.
$\sqrt{x^2}=\pm\sqrt{11}$
$x=\pm\sqrt{11}$
2 Solutions.
$$g(x)=(x+2)^2-1$$
$(x+2)^2-1=0$
$(x+2)^2=1$
$\sqrt{(x+2)^2}=\pm\sqrt{1}$
$x+2=\pm1$
$x=-2\pm1$
So $x=-1,-3$. 2 Solutions.
$$h(x)=(2x+3)^2-32$$
$(2x+3)^2-32=0$
$(2x+3)^2=32$
$\sqrt{(2x+3)^2}=\pm\sqrt{32}$
$(2x+3)=\pm\sqrt{32}$
$x=\frac{-3\pm4\sqrt{2}}{2}$
$x=\frac{-3}{2}\pm2\sqrt{2}$
2 Solutions. Although they look a bit weird, they are both REAL solutions.
$$f(x)=(x-7)^2$$
$\pm\sqrt{0}=\sqrt{(x-7)^2}$
$\pm0=x-7$
$0$ is an *additive identity*. So both answers would be just the same.
$x=7$
1 Solutions.
![[Pasted image 20240812142143.png]]
$$f(x)=(3x-2)^2+75$$
$(3x-2)^2+75=0$
$(3x-2)^2=-75$
Applicable? Yes.
$\sqrt{(3x-2)^2}=\pm\sqrt{-75}$
Notice that there is clearly an imaginary number on the right side $i = \sqrt{-1}$.
We now know that this is the case with no REAL solutions. We can be done here, but there should be 2 imaginary solutions so let's proceed a little further:
$(3x-2)=\pm5\sqrt{-1\cdot 25\cdot 3}$
$(3x-2)=\pm5i\sqrt{3}$
$x=\frac{2\pm5i\sqrt{3}}{3}$
![[Pasted image 20240812143214.png]]
- See how it does not touch the x-axis.
## Using Factoring to Solve Quadratics

There are many ways to do this, but this is Professor Leonard's way (which is the way of the gods themselves and the only way). If we do this method, we cannot get imaginary number.
$$f(x)=x^2+7x+6$$
$x^2+7x+6=0$
Can we do the sqrt method? No, the $7x$ ruined it for us (although we can make it sqrt method-able with *completing the square method*). So, let's do factoring:

Let's rearrange this so that it is easier to do:
- try to have everything in order ($x^{2}\text{ to } x^{1} \text{ to }x^{0}$)
- make sure that our first term is positive ($x^2$ in $x^2+7x+6$)

Since the equation is nice and arranged for us already:
$x^2+7x+6=0$
![[Pasted image 20240812150611.png]]
1. Step 1: get the $b$ value (in this case $7$)
2. Step 2: get the $a\cdot c$ value (in this case $1\cdot 6=6$)
3. Step 3: find 2 values that can be multiplied to get $a\cdot c$ ($6$ here) AND those 2 values can be added to be equal to $b$
So we get $+6$ and $+1$ and these are the factors. Note: this only works if the coefficient of first term is equal to $1$. 
$(x+6)(x+1)=0$
What if the coefficient of first term is NOT equal to $1$. Think about it this way (this is called *factoring by grouping* and is the reason why above shortcut works):
$x^2+7x+6=0$
$(x^2+1x)+(6x+6)=0$
Notice the separation of $7x$ into $1x$ and $6x$ here.
$x(x+1)+6(x+1)=0$
$(x+6)(x+1)=0$, as desired.
Rmb that, for this equation to hold true, either $x+6$ or $x+1$ must equal to $0$. So $x=-1$ and $x=-6$. 2 Solutions.

$$g(x)=3x(x-4)-36$$
Let's re-arrange this first:
$3x^2-12x-36=0$
Can we do the sqrt method? No, so let's do factoring.
For the shortcut method (making the the coefficient of first term $= 1$), let's divide both sides by $3$:
$x^2-4x-12=0$
![[Pasted image 20240812151823.png]]
$(x-6)(x+2)=0$
So, $x=6,-2$.
Let's try not doing it with the shortcut:
$3x^2-12x-36=0$
![[Pasted image 20240812152224.png]]
- notice how we cannot just do $(x-18)(x+6)=0$
$(3x^2-18x)(6x-36)=0$
$3x(x-6)6(x-6)=0$
$(x-6)(3x+6)=0$
So $x=6$ and $x=\frac{-6}{3}=-2$, as above so below.

$$g(x)=3x^2+2+5x$$
Let's re-arrange this:
$0=3x^2+5x+2$
So $a\cdot c=2\cdot 3=6$ and we just need 2 numbers that are a factor of $6$ AND can be added to get 5, which are $2+3=5$.
So:
$(3x^2+3x)+(2x+2)=0$
$3x(x+1)+2(x+1)=0$
$(x+1)(3x+2)=0$
So $x=-1$ and $x=\frac{-2}{3}$
![[Pasted image 20240812162732.png]]
- notice how we could get the same results with our shortcut method by **dividing the factor that we got by $a$.** So we have $x+\frac{3}{3}=0$ and $x+ \frac{2}{3}=0$. Thus,  $x=-1$ and $x=\frac{-2}{3}$, as above so below. With this extra step, the shortcut works *regardless* of $a$.
- Also notice this: $\frac{+3}{+3}=\frac{+1}{+1}$ and $\frac{+2}{+3}$. Now take a look at our factored equation: $(x+1)(3x+2)=0$. 
	- ![[Pasted image 20240812163559.png]]
$$h(x)=-2x^2-5x+12$$
Re-arranging this:
$0=-2x^2-5x+12$
We want the first term to be positive, so:
$2x^2+5x-12=0$
So $a\cdot c=2\cdot -12=-24$ and we just need 2 numbers that are a factor of $-24$ and can be added to get $5$, which are $8+(-3)=5$.
So:
$(2x^2+8x)+(-3x-12)=0$
$2x(x+4)+(-3)(x+4)=0$
$(2x-3)(x+4)=0$
So $x=-4$ and $x=\frac{3}{2}$
$$f(x)=-12x+9+4x^2$$
Re-arranging this:
$4x^2-12x+9=0$
So $a\cdot c=4\cdot 9=36$ and we just need 2 numbers that are a factor of $36$ and can be added to get $-12$, which are $(-6)+(-6)=-12$.
So:
$(4x^2-6x)+(-6x+9)=0$
$2x(2x-3)+(-3)(2x-3)=0$
$(2x-3)(2x-3)=0$
So, $x=\frac{3}{2}$. One solution.
$$g(x)=x^2-5$$
$x^2-5=0$
$x^2=5$
Clearly, we can apply the sqrt method here:
$\sqrt{x^2}=\pm\sqrt{5}$
$x=\pm\sqrt{5}$
We got 2 solutions. Let's try doing it by factoring anyway, just because we can and to prove that these methods all give the same solution:
$x^2+0x-5=0$
So $a\cdot c=1\cdot -5=-5$ and we just need 2 numbers that are a factor of $-5$ and can be added to get $0$, which are $-\sqrt{5}+\sqrt{5}=0$.
So, $(x-\sqrt{5})(x+\sqrt{5})=0$. 2 solutions, as above so below.
## Completing the Square Made Easy

What is the completing the square method? Why does this work?
$$x^2-6x+9=0$$
- Once again, ask yourself: can we use the sqrt method? No.
- Can we use the factoring method? Yes.
$(x-3)(x-3)=0$
Here's the point of this example, what if the $9$ is redacted so that we can't see it? It would like this:
$$x^2-6x\text{ ////}=0$$
- Completing the square finds the number ($9$ or $c$) that will allow us to find the perfect square binomial that satisfies the equation for us
![[Pasted image 20240812182608.png]]
- notice that the left and right is the same number and it will be so for this method since we are *completing the square* $(x+c)^2$

Let's look at an example:
$$f(x)=x^2+4x-3$$
re-arranging this:
$x^2+4x-3=0$
To factor this, we need to find 2 number such that:
1. they can add up to $b$, or $4$ in this case
2. are a factor of $a\cdot c$ or $1\cdot -3=-3$ in this case
After thinking about this for a while, you'll realize that this cannot be done by our usual factoring method.
Let's hold the $c$ or $-3$ responsible, so we'll exclude it from their friends (see how I took him for away) and work with what might work ($x^2+4x$):
$0=x^2+4x$                    $-3$
![[Pasted image 20240812182918.png]]
- this says that we can force the equation to be *factorable* by adding $4$
$0=(x^2+4x+4)-4-3$
	the $-4$ is to undo our forced adding of the $4$
$0=(x+2)(x+2)-7$
$0=(x+2)^2-7$
$(x+2)^2=7$
	Now this is sqrt method-able.
$\sqrt{(x+2)^2}=\pm\sqrt{7}$
$x+2=\pm\sqrt{7}$
$x=-2\pm\sqrt{7}$
2 Solutions.
$$g(x)=x^2-3x+1$$
Sqrt method? No.
Factoring? Let's try:
$x^2-3x+1=0$
Top of my head, can't really think of such 2 numbers. So let's proceed with the CtS method:
1. take the problem one far away
$0=x^2-3x$                 $+1$
![[Pasted image 20240812184202.png]]
$0=(x^2-3x+\frac{9}{4})-\frac{9}{4}+1$
$0=(x- \frac{3}{2})^{2}- \frac{9}{4}+1$
$0=(x- \frac{3}{2})^{2}- \frac{5}{4}$
$\frac{5}{4}=(x- \frac{3}{2})^{2}$
Now we can use the sqrt method:
$\pm\sqrt{\frac{5}{4}}=\sqrt{(x- \frac{3}{2})^2}$
$\pm\frac{\sqrt{5}}{2}=x- \frac{3}{2}$
$x=\frac{3-\sqrt{5}}{2}$
$$h(x)=5x^2-10x+2$$
Sqrt method? No.
Let's try factoring:
![[Pasted image 20240812184912.png]]
doesn't really work. Let's isolate $c$ and work with what might work:
$0=5x^2-10x$             $+2$
$0=5(x^2-2x+\text{   })$       $+2$
![[Pasted image 20240812190056.png]]
$0=5(x^2-2x+1)-5+2$
- notice the $-5$ here instead of $-1$ because if we multiply the 5 outside the parentheses we would get a $+5$. **BE CAREFUL ABOUT THIS!**
$0=5(x-1)^2-5+2$
$\frac{3}{5}=(x-1)^2$
Sqrt method:
$x-1=\pm\sqrt{\frac{3}{5}}$
$x=1\pm\sqrt{\frac{3}{5}}$
$$g(x)=x^2+\frac{2}{3}x-\frac{1}{3}$$
Sqrt method? No.
Factoring? We'll try this later.
Try CtS:
$0=x^{2}+ \frac{2}{3}x$          $- \frac{1}{3}$
![[Pasted image 20240812205352.png]]
$0=(x^{2}+ \frac{2}{3}x + \frac{1}{9})- \frac{1}{9}- \frac{1}{3}$
$0=(x+ \frac{1}{3})^{2}- \frac{1}{9}- \frac{1}{3}$
$0=(x+ \frac{1}{3})^{2}- \frac{4}{9}$
$\frac{4}{9}=(x+ \frac{1}{3})^2$
The sqrt method:
$\pm \sqrt{\frac{4}{9}}=\sqrt{(x+ \frac{1}{3})^2}$
$\pm \sqrt{ \frac{4}{9}}=x+ \frac{1}{3}$
$-\frac{1}{3}\pm \frac{2}{3}=x$
$\frac{-1\pm2}{3}=x$
2 Solutions. $x=- \frac{3}{3}=-1$ and $x=\frac{1}{3}$

We can also do this by factoring:
$0=x^{2}+ \frac{2}{3}x- \frac{1}{3}$
multiply both sides by $3$:
$0\cdot 3=3x^2+2x-1$
![[Pasted image 20240812210102.png]]
So $x=-1$ and $x=\frac{1}{3}$, as above so below.

$$f(x)=3x^2+x-\frac{1}{2} $$
$0=3x^2+x$           $-\frac{1}{2}$
$0=3(x^{2}+ \frac{1}{3}x+....)$          $- \frac{1}{2}$
![[Pasted image 20240812210707.png]]
$0=3(x^{2}+\frac{1}{3}x+\frac{1}{36})- \frac{1}{12}- \frac{1}{2}$
- notice the $- \frac{1}{12}$ here instead of $- \frac{1}{36}$
$0=3(x+ \frac{1}{6})^{2}- \frac{7}{12}$
$\frac{7}{36}=(x+ \frac{1}{6})^2$
Sqrt method:
$\pm\sqrt{\frac{7}{36}}=\sqrt{(x+ \frac{1}{6})^2}$
$\pm\sqrt{\frac{7}{36}}=x+ \frac{1}{6}$
$\pm\frac{\sqrt{7}}{6}- \frac{1}{6}=x$
$x=\frac{-1\pm\sqrt{7}}{6}$
2 Solutions.
$$h(x)=-2x^2+5x-7$$
$0=-2x^2+5x-7$
$2x^2-5x+7=0$
Isolate the $+7$
$0=2(x^{2}- \frac{5}{2}x+....)-....+7$
![[Pasted image 20240812212518.png]]
$0=2(x^{2}- \frac{5}{2}x+ \frac{25}{16})- \frac{25}{8}+7$
- notice the $\frac{-25}{8}$ here instead of $\frac{25}{16}$ because of the $2$ in front of the parentheses
$0=2(x- \frac{5}{4})^{2}+ \frac{31}{8}$
$-\frac{31}{16}=(x- \frac{5}{4})^2$
Sqrt method:
$\pm\sqrt{-\frac{31}{16}}+ \frac{5}{4}=x$
$\frac{5\pm\sqrt{-31}}{4}=x$
$\frac{5\pm\sqrt{31}i}{4}=x$
No real solutions.
![[Pasted image 20240812213330.png]]
## Proving the Quadratic Formula

$f(x)=ax^2+bx+c$
finding x-intercept:
$ax^2+bx+c=0$
We can prove this by using completing the square method (see? this method is useful):
$0=a(x^{2}+ \frac{b}{a}x+....)-....+c$
![[Pasted image 20240813163402.png]]
$0=a(x^{2}+ \frac{b}{a}x+\frac{b^{2}}{4a^{2}})-\frac{b^2}{4a}+c$
$0=a(x+\frac{b}{2a})^{2}- \frac{b^{2}}{4a}+c$
$\frac{\frac{b^{2}}{4a}-c}{a}=(x+ \frac{b}{2a})^{2}$
$\frac{\frac{b^{2}}{4a}-(c\cdot \frac{4a}{4a})}{a}=(x+ \frac{b}{2a})^{2}$
$\frac{b^{2}-4ac}{4a^{2}}=(x+ \frac{b}{2a})^{2}$
$\pm\sqrt{\frac{b^{2}-4ac}{4a^{2}}}=x+ \frac{b}{2a}$
$- \frac{b}{2a}\pm\frac{\sqrt{b^2-4ac}}{2a}=x$
$$\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$$
Thus, proving the formula. If we have negative inside our square root, it means we have an $i$ e.g. graph with no real solution for x-intercept.

### Using the Quadratic Formula

Examples:
$$f(x)=3x^2-5x+1$$
$0=3x^2-5x+1$
$x=\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}$
$a=3,b=-5,c=1$, plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$x=\frac{-(-5)\pm\sqrt{(-5)^{2}-4(3)(1)}}{2(3)}$
$x=\frac{5\pm\sqrt{13}}{6}$
2 Solutions.
$$g(x)=3x(x+2)-1$$
$0=3x(x+2)-1$
$0=3x^2+6x-1$
$a=3,b=6,c=-1$ plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$\frac{-(6)\pm\sqrt{(6)^{2}-4(3)(-1)}}{2(3)}=x$
$x=\frac{-6\pm\sqrt{48}}{6}$
$x=\frac{-6\pm4\sqrt{3}}{6}$
$x=\frac{-3\pm2\sqrt{3}}{3}$
2 Solutions.
$$h(x)=3x^2+x-\frac{1}{2}$$
$0=3x^2+x-\frac{1}{2}$
$a=3,b=1,c=- \frac{1}{2}$ plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$\frac{-(1)\pm\sqrt{(1)^{2}-4(3)(- \frac{1}{2})}}{2(3)}=x$
$\frac{-1\pm\sqrt{7}}{6}=x$
2 Solutions.
$$f(x)=\frac{1}{8}x^2-\frac{1}{4}x-2$$
Let's set equal to 0 and multiply both sides by 8 first:
$0=x^2-2x-16$
$a=1,b=-2,c=-16$ plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$\frac{-(-2)\pm\sqrt{(-2)^{2}-4(1)(-16)}}{2(1)}=x$
$x=\frac{2\pm\sqrt{68}}{2}$
$x=\frac{2\pm2\sqrt{17}}{2}$
$x=1\pm\sqrt{17}$
2 Solutions.
$$f(x)=9x^2-6x+1$$
$0=9x^2-6x+1$
$a=9,b=-6,c=1$ plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$\frac{-(-6)\pm\sqrt{(-6)^{2}-4(9)(1)}}{2(9)}=x$
$\frac{6\pm\sqrt{36-36}}{18}=x$
$x=\frac{1}{3}$
1 Solutions.
$$g(x)=-4x^2-x-4$$

$0=-4x^2-x-4$
$a=-4,b=-1,c=-4$ plugging these in $\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}=x$
$\frac{-(-1)\pm\sqrt{(-1)^{2}-4(-4)(-4)}}{2(-4)}=x$
$\frac{1\pm\sqrt{-63}}{-8}=x$
$\frac{1\pm3\sqrt{7}i}{-8}=x$
To make the denominator positve:
$\frac{-1}{-1}\cdot\frac{1\pm3\sqrt{7}i}{-8}=x$
$\frac{-1\pm3\sqrt{7}i}{8}=x$
No real solutions.
![[Pasted image 20240813185044.png]]
## Finding Intersections of Functions
To find intersections between 2 functions, just set them to equal. For example:
$$f(x)=x^2+6x+3$$$$g(x)=3$$Set them to be equal:
$x^2+6x+3=3$
$x^2+6x=0$
Sqrt method? No.
Factoring? Yep.
$x(x+6)=0$
So, $x=-6$ or $x=0$.
Let's also try quadratic formula:
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(6)\pm\sqrt{(6)^2-4(1)(0)}}{2(1)}$
$x=\frac{-6\pm6}{2}$
So, $x=-6$ or $x=0$.
We have $x$ but we still need $y$. We can find this by plugging our $x$ in one or both of our equations:
$f(-6)=(-6)^2+6(-6)+3$
$f(-6)=3$
So $y=3$, let's try it with $x=0$:
$f(0)=(0)^2+6(0)+3$
$f(0)=3$
As for the other equation: $g(x)=3$, it is clear that whatever $x$ we plug in it will output a $3$ since it is a horizontal line.
Now we have the ordered pairs of: $(-6,3),(0,3)$
![[Pasted image 20240813212209.png]]
$$f(x)=-2x^2+1$$$$g(x)=3x+2$$Set them to be equal:
$-2x^2+1=3x+2$
$0=2x^2-1+3x+2$
$0=2x^2+3x+1$
![[Pasted image 20240813212527.png]]
$0=(2x^2+2x)+(x+1)$
$0=2x(x+1)+(x+1)$
$0=(2x+1)(x+1)$
So $x=- \frac{1}{2}$ and $x=-1$
Replacing these values in both of our equations:
$f(- \frac{1}{2})=-2(- \frac{1}{2})^{2}+1$
$f(- \frac{1}{2})=-2(- \frac{1}{2})^{2}+1$
$f(- \frac{1}{2})=-2\cdot \frac{1}{4}+1$
$f(- \frac{1}{2})= \frac{1}{2}$
and the other equation:
$g(- \frac{1}{2})=3(-\frac{1}{2})+2$
$g(- \frac{1}{2})= \frac{1}{2}$
Same results, proving the validity of equality. Let's try it with $x=-1$:
$f(-1)=-2(-1)^2+1$
$f(-1)=-1$
with $g(x)$:
$g(-1)=3(-1)+2$
$g(-1)=-1$
Valid.
![[Pasted image 20240813213824.png]]
$$f(x)=x^2-x+1$$$$g(x)=2x^2-3x-14$$Set them to be equal:
$x^2-x+1=2x^2-3x-14$
$0=x^2-2x-15$
Let's use the quadratic formula:
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(-2)\pm\sqrt{(-2)^2-4(1)(-15)}}{2(1)}$
$x=\frac{2\pm\sqrt{64}}{2}$
$x=\frac{2\pm8}{2}$
$x=1\pm4$
So, $x=-3$ or $x=5$
To get the ordered pair and check our results:
$f(-3)=(-3)^2-(-3)+1$
$f(-3)=13$
![[Pasted image 20240813214347.png]]
$g(-3)=2(-3)^2-3(-3)-14$
$g(-3)=18+9-14$
$g(-3)=13$
Valid. Let's try $x=5$ with $f(x)$ to get a complete pair:
$f(5)=(5)^2-(5)+1$
$f(5)=21$
![[Pasted image 20240813214646.png]]
## Using Substitutions to Solve Equations
$$g(x)=(3x+4)^2-6(3x+4)+9$$
$0=(3x+4)^2-6(3x+4)+9$
- my first thought is to distribute everything, but this is the case where substitution just work better. Notice the $(3x+4)$ in the first term and second term.
Set $u=3x+4$ (it doesn't have to be $u$; you can name it whatever you want):
$0=u^2-6u+9$
$0=(u-3)(u-3)$
So $u=3$ and so:
$3=3x+4$
$x=- \frac{1}{3}$
This is substitution. We do this to change equations that are NOT quadratic (or is quadratic but arranged weirdly) into quadratic, thus, simplifying it.

Another example:$$f(x)=3x^4-2x^2-1$$
- notice the $x^4$ here, so expect 4 solutions.
First set this to equal to 0:
$0=3x^4-2x^2-1$
We can *substitute* here: set $p=x^2$
$0=3p^2-2p^2-1$
Using factoring:
![[Pasted image 20240813221248.png]]
$0=(p-1)(3p+1)$
So $p=1$ or $p = -\frac{1}{3}$
So:
$1=x^2$
$x=\pm1$
- don't forget your $\pm$ sign!
and
$- \frac{1}{3}=x^2$
$\pm\sqrt{\frac{-1}{3}}=x$
$\pm\sqrt{\frac{1}{3}}i=x$
So there are 2 REAL solutions ($x=1,x=-1$) and 2 IMAGINARY solutions ($x=\sqrt{\frac{1}{3}}i$,$x=-\sqrt{\frac{1}{3}}i$)
![[Pasted image 20240813222449.png]]
- See how it only give 2 x-intercepts when plotted on a real plane
### More examples
$$f(x)=x^\frac{2}{3}-7x^\frac{1}{3}+10$$
$0=x^\frac{2}{3}-7x^\frac{1}{3}+10$
Set $k=x^\frac{1}{3}$
- $0=(x^\frac{1}{3})^2-7(x^\frac{1}{3})+10$
$0=k^2-7k+10$
$0=(k-5)(k-2)$
So $k=5,k=2$
Solve for $x$:
$5=x^\frac{1}{3}$
$5^3=x^{\frac{1}{3}\cdot3}$
$x=125$
and
$2=x^{\frac{1}{3}}$
$x=8$
![[Pasted image 20240813223140.png]]
$$g(x)=x+\sqrt{x}-20$$
$0=x+\sqrt{x}-20$
Set $u=\sqrt{x}$ (let's just use $u$ from now on, I'm sure you get my point):
$0=u^2+u-20$
$0=(u+5)(u-4)$
So $u=4$ and $u=-5$
To solve for $x$:
$4=\sqrt{x}$
$x=4^2$
$x=16$
and
$-5=\sqrt{x}$
$x=25$
![[Pasted image 20240813223753.png]]
- *wait*... but the line does not pass through $(25,0)$. Why?
	Think about it. A square root of $x$ or any value *cannot* be equal to a negative number ($\sqrt{x}=-5$) over real number. So this is a false solution. This happens rarely... but you should always notice it when it happens.
	- For example:
		- $u=\frac{-1-\sqrt{3}}{2}$ and $u=\sqrt{x}$
			- So, $\sqrt{x}=\frac{-1-\sqrt{3}}{2}$. Is this possible over real number? No.
		- $u=\frac{-1+\sqrt{3}}{2}$ and $u=\sqrt{x}$
			- - So, $\sqrt{x}=\frac{-1+\sqrt{3}}{2}$. Is this possible over real number? Yes, $-1+\sqrt{3}$ is NOT a negative number. 

$$h(x)=-2y^{-2}-11y^{-1}+40$$
$0=-2y^{-2}-11y^{-1}+40$
Set $u=y^{-1}$
$0=-2u^2-11u+40$
factor out the negative:
$0=-2(u^{2}+ \frac{11}{2} u-20)$
![[Pasted image 20240813225308.png]]
$0=-2[(2u-5)(u+8)]$
So $u=\frac{5}{2}$ or $u=-8$
Solve for $y$:
$\frac{5}{2}=y^{-1}$
$\frac{5}{2}^{-1}=y^{-1\cdot-1}$
$y=\frac{2}{5}$
and
$-8=y^{-1}$
$y=-\frac{1}{8}$
![[Pasted image 20240813225907.png]]
## Graphing Quadratic Functions
$$f(x)=ax^2+bx+c$$
- quadratic functions are going to all be parabola
![[Pasted image 20240814001537.png]]
**$y$-intercept**: $(0,c)$
**$x$-intercept** (0-2 real solutions): $ax^2+bx+c=0$
**vertex**: $(- \frac{b}{2a},f(x))$ or [[#Completing the Square Made Easy|complete the square]] for vertex form

Examples:$$f(x)=2x^2+8x+5$$
- $a>0$ so it is going to be a parabola opening *upward*
Let's find out the order pairs in this order:
1. vertex
2. y-int
3. x-int
#### Vertex
Let's explain the vertex formula first:$$(- \frac{b}{2a},f(x))$$Rmb the proof for quadratic formula:
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
turning back a few steps:
$\frac{b^{2}-4ac}{4a^{2}}=(x+ \frac{b}{2a})^{2}$
- with this arrangement, we can see that, inside the parentheses of the right side of the equation, we have $x+\text{something}$: this is a *shift left*. So to undo the shift left and get to our vertex we have $- \frac{b}{2a}$ for $x$.
- As for the left part, if we move the it to the right $0=(x+ \frac{b}{2a})^{2}-\frac{b^{2}-4ac}{4a^{2}}$, it will be a *shift up or down*
So to solve for $x$-coordinate of our vertex:
$x=- \frac{b}{2a}$
$x=- \frac{8}{2(2)}$
$x=-2$
So now we have $(-2,f(-2))$. Now we can just evaluate for $y$:
$f(-2)=2(-2)^2+8(-2)+5$
$f(-2)=2(-2)^2+8(-2)+5$
$f(-2)=8-16+5$
$f(-2)=-3$
So our vertex's coordinate is $(-2,-3)$. This says that $-3$ is the lowest point of our graph (if we have $a>0$ or upward opening parabola)
#### $y$-intercept
This is just evaluating our function with a 0.
$f(0)=2(0)^2+8(0)+5$
Now, we clearly see that only 5 is left.
So we have $(0,c)$ or $(0,5)$ as our $y$-intercept.
#### $x$-intercept
Now we don't always have to find the $x$-intercept for every quadratic function. Particularly, these functions:
![[Pasted image 20240814003941.png]]
Why? Because these do NOT have $x$-intercept over the real number plane. And notice how we already have a good idea of how to draw the graph with just the vertex and the $y$-intercept.
![[Pasted image 20240814004232.png]]
Let's find it anyway:
$0=2x^2+8x+5$
Let's do the quadratic formula:
$x=\frac{-(8)\pm\sqrt{(8)^2-4(2)(5)}}{2(2)}$
$x=\frac{-8\pm\sqrt{24}}{4}$
$x=\frac{-8\pm2\sqrt{6}}{4}$
$x=\frac{-4\pm\sqrt{6}}{2}$
So $x\approx-3.22$ and $x\approx-0.77$
![[Pasted image 20240814005005.png]]
### More examples
$$g(x)=-2x^2-4x+2$$
**Vertex**
$(- \frac{b}{2a},f(x)$
$x=- \frac{-4}{2(-2)}$
$x=-1$
$f(-1)=-2(-1)^2-4(-1)+2$
$f(-1)=-2+4+2$
$f(-1)=4$
So our vertex = $(-1,4)$

**y-intercept**
$(0,c)\implies (0,2)$

**x-intercept**
$0=-2x^2-4x+2$
let's use quadratic:
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(-4)\pm\sqrt{(-4)^2-4(-2)(2)}}{2(-2)}$
$x=\frac{4\pm\sqrt{32}}{-4}$
$x=\frac{4\pm4\sqrt{2}}{-4}$
$x=-1\pm\sqrt{2}$
So $x=-1+\sqrt{2}\approx0.41$ and $x=-1-\sqrt{2}\approx-2.41$
![[Pasted image 20240814011103.png]]
![[Pasted image 20240814011131.png]]

$$f(x)=-4x^2-4x-1$$
**Vertex**
$(- \frac{b}{2a},f(x))$
$x=- \frac{-4}{2(-4)}$
$x= -\frac{1}{2}$
Evaluate $f(-\frac{1}{2})$ for $y$:
$f(- \frac{1}{2})=-4(-\frac{1}{2})^2-4(-\frac{1}{2})-1$
$f(- \frac{1}{2})=-1+2-1$
$f(- \frac{1}{2})=0$
So vertex is at $(- \frac{1}{2},0)$
- notice how this is also a *x-intercept*
**y-intercept**
$(0,c)\implies (0,-1)$
**x-intercept**
$0=-4x^2-4x-1$
$0=-4(x^{2}+x+ \frac{1}{4})$
$0=-4(x+ \frac{1}{2})^2$
So $x=- \frac{1}{2}$.
![[Pasted image 20240814182916.png]]

$$g(x)=3x^2+2x+5$$
**Vertex**
$(- \frac{b}{2a},f(x))$
$x=- \frac{b}{2a}$
$x=- \frac{2}{2(3)}$
$x= - \frac{1}{3}$
Evaluate $f(- \frac{1}{3})$:
$f(- \frac{1}{3})=3(- \frac{1}{3})^2+2(- \frac{1}{3})+5$
$f(- \frac{1}{3})=\frac{1}{3}- \frac{2}{3}+ \frac{15}{3}$
$f(- \frac{1}{3})= \frac{14}{3}$
So the vertex is at $(- \frac{1}{3},\frac{14}{3})$

**y-intercept**
$(0,c)\implies (0,5)$

**x-intercept**
$0=3x^2+2x+5$
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(2)\pm\sqrt{(2)^2-4(3)(5)}}{2(3)}$
$x=\frac{-2\pm\sqrt{-56}}{6}$
$x=\frac{-2\pm2\sqrt{14}i}{6}$
$x=\frac{-1\pm\sqrt{14}i}{3}$
So x-intercepts are not real solutions, meaning that the parabola hovers above the $x$-axis.
![[Pasted image 20240814184508.png]]

Let's do one, the other way around:
For a Parabola with a vertex of $(1,-5)$ and a y-int of $-3$, find the function:$$f(x)=a(x+h)^2+k$$Let's distribute this:
$f(x)=ax^2+2ahx+(ah^2+k)$
So $a=a\text{, } b=2ah\text{, and } c=ah^2+k$
Find $h$:
From the vertex formula: $(- \frac{b}{2a},f(x))$, we know that $- \frac{b}{2a}=1=- \frac{2ah}{2a}$. So $h=-1$.
- actually, since we know that the vertex $(1,-5)$, we can imagine that the graph is *shifted right* by 1. By this, we can assume that $h=-1$ since it is the only variable directly affecting $x$.

Find $k$:
We know that $f(1)=-5=a(x+h)^2+k$. Replace $x=1$ and $h=-1$:
$-5=a((1)+(-1))^2+k$
$k=-5$
- similar to $h$, since we know that the vertex is $(1,-5)$, we can refer to the *vertex form*. This means that the graph is shifted down by $5$ so $k=-5$.

Since $c=-3=ah^2+k$:
$-3=a(-1)^2+(-5)$
$a=2$
Recap: $a=2$, $b=2(2)(-1)=-4$, and $c=-3=(2)(-1)^2+(-5)$
So our function is:$$f(x)=2x^2-4x-3$$
![[Pasted image 20240814190614.png]]

This is called a *vertex form*. We can conveniently get $h$ and $k$ if we are given a vertex coordinates.
![[Pasted image 20240814191938.png]] 
## Solving Quadratic Inequalities

Quadratic inequalities: what they are? what they do? how to solve them?
- quadratics: functions that give you a parabola
- inequalities: intervals that give you some value above or below some other values or functions

Let's look at some examples:$$x^2-3x-10\leq 0$$- this is saying: we have an upward parabola and it is below ($\leq$) 0.
Set them equal to 0:
$x^2-3x-10=0$
$(x-5)(x+2)=0$
So $x=5$ and $x= -2$. Now this doesn't solve the inequality, we just have the interval.
![[Pasted image 20240814212624.png]]
To solve the inequalities, notice the less than or equal to ($\leq$) sign: this asks for the interval of $x$ where the output of the function is $\leq 0$, which is would be $[-2,5]$ in this case. In other word, $x^2-3x-10\leq 0$ statement is only true within the interval $[-2,5]$.
![[Pasted image 20240814213301.png]]

$$2x^2<5x+3$$
- this is what this asks: in which interval is the $2x^2$ parabola lessor (under) the line $5x+3$
 ![[Pasted image 20240814213635.png]]
 - we can see from the generated graph but let's calculate the precise interval
Find their intersection by setting them to be equal:
$2x^2=5x+3$
$2x^2-5x-3=0$
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(-5)\pm\sqrt{(-5)^2-4(2)(-3)}}{2(2)}$
$x=\frac{5\pm\sqrt{49}}{4}$
$x=\frac{5\pm7}{4}$
So $x=3$ and $x=- \frac{1}{2}$. The statement: $2x^2<5x+3$ is only true at interval $(- \frac{1}{2}, 3)$.
- at $(-\infty,- \frac{1}{2}]\cup[3,\infty)$, the statement is false. 

$$x(x+1)>20$$
- This is asking for the interval in which the parabola of $x(x+1)$ is less than a horizontal line at $20$.
$x(x+1)=20$
$x^2+x-20=0$
$(x+5)(x-4)=0$
So, $x=-5$ and $x=4$. This statement: $x(x+1)>20$ is only true at interval $(-5,4)$. Let's draw a graph to see if we're right:
![[Pasted image 20240814214805.png]]

$$4x^2+9<6x$$
- this is what this asks: in which interval is the $4x^2+9$ parabola lessor than (under) the line $6x$
$4x^2+9=6x$
$4x^2-6x+9=0$
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(-6)\pm\sqrt{(-6)^2-4(4)(9)}}{2(4)}$
$x=\frac{6\pm\sqrt{36-144}}{8}$
$x=\frac{6\pm6\sqrt{3}i}{8}$
$x=\frac{3\pm3\sqrt{3}i}{4}$
Clearly, there is no real solutions. Let's see the graph but I assume that there is no point on the real plane where $4x^2+9$ parabola lessor than (under) the line $6x$:
![[Pasted image 20240814215423.png]]
So, this statement: $4x^2+9<6x$ is always *false* within the real plane.
	say if we reverse the sign (just for fun): $4x^2+9>6x$, this will instead always be *true* within the real number plane.
## Applications of Quadratic Functions

Let's look at some of the examples:
```
Revenue = Price * Quantity Sold
```
Let's denote the price to be $P$ and quantity sold to be $x$, our input.
$R(x)=P\cdot x$
Say the function of our price is:
$P(x)=- \frac{1}{3}x+100$
- you should already see a downward slope intersecting the y-axis at 100
- see how the more we sell, the lower our price e.g. for bulk selling
We can substitute our function of $P$ in our function $R(x)$:
$R(x)=x(- \frac{1}{3}x+100)$
$R(x)=- \frac{1}{3}x^2+100x$
- notice that this is a downward facing parabola
- rmb that we can find the max value of a downward parabola by looking at their *vertex*
Let's think about our *Domain*:
- we want our revenue to be *positive* (duh), so our domain is $R(x)\geq0$ ([[#Solving Quadratic Inequalities|quadratic inequality]]). 
![[Pasted image 20240814220810.png]]
Let's solve for our domain first:
$- \frac{1}{3}x^2+100x\geq0$
Set them to equal:
$- \frac{1}{3}x^2+100x=0$
$-1(- \frac{1}{3}x^2+100x)=-1(0)$
$\frac{1}{3}x^2-100x=0$
$\frac{1}{3}x^2-100x=0$
$\frac{1}{3}x(x-300)=0$
So $x= 0$ and $x=300$. This is our domain $[0,300]$, or the interval where our revenue will be greater or equal to 0.
- in the interval of $(-\infty,0)\cup(300,\infty)$, we will have to pay people to take our goods

We can even find the revenue at any number of $x$, for example:
$R(100)=- \frac{1}{3}(100)^2+100(100)$
$R(100)=- \frac{1}{3}(100)^2+100(100)$
$R(100)=6666.67$
So if we sold 100 goods, we will have total revenue of 6,666.67.

Next, let's find the max revenue (optimal $x$):
(no. of goods sold to get max revenue, max revenue)=vertex=$(- \frac{b}{2a},f(x))$
$x=- \frac{b}{2a}$
$x=- \frac{100}{2(-\frac{1}{3})}$
$x=- \frac{100}{2(-\frac{1}{3})}$
$x=150$
This means the no. of goods sold to get max revenue is 150. Plug this in our $R(x)$:
$R(150)=- \frac{1}{3}(150)^2+100(150)$
$R(150)=-7500+15000$
$R(150)=7500$
So the max revenue we could get from selling this product according to this model is $7,500.

We can further find the price at which this maximum revenue is attained by plugging in our vertex's $x$ into our price function ($P(x)$):
$P(150)=- \frac{1}{3}(150)+100$
$P(150)=50$
So this max revenue price is $50 per item (or we could just get it from  $\frac{7500}{150}=50$).

### Another example

Say we want to make a really nice garden and we have a 3,000 ft of fence. We want to find the maximum area possible (assuming we have no restriction on our area).
![[Pasted image 20240814222957.png]]
Let's first think about our contraints (what we are limited by):
- we're limited by the perimeter (3,000 ft of fence). So: $3000=2x+2y$ (2 sides of $x$ and 2 sides of $y$)

Next, let's think about what we *want to maximize*:
- we want to maximize the *area*. Let's say: $A=x\cdot y$

Let's try to solve for $x$:
from our constraint equation,
$3000=2x+2y$
$x=1500-y$
replace our $x$ in the area equation:
$A=(1500-y)\cdot y$
This is starting to look familiar.
$A=-y^2+1500y$
This looks just like a quadratic equation (a downward facing parabola). Let's try to find its vertex:
$(- \frac{b}{2a},f(x))$
$x=- 1500/2(-1)$
$x=750$
Okay now we can plug this to find the $y$ coordinate of our vertex:
$f(750)=-(750)^2+1500(750)$
$f(750)=-562500+1125000$
$f(750)=562500$
So our vertex is $(750,562500)$.

So our $y$ sides are 750 ft, we can plug it in our constraint equation:
$3000=2x+2(750)$
$x=750$
So this is a square.
Trivial: [[#Is square the optimum shape for maximizing the area given a fixed perimeter?]]

Last example:
![[Pasted image 20240814224710.png]]
we throw a projectile and want to figure out how far it goes. We're provided a function for the height given how far it goes:$$h(x)=\frac{-32x^2}{(2000)^2}+x$$We know how far it goes when the thing hit the ground or $h(x)=0$, so:
$0=\frac{-32x^2}{(2000)^2}+x$
$\frac{32x^{2}}{2000^{2}}=x$
$32x^2-4,000,000x=0$
$4x(8x-1,000,000)=0$
So $x=0$ (this would be our starting point) and $x= \frac{1000000}{8}=125,000$.

We can also find the maximum height at which this projectile is thrown by finding the vertex:
$x=- \frac{b}{2a}$
$x=- \frac{-4,000,000}{2(32)}$
$x=62,500$
So, at $x=62,500$, the projectile reaches its maximum height. Now find $f(x)$ for the maximum height:
$h(62,500)=\frac{-32(62,500)^2}{(2000)^2}+(62,500)$
Big numbers but:
$h(62,500)=31,250$
#### Is square the optimum shape for maximizing the area given a fixed perimeter?

This is apparently a classic optimization problem, and is often solved using the **isoperimetric inequality**, which states that of all the shapes with a given perimeter, the circle encloses the maximum area.

Since we've considered a square, let's take a brief look at the other shapes:
![[Pasted image 20240814224506.png]]
## Introduction to Polynomial Functions

$f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+...+a_{2}x^{2}+a_{1}x+a_{0}$
- polynomials is a function consisting of $n$ terms which are combined by addition
- notice the descending order
	- Why descending order? the *leading term* and *degree* will tell us a lot about the function and having it in such order is more convenient for interpretation and manipulation.
- Polynomials are smooth and continuous with no cuts, no gaps, no holes, and no asymptotes (which is very convenient).

Components:
- *Leading term*: $a_{n}x^{n}$ (the first term; in descending order)
- *Constant term*: $a_{0}$ (the last term; in descending order)
- *Degree*: $n$ (the *largest* exponent of all the terms e.g. exponent of the *leading term*)

```
Notes:
- Exponents are all non-negative integers (n>=0)
	- From this, we can infer that our domain are always real numbers. We don't have to worry about domain issues. Whew!
- Order by descending exponents
```

Examples:$$f(x)=5x^2+4x^4$$We should order this by descending exponents:
$f(x)=4x^4+0x^3+5x^2+0x+0$
This is a polynomial.
- leading term: $4x^4$
- constant term: $0$
- degree: $4$
$$g(x)=3- \frac{1}{2} x$$
In order:
$g(x)=-\frac{1}{2}x+3$
This is a polynomial.
- leading term: $- \frac{1}{3}x^1$
- constant term: $3$
- degree: $1$
$$h(x)=9$$This is a polynomial (rmb: you don't have to have more than 1 term).
- leading term: $9x^{0}$
- constant term: $0$
- degree: $0$
$$f(x)=0$$This is a polynomial.
- leading term: $0x^{0}$
- constant term: $0$
- degree: No degree
	- Why no degree? this is an edge case because regardless of the degree e.g. $0x^{31}$ or $0x^{8}$, you will still get zero. Meaning that the degree does not matter so we say that it is no degree instead of 0.
$$f(x)=x^{\frac{3}{2}}+2x-1$$This is NOT a polynomial. Think about it this way:
- when your term has fraction $x^{\frac{a}{b}}$, it is just $\sqrt[b]{x^{a}}$. So in this case, it is just $\sqrt{x^3}$ which is a *radical*.
- if it was $x^{\frac{4}{2}}$ then it would just be $x^{2}$, which is fine in a polynomial.
$$G(x)=1-\frac{4}{x}$$This is NOT a polynomial.
$G(x)=1-4x^{-1}$
- rmb: Exponents are all non-negative integers ($n\geq0$)
$$f(x)=9x^4 -\pi x^{2}+\frac{1}{2}$$This is a polynomial.
- leading term: $9x^{4}$
- constant term: $\frac{1}{2}$
- degree: $4$
### More examples
$$g(x)=\frac{x^2-5}{x^4}$$ This is NOT a polynomial:
$g(x)=\frac{x^{2}}{x^{4}}- \frac{5}{x^{4}}$
$g(x)=x^{-2}-5x^{-4}$
- rmb: Exponents are all non-negative integers ($n\geq0$)
$$h(x)=\frac{3x^2-1}{7}$$This is a polynomial.
- leading term: $\frac{3}{7}x^{2}$
- constant term: $- \frac{1}{7}$
- degree: $2$
$$G(x)=2\sqrt{x}(\sqrt{x}+1)$$Be careful with these one. We have to consider the domain issue before distributing this as I'm sure you are very eager to do. This is clearly NOT a polynomial. Even after we distribute:
$G(x)=2x+2\sqrt{x}$
- there are still $x^{\frac{1}{2}}$ term in there
What if this was the case:$$G(x)=2\sqrt{x}(\sqrt{x})$$Simplifying it gets you $G(x)=2x$ and seems like a perfectly fine polynomial. Simplifying the function doesn't remove the domain restriction that was present in the original form of the function. So this is also NOT a polynomial.
$$F(x)=2x^3(x^2-1)(x-1)^2$$First look, this is probably a polynomial but there's just so much distribution to simplify it. When we see such things, if you really want to distribute it manually, start from the right. 

**But here's professor Leonard technique for finding the *leading term* (thank you, professor Leonard):** ^217787
1. add the dot product between every thing
$2\cdot x^{3}\cdot (x^{2}-1)\cdot (x-1)^{2}$
2. take the largest power of that you would get if you were to distribute it
$2\cdot x^{3}\cdot (x^{2}-1)^{1}\cdot (x-1)^{2}$
3. you will get your leading term
$2\cdot x^{3}\cdot x^{2}\cdot x^{2}$
So, the leading term is $2\cdot x^{3+2+2}=2x^{7}$

Let's do a slightly modified example for clarity, starting with step 2:
$2\cdot x^{3}\cdot (x^{2}-1)^{3}\cdot (x-1)^{2}$
- notice that the third term is cubed now
$2\cdot x^{3}\cdot x^{6}\cdot x^{2}$
So the leading term for this would be $2x^{11}$
## Power Functions

What are power functions? Polynomial functions with only *one* term. This is important for understanding the *end behavior* (how it will ultimately look in a graph) of a polynomial.$$f(x)=ax^n$$Power functions are very predictable, there are 2 patterns: [[#Properties of Functions - Even vs Odd|even and odd]]. Power functions, with only one term, there are no shift left, right, up, nor down.

Rmb:
- All odd functions contain 3 key points: $(-1,-1),(0,0),(1,1)$
	- rmb: $\frac{1}{x}$, which has vertical asymptotes at $x=0$ and does not contain $(0,0)$, is NOT a polynomial and thus not a power function.
- All even functions contain 3 key points: $(-1,1),(0,0),(1,1)$
$$f(x)=x$$![[Pasted image 20240815200406.png]]
$$f(x)=x^2$$![[Pasted image 20240815200419.png]]
$$f(x)=x^3$$![[Pasted image 20240815200438.png]]
$$f(x)=x^4$$![[Pasted image 20240815200455.png]]
- notice the similarity but slight difference between $x^{2}$ parabola and $x^4$ parabola here. It's the same shape but more *dramatic*.

And so on (do you see how *dramatic* it is? so dramatic.):
**Odd functions**
![[Pasted image 20240815201006.png]]
**Even functions**
![[Pasted image 20240815201041.png]]

The coefficient tells us about [[#Introduction to Graph Transformation|how the power functions are transformed]]:
- rmb: there are no shift left/right/up/down with power function, only stretch/compress and reflection

Let's talk about domain and range a little for power functions:
**Domain:** All real numbers for both odd and even functions
**Range:** Differs a bit for odd and even
- **Odd:** $(-\infty,\infty)$
- **Even:** $[0,\infty)$ in cases of positive coefficient or $(-\infty,0]$ in cases of negative coefficient

### More examples
$$G(x)=3(x+2)^5-3$$
Do we have to distribute $3(x+2)(x+2)(x+2)(x+2)(x+2)$? That's horrible! Let's instead use the idea from transformation and power function:
- notice the *shift left* by 2 and *shift down* by 3
- the 3 in front of the parentheses will affect our key points
![[Pasted image 20240815202910.png]]
We dotted out the key points based on our new origin. ![[Pasted image 20240815203328.png]]
Knowing that $x^5$ is super *dramatic*, so:
![[Pasted image 20240815203454.png]]
There we have it.
![[Pasted image 20240815203731.png]]

Next example:$$F(x)=3-(x-2)^4$$Let's re-arrange a little:
$F(x)=-(x-2)^4+3$
- notice that it is *shifted up* by 3 and *shifted right* by 2
- negative in front of parentheses so a *reflection*, affecting our key points
![[Pasted image 20240815204414.png]]
![[Pasted image 20240815204500.png]]
## Multiplicity and End Behavior of Polynomials
### Multiplicity

When you solve a polynomial equation like $P(x)=0$, the roots are the values of $x$ that make the equation true. **Multiplicity** is the number of times a particular root repeats. In other words, it's how "repeated" a root is.
- - If $x=2$ is a root of $P(x)=0$, and when you factor the polynomial, you find that $(x-2)$ appears twice (or $(x-2)(x-2)$ or $(x-2)^2$), then $x=2$ is a root with **multiplicity 2**.
- If $x=−3$ is a root, and $(x+3)$ appears three times in the factorization (or $(x+3)^3$), then $x=−3$ is a root with **multiplicity 3**.

Let's do some example:$$f(x)=7x^2\cdot(x-2)\cdot(x+\frac{1}{2})^4\cdot(x+3)^5$$
1. Set this equal to 0. This is to find the roots and this is a form that is familiar for solving polynomials (finding x-intercepts):
$7x^2\cdot(x-2)\cdot(x+\frac{1}{2})^4\cdot(x+3)^5=0$
2. For every factor that has a variable or $x$, separate them with a parentheses:
$7\cdot(x)^2\cdot(x-2)^1\cdot(x+\frac{1}{2})^4\cdot(x+3)^5=0$
3. Set each factor equal to 0 by *zero product property*:
$x=0\implies x=0$
$x-2=0\implies x=2$
$x+ \frac{1}{2}=0\implies x=- \frac{1}{2}$
$x+3=0\implies x=-3$
These are our $x$-intercepts. Using [[#^{217787|professor Leonard's technique]], we can find the leading term which is: $7x^{2+1+4+5}=7x^{12}$. This tells us that our graph would can have a maximum of $12$ roots (or solutions). But we've only found 4 as stated above? Well, it is because the x-intercepts above can happen *multiple* time (multiplicity). 
Above text can be restated as:$$7(x)(x)\cdot(x-2)\cdot(x+\frac{1}{2})(x+\frac{1}{2})(x+\frac{1}{2})(x+\frac{1}{2})\cdot(x+3)(x+3)(x+3)(x+3)(x+3)$$Whew... I'm sure you see this is just like factorization for finding our x-intercept.
$x=0\implies x=0$. This has a multiplicity of **2** (notice that this is just the exponent). 
$x-2=0\implies x=2$. This has a multiplicity of **1**. 
$x+ \frac{1}{2}=0\implies x=- \frac{1}{2}$. This has a multiplicity of **4**. 
$x+3=0\implies x=-3$. This has a multiplicity of **5**. 

Next, the behavior of multiplicity is a bit different for *even* vs *odd* multiplicity:
- Roots with *even* multiplicity means it will *bounce off* the x-axis.
![[Pasted image 20240815212319.png]]
	notice that the line touches x-axis then "bounce off"
- Roots with *odd* multiplicity means it will *cross* the x-axis
![[Pasted image 20240815212632.png]]

$x=0\implies x=0$. This has a multiplicity of 2. **Even**. 
	at $x=0$ the graph will *bounce*
$x-2=0\implies x=2$. This has a multiplicity of 1. **Odd**.
	at $x=2$ the graph will *cross*
$x+ \frac{1}{2}=0\implies x=- \frac{1}{2}$. This has a multiplicity of 4. **Even**.
	at $x=- \frac{1}{2}$ the graph will *bounce*
$x+3=0\implies x=-3$. This has a multiplicity of 5.  **Odd**.
	at $x=-3$ the graph will *cross*
![[Pasted image 20240815213900.png]]
### End Behavior

Rmb: Power functions help us understand the *end behavior* of a function. We can look at any polynomial as a power function by only considering the *leading term*.
Say: $$f(x)=3x^5-2x^2+1$$This will look, *end behavior-wise*, very much like $3x^5$
![[Pasted image 20240815214435.png]]
- notice the gap in the middle, this is intentionally left blank because there might be some squiggly wiggly in the middle, but the end behavior will looks like $3x^5$.
$$g(x)=-2x^3-5x^4+7$$ Re-arranging this:
$g(x)=-5x^4-2x^3+7$
![[Pasted image 20240815214758.png]]

Notes:
- if a poly has degree $n$, then there will be at most $n-1$ *turning points*
	- turning points are simply your *local max/min*.
	- imagine a poly with degree 5:
	![[Pasted image 20240815215045.png]]
	See how a fifth turning point will make the graph disagree with expected end behavior. So, at *most* (it doesn't always have to be $n-1$), there can only be $n-1$ turning points.
- all poly create continuous curves -> no "holes" nor "cusps"
	![[Pasted image 20240815215447.png]]
	For your reference, these are *cusp*.

Let's go back to this function a little:$$f(x)=7x^2\cdot(x-2)\cdot(x+\frac{1}{2})^4\cdot(x+3)^5$$We know that the leading term is $7x^{12}$. With only this, we already know how the end behavior is going to look like:
![[Pasted image 20240815215809.png]]
## Creating Polynomials from Real Zeros

From this section, we'll learn how to create a poly from just roots or x-intercepts.
- rmb: with x-intercepts, we can create *factors*.

For example:$$f(x)=x^2+2x-8$$To find roots:
$0=x^2+2x-8$
$0=(x+4)(x-2)$
So from *zero product property*:
$x=-4$ and $x=2$. These are our roots.

What if $x=-4$ and $x=2$ is all we're given? Can we work backward from this? *Yes.*

Suppose x-intercepts of some $f(x)$ are -3, 4, 1, 0, what are the functions?
$x=-3 \implies x+3=0$
$x=4 \implies x-4=0$
$x=1 \implies x-1=0$
$x=0 \implies x=0$
Zero product property works *both way*, so let's do one in *reverse*:
$x(x+3)(x-4)(x-1)=0$
So $x(x+3)(x-4)(x-1)$ is one of the polynomial with such roots.
- notice how we can add *any number* in the front, and the roots will still be the same e.g. $-7x(x+3)(x-4)(x-1)$. So we leave an $a$ to denote that it can be *anything*.
- you may have to distribute this sometimes (yuck). if this is the case, start from right-to-left.
$$f(x)=ax(x+3)(x-4)(x-1)$$

More examples:
**Zeros:** $-1,0,4,-9$
**Degree:** 4
- zeros just means x-intercepts
$x=-1 \implies x+1=0$
$x=0 \implies x=0$
$x=4 \implies x-4=0$
$x=9 \implies x-9=0$
So, reverse zero product property:
$x(x+1)(x-4)(x-9)=0$
rmb: this is one of the many functions that satisfies the zeros provided above. So:$$f(x)=ax(x+1)(x-4)(x-9)$$Wait... does the given degree of 4 in the problem statement play any role in this? Yes, it actually is a little hint for us. The number of roots that we have should NOT exceed 4. 
This also make sure that you don't just add irreducible quadratic to it:
- now what does that mean? say we don't have the degree statement: we can just add *irreducible quadratic* to our factors as much as we'd like: $f(x)=ax(x+1)(x-4)(x-9)(x^{2}+9)(x^{2}+5)$...
	- *irreducible quadratic* are just quadratics that *cannot be factored any further* e.g. over real number, $(x^2+9)$ can only be factored as $(x+3i)(x-3i)$ which is not real number.
	- these irreducible quadratic doesn't add to your number of *REAL* roots (unless ofc you're working over complex number)

Next example:
**Zeros:** 1 - Mult. 1, 2 - Mult. 2
**Degree:** 3
So we have:
$x=1\implies x-1=0, Mult. 1$
$x=2\implies x-2=0, Mult. 2$
So:
$0=(x-1)^{1}(x-2)^{2}$
This agrees with the specified degree of 3, so:
$f(x)=a(x-2)^2(x-1)$

Next example:
**Zeros:** -2 - Mult. 2, 5 - Mult. 1, 0 - Mult.3, $\frac{1}{2}$ - Mult. 3
**Degree:** 9
So we have:
$x+2=0, Mult. 2$
$x-5=0, Mult. 1$
$x=0, Mult. 3$
$x- \frac{1}{2}=0, Mult. 3$
So:
$0=x^3(x- \frac{1}{2})^{3}(x+2)^{2}(x-5)$
This agrees with the specified degree of 9, so:
$f(x)=ax^3(x- \frac{1}{2})^{3}(x+2)^{2}(x-5)$
### More examples, but from graphs...
![[Pasted image 20240815235231.png]]
So x-intercepts at: 1 and 2
$x-1=0$, Mult. 1
$x-2=0$, Mult. 1
Don't forget the line crossing x-axis at $x=0$, so:
$x=0$, Mult. 1
So:
$0=x(x-1)(x-2)$
Notice that we have 2 turning points, this mean that this a degree 3 poly. Furthermore, the end behavior of this graph looks like an odd exponent function. It is climbing so the coefficient should not be negative. Summing up:
$f(x)=ax(x-1)(x-2)$

![[Pasted image 20240815235904.png]]
First glance, we have 3 x-intercepts:
$x+1=0$, Mult. 1
$x-1=0$, Mult. 1
$x-2=0$, Mult. 1
There seems to be 2 turning points, so it should have a degree of 3. Also note that the graph seems to be *falling* so the coefficient of the leading degree should be a negative value.
$0=(x+1)(x-1)(x-2)$
So:
$f(x)=a(x+1)(x-1)(x-2)$
Notice the y-intercept at $(0,-1)$, with this we can find *exactly* what $a$ actually is:
$-1=a(0+1)(0-1)(0-2)$
$-1=2a$
$a=- \frac{1}{2}$
Rmb our note about the coefficient being negative since the graph is falling? That's proven. Furthermore, we now have a specific number as $a$ (not just one of many possibilities anymore). So:$$f(x)=-\frac{1}{2}(x+1)(x-1)(x-2)$$
Last example:
![[Pasted image 20240816000805.png]]
First glance, we have 3 x-intercepts:
$x+4=0$, Mult. 1
$x+1=0$, Mult. *Even* (since it bounce off)
$x-3=0$, Mult. 1
Notice that we have 3 turning points, we most likely have a degree of 4 here. So that even number for multiplicity is 2.
$0=(x+4)(x+1)^{2}(x-3)$
The end behavior seems to me like an upward parabola (which agree with our above statement that we have a degree of 4), so $a$ is going to be positive.
$f(x)=a(x+4)(x+1)^2(x-3)$
Although we're not given a y-intercept here, we are given a point $(1,-8)$. Let's check this out:
$-8=a(1+4)(1+1)^2(1-3)$
$-8=-40a$
$a=\frac{1}{5}$
So, this specific poly is:$$f(x)=\frac{1}{5}(x+4)(x+1)^2(x-3)$$
## How to Sketch Polynomial Functions
$$h(x)=-2(x-7)(x+ \frac{1}{2})^{2}(x+4)^{3}(x^2+9)^2$$
1. leading term: $-2x^{1}\cdot x^{2}\cdot x^{3}\cdot x^{2\cdot2} =-2x^{10}$
	- degree: $10$
	- max turning point: $n-1=9$
	- end behavior: downward-facing parabola
2. y-intercept:
	- y-intercept are just where $x=0$, so:
		- $h(0)=-2(0-7)(0+ \frac{1}{2})^2(0+4)^{3}(0^{2}+9)^{2}$
		- $h(0)=-2(-7)(\frac{1}{4})(64)(81)$
		- $h(0)=18144$
		- So our y-intercept is: $(0,18144)$
3. x-intercept:
	- x-intercept are just where $f(x)=0$, so:
		- $0=-2(x-7)(x+ \frac{1}{2})^{2}(x+4)^{3}(x^2+9)^2$
		- using zero product property:
			- $x=7$, mult. 1
			- $x=- \frac{1}{4}$, mult. 2
			- $x=-4$, mult. 3
			- $x^{2}+9$ does not count as it is a *irreducible quadratic* and cannot be factored further under real numbers.
				- if it were to be $(x^{2}-9)$ instead? we would factor that and become $(x-3)^{2}(x+3)^{2}$, which *would* count towards our x-intercepts.

Next example:$$f(x)=x^2(x-3)$$
1. leading term: $x^3$
	- max T.P.s: $n-1=2$
	- end behavior: climbing (positive) cubed power function
1. y-intercept:
	- $f(0)=0^{2}(0-3)$
	- $f(0)=0$
	So: $(0,0)$
3. x-intercept:
	- $0=x^{2}(x-3)$
	- zero product property:
		- $x=0$, mult. 2
		- $x=3$, mult. 1
 Since our y-intercept is also on our x-axis, we should use another value for better reference. Say $x=1$:
 $f(1)=1^2(1-3)$
 $f(1)=-2$
 So $(1,-2)$.
 The local min will be $(2,-4)$. You'll learn how to find this in calculus 1. For now you actually only need the points you've made above to "sketch" the graph:
 ![[Pasted image 20240816164554.png]]
 now this is not really exact but it gives a good idea of how the function looks.
 ![[Pasted image 20240816164703.png]]
 *See*? Good enough.
### More examples
$$f(x)=-2(x+2)(x-2)^3$$
1. leading term: $-2x\cdot x^{3}=-2x^{4}$
	- degree: 4
	- max TPs: 3
	- End behavior: downward-facing parabola
2. y-intercept:
	- $f(0)=-2(0+2)(0-2)^{3}$
	- $f(0)=32$
	So: $(0,32)$
3. x-intercept:
	- $0=-2(x+2)(x-2)^{3}$
	- zero product property:
		- $x=-2$, mult. 1 (cross)
		- $x=2$, mult. 3 (cross)
![[Pasted image 20240816165556.png]]
	Look... it's hard to draw with a mouse, okay?
FYI: we would get a better reference for our graph if we also evaluate $f(1)$.

Next example:$$h(x)=(x+4)^2(1-x)$$
re-arrange: $h(x)=(x+4)^{2}\cdot(-1)(x-1)$
$h(x)=-(x+4)^{2}(x-1)$
1. leading term: $-x^{3}$
	- degree: 3
	- max TP: 2
	- end behavior: reflected (falling) cubed power function
2. y-intercept:
	- $h(0)=-(0-1)(0+4)^2$
	- $h(0)=16$
	So: $(0,16)$
3. x-intercept:
	- $0=-(x-1)(x+4)^2$
	- zero product property
		- $x=1$, mult. 1 (cross)
		- $x=-4$, mult. 2 (bounce)
![[Pasted image 20240816170324.png]]
	Okay. That's horrible.
![[Pasted image 20240816170428.png]]
	That's actually much closer than I thought it would be. 
	To make it looks better:
	- We can evaluate more points for reference e.g. $f(-1)$, etc.
	- If we know calculus 1, we could find the local max.

Next example:$$f(x)=-5x(x^2-4)(x+3)$$
1. leading term: $-5x^{1+2+1}=-5x^{4}$
	- degree: 4
	- max TP: 3
	- end behavior: downward-facing parabola
2. y-int:
	- $f(0)=-5(0)(0^2-4)(0+3)$
	- $f(0)=0$
	So, $(0,0)$
3. x-int:
	 - $0=-5x(x^2-4)(x+3)$
	 - $0=-5x(x+2)(x-2)(x+3)$
	 - zero product property:
		- $x=0$, mult. 1
		- $x=-2$, mult. 1
		- $x=2$, mult. 1
		- $x=-3$, mult. 1
Since our y-intercept is on x-axis, let's evaluate another point for reference:
$f(1)=-5(1)(1^2-4)(1+3)$
$f(1)=-5(1)(-3)(4)$
$f(1)=60$
So we have another point in the function: $(1, 60)$
![[Pasted image 20240816171728.png]]
![[Pasted image 20240816171806.png]]
	Just about. The hand drawn are all estimates regarding the local max and min so it is a miracle how close it is.

Last example:$$g(x)=2(x-1)^2(x^2-16)$$
- Leading term: $2x^{2+2}=2x^4$
	- degree: 4
	- max TP: 3
	- end behavior: upward facing parabola
- y-intercept:
	- $g(0)=2(0-1)^2(0^2-16)$
	- $g(0)=2(1)(-16)$
	- $g(0)=-32$
	So, $(0,-32)$
- x-intercept:
	- First, we must also factor $x^2-16$ since it is factorable: $g(x)=2(x-1)^{2}(x-4)(x+4)$
	- $0=2(x-1)^{2}(x-4)(x+4)$
	- zero product property:
		- $x=1$, mult. 2 (bounce)
		- $x=4$, mult. 1 (cross)
		- $x=-4$, mult. 1 (cross)
![[Pasted image 20240816172757.png]]
![[Pasted image 20240816172811.png]]
	we're off by a huge mark here with our local mins on TP 1 and TP 3. But the general shape is correct (which is mostly due to our determination of end behavior from the leading term).

## Synthetic Division and Long Division of Polynomials

We're going to be using this a lot for [[#Decartes Rule of Signs]] and in [[#How to Use the Rational Zeros Theorem|Rational Zeros Theorem]] (which gives a list of rational number that potentially are factors of your polynomial). But first, we must introduce the concept of *Factor Theorem*.
### Factor Theorem

The theorem states:
```
If, upon division, you get a remainder of '0', your divisor is a factor of your dividend.
```
![[Pasted image 20240816180659.png]]
![[Pasted image 20240816180805.png]]
- $6$ is a factor of $48$

Say, we are going to check if $x=1$ is a x-intercept of $f(x)=2x^3-x^2+2x-3$. So we're testing if this statement is *True*: $f(1)=0$.
$f(1)=2(1)^3-(1)^2+2(1)-3$
$f(1)=2-1+2-3$
$f(1)=0$
Yes this is an x-intercept. So $(x-1)$ is a factor of our poly. This is just a fact checker for our long division results.

Let's do a long division with $(x-1)$ of the polynomial to check if it is a factor (it feels redundant at this point, but this is to teach a concept). A few points before we begin:
1. make sure that we do have the poly in order (highest -> lowest degree)
2. where do we get the $(x-1)$? From the Rational Zero Theorem which you'll soon learn.
Here's the setup. Let's begin:![[Pasted image 20240816181855.png]]
1. divide the first term of the dividends by the first term of the divisor: $\frac{2x^{3}}{x}=2x^{2}$
	1. the first term of the dividends will *always* be subtracted away (eliminated)
2. we put $2x^{2}$ as the first part of our quotient
3. now we distribute $2x^{2}$ to $(x-1)$
![[Pasted image 20240816182252.png]]
	- be very very very aware of sign error here. what's going on is you're subtracting a poly with a poly so: $(2x^{3}-x^{2})-(2x^{3}-2x^{2})=2x^{3}-x^{2}-2x^{3}+2x^{2}$. 
![[Pasted image 20240816182425.png]]
	Put a parentheses to avoid this sign error
4.  Pull the next term down as you would a when long dividing an integer![[Pasted image 20240816182600.png]]
5. Repeat step 1 until complete. So:
	1. $\frac{x^{2}}{x}=x$
	2. We add $+x$ as the next part of the quotient.
	3. we distribute $x$ to $x-1$ and subtract from $x^{2}+2x$
	4. and so on... (notice the algorithmic nature of the process.)
![[Pasted image 20240816182928.png]]
We got a 0! This means that $(x-1)$ is a factor of $f(x)$ according to *Factor Theorem*. So, now we get:$$f(x)=(x-1)(2x^2+x+3)$$
$2x^2+x+3$ is no longer factor-able.
- $x=\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}$
- $x=\frac{-(1)\pm\sqrt{(1)^{2}-4(2)(3)}}{2(2)}$
- $x=\frac{-1\pm\sqrt{-23}}{4}$
We're done here since there is clearly an $i$ involved here. But say that instead of $2x^2+x+3$, we have $2x^{4}+x+3$. Now this seems like it might be further factor-able and thus we should repeat the long division process until we get all the factors.

We have another way to this which is shorter, called *Synthetic Division*. The downside is that it does not work (or does not work as well) for every divisor.
	it only works for *straight lines* as a *divisor* e.g. $x+1$, $2x-1$, etc. and not things like $x^4$, $x^3-8$
Let's try this method out with $f(x)=2x^3-x^2+2x-3$:
This is the set-up.
![[Pasted image 20240816183922.png]]
Notice *how* we set this up:
![[Pasted image 20240816184112.png]]
- the *dividend* is the coefficient of each term
- the *divisor* is the x-intercept (not the factor like in long division)

Here are the steps:
1. pull down the first term
![[Pasted image 20240816184409.png]]
2. multiply that term with divisor
![[Pasted image 20240816184456.png]]
3. now *add* them together
![[Pasted image 20240816184548.png]]
4. repeat the process until finished
![[Pasted image 20240816184703.png]]
The final term (0) is our remainder, the same as the result of our long division.
Essentially, we were just lowering the exponent of each term by 1. 

See how we can get the quotient:![[Pasted image 20240816185012.png]]
So we have:$$f(x)=(x-1)(2x^2+x+3)$$
- rmb: although we used 1 as a divisor, we derived this from the factor of x-intercept which is $(x-1)$, NOT $(x+1)$. YOU know that you are prone to this kind of mistakes.
### More examples
$$g(x)=3x^6+82x^3+27$$
From my advanced calculus skill, I know that $x=-3$.
Let's do the long division first:
![[Pasted image 20240816200508.png]]
0! Yay! So $x+3$ is a factor of $g(x)$ (as my advanced calculus skill suggested):
$$g(x)=(x+3)(3x^5-9x^4+27x^3+x^2-3x+9)$$
We're done... for now. 
	Later, when we get to the *[[#How to Use the Rational Zeros Theorem|Rational Zeros Theorem]]*, we can still find more x-intercept in the $3x^5...$ by re-doing this until we're left with fewer terms.

Let's try the synthetic division:
![[Pasted image 20240816200155.png]]
Same results:
- our divisor $-3$ or $x+3=0$ is factor of $g(x)$
- we also got out the quotient which is $3x^5-9x^4+27x^3+x^2-3x+9$
So:$$g(x)=(x+3)(3x^5-9x^4+27x^3+x^2-3x+9)$$
Another example:
$$h(x)=4x^3-3x^2-8x+4$$
Once again, thanks to my my advanced calculus skill, I know that $x=2$.
Let's do the long division:
![[Pasted image 20240816201010.png]]
The remainder is NOT 0. So my advanced calculus skill is unreliable since $x=2$ or $(x-2)$ is NOT a factor of $h(x)$.

So, we've lost our time and mental energy on this for *nothing*? No, we can salvage this and still get something relevant out of it:
![[Pasted image 20240816201356.png]]
- notice the color code here
- this is useful on occasions e.g. in calculus 2 when we do *integral*

Let's try synthetic division:
![[Pasted image 20240816201559.png]]
- same results: we got a remainder of 8
- like in long division, we can salvage this and get a relevant quotient, which is $4x^{2}+5x+2+\frac{8}{x-2}$.
So:$$h(x)=(x-2)(4x^{2}+5x+2+\frac{8}{x-2})$$
- is this relevant? Yes. Is this very helpful? No, since $x=2$ is still not really our x-intercept.
## Descartes Rule of Signs

This is going to be very useful in solving polys using the [[#How to Use the Rational Zeros Theorem|Rational Zeros Theorem]]. This tell us the number of x-intercept you have *by counting the number of signs changes*! That's **crazy**! Using it with the RZ Theorem is going to be very powerful.
So, in steps:
1. Poly in order
	$f(x)=2x-2+2x^{2}=2x^{2}+2x-2$ (descending order)
2. count sign changes from left -> right
	==We will have either *the count* **OR** an *even number* (2,4,...) less than this count amount of **POSITIVE** x-intercept==. 
	e.g. $f(x)=-4x^{7}+x^{3}-x^{2}+2$, has 3 sign changes![[Pasted image 20240817134101.png]]
	We have either **3** (the *count*) **OR** 1 ($3-2=1$, 2 is the *even number*) is the amount of our POSITIVE ($x>0$) x-intercept.
		*Why* an even number less than the sign count? It has to do with *irreducible quadratics* and the poly's *degree*. So the poly's degree determine the *max* amount of x-intercepts that we could have, including both real and complex solutions. 
		Say we have some irreducible quadratics of our poly, for example: $x^{2}+25$, this would count towards our degree but NOT towards our number of *real* x-intercepts. And since we could factor and get 2 (notice the *even number*?) complex solutions out of it e.g. $(x+5i)(x-5i)$, that is why we subtract *even* numbers from our count of sign changes.
	Subtract with even numbers until we have 1 or 0 e.g. if we counted 5 sign changes, then the possible amount of x-ints is 5 or 3 ($5-2$) or 1 ($5-4$).
1. evaluate $f(-x)$ and repeat *step 2*
	==We will have either *the count* **OR** an *even number* (2,4,...) less than this count amount of **NEGATIVE** x-intercept. ==
	Why evaluate $f(-x)$? We are simply changing the signs of our *odd-powered* terms (in this case, $-4x^{7}, x^{3}$). Our *even-powered* terms and our *constant* will NOT be affected by this.
	e.g. $f(-x)=-4(-x)^{7}+(-x)^{3}-(-x)^{2}+2=4x^{7}-x^{3}-x^{2}+2$
	![[Pasted image 20240817140109.png]]
	We have either **2** (the *count*) **OR** 0 ($2-2=0$, 2 is the *even number*) is the amount of our NEGATIVE ($x<0$) x-intercept.
		either 2 or 0 means that, if you've found one negative intercept, there must be another one (since it's either 2 or none at all).
So, within our example, we know that we have AT MOST 5 x-intercept (3 positives and 2 negatives). With the degree of 7, this means that we're going to have AT LEAST 2 complex solutions or 1 irreducible quadratic. This is very valuable information.
### More examples
$$g(x)=-x^2+2x^3+2x-3$$
1. arrange it in order
$g(x)=2x^{3}-x^2+2x-3$
2. count the sign changes
There are 3 sign changes. So there must be either 3 or 1 ($3-2=1$) amount of POSITIVE x-intercept(s). 
3. evaluate $f(-x)$ repeat step 2
$g(-x)=-2x^{3}-x^{2}-2x-3$
There are 0 sign changes. This mean that we have 0 NEGATIVE x-intercept.

What does this mean? Note that with a degree of 3, I see 2 case scenarios:
1. We have 3 *positive* x-intercepts and no *negative* x-intercept.
2. We have 1 *positive* x-intercepts and 2 *complex* x-intercepts.

Let's proves this:
Set equal to 0:
$0=2x^{3}-x^2+2x-3$
$0=2x(x^{2}- \frac{1}{2}x+1)-3$
Let's do quadratic on the inside of the parentheses:
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$x=\frac{-(- \frac{1}{2})\pm\sqrt{(- \frac{1}{2})^2-4(1)(1)}}{2(1)}$
$x=\frac{\frac{1}{2}\pm\sqrt{- \frac{15}{4}}}{2}$
Okay, it seems like we have found our 2 complex x-intercepts. This likely fit with our second scenario, so we just need to find that 1 *positive* x-intercepts. We *cannot* really do this without the *rational zeros theorem* (highlighting its importance), or brute-forcing this by testing every positive integer. ![[Pasted image 20240817144954.png]]
	I cheated and use a graph. Apparently, the single positive x-int that we have is $x=1$. 

$$h(x)=3x^6+82x^3+27$$
1. arrange it in order (it already is in order)
2. count the sign changes
There are none. So we have 0 positive x-int.
3. evaluate $f(-x)$ repeat step 2
$h(x)=3x^{6}-82x^{3}+27$
There either are 2 negative x-ints OR none at all ($2-2=0$).

Note that with the degree of 6, there should be 2 case scenarios:
1. There are 2 negative x-ints and 4 complex x-ints (or 2 irreducible quadratics)
2. There are no real x-ints and 6 complex x-ints (or 3 irreducible quadratics)

Let's proves this:
Set equal to 0:
$0=3x^6+82x^3+27$
Say $u=x^3$, we have $0=3u^2+82u+27$.
$u=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$u=\frac{-(82)\pm\sqrt{(82)^2-4(3)(27)}}{2(3)}$
$u=\frac{-82\pm\sqrt{6400}}{6}$
$u=\frac{-82\pm\sqrt{6400}}{6}$
$u=\frac{-82\pm80}{6}$
So $u=- \frac{1}{3}$ or $u=-27$
Since $u=x^{3}$:
1. $u=- \frac{1}{3}$
$x^{3}= - \frac{1}{3}$
$x=\sqrt[3]{- \frac{1}{3}}$
- note: this is not an even root so we don't need to put $\pm$ here.
$x=-\frac{\sqrt[3]9}{3}\approx-0.693...$
2. $u=-27$
$x^3=-27$
$x=\sqrt[3]{-27}$
$x=-3$

We have 2 negative x-ints and this coincides with the first scenario.![[Pasted image 20240817143340.png]]
## How to Use the Rational Zeros Theorem

Rmb: The main *goal* of this is to find the *factors* of our polys. 

So, the Rational Zeros Theorem:$$f(x)=a_nx^n+...+a_0=$$
1. Find factors of $a_0$ (constant) and call them $p$
2. Find factors of $a_n$ (leading coefficient) and call them $q$
3. Make a list of all possible $\frac{p}{q}$.
4. Check with [[#Descartes Rule of Signs]] and keep it in mind going forward to eliminate some of the choices.
	- notice how this make the whole process MUCH less tedious
5. We evaluate the remaining choice to see if it's a factor (check if $f(\frac{p}{q})=0$).
6. If you find a factor, we can use [[#Synthetic Division and Long Division of Polynomials|synthetic or long division on polys]] to get the quotient.
7. With the new quotient, go through the list again to check for [[#Multiplicity|multiplicity]].
8. Repeat step 4 until satisfied.

For example:$$f(x)=2x^3+11x^2-7x-6$$To take a little notes of our initial observations:
- end behavior: climbing cubed power functions ($2x^3$)
- degree of 3 (at most 3 x-ints)
- y-int at $(0,6)$
- [[#Descartes Rule of Signs]], considering that we have a degree of 3:
	- 1 positive x-int
	- $f(-x)=-2x^3+11x^2+7x-6$: 2 or 0 negative x-int
	- I see 2 scenarios that make sense:
		- 1 *positive* and 2 *negative* x-int
		- 1 *positive* and 2 *complex* x-int

Okay, let's begin:
- our $a_0=-6$, what is the factors of $-6$ (or $6$, since we get the same list of number regardless of sign anyway):
	- $p=[\pm1,\pm2,\pm3,\pm6]$
		- notice that we have 4 *negatives* and 4 *positives*, and rmb our results from the *descartes rule of signs*.
- our $a_n=2$, what is the factors of $2$:
	- $q=[\pm1,\pm2]$
		-  notice that we have 2 *negatives* and 2 *positives*
- make a list of all possible $\frac{p}{q}$.
	- $\frac{p}{q}=[\pm1,\pm2,\pm3,\pm6,\pm \frac{1}{2},\pm \frac{2}{2},\pm \frac{3}{2},\pm \frac{6}{2}]$
		- notice that there are some duplicates here, we can ofc remove those
	- $\frac{p}{q}=[\pm1,\pm2,\pm3,\pm6,\pm \frac{1}{2},\pm \frac{3}{2}]$
		- now we have a list of 12 candidates for our x-intercept
- let's evaluate some of the numbers on the list:
$f(1)=2(1)^3+11(1)^2-7(1)-6$
$f(1)=2+11-7-6$
$f(1)=0$
Lucky! We already found our first factor: $(x-1)$, let's get the quotient using synthetic division:
![[Pasted image 20240817160127.png]]
$f(x)=(x-1)(2x^2+13x+6)$
- We've found 1 positive x-int out of 1. So there are 2 x-ints left but it can be either both complex or both negative. Our quotient: $2x^2+13x+6$, is a quadratic, making this much easier by factoring instead of repeating the whole process again.
![[Pasted image 20240817160516.png]]
So the factor of $2x^2+13x+6$ is $(x+6)(2x+1)$. Thus, we have 2 more negative x-ints: $x=-6$ and $x=- \frac{1}{2}$. Now we have:$$f(x)=(x-1)(x+6)(x- \frac{1}{2})$$Note: all of our factors have a [[#Multiplicity|multiplicity]] of 1 (odd), making all x-intercepts *cross* the x-axis.

This is a perfect fit for our first scenario of having 1 *positive* ($x=1$) and 2 *negative* x-int ($x=-6$ and $x=- \frac{1}{2}$). All seems good but let's check again with a graph to by triply sure:
![[Pasted image 20240817161239.png]]
Perfect fit.

Another example:$$h(x)=3x^3+6x^2-15x-30$$Initial observations:
- $3x^3$: climbing odd power function
- degree: 3
- y-int at $(0,-30)$
- rule of signs:
	- 1 sign change $\implies$ 1 positive x-int
	- $h(-x)=-3x^3+6x^2+15x-30$: 2 sign change $\implies$ 2 or 0 negative x-int
	- 2 scenarios:
		- 1 positive x-int and 2 negative x-ints
		- 1 positive x-int and 2 complex x-ints

Before considering our rational zeros, let try factoring first:
$h(x)=3x^3+6x^2-15x-30$
$h(x)=3x(x^2+2x-5)-30$
$h(x)=3x(x-1+\sqrt{6})(x-1-\sqrt{6})-30$
This does not looks nice at all. Let's evaluate our approach:
$h(x)=3x^3+6x^2-15x-30$
Using grouping:
$h(x)=3x^2(x+2)+(-15)(x+2)$
$h(x)=(3x^2-15)(x+2)$
$h(x)=3(x^2-5)(x+2)$
Notice that $(x^2-5)$ can be factored further:
$h(x)=3(x-\sqrt{5})(x+\sqrt{5})(x+2)$
We already have 3 x-int: $x=-2,x=-\sqrt{5}$ and $x=\sqrt{5}$. 2 negatives and 1 positive, which fits the first scenario. We're done here but let's recheck with $\frac{p}{q}$ list again.

Consider our list of $\frac{p}{q}$:
- our $a_0$ or constant is -30, so our $p=[\pm1,\pm2,\pm3,\pm5,\pm6,\pm10,\pm15,\pm30]$
- our $a_n$ is 3, so our $q=[\pm1,\pm3]$
- $\frac{p}{q}=[\pm1,\pm2,\pm3,\pm5,\pm6,\pm10,\pm15,\pm30, \pm \frac{1}{3},\pm \frac{2}{3},\pm \frac{3}{3},\pm \frac{5}{3},\pm \frac{6}{3},\pm \frac{10}{3},\pm \frac{15}{3},\pm \frac{30}{3}]$
	- eliminating the dupes: $\frac{p}{q}=[\pm1,\pm2,\pm3,\pm5,\pm6,\pm10,\pm15,\pm30, \pm \frac{1}{3},\pm \frac{2}{3},\pm \frac{5}{3},\pm \frac{10}{3}]$
Notice how $x=-\sqrt{5}$ and $x=\sqrt{5}$ is **NOT** within the list, as they are *irrational* numbers (the theorem's name is literally "*Rational* Zeros Theorem"). 
	This highlights the fact that our $\frac{p}{q}$ list will not give us *everything* but a starting point (which is very useful but NOT everything). 

### More examples
$$g(x)=x^5-7x^4+19x^3-37x^2+60x-36$$Initial observations:
- $x^5$: climbing *odd* power function
- degree: 5
- y-int at $(0,-36)$
- rule of signs:
	- 5 sign change $\implies$ 5 or 3 ($5-2=3$) or 1 ($5-4=1$) positive x-ints (that's a lot...)
	- $h(-x)=-x^5-7x^4-19x^3-37x^2-60x-36$: 0 sign change $\implies$ no negative x-int
	- A few possible scenarios: 
		- 5 positive x-int
		- 3 positive x-ints & 2 complex x-ints
		- 1 positive x-ints & 4 complex x-ints

Try factoring first:
$g(x)=x^3(x^2-7x+19)+(-1)(37x^2-60x+36)$
let's do [[#Using the Quadratic Formula|quadratic formula]] for both factored quadratics:
Me from the future: I've tried this with horrendous results. We got $\frac{7\pm3\sqrt{3}i}{2}$ and $\frac{60\pm\sqrt{1728}i}{72}$. Do not come this way. It is too dark in here... It is not a very smart approach to do group it in such a way anyway since our main goal is to find all factors.

Let's do our rational zeros then:
- $a_0=-36$ so our $p=[\pm 1,\pm 2,\pm 3,\pm 4,\pm 6,\pm 9, \pm 12, \pm 18, \pm 36]$, that's a total of 18, with 9 each for positive and negatives.
- $a_n=1$ so our $q=[\pm 1]$
- $\frac{p}{q}=[\pm 1,\pm 2,\pm 3,\pm 4,\pm 6,\pm 9, \pm 12, \pm 18, \pm 36]$
	- from our rule of signs, we know that our solutions are strictly positive so we can cut down *half* of our work (hooray!): $\frac{p}{q}=[1,2,3,4,6,9,12,18,36]$
let's evaluate starting with $g(1)$:
$g(1)=(1)^5-7(1)^4+19(1)^3-37(1)^2+60(1)-36$
$g(1)=1-7+19-37+60-36$
$g(1)=0$
Lucky! $x=1$ or $(x-1)$ is one of our factor (which may be our only one, or one of three ,or one of five x-ints to be found), let's do a synthetic division:
![[Pasted image 20240817175849.png]]
So we have:
$g(x)=(x-1)(x^{4}-6x^{3}+13x^{2}-24x+36)$

Let's continue with our next $\frac{p}{q}$ with our new (and more convenient) arrangements for $g(x)$:
$g(x)=(x-1)(x^{4}-6x^{3}+13x^{2}-24x+36)$
- the $(x-1)$ factor in the front does not really matter, since if the second parentheses sum up to 0 then 0 multiplied by anything will equal to 0.
$g(2)=((2)-1)((2)^{4}-6(2)^{3}+13(2)^{2}-24(2)+36)$
$g(2)=(1)(16-6(8)+13(4)-24(2)+36)$
$g(2)=(1)(16-48+52-48+36)$
$g(2)=8$
Not so lucky this time... Let's continue:
$g(3)=(3)^5-7(3)^4+19(3)^3-37(3)^2+60(3)-36$
$g(3)=243-7(81)+19(27)-37(9)+60(3)-36$
$g(3)=243-567+513-333+180-36$
$g(3)=0$
Note from the future: I mistakenly did this for our original arrangement of the function, but I'll leave this here just to show that the results will be the same anyway:
$g(3)=(3-1)((3)^{4}-6(3)^{3}+13(3)^{2}-24(3)+36)$
$g(x)=(2)(81-6(27)+13(9)-24(3)+36)$
$g(x)=(2)(81-162+117-72+36)$
$g(x)=(2)(0)$
$g(x)=0$

$x=3$ or $(x-3)$ is one of our factor. Now that we found 2 there must be at least 1 more (than can be up to 3 more). let's do a synthetic division with $(x^{4}-6x^{3}+13x^{2}-24x+36)$:
![[Pasted image 20240817180819.png]]
$g(x)=(x-1)(x-3)(x^3-3x^2+4x-12)$
Before we proceed, we can attempt factoring here and hope for the best:
$g(x)=(x-1)(x-3)[x^{2}(x-3)+4(x-3)]$
$g(x)=(x-1)(x-3)(x-3)(x^{2}+4)$
$g(x)=(x-1)(x-3)^{2}(x^{2}+4)$

We're done here. 
- We've found 3 real and positive solutions for x-ints, with one being $x=1$ with mult. of 1 and another being $x=3$ with mult. of 2, which adds up to 3 as expected. 
		This means that at $x=1$ the line will *cross* the x-axis and bounce at $x=3$. This matches the end behavior we expected.
- We also have found an *irreducible quadratic* in $(x^{2}+4)$, which gives 2 complex solutions, thus fitting our *second* expected scenario.
![[Pasted image 20240817183342.png]]

$$f(x)=2x^5-x^4+48x^3-24x^2-50x+25$$
Initial observations:
- $x^5$: climbing *odd* power function
- degree: 5
- y-int at $(0,25)$
- rule of signs:
	- 4 sign change $\implies$ 4 or 2 ($4-2=2$) or 0 ($4-4=0$) positive x-ints
	- $f(-x)=-2x^5-x^4-48x^3-24x^2+50x+25$: 1 sign change $\implies$ 1 negative x-int
	- 3 possible scenarios: 
		- 1 negative x-int and 4 positive x-ints
		- 1 negative x-int and 2 positive x-ints and 2 complex x-int
		- 1 negative x-int and 0 positive x-ints and 4 complex x-int

Let's do our rational zeros:
- $a_0=25$ so our $p=[\pm 1,\pm 5, \pm 25]$
- $a_n=2$ so our $q=[\pm 1, \pm 2]$
- $\frac{p}{q}=[\pm 1,\pm 5, \pm 25, \pm \frac{1}{2},\pm \frac{5}{2}, \pm \frac{25}{2}]$

Let's evaluate, let's start with the negative root first since there'll surely be 1:
$f(-1)=2(-1)^5-(-1)^4+48(-1)^3-24(-1)^2-50(-1)+25$
$f(-1)=-2-1-48-24+50+25$
$f(-1)=0$
Thank the gods. $x=-1$ (or $(x+1)$) is our only negative x-ints:
![[Pasted image 20240817184611.png]]
$f(x)=(x+1)(2x^4-3x^3+51x^2-75x+25)$

Let's continue, now with positives:
$f(1)=(1+1)(2(1)^4-3(1)^3+51(1)^2-75(1)+25)$
$f(1)=(2)(2-3+51-75+25)$
$f(1)=0$
Another jackpot. $x=1$ or $(x-1)$ is our one of our positive roots:
![[Pasted image 20240817185151.png]]
$f(x)=(x+1)(x-1)(2x^3-x^2+50x-25)$
We can group this:
$f(x)=(x+1)(x-1)[x^2(2x-1)+25(2x-1)]$
$f(x)=(x+1)(x-1)(2x-1)(x^2+25)$
We're done here. 1 negative x-int and 2 positive x-ints and 2 complex x-ints from the irreducible quadratic: $(x^2+25)$, fitting the expected second scenario. 
![[Pasted image 20240817190056.png]]
## Introduction to Complex Solutions of Polynomials

Every poly can be factored into linear & irreducible quadratics over the REAL number system. But. if we allow complex solutions, a poly can be factored into all linears.

Notes:
- A *conjugate* of $a+bi$ is $a-bi$ and vice versa
- All complex solutions come in *conjugate pairs*:
	- if we get $2-3i$, we're guaranteed another complex solution: $2+3i$
	- if we get $-7+5i$, we're guaranteed another complex solution: $-7-5i$
Think about what make irreducible quadratics, irreducible quadratics? 
$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
We get an irreducible quadratics when $b^2-4ac$ aka. the *discriminant*, is *negative*. 
$x=\frac{-b}{2a}\pm\frac{\sqrt{\text{some negative numbers}}}{2a}$
$x=\frac{-b}{2a}\pm\frac{\sqrt{\text{some numbers }}\cdot i}{2a}$
Using complex system allows us to further reduce *irreducible* quadratics which will be in the form of $a+bi$.

For example:
A degree 6 poly has the following zeros: $2, 2+i, -3-i, 0$
	Notice that we only have 4 when we should have 6. 
	$2+i$ and $-3-i$ are complex solutions and they must come in pairs due to the $\pm$ in quadratic equation we mentioned above. So, we must also include $2-i$ and $-3+i$ as part of our solutions.
Notice how the no. of our complex solutions are always going to be *even*, since they come in pairs.

A degree 7 poly has the following zeros: $i, 3-2i, -4, -2+i$
	We must also include $0-i$, $3+2i$, and $-2-i$ to complete our pairs.
	So, we have 1 real solution and 6 complex solutions.
Notice that a poly with odd degree MUST have a least one real x-intercept (unlike even degree polys aka. parabolas).
![[Pasted image 20240817205411.png]]
## Creating Polynomials from Complex Solutions

For example:
Say we have a degree 4 poly with the following zeros: $3+2i$ and $4$ - mult.2
	We already have 2 real solutions ($x=4$ mult.2 or repeated twice) and complex solutions come in pairs, so $3+2i$ comes with its conjugate pair: $3-2i$.
$f(x)=(x-4)^{2}(x+3+2i)(x+3-2i)$
Easy. Is this correct? Let's see:
- $x=3+2i \implies x-3+2i=0$
	- we also want to group the real part and separate them from imaginary part so: $(x-3)+2i=0$
- $x=3-2i \implies x-3-2i=0$
	- separate real from imaginary: $(x-3)-2i=0$
- $x=4 \implies x-4=0$ with mult. 2
Once again, BEWARE OF THE SIGNS:
$f(x)=(x-4)^{2}(x-3+2i)(x-3-2i)$
There. Done? Well... no. Remember that [[#Creating Polynomials from Real Zeros|this chapter]] and how we can add *any number* in the front, and the roots will still be the same? This is applicable here, so the correct one would be:$$f(x)=a(x-4)^{2}[(x-3)+2i][(x-3)-2i]$$Done? Almost. You still have to distribute the complex solutions to get irreducible quadratics. This is why we needed to separate the real and imaginary part so we can use FOIL easily:
$f(x)=a(x-4)^{2}[(x-3)^{2}-2i(x-3)+2i(x-3)-2^2i^2]$
- With such arrangement, Outer and Inner will *always* cancel each other out. 
$f(x)=a(x-4)^{2}[(x-3)^{2}+4]$
$f(x)=a(x-4)^{2}[(x^2-3x-3x+9)+4]$
$f(x)=a(x-4)^{2}(x^2-6x+13)$
We can be done here. But if you want to, you can still distribute the first term:
$f(x)=a(x^2-8x+16)(x^2-6x+13)$
For a perfect score, we can distribute one more time to get a degree 4 poly:
$f(x)=a(x^4-14x^3+77x^2-200x+208)$
We're done. If we have a reference point like a y-intercept, we could solve for $a$, but in this case where were not given a point, leave it there.
### More examples
Say we have a degree 4 poly with the following zeros: $i$ and $1+2i$
	So we have a parabola that never touches x-axis on the real plane. The another pair of complex solutions is $-i$ and $1-2i$.
Let's spread it out:
- $x=i \implies x-i=0$
- $x=-i \implies x+i=0$
- $x=1+2i \implies (x-1)+2i=0$
- $x=1-2i \implies (x-1)-2i=0$
$f(x)=a(x-i)(x+i)[(x-1)+2i][(x-1)-2i]$
Let's distribute:
$f(x)=a(x^2+1)[(x-1)^{2}+4]$
The first term is irreducible but the second term is:
$f(x)=a(x^{2}+1)[(x^2-2x+1)+4]$
$f(x)=a(x^{2}+1)(x^2-2x+5)$
$f(x)=a(x^4-2x^3+6x^2-2x+5)$

Say we have a degree 5 poly with the following zeros: 1 mult. 3 and $1+i$
	the conjugate pair of $1+i$ is $1-i$. Thus, we now have 5 solution matching the degree.
Listing it out:
- $x-1=0$, mult. 3 (*cross*)
- $(x-1)+i=0$
- $(x-1)-i=0$
So:
$f(x)=a(x-1)^{3}[(x-1)+i][(x-1)-i]$
$f(x)=a(x-1)^{3}[(x-1)^{2}+1]$
$f(x)=a(x-1)^{3}[(x^{2}-2x+1)+1]$
$f(x)=a(x-1)^{3}(x^{2}-2x+2)$
We can distribute further but it's a bit tedious so I'll skip.
### Finding ALL Solutions of Polynomials

Steps:
1. Find a zero
2. Create a factor
	- linear for a REAL zero and use [[#Synthetic Division and Long Division of Polynomials|synthetic division]]
	- quadratic for a complex pair and use [[#Synthetic Division and Long Division of Polynomials|long division]]
3. Try to factor or repeat.

For example:$$f(x)=x^3-4x^2+4x-16$$Has a zero of $2i$. Find the rest:

Initial observation:
- we have a degree 3 poly
- y-int at $(0,-16)$
- [[#Descartes Rule of Signs|Rule of signs]]:
	- 3 or 1 positive x-ints
	- $f(-x)=-x^3-4x^2-4x-16$: 0 negative int
	- 2 scenarios:
		- all 3 x-ints real positive number
			- this is impossible due to the given $2i$ as one of the complex solutions.
		- 1 x-int is a positive number and the rest are complex pair
			- This scenario is the only one that fits.
- Conjugate pair of $2i$ is $-2i$

Spreading this out: 
- $x-2i=0$
- $x+2i=0$
Let's turn this into a irreducible quadratic before using it for long division:
$(x-2i)(x+2i)=x^2+4$
![[Pasted image 20240817215306.png]]
The only real positive x-int is $x=4$. We got all x-ints for a degree 3 poly now:
$f(x)=a(x^{2}+4)(x-4)$
Let's find $a$ from our y-intercept first before we distribute further:
$-16=a(0^{2}+4)(0-4)$
$-16=-16a$
$a=1$
Completing our poly:$$f(x)=x^3-4x^2+4x-16$$So:
- leading term: $x^3$
- end behavior: climbing cubed power function
- has the following zeros: $x=4$, $x=2i$, and $x=-2i$
![[Pasted image 20240817215923.png]]

### More examples
$$g(x)=x^4 -9x^3 +21x^2+21x-130$$Has a zero of $3-2i$. Find the rest:

Initial observations:
- we have a degree 4 poly
- y-int at $(0,-130)$
- [[#Descartes Rule of Signs|Rule of signs]]:
	- 3 or 1 positive x-ints
	- $f(-x)=x^{4}+9x^{3}+21x^{2}-21x-130$: 1 negative int
	- only 1 possible scenario: 1 negative int, 1 positive int, and 2 complex ints (given by the example)
- Conjugate pair of $3-2i$ is $3+2i$
	- $(x-3)+2i=0$
	- $(x-3)-2i=0$

Okay, let's get the irreducible quadratic first:
$[(x-3)+2i][(x-3)-2i]=(x-3)^{2}+4=(x^2-6x+9)+4=x^2-6x+13$
We can use $x^2-6x+13$ to do long division:
![[Pasted image 20240817221648.png]]
So:
$f(x)=(x^2-6x+13)(x^2-3x-10)$
Let's try factoring the second parentheses:
![[Pasted image 20240817221744.png]]
So: 
$f(x)=(x^2-6x+13)(x-5)(x+2)$
So our x-ints are: $x=5,x=-2,x=3-2i,x=3+2i$
	1 negative int, 1 positive int, and 2 complex ints as expected.
![[Pasted image 20240817222059.png]]

$$f(x)=x^4 -1$$
Initial observations:
- degree: 4
- y-int: $(0,-1)$
- This one is just $x^4$ parabola shifted down, so we know that it will have 1 negative and 1 positive solution. There will likely be a complex pair.

We can factor this:
$f(x)=x^4 -1$
- this feel just like a difference of squares
$f(x)=(x^2-1)(x^2+1)$
- the 1st parentheses is certainly a difference of squares and the 2nd one is an irreducible quadratic.
$f(x)=(x+1)(x-1)(x^2+1)$
Within the complex number system, we can further factor the $(x^{2}+1)$, which would be $(x+i)(x-i)$. So:
$f(x)=(x+1)(x-1)(x+i)(x-i)$
So our x-intercepts are $x=-1, x=1, x=-i, x=i$. 1 negative and 1 positive solution. There will likely be a complex pair as expected.
![[Pasted image 20240818011008.png]]

$$g(x)=x^4+13x^2+36$$
Initial observations:
- we have a degree 4 poly
- y-int at $(0,36)$
- This one is just $x^4$ parabola shifted up (floating above the x-axis). It is expected that we will have 4 complex solutions.
	- Rule of signs agree with this as there is no sign changes for both the original function and from evaluating $f(-x)$

Substitute $x^{2}=u$ and set the equation to 0:
$0=u^{2}+13u+36$
$0=(u+9)(u+4)$
So $u=-9$ and $u=-4$
- $u=-9$
$x^2=-9$
$x=\pm \sqrt{-9}$
$x=\pm3i$
- $u=-4$
$x^2=-4$
$x=\pm\sqrt{-4}$
$x=\pm2i$
We now have 2 conjugate pairs from our complex solutions, totaling 4 solutions, namely: $x=3i, x=-3i, x=2i, x=-2i$.$$g(x)=(x-3i)(x+3i)(x-2i)(x+2i)$$![[Pasted image 20240818130213.png]]

$$f(x)=x^4+2x^3+22x^2+50x-75$$Initial observations:
- leading term: $x^4$
	- degree: 4
	- end behavior: upward facing parabola
- y-int: $(0,-75)$
- Rule of signs:
	- 1 sign changes $\implies$ 1 positive x-int
	- evaluate $f(-x)=x^4-2x^3+22x^2-50x-75$. 3 sign changes $\implies$ 3 or 1 negative x-ints
	- 3 scenarios:
		- 1 positive, 1 negative, 2 complexes
		- 1 positive, 3 negatives

Let's list out our $\frac{p}{q}$:
- $p=[\pm 1,\pm 3,\pm 5, \pm 15, \pm 25, \pm 75]$
- $q=[\pm1]$
- $\frac{p}{q}=[\pm 1,\pm 3,\pm 5, \pm 15, \pm 25, \pm 75]$
Let's evaluate with 1 and -1 first:
$f(1)=(1)^4+2(1)^3+22(1)^2+50(1)-75$
$f(1)=1+2+22+50-75$
$f(1)=1+2+22+50-75$
$f(1)=0$
We've found our only positive x-int: $x=1$ (or $(x-1)$ as a factor):
![[Pasted image 20240818131210.png]]
So we have:$$f(x)=(x-1)(x^3+3x^2+25x+75)$$From grouping:
$f(x)=(x-1)[x^2(x+3)+25(x+3)]$
$f(x)=(x-1)(x+3)(x^{2}+25)$
$f(x)=(x-1)(x+3)(x+5i)(x-5i)$
Done. Our x-ints are $x=1, x=-3,x=-5i,x=5i$, fitting our first scenario of 1 positive, 1 negative, 2 complexes.
![[Pasted image 20240818133226.png]]

$$g(x)=3x^4+5x^3+25x^2+45x-18$$
Initial observations:
- leading term: $3x^4$
	- degree: 4
	- end behavior: upward facing parabola
- y-int: $(0,-18)$
- Rule of signs:
	- 1 sign changes $\implies$ 1 positive x-int
	- evaluate $f(-x)=3x^4-5x^3+25x^2-45x-18$. 3 sign changes $\implies$ 3 or 1 negative x-ints
	- 3 scenarios:
		- 1 positive, 1 negative, 2 complexes
		- 1 positive, 3 negatives

Let's list out our $\frac{p}{q}$:
- $p=[\pm 1,\pm 2,\pm 3,\pm 6,\pm 9,\pm 18]$
- $q=[\pm1,\pm 3]$
- $\frac{p}{q}=[\pm 1,\pm 2,\pm 3,\pm 6,\pm 9,\pm 18,\pm \frac{1}{3},\pm \frac{2}{3},\pm \frac{3}{3},\pm \frac{6}{3},\pm \frac{9}{3},\pm \frac{18}{3}]$
	- remove the dupes: $\frac{p}{q}=[\pm 1,\pm 2,\pm 3,\pm 6,\pm 9,\pm 18,\pm \frac{1}{3},\pm \frac{2}{3}]$

Let's find our only positive x-int first:
- $x=1$
$f(1)=3(1)^4+5(1)^3+25(1)^2+45(1)-18$
$f(1)=3+5+25+45-18$
$f(1)=60$

I've tried with a few more numbers and already knew that this is going to take long... Let's cheat a little and use python to iterate and evaluate functions for us using our list of positive $\frac{p}{q}$:
```python
p_over_q=[1,2,3,6,9,18,1/3,2/3]
for x in p_over_q:
    x = x
   print('f({})='.format(x)+str(eval(latex_to_python('3x^4+5x^3+25x^2+45x-18'))))
```
Output:
```python
f(1)=60
f(2)=260
f(3)=720
f(6)=6120
f(9)=25740
f(18)=352980
f(0.3333333333333333)=0.0 #this is \frac{1}{3}
f(0.6666666666666666)=25.185185185185183 #this is \frac{2}{3}
```
So $x=\frac{1}{3}$ is our only positive x-int. Let's proceed to use synthetic division:
![[Pasted image 20240818135456.png]]
$g(x)=(x-\frac{1}{3})(3x^3+6x^2+27x+54)$
We can do grouping here:
$g(x)=(x-\frac{1}{3})[3x^2(x+2)+27(x+2)]$
$g(x)=(x-\frac{1}{3})(3x^2+27)(x+2)$
$g(x)=(x-\frac{1}{3})3(x^2+9)(x+2)$
bring the 3 up front:
$g(x)=3(x-\frac{1}{3})(x^2+9)(x+2)$
Factoring the irreducible quadratic:
$g(x)=3(x-\frac{1}{3})(x+3i)(x-3i)(x+2)$
There we have it: $x= \frac{1}{3}, x=-3i, x=3i, x=-2$. 1 positive, 1 negative, 2 complexes.
### Notes on Converting LaTeX to Python Equation
Since we'll be doing this a lot, let's create a simple function for this:
```python
def latex_to_python(eq: str):
    eq = eq.replace("^","**")
    new_eq=""
    for i,char in enumerate(eq):
        if char=="x":
            if i>0 and eq[i-1].isdigit():
                new_eq += '*'
        new_eq += char
    return new_eq
```

```input
"x^4+2x^3+22x^2+50x-75"
```

```output
'x**4+2*x**3+22*x**2+50*x-75'
```
## Finding Vertical Asymptotes of Rational Functions

Rational Functions are *fractions* ($\frac{a}{b}$) functions. With fractions, come domain issues where the denominator is equal to 0 ($b=0$) causing a point to be *undefined*.
- With this domain issue, you graph can either have a *hole* (discontinuity) or a *vertical asymptotes*.

If the denominator is equal to 0 at $x$, then at $x$, there will be one of two types of discontinuities:
1. **Hole** (*removable* discontinuity)
	Why *removable*? Because you can fill (or remove) a hole with one point (we'll see this in our examples).
	This happens when the factor causing the denominator = 0 **CAN** be cancelled.
	A hole can be imagined as a type of "point".
![[Pasted image 20240818141906.png]]
2. Vertical asymptote
	This happens when factor causing denominator = 0 **CANNOT** be cancelled.
![[Pasted image 20240818142211.png]]
	There will be 4 types of vertical asymptotes (notice the how multiplicty interacts with the vertical asymptotes): 
![[Pasted image 20240818142530.png]]
### Examples
$$f(x)=\frac{x+3}{x-4}$$
- Identify the domain issues: 
	- notice how this already appear factored
	- Setting $x-4=0 \implies x=4$. This value of $x$ will cause the denom. = 0
- Next question is: can this $x$ be *cancelled*: this will determine if we have a hole or vertical asymptotes
	- can we cancel $(x-4)$ with our numerator: $(x+3)$? No, we have a **vertical asymptote**.
	- Notice that: $f(x)=\frac{x+3}{(x-4)^{1}}$. $(x-4)^{1}$ have a multiplicity of 1 and thus, we have an *odd* vertical asymptote.
![[Pasted image 20240818144133.png]]

$$g(x)=-\frac{2}{(x-1)^2}$$
- Identify the domain issues: 
	- notice how this already appear factored
	- Setting $x-1=0 \implies x=1$. This value of $x$ will cause the denom. = 0. So, $D: x\neq 1$.
- Can this $x$ be cancelled? No, we can't. So we have a **vertical asymptote**.
	- $g(x)=-\frac{2}{(x-1)^2}$. Notice that we have an *even* vertical asymptote.
	- Notice $(x-1)$ is a [[#Introduction to Graph Transformation|right shift]], and the $-1$ in front suggest a *reflection*
![[Pasted image 20240818144233.png]]

$$h(x)=\frac{2x}{x^2-4}$$

- Identify the domain issues: 
	- We should factor this first: $h(x)=\frac{2x}{(x+2)(x-2)}$
	- Setting $x-2=0 \implies x=2$ and $x+2=0 \implies x=-2$. These values of $x$ will cause the denom. = 0. So, $D: x\neq -2, x\neq2$.
- Can this $x$ be cancelled? No, we can't. So we have a **vertical asymptote**.
	- $h(x)=\frac{2x}{(x+2)(x-2)}$. Notice that we have 2 *odd* vertical asymptote, one at $x=-2$ and another at $x=2$.
![[Pasted image 20240818144922.png]]
$$G(x)=\frac{x^2-9}{x^2+4x-21}$$
- Factor: $G(x)=\frac{(x+3)(x-3)}{(x+7)(x-3)}$
- Cancel the $(x-3)$ in the numerator and denominator. Wait... No, we MUST identify the domain issue first.
	- Setting $x+7=0 \implies x=-7$ and $x-3=0 \implies x=3$. These values of $x$ will cause the denom. = 0. So, $D: x\neq -7, x\neq3$. This domain issue will stick with us even after we cancelled $(x-3)$ in the numerator and denominator.
- Can these $x$ be cancelled?
	- For $(x+7)^1$, no. So we have an odd vertical asymptote at $x=-7$.
	- For $(x-3)^1$, yes! So we have an *hole* at $x=3$.
![[Pasted image 20240818145626.png]]
	notice how at $x=3$, there is no force barrier and the line seems to continue just fine. But there is actually a *hole* creating discontinuity in the line at $x=3$.
![[Pasted image 20240818150029.png]]
	notice how $F(x)=\frac{(x-3)(x+3)}{(x+7)(x-3)}=\frac{(x+3)}{(x+7)}$ is exactly the same *graphically*. Except that if we went straight to $G(x)=\frac{(x+3)}{(x+7)}$, we wouldn't have known the existence of the hole at $x=3$.
	However, with the simplified $G(x)=\frac{(x+3)}{(x+7)}$, we can now *fill in* (or *remove*) the hole at $x=3$.
	$G(3)=\frac{6}{10}=\frac{3}{5}$
	So we *fill* the hole using this value to create a more accurate graph (notice that I used a white-colored point here).
![[Pasted image 20240818150552.png]]
## Graphing Rational Functions with Transformations

This section study the interplay between rational functions and vertical asymptotes.
$$f(x)=\frac{1}{x}$$
This has a specific name for it aka. *reciprocal functions*. Notice how $D: x\neq 0$ (*odd* vertical asymptote at $x=0$). Also notice how $f(x)$ can *never* be equal 0 which means that we have a horizontal asymptote at $y=0$.
So:
![[Pasted image 20240818160731.png]]
Key points:
- $(1,1)$
- $(-1,-1)$
![[Pasted image 20240818175806.png]]

$$f(x)=\frac{1}{x^2}$$
Same as with reciprocal functions, notice how $D: x\neq 0$ but now we have *even* vertical asymptote instead of odd at $x=0$. The bigger the $x$ the closer $f(x)$ is to 0, imagine $x=1,000,000$ and it is squared. That's super close to 0. Now imagine $x$ being negative, e.g. $x=-1,000,000$. Since it is squared it become positive anyway. This means our key points will be $(1,1),(-1,1)$, a mirror image.

Key points:
- $(1,1)$
- $(-1,1)$
![[Pasted image 20240818175819.png]]

### Examples with Transformation
$$f(x)=\frac{1}{x^2}+3$$
Notice the vertical shift up by 3.
$$g(x)=\frac{1}{(x-1)^2}-2$$
Notice the vertical shift down by 2 and shift right by 1.
![[Pasted image 20240818180604.png]]

Let's try more:
$$h(x)=\frac{-2}{(x+3)^2}-4$$
Notice the vertical shift down by 4 and shift left by 3. $(x+3)^2$ has a multiplicity of 2 so an even vertical asymptote at $x=-3$ is expected ($D: x\neq -3$). $-2$ suggest a reflection and vertical stretch.
Key points:
- $(1,1)$ -> $(1,-2)$
	- this is from the -2
- $(-1,1)$ -> $(-1,-2)$
![[Pasted image 20240818182421.png]]
	Imagine $x=-3.000001$, so $x+3=-0.000001$. Square it and we get a very very very small number as a denominator. So $f(x)$ grows to negative infinity quickly. Vice versa, imagine $x=-2.999999$, so $x+3=0.000001$. Square it and we get the same very small number. So, from whatever side, as x approach -3 it will go to negative infinity.

$$G(x)=-\frac{1}{x+1}+2$$
Notice the vertical shift up by 2 and shift left by 1. $(x+3)^1$ has a multiplicity of 1 so an odd vertical asymptote at $x=-1$ is expected ($D: x\neq -1$). $-1$ suggest a reflection.
Key points:
- $(1,1)$ -> $(1,-1)$
- $(-1,-1)$ -> $(-1,1)$
![[Pasted image 20240818182558.png]]

## Finding a Horizontal Asymptote of a Rational Function

Horizontal asymptote occurs when the $\text{degree of denominator} \geq \text{degree of numerator}$.
- $\text{degree of denominator} > \text{degree of numerator}$, horizontal asymptote will be at $y=0$. ^2d8963
- $\text{degree of denominator} = \text{degree of numerator}$, horizontal asymptote will be at y=leading coefficient.

Notes 1:
- End behavior is always determined by the *leading terms*.

$$f(x)=\frac{4x^3-7x+1}{7x^5+2x^3-3}$$
Think about leading term this way: $f(x)\approx\frac{4x^3}{7x^5}$.
- we have a case of $\text{degree of denominator} > \text{degree of numerator}$, so our horizontal asymptote will be at $y=0$.
- We can further simplify this to get an even better idea: $\frac{4}{7x^2}$
	- Imagine your $x$ getting really large, like a billion.
	- Now imagine you $x$ gets super small, like 0.000001
	- From left to right, $y$ starts super low and shoots up to positive infinity near the middle y-axis, then gets lower as we pass it.
		Regardless of either x is positive or negative, the square will makes it positive.
		- As $x$ approaches $\infty$, $f(x)$ approaches 0.
		- As $x$ approaches $-\infty$, $f(x)$ approaches 0.
		- Ain't this interesting... This is the core concepts in Calculus 1, where we study the *limit*, which asks: what is the function approaching as it get closer and closer to some $x$ value.
- Note how we $x$ cannot equal to 0 and thus $y$ (or 4 divided by something not 0) can never be 0.
- Notice how just with our *leading term*, tells us a LOT about the end behavior.
	- Imagine if we have odd asymptotes like $\frac{4}{7x}$, and think why it is the way it is. Imagine really large and super small numbers.

Notes 2:
- You *can* cross a horizontal asymptote. Unlike its vertical counterpart, the horizontal asymptote takes effect, generally speaking, at the end behavior
![[Pasted image 20240819182159.png]]
$$g(x)=\frac{8x^3-2x+3}{2x^3+x^2-7x+5}$$
- First thing we do, look at the leading term: $\frac{8x^3}{2x^3}$
	- Notice that $\text{degree of denominator} = \text{degree of numerator}$, this means that the horizontal asymptote will be at y=leading coefficient, which is $\frac{8}{2}=4$.
		- Notice that if $\text{degree of denominator} = \text{degree of numerator}$, we can *always* cancel them out, leaving only a *constant*.
		- This means that, end behavior-wise, $g(x)\approx4$.
			In other words, as $x$ approaches $\infty$, $f(x)$ approaches 4, and as $x$ approaches $-\infty$, $f(x)$ approaches 4.

## Finding an Oblique Asymptote of a Rational Function

Oblique asymptote occurs when the $\text{degree of denominator} < \text{degree of numerator}$. by *exactly* 1.
- For example, say: $\frac{8x^{2}}{4x}$. Simplifying this, we get $2x$. Notice how this is just a *slanted straight line*.
- What if we have, instead, say: $\frac{8x^{3}}{4x}$. Simplifying this, we get $2x^2$. This becomes a *parabola* instead.

Notes:
- **Must** know [[#Synthetic Division and Long Division of Polynomials|long division]].
- Oblique Asymptote is also called *Slanted Asymptote*.

For example:$$f(x)=\frac{3x^4-x^2}{x^3-x^2+1}$$- First thing, consider the leading term: $\frac{3x^{4}}{x^{3}} \implies 3x$
	- As $x$ approaches $\infty$, $f(x)$ also approaches $\infty$
	- As $x$ approaches $-\infty$, $f(x)$ also approaches $-\infty$
	- This end behavior is the very same as a straight line.

To find our oblique asymptote, we can use [[#Synthetic Division and Long Division of Polynomials|long division]] to find out:
![[Pasted image 20240819183904.png]]
- we know that our oblique asymptote would look something like: $y=ax+b$
- Notice how once we see a number in this format on our *quotient*, we're *done*. That's our oblique asymptote: $3x+3$.

Note:
- like horizontal asymptote, we *can* cross the oblique asymptote (just think of it as a little slanted horizontal asymptote).

## Finding End Behavior of Rational Functions

We already have cases where $\text{degree of denominator} \geq \text{degree of numerator}$ (horizontal asymptote) and $\text{degree of denominator} < \text{degree of numerator}$ by exactly 1 (oblique).
What happens when the $\text{degree of denominator} < \text{degree of numerator}$. by *more than* 1?

Let's look at an example:$$g(x)=\frac{4x^5-7x+1}{x^3+1}$$- Look at the leading term: $\frac{4x^{5}}{x^{3}}=4x^{2}$
	- Notice that this is just a vertically stretched *parabola*. And that's exactly what the end behavior will be like.
		- As $x$ approaches $\infty$, $f(x)$ also approaches $\infty$ (although much quicker compared a straight line)
		- As $x$ approaches $-\infty$, $f(x)$ also approaches $\infty$ (square out the negative sign)

- Imagine $\frac{-4x^{5}}{x^{3}}$ or $\frac{4x^{6}}{x^{3}}$, in all cases the denominator can be completely *eliminated* and we're left with a good ol' poly (or power functions in the leading term).
## Finding Asymptotes and Holes of Rational Functions

Here's a brief summary from our previous lessons on rational functions:
1. End behavior:
	- horizontal
	- oblique
	- power functions
2. Factor
3. Define our *Domain*
4. Determine any *vertical asymptote* or *holes*
5. Simplify and evaluate for hole if necessary

$$f(x)=\frac{3x+5}{x-6}$$
1. End behavior
	Our leading term would be $\frac{3x}{x}=3$. Notice the denominator = numerator so we have a *horizontal asymptote* at $y=3$.
2. Factor
	This already come factored, so we can proceed.
3. Define our *Domain*
	Our Domain is: $D: x\neq6$.
4. Determine any *vertical asymptote* or *holes*
	Can $x$ in the denominator be *cancelled*? No, $(x-6)$ cannot be cancelled. So we have a vertical asymptote at $x=6$.
5. Simplify
	We cannot really simplify any further. We're done.

This is how I guessed it would look.
![[Pasted image 20240819195838.png]]![[Pasted image 20240819200209.png]]

$$g(x)=\frac{x^3}{x^4-1}$$
1. E.B. (stands for end behavior from now on):
	leading factor $=\frac{x^{3}}{x^{4}}=\frac{1}{x}$. So the factor at the denominator is > the factor at numerator, meaning that we have a horizontal asymptote at $x=0$.
2. Factor:
	$g(x)=\frac{x^{3}}{x^{4}-1}=\frac{x^{3}}{(x^{2}-1)(x^{2}+1)}=\frac{x^{3}}{(x-1)(x+1)(x+i)(x-i)}$
3. Domain:
	From the factors in the denominator, we know that: $D: x\neq1,x\neq-1,x\neq i,x\neq -i$.
4. Vert. asymp. or hole:
	Can any of the factors in the denominator be cancalled? No, we cannot for any of them. Thus, we have a vertical asymptote @ 1 and -1 ($i$ and $-i$ is imaginary so we can ignore it). No holes.
5. Simplify
	This is already simplified.

I can't really imagine what will happen between $(-1,1)$ interval but I know that the E.B. is just $\approx \frac{1}{x}$
![[Pasted image 20240819201243.png]]
![[Pasted image 20240819201500.png]]
	That's how it looks. I don't understand why the middle part is the way it is so let's think about it:
	- say we have x that is very very close to -1 like -0.99999...:
		$g(-0.99...)=\frac{(-0.99...)^3}{(-0.99...)^4-1}$
		$g(-0.99...)\approx\frac{-0.97}{0.97-1}$
		$g(-0.99...)\approx\frac{-0.97}{0.96-1}$
		$g(-0.99...)\approx\frac{-0.97}{-0.04}$
		$g(-0.99...)\approx24.5$
		This is a poorly done approximate but it is good enough for our current purpose. 
		We can see how the closer $x$ approaches $-1$ *from the right* $f(x)$ shoots up to $+\infty$.
		If $x$ approaches from the left and is a number very close to -1 such as $-1.00...01$, the denominator shoots down to $-\infty$ because $\frac{-1.00...01}{0.00..1}$ is just a very big negative number.
	- Similarly for $x$ that is very close to 1 such as $0.99...$ and $1.00...1$
### More examples

$$G(x)=\frac{x^4-16}{x^2-2x}$$
1. E.B.:
	$\frac{x^{4}}{x^{2}}=x^{2}$. The E.B. is going to be an upward-facing parabola.
2. Factor:
	$G(x)=\frac{(x^{2}+4)(x^{2}-4)}{x(x-2)}=\frac{(x-2)(x+2)(x^{2}+4)}{x(x-2)}$
	We'll leave $(x^{2}+4)$ alone here as factoring it would just get us complex solutions anyway.
3. Domain:
	$D: x\neq0, x\neq2$. 
4. Vert. asympt. or hole
	Can we cancel $(x-2)$? Yes, this is a hole. Can we cancel $x$? No, so vert. asympt. at 0.
	Notice how the factor -> domain really helps us easily identifying whether we have vert. asympt. or hole.
5. Simplify
	We have a hole so we can simplify to plug in exactly where the hole is. $G(x)=\frac{(x^{2}+4)(x^{2}-4)}{x(x-2)}=\frac{(x+2)(x^{2}+4)}{x}$
	Let's plug in 2 (where our hole is):
	$G(2)=\frac{((2)+2)((2)^{2}+4)}{2}$
	$G(2)=\frac{(4)(8)}{2}$
	$G(2)=16$

Here's how I imagine it:
![[Pasted image 20240819203147.png]]
	I forgot to put 16 on the y-axis, but yeah, the hole is at $(2,16)$.
No clue on how the middle part behaves.
	Let's try $x=-0.000001$. So: 
	$G(-0.000001)=\frac{(-0.000001)^4-16}{(-0.000001)^2-2(-0.000001)}$
	$G(-0.000001)=\frac{0.00...1-16}{0.00...1+0.000002}$
	$G(-0.000001)=\frac{-15.999...}{0.000002001}$
	This is just a very big negative number. So as $x$ approaches 0 from *the left side*, $f(x)$ shoots down to $-\infty$.
![[Pasted image 20240819205354.png]]
	See? But notice how the E.B. is still an upward-facing parabola.

$$F(x)=\frac{2x^2-5x-12}{3x^2-11x-4}$$
1. E.B.:
	leading factor: $\frac{2x^{2}}{3x^{2}}=\frac{2}{3}$. Notice that the factor at num. = factor at denom. So we have a horizontal asymp. @ $\frac{2}{3}$.
2. Factor:
	At the numerator:![[Pasted image 20240819204938.png]]
	At the denominator:![[Pasted image 20240819205529.png]]
	So: $F(x)=\frac{(x-4)(2x+3)}{(x-4)(3x+1)}$
3. Domain:
	$D: x\neq4, x\neq - \frac{1}{3}$
4. Vert. Asympt. or Hole:
	We have a hole at $x=4$ since $(x-4)$ can be cancalled and vert. asympt. at $x= - \frac{1}{3}$.
5. Simplify
	$F(x)=\frac{(2x+3)}{(3x+1)}$
	Evaluate:
	$F(4)=\frac{2(4)+3}{3(4)+1}=\frac{11}{13}$
	So our hole is at $(4, \frac{11}{13})$.

I know that the E.B. is going to be $y=4$ but I don't know on which side should I draw on so I'll leave it like this.
![[Pasted image 20240819210320.png]]
![[Pasted image 20240819210641.png]]

$$g(x)=\frac{x^3-8}{x^2-5x+6}$$
1. E.B.:
	$\frac{x^{3}}{x^{2}}$: notice how this is a case of *oblique asymptote* (factor of num. > factor of denom. by exactly 1). The E.B. will be like a straight slated line.
2. Factor:
	At the denom.:
	![[Pasted image 20240819211125.png]]
	$g(x)=\frac{x^{3}-8}{(x-3)(x-2)}$
	What's next? Oh... we can use long division to find the $y=ax+b$:![[Pasted image 20240819211458.png]]
	So our oblique asymptote is at $y=x+5$.
3. Domain:
	We've mistakenly factor in the previous step but it's useful here: $g(x)=\frac{x^{3}-8}{(x-3)(x-2)}$.
	So, $D:x\neq3,x\neq2$.
4. Vert. Asymp. or Hole:
	![[Pasted image 20240819211822.png]]
	From [[#Synthetic Division and Long Division of Polynomials|synthetic division]], we see $(x-2)$ is a factor of $x^{3}-8$, re-writing this:
	$g(x)=\frac{(x-2)(x^2+2x+4)}{(x-3)(x-2)}$.
	I feel that $(x-3)$ surely is not a factor of $(x^2+2x+4)$, but let's see:
	$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
	$x=\frac{-(2)\pm\sqrt{(2)^2-4(1)(4)}}{2(1)}$
	$x=\frac{-2\pm\sqrt{4-16}}{2}$
	We clearly have complex factors here so let's stop.
	To summarize, we have a hole at $x=2$ and a vert. asymp. at $x=3$.
5. Simplify
	$g(x)=\frac{x^{2}+2x+4}{x-3}$
	$g(2)=\frac{(2)^{2}+2(2)+4}{(2)-3}$
	$g(2)=\frac{4+4+4}{-1}$
	$g(2)=-12$
	The hole is at $(2,-12)$.
![[Pasted image 20240819213503.png]]
![[Pasted image 20240819213437.png]]

$$H(x)=\frac{6x^2+7x-5}{3x+5}$$
1. E.B.:
	$\frac{6x^{2}}{3x}=2x$. Notice how this is another case of *oblique asymptote* (factor of num. > factor of denom. by exactly 1). 
2. Factor:
	@ the numerator:![[Pasted image 20240819214007.png]]
	So: $H(x)=\frac{(3x+5)(2x-1)}{(3x+5)}$.
	Hm... So we have 2 factors in form of $y=ax+b$. I wonder which one is our oblique asymptote...
	![[Pasted image 20240819214251.png]]
	The result of long division above points at $(2x-1)$ as our line. But why?
	Notice how we can cancel our $(3x+5)$s from our denom. and num. (which means that we'll have a hole), leaving only $(2x-1)$, making it the location of our oblique asymptote.
1. Domain:
	$D: x\neq -\frac{5}{3}$
4. Vert. Asymp. or Hole:
	We kind of have done this in step 2. So let's skip this.
5. Simplify
	To fill in our hole, evaluate $H(x)=2x-1$, with $x=-\frac{5}{3}$:
	$H(- \frac{5}{3})=2(- \frac{5}{3})-1$
	$H(- \frac{5}{3})=- \frac{13}{3}$
	So our hole is at $(- \frac{5}{3},- \frac{13}{3})$.

![[Pasted image 20240819215138.png]]
![[Pasted image 20240819215705.png]]
	Straight line, as expected. Notice that the function follows the oblique asymptote exactly. Why? because after simplification, $H(x)=2x-1$, exactly the same as our oblique asymptote. The only difference is that we have a hole in the line for $H(x)=\frac{6x^2+7x-5}{3x+5}$.

## Graphing Rational Functions

This section ties everything together. Here's a summary of steps:
1. Find horizontal or oblique asymptote OR end behavior.
2. Factor, find multiplicity, and find vertical asymptote(s) and/or hole(s)
3. Find x-intercepts by making the numerator = 0
4. Find y-intercept by plugging $x=0$.
5. Set $f(x)$ equal to horizontal or oblique asymptote to check for intersection (not for $y=0$).
	why not? $y=0$ is just our x-intercepts and we have done that in step 3.
6. Make a number line with key points and find extra points.
7. *Graph*.

For example:$$f(x)=\frac{x-1}{x^2-4}$$
1. Our EB is going to look like $f(x)\approx \frac{x}{x^{2}} = \frac{1}{x}$
	Think about $\lim_{x\to\infty} \frac{1}{x}$ or what happen to $f(x)$ as $x\to\infty$.
	Note how $f(x)$ will get super small but never reach 0. So, we have a horizontal asymptote at $y=0$.
2. Factor
	$f(x)=\frac{x-1}{(x-2)(x+2)}$. We don't have a hole since both factors in the denom. cannot be cancelled. Thus they are both vertical asymptote, one at $x=2$ and another at $x=-2$. 
	Both of our factors have multiplicity of 1 and thus, they are both odd vert. asym.
	If we have a hole, we will find the hole first before going to step 3 where we have to set the num. = 0.
3. Find x-intercepts
	1. Set $x-1=0 \to x=1$. We have x-intercept at 1.
		- why this? It's the only way to $f(x)$ can be 0. If we set the denom. = 0 then we just get *undefined*.
	2. Notice that $(x-1)^{1}$ has a multiplicity of 1 (odd). Thus, it will *cross* the x-axis instead of bounce.
4. Find y-intercept
	$f(0)=\frac{(0)-1}{(0)^{2}-4}= \frac{1}{4}$. So y-intercept is at $(0, \frac{1}{4})$.
5. Set $f(x)$ equal to horizontal or oblique asymptote to check for intersection.
	We can *skip* this because we have we have a horizontal asymptote at $y=0$ and the intersection is just the x-intercept.
6. Make a number line with key points and find extra points.
	1. Make a number line with some important points.![[Pasted image 20240820184020.png]]
	2. Plug some additional values (it can be any value) to get a better idea of the behavior between that interval. ![[Pasted image 20240820184248.png]]
	3. Evaluate and get more points.
		$f(-3)=-0.8$
		$f(-1)=0.67$
		$f(1.5)=-0.28$
		$f(3)=0.4$
		![[Pasted image 20240820184634.png]]
7. Graph
	When we graph, look through the previous step in order:
	1. E.B.
	2. V.A. or Hole
	3. x-int
	4. y-int
	5. Intersection
	6. Addt. points
	![[Pasted image 20240820185115.png]]
	I didn't do step 6 since it would be messy but you get the point. I'm sure you can see why we would want additional points unpack all of these.
	Let's try this:![[Pasted image 20240820185804.png]]
	Notice that point $(-1,0.67)$ has *no x-intercept before it*, which means that it can only come down from above to *cross* at the x-intercept at $x=1$.![[Pasted image 20240820190056.png]]
	Notice the odd V.A.s that we have, both have lines that goes on opposite directions (one to $-\infty$ and another to $\infty$) as defined.
![[Pasted image 20240820190536.png]]

### More examples
$$f(x)=\frac{x^4-1}{x^2-4}$$
1. E.B.
	$f(x)\approx \frac{x^{4}}{x^{2}}=x^{2}$. We don't have a H.A. nor O.A. and our E.B. is an upward-facing parabola.
2. Factor
	$f(x)=\frac{(x^{2}+1)(x^{2}-1)}{(x+2)(x-2)}=\frac{(x^{2}+1)(x-1)(x+1)}{(x+2)(x-2)}$
	So we have V.A. at $x=2, -2$.
3. Find x-intercept
	$0=(x^{2}+1)(x-1)(x+1)$
	We have *odd* x-intercept at 1 and -1 and other a complex pair.
4. Find y-intercept
	$f(0)=\frac{(0)^{4}-1}{(0)^{2}-4}$
	y-intercept at $(0,\frac{1}{4})$
5. Find the intersection with H.A. or O.A.
	We have none so we can skip this.
6. Draw a number line with key points and add additional points
	![[Pasted image 20240820201106.png]]
	$f(-3)=16.0$
	$f(-1.5)=-2.32$
	$f(0.5)=0.25$, notice how this output is the same as $f(0)$? Nothing too deep, it's just interesting.
	$f(1.5)=-2.32$
	$f(3)=16.0$
	Notice kind of the symmetry here since it is a parabola interacting with *odd* V.A.![[Pasted image 20240820201326.png]]
7. Graph
	Our middle part is a downward facing parabola according to our *odd* x-intercepts:![[Pasted image 20240820202156.png]]
	Since we have odd V.A.s, with the middle part going down to $-\infty$, we must come from $\infty$ from the another side of each V.A.s:![[Pasted image 20240820202445.png]]
	Now, our E.B. is an upward-facing parabola, so:![[Pasted image 20240820202529.png]]
	If we know our local mins, this will be much clearer. But that's for Calculus 1.
![[Pasted image 20240820202541.png]]
	Close enough.

$$f(x)=\frac{3x^2-3x}{x^2+x-12}$$
1. E.B.
	$f(x)\approx \frac{3x^{2}}{x^{2}}=3$
	We have a H.A. at $y=3$.
2. Factoring
	$f(x)=\frac{3x(x-1)}{(x+4)(x-3)}$
	We have V.A.s at $x=-4,3$
3. x-intercept
	$0=3x(x-1)$
	We have x-intercept at $x=0$ (odd mult.) and $x=1$ (odd mult.).
4. y-intercept
	$f(0)=\frac{3(0)^2-3(0)}{(0)^2+(0)-12}$
	We have a y-intercept at $(0,0)$
5. Set our function = H.A. to find intersection
	$3=\frac{3x^2-3x}{x^2+x-12}$
	$3(x^2+x-12)=3x^{2}-3x$
	$3x^{2}+3x-36=3x^2-3x$
	$6x=36$
	$x=6$
	So the intersection between $f(x)$ and $y=3$ is at $(6,3)$.
6. Draw number line with KPs and add additional points.
	![[Pasted image 20240820204645.png]]
	$f(-5)=11.25$
	$f(-2)=-1.8$
	$f(0.5)=0.067$
	$f(2)=-1.0$
	$f(4)=4.5$
7. Graph it!
	![[Pasted image 20240820210500.png]]
	Notice that we *cross* the H.A. at $(6,3)$. So going right, the line stay right below $y=3$.
![[Pasted image 20240820210628.png]]

$$f(x)=\frac{2x^2-5x+2}{x^2-4}$$
1. E.B.
	$f(x)\approx \frac{2x^{2}}{x^{2}}=2$
	So we have a H.A. at $y=2$.
2. Factor
	![[Pasted image 20240820211133.png]]$f(x)=\frac{(2x-1)(x-2)}{(x+2)(x-2)}$
	So we have a V.A. at $x=-2$ and a hole at $x=2$, both with odd mult. 
	Let's simplify to get a point for our hole:
	$f(x)=\frac{(2x-1)}{(x+2)}$
	$f(2)= \frac{3}{4}$
	So our hole is at $(2,\frac{3}{4})$.
3. x-intercept
	$0=(2x-1)(x-2)$
	So our x-intercepts are at $x= \frac{1}{2}$ and $x=2$. Wait... we can't have x-intercept at $x=2$ since that is a hole! So only $x= \frac{1}{2}$ is applicable here.
	We can actually just do $0=2x-1$ and get the same results.
1. y-intercept
	$f(0)=\frac{2(0)^2-5(0)+2}{(0)^2-4}$
	$f(0)=\frac{2}{-4}$
	$f(0)=-\frac{1}{2}$
	So our y-intercept is at $(0,- \frac{1}{2})$
5. Find intercept with H.A.
	$2=\frac{2x^2-5x+2}{x^2-4}$
	$2(x^{2}-4)=2x^{2}-5x+2$
	$2x^2-8=2x^{2}-5x+2$
	$x=2$
	So the intercept with H.A. is at $(2,2)$. Wait but at $x=2$ we have a hole. This is nonsense! Let's try it with a simplified equation:
	$2=\frac{2x-1}{x+2}$
	$2x+4=2x-1$
	$4=-1$
	This is also a nonsense! This means that there is NO intersection between $f(x)$ and H.A. 
		So whether you choose the simplified or non-simplified version, it leads to the same conclusion, which is just nonsense.
6. Number line with KPs and some additional points
	![[Pasted image 20240820212015.png]]
	$f(-3)=7.0$
	$f(-1)=-3.0$
	$f(1)=0.34$
	$f(3)=1.0$
7. Graph it!
	![[Pasted image 20240820213801.png]]
![[Pasted image 20240820213931.png]]

$$f(x)=\frac{x^3-1}{x^2-9}$$
- E.B.
	$f(x)\approx \frac{x^{3}}{x^{2}}=x$
	We have an O.A. Let's try to find where it is:
	We can't really factor so let's do long division. ![[Pasted image 20240820214421.png]]
	Our O.A. is at $y=x$.
- Factor
	We have a difference of cube on the num.![[Pasted image 20240820214711.png]]
	$x^{3}+(-1)^{3}=(x+(-1))(x^{2}-(x)(-1)+(-1)^{2})=(x-1)(x^{2}+x+1)$
	So:
	$f(x)=\frac{(x-1)(x^{2}+x+1)}{(x-3)(x+3)}$
	Sum or Difference of Cubes is NOT factorable. 
	Our V.A.s is at $x=3$ and $x=-3$.
- x-intercept
	$0=(x-1)(x^{2}+x+1)$
	So our x-int is at $x=1$ with mult. 1.
- y-intercept
	$f(0)=\frac{(0)^3-1}{(0)^2-9}$
	$f(0)=\frac{1}{9}$
	y-int. at $(0,\frac{1}{9})$
- intercept with O.A.
	$x=\frac{x^3-1}{x^2-9}$
	$x(x^2-9)=x^3-1$
	$x^3-9x=x^3-1$
	$-9x=-1$
	$x= \frac{1}{9}$
	There will be an intersection with O.A. at $x=\frac{1}{9}$. We also need to evaluate this for *a point*:
	$f(\frac{1}{9})=\frac{1}{9}$
	I cheated and used python but actually, since O.A. is at $y=x$, we can replace $x=\frac{1}{9}$ here and get that $f(\frac{1}{9})=\frac{1}{9}$.
- Number line, KPs, and additional points
	![[Pasted image 20240820220213.png]]
	$f(-4)=-9.28$
	$f(-2)=1.8$
	$f(2)=-1.4$
	$f(4)=9.0$
- Graph it!
	![[Pasted image 20240820220946.png]]
![[Pasted image 20240820221124.png]]

$$f(x)=\frac{x^2(x-1)^2}{(x+3)^4}$$
- E.B.
	Do a [[#^217787|fake distribution]]: $f(x)\approx \frac{x^{4}}{x^{4}}=1$
	We have a H.A. at $y=1$.
- Factor
	This already come factored. Our V.A. is $x=-3$ with a multiplicity of 4 (we finally got an example of *even*. Yay!) The behavior around this V.A. will probably be something like this:
	![[Pasted image 20240820221605.png]]
- x-intercept
	$0=x^{2}(x-1)^{2}$ 
	So we have $x=0$ with *even* mult. (bounce) and another at $x=1$ with *even* mult. (bounce).
- y-intercept
	$f(0)=\frac{(0)^2((0)-1)^2}{((0)+3)^4}$
	$f(0)=0$
	$(0, 0)$
- Intersection with H.A.
	$1=\frac{x^2(x-1)^2}{(x+3)^4}$
	$(x+3)^{4}=x^{2}(x-1)^{2}$
	That's a lot of distribution. Even Professor Leonard doesn't want to do it. In real-life, you have to do what you have to do. But for now, let's just follow what he did:
	- evaluate $f(-1)$ and $f(-2)$ to get an idea of how it looks:
		- $f(-1)=\frac{1}{4}$ and $f(-2)=36$
- Skip to: Graph it!
	![[Pasted image 20240820224703.png]]
	Notice the behavior of the line around an even V.A. Now we actually have to distribute to know (or via some other math sorcery) whether the line will *cross* the H.A. again.

![[Pasted image 20240820225046.png]]
Here's a little zoom in to see the 2 *bounces* in action.
![[Pasted image 20240820224922.png]]

$$f(x)=2x+\frac{9}{x}$$
We will be going through this one quickly, so it will not follow the usual steps.
The general advice for this kind of thing is to make it one fraction:
$f(x)=\frac{2x^{2}+9}{x}$
Now we can see that:
- We will have a V.A. at $x=0$.
- Notice the O.A. because the leading factor is $\frac{2x^{2}}{x}$ (degree of num. > degree of denom. by exactly 1). A long division will show that O.A. is at $y=2x$.
	- No intercept with O.A. Imagine $2x=2x+ \frac{9}{x}$.
- There will be no y-intercept (we can't plug in 0 as the denom. is just $x$)
![[Pasted image 20240820230121.png]]

Final one:
![[Pasted image 20240820230201.png]]
Can we get a function from this graph? Let's try:
- V.A. at $x=-3$ (*odd* mult.) and $x=1$ (*even* mult.)
	- the denom. is probably $\frac{\text{something}}{a(x+3)^{\text{odd n}}(x-1)^{\text{even n}}}$
- H.A. at $y=2$
	- So the leading degree of denom. = the leading degree of num: $\frac{2x^{n}}{x^{n}}$
- x-intercept
	- at $x=-1$ or $(x+1)$, even mult.
	- at $x=3$ or $(x-3)$, odd mult.
	This is from setting the num. to be equal to 0: $0=a(x-3)^{\text{odd n}}(x+1)^{\text{even n}}$
- y-intercept
	- at $y=-2$
	- So $f(0)=-2$
Let's summarize what we have so far:
$f(x)=\frac{2(x-3)^{\text{odd n}}(x+1)^{\text{even n}}}{(x+3)^{\text{odd n}}(x-1)^{\text{even n}}}$
We don't really know whether the odd $n$ > even $n$ or vice versa, but that whatever is greater, the leading factor's degree of denom. = the degree of num. 
Let's just say that the even $n$ is 2 and odd $n$ is 1.
$f(x)=\frac{2(x-3)^{1}(x+1)^{2}}{(x+3)^{1}(x-1)^{2}}$
![[Pasted image 20240820232528.png]]
That's a match. 
## Inequalities with Functions - Graphically

![[Pasted image 20240821180840.png]]
$f(x)\geq0$, this is just asking: on which interval on the x-axis, is your function *above* or *equal* to the x-axis? 
	The answer is: $(-\infty,0]\cup[1,2]$.
$f(x)<0$, on which interval on the x-axis, is your function *below* the x-axis? 
	The answer is: $(0,1)\cup(2,\infty)$.

![[Pasted image 20240821182222.png]]
- $f(x)>0$
	$(-1,1)\cup(2,\infty)$
- $f(x)\leq0$ 
	$(-\infty,-1]\cup[1,2]$

![[Pasted image 20240821182424.png]]
- $f(x)<0$
	$(-2,0)\cup(2,\infty)$
- $f(x)\geq0$
	$(-\infty,-2)\cup[0,2)$

![[Pasted image 20240821182717.png]]
- $f(x)>0$
	$(-\infty,-2)\cup(-2,2)\cup(6,\infty)$
- $f(x)\leq0$
	$[2,4)\cup(4,6]$

## Inequalities with Polynomial Functions

$$(x-5)^{2}(x+2)<0$$
- x-intercept at $x=5$ and $x=-2$
	- at $x=5$, it will be a bounce since it has a mult. of 2, an even number. note that this bounce will **NOT** cross the x-axis.
	- at $x=-2$, it will be a *cross*
- The E.B. will be a power 3 function:
	- ![[Pasted image 20240821183301.png]]
Think in a number line:
![[Pasted image 20240821183412.png]]
It will probably be something like this. So the interval where $(x-5)^{2}(x+2)<0$ is: $(-\infty,-2)$.

Note: In case where we have a $(x-5]^{2}(x+2)\leq0$, the answer will be $(-\infty,-2)\cup\{5\}$ instead. 

We can recheck our answer by plugging in any number between each intervals and evaluate. It should be a T, F, F statement respectively going from left-to-right:
	Evaluate if $f(-3)<0$ is *True*. 
		$f(-3)=(-3-5)^2(-3+2)=-64$; so $-64<0$ is True.
	Evaluate if $f(0)<0$ is *False*.
		$f(0)=(0-5)^{2}(0+2)=50$; so $50<0$ is False.
	Evaluate if $f(6)<0$ is *False*.
		$f(6)=(6-5)^{2}(6+2)=8$; so $8<0$ is False.
	As desired.
Or we can cheat this process a little and just evaluate any number in the middle interval e.g. in this case 0. And think about it this way:
- We know that $f(0)<0$ is *False*. So can we refer this and imply what *cross* and *bounce* do to the other two intervals?
	- Cross means that you'll end up with a positive sign after a cross.
		- So, if the middle part is F, then what is before the cross should be the opposite of F, so it would be T.
	- Bounce means that you'll have the same sign as before.
		- So, if the middle part is F, then what comes after the bounce should still be F.
	So, by logic, we have T, F, F. As desired.

$$x^3-4x^2\geq0$$
Re-arranging this:
$x^{2}(x-4)\geq0$
- x-intercept at $x=4$ (mult. 1) and $x=0$ (mult. 2)
- E.B. will be like: $x^{3}$
![[Pasted image 20240821183803.png]]
So the interval where $x^3-4x^2\geq0$ is at: $\{0\}\cup[4,\infty)$.

Let's evaluate the middle interval, say $f(2)\geq0$:
	$f(2)=(2)^{3}-4(2)^2=-8$
	So $-8\geq0$ is *False*.
	We have a bounce at $x=0$, so any $x$ before the bounce would still be F.
	We have a cross at $x=4$, so any $x$ after the cross would be T.
	So we have a F, F, T. Corresponding what we have in the graph.  
### More examples
$$x^3+2x^2\geq3x$$
The question is asking this, but we can arrange it in a way that make it much easier to understand:
![[Pasted image 20240821202309.png]]
Re-arranging this:
$x^{3}+2x^{2}-3x\geq0$
Now we just have our usual x-axis instead of the oblique line $3x$.
- factoring this: $x(x^{2}+2x-3)\to x(x+3)(x-1)$
	So we have x-int at $x=0$, $x=-3$, $x=1$.
- the E.B. is just: $x^{3}$
![[Pasted image 20240821201233.png]]
So, our answer is $[-3,0]\cup[1,\infty)$.

Evaluate, say, $f(-1)$:
	$(-1)^{3}+2(-1)^{2}\geq3(-1)$
	$-1+2\geq-3$
	$1\geq-3$
	which is *True*.
By logic, the interval:
- before $x=-3$ or the cross would be F.
- after $x=0$ would be F.
- Since after $x=0$ is a F, after $x=1$ would be the opposite of that, which is T.
So we have F, T, F, T.

$$x^4>1$$
![[Pasted image 20240821202613.png]]
Re-arranging this:
$x^4-1>0$
- Factor
	$(x^{2}-1)(x^{2}+1)>0$
	$(x-1)(x+1)(x^{2}+1)>0$
	Inside the third parentheses is an irreducible quadratic (a sum of square).
- x-int
	So we have x-int at $x=1$ and $x=-1$, both of which has a mult. of 1 and thus crosses.
- E.B.
	would be $x^{4}$, which is an upward-facing parabola
![[Pasted image 20240821201924.png]]
So, our answer is: $(-\infty,-1)\cup(1,\infty)$

We have a T, F, T (TFT. Nice.)
## Inequalities with Rational Functions

2 things to know before we begin:
1. Find x-intercepts by setting the numerator = 0
2. Find Vertical Asymptotes by setting the denominator = 0

For example:$$\frac{(x-3)(x+2)}{x-1}\leq0$$Find x-intercept:
$(x-3)(x-2)=0$
By *zero product property*, we have x-intercepts at $x=3$ (mult.1) and $x=-2$ (mult.1).
![[Pasted image 20240821220411.png]]
Find V.A.:
$x-1=0$
So, at $x=1$ we have a V.A. with a mult. of 1.
![[Pasted image 20240821220400.png]]

Our E.B. will be an [[#Finding an Oblique Asymptote of a Rational Function|oblique line]] at $y=x$.

We can think about it graphically as such:
![[Pasted image 20240821220641.png]]

Or, the easier way, is to plug in a value in any interval and use it to deduce the rest:
	Say $f(-1)=\frac{(-1-3)(-1+2)}{-1-1}=\frac{-4}{-2}=2$
	So is $2\leq0$. No, this is *False*.
	Since $x=-1$ is in the interval right before the *odd* V.A. at $x=1$, which must be from the opposite side. So we know that it is *True* in that interval.
	![[Pasted image 20240821221129.png]]
	Now we have 2 crosses at $x=-2$ and $x=-3$, which means that it must have the opposite sign of whatever the interval next to it has. So before $x=-2$ is True, and after $x=3$ is *False*.
	![[Pasted image 20240821221400.png]]
	So, we have T, F, T, F, which corresponds to our graph.
Almost forgot to write our answer, it is: $(-\infty,-2]\cup(1,3]$


$$\frac{(x+5)^2}{x^2 -4}>0$$
- x-intercept
	$(x+5)^2=0$
	So our x-int is at $x=-5$ with a mult. of 2 (even). We have a bounce.
- V.A.
	$(x^2-4)=0$
	$(x-2)(x+2)=0$
	So our *odd* V.A.s at $x=2$ and $x=-2$.
- E.B.
	$\frac{x^{2}}{x^{2}}=1$
	Our E.B. will be a straight line at 1.

![[Pasted image 20240821222708.png]]
We can be more detailed and find the intercepts with our H.A. at $y=1$:
$1=\frac{(x+5)^2}{x^2 -4}$
$x^2-4=x^2+10x+25$
$-29=10x$
$x=- 2.9$
![[Pasted image 20240821223157.png]]
See?

Now for our answer, it is: $(-\infty,-5)\cup(-5,-2)\cup(2, \infty)$.

We can also think about it logically by evaluating one point at deduce the rest:
$f(0)=\frac{25}{-4}$
So $- \frac{25}{4}\geq0$ is *False*. Since we have *odd* V.A.s at $x=-2$ on the left and $x=2$ on the right, any number in both of those intervals will be *True*. Finally, we have a bounce at $x=-5$ so the interval before $x=-5$ will be have the same sign as the one right next to it, which is positive, and thus it is *True*. So we have T, T, F, T.

$$\frac{x(x^2+1)(x-2)}{(x-1)(x+1)}\geq0$$
- x-intercept
	This already come factored, which is convenient:
	$x(x^2+1)(x-2)=0$
	The middle term is an irreducible quadratic, so, we only have $x=0$ and $x=2$ as our x-int.
- V.A.
	We have $(x-1)(x+1)=0$, which means that we have *odd* V.A.s at $x=1$ and at $x=-1$.
- E.B.
	$x^{4}/x^{2}=x^{2}$, which is just an upward facing parabola.

![[Pasted image 20240821230017.png]]
So our answer is: $(-\infty,-2)\cup[0,1)\cup[2,\infty)$.

Let's evaluate one for old time sakes:
$f(3)=\frac{(3)((3)^{2}+1)((3)-2)}{((3)-1)((3)+1)}$
This cannot be negative, so it is *True*. Note that 3 in the right most interval or $[2,\infty)$. Working right to left:
- *False*, since we crossed at $x=2$.
- *True*, since we have an *odd* V.A.
- *False*, since we cross at $x=0$.
- *True*, since we have an *odd* V.A.
So, in left-to-right order: T, F, T, F, T.

### Inequalities with a Constant or a Function

What if we have an inequality that is not set to $\geq$ or $\leq$ 0, but *a constant or another function*?
1. Set = to find intersection
	For example: $\frac{3x-5}{x+2}\leq2 \to \frac{3x-5}{x+2}=2$.
	Why do we do this? Intersection is the point where our truth of our statement changes e.g. from true to false and vice versa.
2. Find V.A. by setting the denominator = 0

$$\frac{3x-5}{x+2}\leq2$$
1. Find intersection
$\frac{3x-5}{x+2}=2$
$3x-5=2x+4$
$x=9$
This is our point of intersection.
2. Find V.A.
$x+2=0$
$x=-2$
We have an *odd* V.A. at $x=-2$.
![[Pasted image 20240821231625.png]]
Let's plug in something between -2 and 9, say $f(0)$:
$\frac{3(0)-5}{0+2}\leq2$
$- \frac{5}{2}\leq2$
This is *True*. From this we can deduce:
![[Pasted image 20240821231834.png]]
So, F, T, F. Our answer is $(-2,9]$.
	include the 9 since it is the point of intersection.

Or we can do this graphically:
- E.B. is $y=3$
![[Pasted image 20240821232136.png]]

We can also do:
$\frac{3x-5}{x+2}-\frac{4}{2}\leq0$
and try to get a common denominator.

![[Pasted image 20240821232721.png]]

$$\frac{5}{x-3}\geq\frac{3}{x+1}$$
1. Find the intersection
	Once again, this is where our truth of our statement changes e.g. from true to false and vice versa.
	So:
	$\frac{5}{x-3}=\frac{3}{x+1}$
	$5x+5=3x-9$
	$2x=-14$
	$x=-7$
	This is our point of intersection.
2. Find V.A.
	For $\frac{5}{x-3}$, $x-3=0$. Making $x=3$ *odd* V.A. for this function.
	For $\frac{3}{x+1}$, $x+1=0$. Making $x=-1$ *odd* V.A. for this function.
	Notice that if we combine them to make one side equal to 0:
	$\frac{5}{x-3}-\frac{3}{x+1}\geq0$
	We'll still have the same thing.
![[Pasted image 20240821233251.png]]
This one is a bit harder to think graphically, so our truth logic thingy is more convenient here, say I evaluate $f(0)$;
$\frac{5}{0-3}\geq\frac{3}{0+1}$
$\frac{5}{-3}\geq3$
This is *False*.
![[Pasted image 20240821233816.png]]
	I can't even think about draw a graph here since we have essentially turn one function into a straight line and morph the space around the other. I think this is interesting so I will write a small section about it.

So we have F, T, F, T. And our answer is $[-7,-1)\cup(3,\infty)$.
![[Pasted image 20240821234312.png]]
	Here's the graph. We're looking for where *red* is above *blue*.

#### Conformal Mapping and Coordinate Transformation

You'll learn more about this in *differential geometry* and *complex analysis*, but here's an overview of how cool these things look.

1. **Conformal Mapping**:

- **Definition**: Conformal mapping is a technique used in complex analysis to transform one complex plane into another while preserving angles. This can be used to map complicated shapes or functions into simpler ones while retaining the fundamental properties of the function.
- **Application**: You can use conformal mapping to transform the space so that one of your functions becomes a straight line, while the other function undergoes a transformation based on the mapping. However, conformal mappings are usually applied to functions of a complex variable.
![[Pasted image 20240821235120.png]]

2. **Coordinate Transformation**:

- **Definition**: A coordinate transformation involves changing the coordinate system in which a function is expressed. This can involve translating, rotating, scaling, or otherwise modifying the coordinates in which the function is defined.
- **Application**: You could apply a transformation that shifts one of the functions so that it becomes a constant, effectively "flattening" the function. The transformation will simultaneously morph the space around the other function, changing how it appears without altering its inherent mathematical form.

Effects of different coordinate transformations. (a) Conformal coordinate transformation. (b) Affine coordinate transformation. (c) Projective coordinate transformation:
![[Pasted image 20240821234944.png]]

## Composition of Functions

This is when one **entire** function is *substituted* into the *variable* of another function.
For example:
For $f(x), g(x)$: $$(f \circ g)(x)=f(g(x))$$Here's how you read it: $f$ of $g$ of $x$.

Say we have:$$f(x)=2x^2-5$$$$g(x)=1-3x^2$$
What is:$$(f\circ g)(x)$$$(f\circ g)(x)=2(1-3x^{2})^{2}-5$
$(f\circ g)(x)=2(1-6x^{2}+9x^{4})-5$
$(f\circ g)(x)=2-12x^{2}+18x^{4}-5$
$(f\circ g)(x)=18x^{4}-12x^{2}-3$

What is:$$(g\circ f)(x)$$$(g\circ f)(x)=1-3(2x^{2}-5)^{2}$
$(g\circ f)(x)=1-3(4x^{4}-20x^{2}+25)$
$(g\circ f)(x)=1-12x^{4}+60x^{2}-75$
$(g\circ f)(x)=-12x^{4}+60x^{2}-74$

What is:$$(f\circ f)(x)$$$(f\circ f)(x)=2(2x^{2}-5)^2-5$
$(f\circ f)(x)=2(4x^{4}-20x^{2}+25)-5$
$(f\circ f)(x)=(8x^{4}-40x^{2}+50)-5$
$(f\circ f)(x)=8x^{4}-40x^{2}+45$

What is:$$(g\circ g)(x)$$$(g\circ g)(x)=1-3(1-3x^{2})^2$
$(g\circ g)(x)=1-3(9x^{4}-6x^{2}+1)$
$(g\circ g)(x)=1-27x^{4}+18x^{2}-3$
$(g\circ g)(x)=-27x^{4}+18x^{2}-2$

What is:$$(f\circ g)(1)$$We know that: $(f\circ g)(x)=18x^{4}-12x^{2}-3$. So:
$(f\circ g)(1)=18(1)^{4}-12(1)^{2}-3$
$(f\circ g)(1)=18-12-3$
$(f\circ g)(1)=3$
Or we can also look at it as: $f(g(1))$
$(f\circ g)(1)=2(1-3(1)^{2})^{2}-5$
$(f\circ g)(1)=2(-2)^{2}-5$
$(f\circ g)(1)=8-5$
$(f\circ g)(1)=3$

What is:$$(g\circ f)(2)$$We know that, $(g\circ f)(x)=-12x^{4}+60x^{2}-74$. So:
$(g\circ f)(2)=-12(2)^{4}+60(2)^{2}-74$
$(g\circ f)(2)=-192+240-74$
$(g\circ f)(2)=-26$
Let's check our answer with $g(f(2))$, which should be easier in this case:
$(g\circ f)(2)=1-3(2(2)^{2}-5)^{2}$
$(g\circ f)(2)=1-3(3)^2$
$(g\circ f)(2)=1-27$
$(g\circ f)(2)=-26$

What is:$$(f\circ f)(-1)$$$(f\circ f)(x)=8(-1)^{4}-40(-1)^{2}+45$
$(f\circ f)(-1)=8-40+45$
$(f\circ f)(-1)=13$

What is:$$(g\circ g)(0)$$$(g\circ g)(x)=-27(0)^{4}+18(0)^{2}-2$
$(g\circ g)(0)=-2$
## Finding Domain of Composite Functions

For $f(x), g(x)$: $$(f \circ g)(x)=f(g(x))$$
- the $g(x)$ inside $f$ is called an *inside function*. Find the **Domain** of the inside function *first*.
- Then find the **Domain** of simplified composition or simplified $f(g(x))$.
Our Domain is a combination of the results from these two.

Say we have:$$f(x)=2x^2-5$$$$g(x)=1-3x^2$$- Note that we don't see any *even* radicals, denominators, nor logarithms for both of these functions, which means that $D:\{x|x \text{ is all real numbers}\}$

Say we want to find the Domain of $(f\circ g)(x)$:
- The inside function of $(f\circ g)(x)$ is $g(x)$ and Domain of $g(x)$ is $D:\{x|x \text{ is all real numbers}\}$.
- $(f\circ g)(x)=18x^{4}-12x^{2}-3$ (from the [[#Composition of Functions|previous section]]). We don't see any square roots or other even radicals, denominators, nor logarithms for this function, so the Domain of our simplified composition is $D:\{x|x \text{ is all real numbers}\}$.
So we can conclude that the Domain of $(f\circ g)(x)$ is $D:\{x|x \in \mathbb{R}\}$.

Let's look at a more complicated example:
Say we have:$$f(x)=\frac{x}{x+3}$$- Here we have a denominator of $x+3$. This means that our $x$ can be anything but -3 or else the denominator become a zero and the universe will collapse itself. So, $D:\{x:x\neq-3\}$.
$$g(x)=\frac{2}{x}$$- Same case here but $x$ cannot be 0. So, $D:\{x:x\neq0\}$

Now we have identified the Domain for each of our potential *inside functions*. Let us now look at the composite functions:$$(f\circ g)(x)$$$(f\circ g)(x)=\frac{\frac{2}{x}}{\frac{2}{x}+3}$
$(f\circ g)(x)=\frac{\frac{2}{x}}{\frac{2}{x}+\frac{3x}{x}}$
$(f\circ g)(x)=\frac{\frac{2}{x}}{\frac{2+3x}{x}}$
$(f\circ g)(x)=\frac{2}{x}\cdot \frac{x}{2+3x}$
$(f\circ g)(x)=\frac{2}{2+3x}$
Find $x$ that makes $2+3x=0$:
$2+3x=0$
$x=- \frac{2}{3}$
So the Domain of our simplified composition is $D:\{x:x\neq - \frac{2}{3}\}$

Combining the 2, we can conclude that the Domain of $(f\circ g)(x)$ is $D:\{x:x\neq - \frac{2}{3}, x\neq0\}$.

What about:$$(g\circ f)(x)$$$(g\circ f)(x)=\frac{2}{\frac{x}{x+3}}$
$(g\circ f)(x)=2\cdot\frac{x+3}{x}$
$(g\circ f)(x)=\frac{2x+6}{x}$
So $D:\{x:x\neq0\}$ is the Domain of our simplified composite function. Since $f(x)$, which is our inside function, has a domain of $D:\{x:x\neq-3\}$. We combine the two and get the Domain of $(g\circ f)(x)$: $D:\{x:x\neq0, x\neq-3\}$. 

### More examples

Say we have:$$f(x)=x^2 +1$$- Here we don't see any *even* radicals, denominators, nor logarithms, which means that $D:\{x|x \in \mathbb{R}\}$ for this function.
$$g(x)=\sqrt{x-1}$$- Notice the even radicals (square root) here. [[#Finding the Domain of Functions|Remember]] that inside of our square root should not be a negative number since we are working in real number system. So $x-1\geq0 \to x\geq1$. So, $D:\{x|x\geq1\}$.

$$(f\circ g)(x)$$
$(f\circ g)(x)=(\sqrt{x-1})^{2}  +1$
Square root and square are inverse function of one another so they cancel each other out. 
	Note that they can only cancel one another out under the condition of our domain. Imagine $(\sqrt{-1})^{2}$ under real number system (it would be $i$ under imaginary number system).
$(f\circ g)(x)=x-1+1$
$(f\circ g)(x)=x$
The Domain of our composite function is  $D:\{x|x \in \mathbb{R}\}$. However, we must not forget the domain of our inside function which is $g(x)$, although it has become hidden here, which is $D:\{x|x\geq1\}$. So, the Domain of $(f\circ g)(x)$ is $D:\{x|x\geq1\}$.

$$(g\circ f)(x)$$
$(g\circ f)(x)=\sqrt{(x^{2}+1)-1}$
$(g\circ f)(x)=\sqrt{x^{2}}$
$(g\circ f)(x)=x$
Now this is an interesting *contrast* to the previous example. The Domain for $(g\circ f)(x)$ is $D:\{x|x \in \mathbb{R}\}$. Notice how our inside function or $f(x)$ make it *impossible* to make inside the square root negative, which is why we don't have any Domain issues in this case. 

Notice that $(f\circ g)(x)$ and $(g\circ f)(x)$ simplified output the same thing, which is $x$. This is because they are inverse function of one another and this will always be the case for other cases of composite functions of inverse functions.

## One-to-One Functions

One-to-One Functions are just functions where one input give one *unique* output.

This is necessary for developing the idea of [[#Finding Inverse Functions|inverse functions]]. 
	In an inverse function, we will switch $x$ with $y$ values. So we will need the function to be one-to-one.

| Employee | ID  |
| -------- | --- |
| Mark     | 325 |
| Joe      | 184 |
| Ty       | 007 |
| Jane     | 291 |
Notice how one employee can be mapped to a unique ID and vice versa. Imagine an inverse function of this:

| ID  | Employee |
| --- | -------- |
| 325 | Mark     |
| 184 | Joe      |
| 007 | Ty       |
| 291 | Jane     |
What if our function is not one-to-one?

| Employee | ID  |
| -------- | --- |
| Mark     | 325 |
| Joe      | 184 |
| Ty       | 007 |
| Jane     | 007 |
This is still a function (one input gives one output). If we inverse it, notice how inputting '007', we will not know for sure what will come out:

| ID  | Employee |
| --- | -------- |
| 325 | Mark     |
| 184 | Joe      |
| 007 | Ty       |
| 007 | Jane     |
This is NOT a function (one input gives two output). In inverse function, where output become input and vice versa, this (non one-to-one functions) just doesn't make sense.

Say we have:$$f=\{(1,-2),(3,4),(-7,1),(18,12)\}$$$$g=\{(2,6),(11,9),(-5,-2),(6,-3),(-1,6)\}$$Here our inputs are the $x$ values and outputs are the $y$ values.
- Notice the difference in relationships of input and output in $f$ and $g$:
	- For $f$
		- Looking at our inputs ($x$): 1, 3, -7, 18. All of these are unique and thus $f$ is a *function*.
		- Looking at our outputs ($y$): -2, 4, 1, 12. All of these are unique and thus $f$ is a *one-to-one function*.
		- Does $f$ has an inverse? Yes, because it is one-to-one.
	- For $g$
		- Looking at our inputs ($x$): 2, 11, -5, 6, -1. All of these are unique and thus $g$ is a *function*.
		- Looking at our outputs ($y$): 6, 9, -2, -3, 6. 6 are repeated twice and $g$ is NOT a *one-to-one function*.
		- Does $g$ has an inverse? No, because it is NOT one-to-one.
	- Inverses are how we mathematically *undo* a lot of the things that we have e.g. why do we have subtraction? because we have addiction. why do we have division? because we have multiplication. why do we have logarithm? because we have exponential, and so on.

How do we check for repeated inputs or outputs graphically:
![[Pasted image 20240825155753.png]]
- Say we want to check if our $x$ are repeated, we draw a *vertical line* aka. vertical line test to check if this represent a functional relationship.
- Say we want to check if our $y$ are repeated, we draw a *horizontal line* aka. horizontal line test to check if this represent a one-to-one functional relationship.

Let's look at some examples:
**a straight line**
![[Pasted image 20240825160043.png]]
![[Pasted image 20240825160127.png]]
This is one-to-one.

![[Pasted image 20240825160302.png]]
This is one-to-one.

a parabola?
![[Pasted image 20240825160354.png]]
This is NOT one-to-one (it is still a function). But wait... a parabola has an inverse function?
- A **parabola** represented by the function $f(x) = x^2$ is **not one-to-one** over the entire set of real numbers because it fails the Horizontal Line Test. 
	- For example, $f(2)=4$ and $f(−2)=4$, which means $x^2 = 4$ has two different inputs $x=2$ and $x=−2$ that give the same output.
- The **square root function**, $g(x) = \sqrt{x}$​, is commonly considered the "inverse" of the function $f(x) = x^2$ when restricted to **non-negative values**. This is because when we restrict the domain of $f(x) = x^2$ to $x \geq 0$, the function becomes one-to-one. 

## Finding Inverse Functions

A function has an inverse if and only if it is [[#One-to-One Functions|one-to-one]]. 
- inverse functions *undo* each other
- for $f(x)$ is a one-to-one function, the inverse is $f^{-1}(x)$, pronounced $f$ inverse of $x$, and it is also one-to-one.

Let's look at an example when we have a *function* and we *compose* it with its inverse:
- $(f\circ f^{-1})(x)=x$ 
- $(f^{-1}\circ f)(x)=x$
Notice both just output back our input ($x$) because the function and its inverse just cancel out one another leaving our output the same as our input.

Say, for example, $f=\{(1,-2),(3,5),(7,-3),(5,8)\}$, then $f^{-1}=\{(-2,1),(5,3),(-3,7),(8,5)\}$.

Let's take a look at some of the examples:
$$f(x)=1-3x$$
How do we figure out the inverse of $f(x)$? To find an inverse, we want to switch our input ($x$) with output ($y$). 
Let's call it $x$ and $y$ first:
$y=1-3x$
Now simply switch $x$ and $y$:
$x=1-3y$
Now solve for $y$. 
$y=\frac{x-1}{-3}$
$y=- \frac{x-1}{3}$ or $y=\frac{-x+1}{3}$
Why solve for $y$? Notice how rearranging it this way *undoes* our previous operations, which is what an inverse does. Now renaming this to our official notation:
$f^{-1}(x)=\frac{-x+1}{3}$

$$g(x)=x^3+4$$
First ask yourself, is this a one-to-one function? Yes, this is just a cubed power function shifted up by 4. So it *has* an inverse.
$y=x^{3}+4$
$x=y^3+4$
$x-4=y^3$
$\sqrt[3]{x-4}=y$
Power three retains the signs of their *radicands* so no need for $\pm$ sign like we would in even roots.
So: $g^{-1}(x)=\sqrt[3]{x-4}$.
Let's be playful and try composing $g(x)$ with our newfound inverse $g^{-1}(x)$:
$(g\circ g^{-1})(x)=(\sqrt[3]{x-4})^3+4$
$(g\circ g^{-1})(x)=x$
This is just to drill down the idea that the output of composition of a function with its inverse will just be the input ($x$). This idea will lead to how can we solve exponentials and logarithms.

$$h(x)=x^2+9$$
First ask yourself, is this a one-to-one function? No, this is a parabola (shifted up by 9) and these certainly does not pass the *horizontal* line test. However, we can fix this by looking at only one side of the parabola (separated by its axis of symmetry).
![[Pasted image 20240825181616.png]]
Let's look at this algebraically:
$y=x^{2}+9$
$x=y^2+9$
$x-9=y^2$
$\pm\sqrt{x-9}=y$
Hey, one-to-one are not supposed to have 2 outputs. We must close our eyes, and only look at where we actually have one-to-one. This is done by fixing our Domain to $x\geq0$, leaving us with positive x-axis. With $D:\{x\geq0\}$, we're now left with:
$+\sqrt{x-9}=y$
Which gives one *unique* output.
Re-writing this as: $h^{-1}(x)=\sqrt{x-9}$
### More examples
$$f(x)=\frac{4}{2-x} $$
Let's briefly discuss how this function looks:
- E.B.
	$\frac{1}{x}$ and we have [[#^2d8963|a horizontal asymptote]] at $y=0$
- x-intercept
	There's none since we have a H.A. at $y=0$
- y-intercept
	$f(0)=2$
- V.A.
	at $x=2$, and it's not a hole since $x$ can't be cancelled.
![[Pasted image 20240825183910.png]]

Now onto our inverse:
$y=\frac{4}{2-x}$
$x=\frac{4}{2-y}$
$(2-y)(x)=4$
$-y=\frac{4}{x}-2$
$y=2-\frac{4}{x}$
$y=\frac{2x-4}{x}$
So: $f^{-1}(x)=\frac{2x-4}{x}$. Let's think about how this looks graphically:
- E.B.
	degree of denom = degree of num. ($\frac{2x}{x}$) so we have a H.A. at $y=2$, which is also our end behavior.
- x-intercept
	$0=2x-4$
	$x=2$
- y-intercept
	$f(0)=\frac{2(0)-4}{0}$
	This is *undefined* so we have a V.A. at $x=0$.
- Additional point for reference
	$f(-1)=\frac{2(-1)-4}{-1}$
	$f(-1)=6$
Notice how a V.A. @ $x=2$ and a H.A. @ $y=0$ for our original function become a V.A. @ $x=0$ and a H.A. @ $y=2$ for the inverse. They switch just like Domain and Range!
![[Pasted image 20240825184943.png]]

Let's look at the actual graph:
![[Pasted image 20240825185423.png]]

$$g(x)=\frac{-2x}{x-1}$$
This seems like a one-to-one function. Let's proceed:
$y=\frac{-2x}{x-1}$
$x=\frac{-2y}{y-1}$
$x(y-1)=-2y$
$xy-x=-2y$
$-x=-2y-xy$
$-x=-y(2+x)$
$\frac{-x}{2+x}=-y$
$y=\frac{x}{x+2}$
So: $g^{-1}(x)=\frac{x}{x+2}$.

Let's compose $(g\circ g^{-1})(x)$, just for fun:
$(g\circ g^{-1})(x)=\frac{-2(\frac{x}{x+2})}{(\frac{x}{x+2})-1}$
$(g\circ g^{-1})(x)=\frac{\frac{-2x}{x+2}}{\frac{x-x-2}{x+2}}$
$(g\circ g^{-1})(x)=\frac{\frac{-2x}{x+2}}{\frac{-2}{x+2}}$
$(g\circ g^{-1})(x)=\frac{-2x}{x+2}\cdot \frac{x+2}{-2}$
$(g\circ g^{-1})(x)=x$
We still got an $x$. This is a way to check if this is truly the inverse for $g(x)$ and that reality hasn't collapse itself yet.

$$h(x)=- \frac{3x+4}{x-2}$$
One-to-one? Seems so.
$y=- \frac{3x+4}{x-2}$
$x=- \frac{3y+4}{y-2}$
$x=\frac{-3y-4}{y-2}$
$x(y-2)=-3y-4$
$xy-2x=-3y-4$
$xy+3y=-4+2x$
$y(x+3)=-4+2x$
$y=\frac{2x-4}{x+3}$
So, $h^{-1}(x)=\frac{2x-4}{x+3}$.

$$f(x)=\frac{x^2+3}{3x^2}$$
One-to-one? Well let's see:
$y=\frac{x^{2}+3}{3x^{2}}$
$x=\frac{y^{2}+3}{3y^{2}}$
$x(3y^{2})=y^{2}+3$
$3xy^2=y^{2}+3$
$3xy^{2}-y^{2}=3$
$y^{2}(3x-1)=3$
$y^{2}=\frac{3}{3x-1}$
$y=\pm\sqrt{\frac{3x}{3x-1}}$
This is not a one-to-one function as it is an even function. We must set our Domain. Let's set $x\geq0$ and be done with it. Wait... if $x=0$ then the output will just be undefined. Our Domain should be $x>0$. So we're left with:
$y=+\sqrt{\frac{3x}{3x-1}}$

Let's think about the graphical representation of $f(x)=\frac{x^2+3}{3x^2}$ for a second here:
- E.B.
	$\frac{x^{2}}{3x^{2}}$, our E.B. will be a H.A. at $\frac{1}{3}$.
- Factor
	$\frac{x^{2}+3}{3x(x)}$
	So we have a V.A. at $x=0$ with a multiplicity of 2 (even).
- x-intercept
	$0=x^{2}+3$
	$-3=x^2$
	$x=\pm\sqrt{-3}$
	So we have no real x-intercept.
- y-intercept
	$f(0)=\frac{0^{2}+3}{3(0)^{2}}$
	$f(0)=\frac{3}{0}$
- Additional points for reference
	$f(1)=\frac{1^{2}+3}{3(1)^{2}}$
	$f(1)=\frac{4}{3}$
	Since this is an even function, we can infer that $f(-1)$ will output the same thing.
![[Pasted image 20240825201439.png]]
### Notes on Graphical Representation of Inverse Functions

Graphically, because we switch our $x$ with our $y$, we are going to *reflect* $f$ over $y=x$ line.
![[Pasted image 20240825201118.png]]
Think about it this way:

| g      | $g^-1$ |
| ------ | ------ |
| (-2,1) | (1,-2) |
| (-1,0) | (0,-1) |
| (0,-2) | (-2,0) |
| (3,-7) | (-7,3) |
This scale is off but you get the idea.![[Pasted image 20240825202244.png]]
Notice how the Domain and Range switch between the function and the inverse.
## Graphs of Exponential Functions
$$f(x)=a^x $$
- $x$ is the *variable*
- $a$ is the *base*

Notice the difference between exponential and polynomials:
- whereas a *polynomial* takes a *variable* and raise it to a *constant* exponent
- an *exponential* switches that and take a positive *constant* (not 1 and zero but can be anything between) as the base and raise it to a *variable*

For $f(x)=a^{x}, a>0$
- If $a>1$:
	Say $a=2$, so $2^{x}$![[Pasted image 20240826161220.png]]
	Notice the horizontal asymptote at $y=0$. If $x<0$ e.g. $x=-1$, then $2^{-1}=\frac{1}{2^{1}}$ and if $x=-2$, then $2^{-2}=\frac{1}{2}^{2}$. Here are some of the points on $f(x)=2^{x}$:
	- $(-2,\frac{1}{4 })$
	- $(-1,\frac{1}{2})$
	- $(0,1)$
	- $(1,2)$
	- $(2,4)$
	Notice how this can *never* reach zero and that the graph is *always climbing*. The higher the $a$, the steeper the climb.
- If $a<1$:
	Say $a=\frac{1}{2}$, so $\frac{1}{2}^{x}$![[Pasted image 20240826161601.png]]
	Once again, notice the H.A. at $y=0$. If $x<0$ e.g. $x=-1$, then $\frac{1}{2}^{-1}=\frac{2}{1}^{1}$ and if $x=-2$, then $\frac{1}{2}^{-2}=\frac{2}{1}^{2}$. Here are some of the points on $f(x)=\frac{1}{2}^{x}$:
	- $(-2,4)$
	- $(-1,2)$
	- $(0,1)$
	- $(1,\frac{1}{2})$
	- $(2,\frac{1}{4})$
	Notice how this can *never* reach zero and that the graph is *always falling*. The closer $a$ is to 0, the steeper the fall.
- Notice the common points in the above two examples
	Any $a^{0}=1$ and any $a^{1}=a$. That's our key points:
	- $(0,1)$  
	- $(1,a)$
	They both have a horizontal asymptote at $y=0$
- What if $a=1$? It will just be a straight line at $y=1$ since, for any $x$, $1^{x}=1$. What if $a=0$ ? Well you get straight line at 0.

One more thing that we must know about exponential functions:$$f(x)=e^x$$- $e$ is Euler's number ($e\approx2.7$), it occurs a *lot* in nature and in mathematics.![[Pasted image 20240826163238.png]]

All of these functions are [[#One-to-One Functions|one-to-one]], thus they have an [[#Finding Inverse Functions|inverse]] (namely, logarithm).
## Graphing Exponential Functions with Transformations

Firstly, rmb the key points discussed on the previous section for $f(x)=a^{x}$:
- $(0,1)$
- $(1,a)$
And that we have a H.A. at $y=0$.

Let's look at some examples:$$f(x)=3^x-2$$So we have $a=3$ which is more than 1. It should be a bit steeper than $2^{x}$. Notice that the $-2$ is subtracted from the *function* (*after* the exponential part or $3^x$). This means that the function is shifted down by 2 (denoted S.D. below). 
![[Pasted image 20240826164610.png]]
Rmb our key points, we just plot it based on our new baseline:
- $(0,1)$
- $(1,a)$
![[Pasted image 20240826164844.png]]
Since $a>1$, the graph is growing (you can infer from your key points):
![[Pasted image 20240826164934.png]]
This is only a sketch and more points can be added for more precision.

$$f(x)=2^{x+2} $$
Tips: put a parentheses on whatever affects our input (the exponent):
$f(x)=2^{(x+2)}$
Now we clearly see that this $+2$ directly affect our input, this is a shift left.

The red dots below are points on $2^{x}$, and the blue dots are points on $2^{(x+2)}$:![[Pasted image 20240826165508.png]]
Notice how the $+2$ reaches make $2^{(x+2)}$ points reach some value $y$ faster than $2^{x}$ by 2.
Once again just plot our key points based on our new baseline:
- $(0,1)$
- $(1,a)$
![[Pasted image 20240826165957.png]]

$$f(x)=-3^x+1$$
Rmb the difference between $-3^x$ and $(-3)^x$:
- say $-3^{2}=-1\cdot 3^2=-9$ 
- $(-3)^{2}=9$
So, let's re-arrange a little to make it clearer:
$f(x)=-(3)^{x}+1$
$+1$ is a shift up by 1. We don't see anything directly affecting our $x$ so no horizontal shift. The $-()$ is a *reflection*. 
Let's look at our key points (note that these key points are relative):
- $(0,1)\to(0,-1)$
- $(1,a)\to(0,-a)$
![[Pasted image 20240826171122.png]]

$$f(x)=1-2^{x+3} $$
Let's re-arrange:
$f(x)=-(2)^{(x+3)}+1$
Shift up by 1, shift left by 3, and a reflection.
![[Pasted image 20240826171420.png]]

$$f(x)=3(\frac{1}{2})^x$$
Notice that $a<1$ so the graph should be *falling* before any shifting. No vertical or horizontal shift but we have a vertical stretch from the coefficient of 3.
Key points:
- $(0,1)\to (0,3)$, from the coefficient of 3
- $(1,\frac{1}{2})\to(1, \frac{3}{2})$
![[Pasted image 20240826173059.png]]
### Examples with Base $e$
$$f(x)=e^{x+2}-1$$
We have a shift left by 2 and shift down by 1. The fact that it has base $e$ shouldn't change anything much. $e\approx2.71$ so it is more than 1, thus the graph should be climbing.
Key points:
- $(0,1)$
- $(1,e)$
Our y-intercept is: $f(0)=e^{2}-1\approx6.344$
![[Pasted image 20240826173651.png]]

$$g(x)=5-2e^{-x+1}$$
Okay this is a more complex one, let's re-arrange it:
$g(x)=-2\cdot e^{-(x-1)}+5$
Let's think about this:
- Clearly a shift up by 5
- Notice that we put a parentheses in such a way that make $x$ positive. There is a right shift by 1. The $-()$ directly affect the input variable which is a reflection about y-axis.
- $-2$ is a vertical stretch and a reflection about the x-axis
Let's do this one a little slowly so we don't mess up:
![[Pasted image 20240826174517.png]]
The shift right and shift up is taken care of. Now, let's look at our key points:
- $(0,1) \to (0,-2)$
	- $(-1 \cdot 0, 1 \cdot -2)$
- $(1,e) \to (-1, -2e)$
	- $(-1 \cdot 1, e \cdot -2)$
![[Pasted image 20240826174837.png]]

## Solving Exponential Equations with Common Bases

We learned one-to-one functions, so that we can learn about inverses. We learn about inverses, so that we know that composing a function with its inverse will undo one another. Exponential functions are one-to-one, Logarithms are their inverse and composing the two will undo it (solve it), and this is the general approach for solving these equations. 
However, there are times when you can solve it without logarithm, namely when you have common bases.

**If $a^{x}=a^{y}$, then $x=y$.**
	Imagine $2^{x}=2^{3}$. The only value that make this statement true is if $x=3$.

For example,$$2^{-x}=16$$Make the right side base 2 to get common bases.
$2^{-x}=2^{4}$
So, we can infer that:
$-x=4$
$x=-4$
### More examples
$$2^{2x-1}=4^{3x+1}$$
Make the right side base 2:
$2^{2x-1}=2^{2(3x+1)}$
So:
$2x-1=2(3x+1)$
$2x-1=6x+2$
$-3=4x$
$x=- \frac{3}{4}$

$$25^{x+3}=\frac{1}{125}$$
Make the right side base 5:
$5^{2(x+3)}=125^{-1}$
$5^{2(x+3)}=(5^{3})^{-1}$
$5^{2(x+3)}=5^{-3}$
So:
$2(x+3)=-3$
$2x+6=-3$
$2x=-9$
$x=- \frac{9}{2}$

$$9^{2x}\cdot 27^{x^2}=\frac{1}{3}$$
$(3^2)^{2x}\cdot (3^{3})^{x^{2}}=3^{-1}$
$3^{4x}\cdot 3^{3x^{2}}=3^{-1}$
$3^{3x^{2}+4x}=3^{-1}$
So:
$3x^{2}+4x=-1$
$3x^2+4x+1=0$
![[Pasted image 20240826181046.png]]
$(x+1)(3x+1)=0$
By zero product property:
$x=-1$ and $x= - \frac{1}{3}$

$$3^{x^2}\cdot \frac{1}{3^7}=27^{2x} $$
$3^{x^{2}}\cdot 3^{-7}=(3^{3})^{2x}$
$3^{x^{2}}\cdot 3^{-7}=3^{6x}$
So:
$x^{2}-7=6x$
$x^2-6x-7=0$
![[Pasted image 20240826181337.png]]
$(x-7)(x+1)=0$
So $x=7$ and $x=-1$

$$e^{x^2}=e^{3x}\cdot \frac{1}{e^2}$$
$e^{x^2}=e^{3x}\cdot e^{-1\cdot2}$
So:
$x^{2}=3x-2$
$x^{2}-3x+2=0$
![[Pasted image 20240826181525.png]]
$(x-2)(x-1)=0$
So $x=2$ and $x=1$.
## Introduction to Logarithms and Their Graphs

Where logarithms come from? Why do they exists? What do their graph looks like?

Let's take a little look at [[#Graphs of Exponential Functions|Exponentials]]:
- Key points are: $(0,1),(1,a)$ 
- Horizontal Asymptote somewhere (without transformation, at $y=0$)
- Domain is all real numbers (no Domain issues)
- Range is $(0,\infty)$
	- We can't really get an output of 0 from exponential functions
- Exponentials are [[#One-to-One Functions|one-to-one]] functions, meaning that they have [[#Finding Inverse Functions|inverses]]

Red line is $f(x)=a^{x}, a>1$ or an exponential function, whereas the blue line is its inverse (reflected across $y=x$). Notice how the red line has a horizontal asymptote at $y=0$, while the blue line has a vertical asymptote at $x=0$ (they switched!)
![[Pasted image 20240827192627.png]]

Similarly, red line is $f(x)=a^{x}, a<1$. Notice the point of intersection between red and blue line, that's when you switch $x$ and $y$ and still get the same thing ($y=x$).
![[Pasted image 20240827193344.png]]

Notice how the inverses are the opposite of their original functions.
- In both $a>1$ and $0<a<1$:
	- The Domain of *Exponentials* are all real numbers or $(-\infty,\infty)$, but the Range is $(0,\infty)$.
	- The Domain of *Logarithms* are $(0,\infty)$, but the Range is all real numbers or $(-\infty,\infty)$.
	They switched! *Domain* become *Range* and vice versa. $x$ become $y$ and vice versa. *H.A.* become *V.A.* and vice versa.

Let's look at the logarithms seperately:
- $a>1$
	![[Pasted image 20240827194823.png]]
- $a<1$
	![[Pasted image 20240827194622.png]]
Let's list out some of its properties:
- Key points: $(1,0),(a,1)$
- They have V.A. instead of H.A.
- D: $(0,\infty)$; what a very optimistic function, *always positive*!
- R: $(-\infty,\infty)$

What does this mean *algebraically*?
$f(x)=a^x$
$y=a^x$
switch $x$ and $y$.
$x=a^y$
How do we solve for $y$? There must be a algebraic expression to represent this operation, thus:
$y=\log_a{x}$
$f^{-1}(x)=\log_a{x}$
![[Pasted image 20240827195410.png]]

Let's look at some example:
$$9=3^x $$
$\log_3{9}=2$
Notice how $\log$ separate the base from its exponent, bringing them to opposite side of your equation, and the $9$ become your argument for the log function. Read this as: from *base* 3 what *exponent* we need to get 9? That would be 2.

$$a^3=2.1$$
$\log_{a} {2.1}=3$

$$2^x=7.2$$
$\log_2{7.2}=x$
Notice how $log$ rips apart the base and the exponent, making the equation solve for $x$. It *undoes* the exponent.

$$10^x =2.3$$
$\log_{10}2.3=x$
Notice that we have a base of 10. This is called a *common log*, we don't even have to write the base here: $\log2.3=x$. You can call this *log of 2.3* and people will understand that this is a common log and has a base of 10.

$$e^x =8$$
$\log_{e}{8}=x$
Notice that we have a base of $e$, which is the Euler's number or *natural* number. This is called a *natural log* and is written as: $\ln8=x$. 
	Ironically, you'll probably see that natural logs are more common than common logs.

Let's do the reverse and convert $\log$ notation back to exponent:
$$\log_3 \frac{1}{9}=-2$$
$3^{-2}=\frac{1}{9}$

$$\log_b 4=2$$
$b^{2}=4$
$b=\pm2$? 
Rmb, when we talk about logarithm and exponential functions, negative *bases* are *disallowed*. So $b=2$. Be *very* careful about this.

$$\log_2 6=x$$
$2^{x}=6$

$$\ln4=x$$
$e^{x}=4$

$$log_{10}  x=3$$
$10^{3}=x$
$x=1000$

Notice from our little back-and-forth between exponentials and logarithms, is that they help solve one another because they are inverse of another.

Let's see some examples where we actually solve for $x$:
$$log_5 25=x$$
This is asking what power do you need to go from 5 to 25? the answer is 2.
$5^{x}=25$
$5^{x}=5^{2}$
Notice the [[#Solving Exponential Equations with Common Bases|common bases]]:
$x=2$

$$\log_{\frac{1}{3}}9=x$$
$\frac{1}{3}^{x}=9$
$\frac{1}{3}^{x}=\frac{1}{3}^{-2}$
$x=-2$

$$\log\sqrt{10}=x$$
$10^x=\sqrt{10}$
$10^{x}=10^{\frac{1}{2}}$
$x=\frac{1}{2}$

$$\log_5 \sqrt[3]{25}=x$$
$5^{x}=\sqrt[3]{25}$
$5^{x}=25^{\frac{1}{3}}$
$5^{x}=5^{\frac{2}{3}}$
$x=\frac{2}{3}$

$$\log_{\sqrt{3}}9=x$$
$\sqrt{3}^{x}=9$
$3^{\frac{x}{2}}=3^{2}$
$\frac{x}{2}=2$
$x=4$

$$\ln e^3=x$$
$e^{x}=e^{3}$
$x=3$

$$\log_{2}1=x$$
$2^x=1$
$2^x=2^0$
$x=0$

### Notes on Domain of Logarithms

Rmb, our domain issues:
- the denominator can't be 0 ($\frac{x}{y}, y\neq0$)
- radicands must be greater or equal to 0 ($\sqrt{x}, x\geq0$)
- with $\log$, our $\text{argument of log} > 0$ or must be *positive*
Try pressing ln(0) in your calculator. That'll do it to the bastard...

Say:$$f(x)=\ln(x-3)$$Our argument sits inside the parentheses, $x-3$.
- notice that $-3$ is a shift right
So:
$x-3>0$
$x>3$
This is our Domain. $D:\{x>3\}$.

$$g(x)=3-2\log_{4}[5-\frac{x}{2}]$$
Our argument is $5- \frac{x}{2}$.
Some notes on transformation, re-arranging this: $-2\log_{4}[- \frac{1}{2}(x- 10)]+3$.
- Outside the argument
	- -2 is a vertical stretch and a reflection about x-axis
	- +3 is a shift up
- Inside the argument
	- $-10$ is a shift right
	- $- \frac{1}{2}$ is a [[#^9ec6e7|horizontal stretch]] and a reflection about y-axis

Back to our Domain:
$5- \frac{x}{2}>0$
$- \frac{x}{2}>-5$
	DO NOT DO THIS: $\frac{x}{-2}>-5\to x>10$. This completely neglect the necessary operation of multiplying both side by -2, changing the direction of this inequality.
$- \frac{x}{2}\cdot-2<-5\cdot-2$
$x<10$
So: $D:\{x<10\}$

$$h(x)=\log_5[\frac{x+1}{x}]$$
Domain:
$\frac{x+1}{x}>0$
$\frac{x+1}{x}\cdot x>0\cdot x$
$x+1>0$
$x>-1$
But wait... since the denominator is $x$, we can't let $x=0$. So $x\neq0$. Furthermore:
- $x\neq0$ meaning that we have a V.A. at $x=0$
- since our numerator is $x+1$, we know that our x-intercept at $x=-1$ with a mult. of 1, which is a cross.
We can use a number line to list out our Domain issues:
![[Pasted image 20240827211335.png]]
- any $x>0$ here would be *true* (try it.)
- since we have an odd V.A., rmb how they would come from opposite directions, so this one must be *false*
	![[Pasted image 20240827211451.png]]
- from $[-1,0]$ where this is false, since we have a cross at $x=-1$, the interval before that must be *true*
So our Domain is: $D:(-\infty,-1)\cup(0,\infty)$.

## Graphing Logarithms with Transformations

Rmb, what we knew about [[#Introduction to Logarithms and Their Graphs|graphing logarithms]]:
- $a>1$
	![[Pasted image 20240827194823.png]]
- $a<1$
	![[Pasted image 20240827194622.png]]
Let's list out some of its properties:
- Key points: $(1,0),(a,1)$
- They have V.A. at $x=0$
- D: $(0,\infty)$
- R: $(-\infty,\infty)$

$$f(x)=2+\ln(x-1)$$
Let's re-arrange this:
$f(x)=\ln(x-1)+2$
- +2 means shift up by 2
- -1 inside the argument mean right shift by 1
Let's write our key points:
- $(1,0)$
- $(a,1)$, since a is the base which would be e in our case so: $(e,1)$
Consider the Domain:
$x-1>0$
$x>1$
So the V.A. is at $x=1$.
![[Pasted image 20240827235241.png]]
Since our base is $e$, which is more than one. It should look like this:
![[Pasted image 20240827194823.png]]

Here's our graph:
![[Pasted image 20240827235600.png]]

$$g(x)=3-2\log_{4}[5-\frac{x}{2}]$$
re-arranging this: $-2\log_{4}[- \frac{1}{2}(x- 10)]+3$. ^2475b3
- Outside the argument
	- -2 is a vertical stretch and a reflection about x-axis
	- +3 is a shift up
- Inside the argument
	- $-10$ is a shift right
	- $- \frac{1}{2}$ is a [[#^9ec6e7|horizontal stretch]] and a reflection about y-axis

Key points:
- $(1,0)\to (\frac{1}{- \frac{1}{2}},0 \cdot -2) \to (- 2,0)$
- $(4,1)\to (\frac{4}{-\frac{1}{2}}, 1\cdot -2)\to (-8,-2)$

Notes on Horizontal Stretch/Compression:
- **If $k>1$**: This causes a **horizontal compression** by a factor of $\frac{1}{k}$​. You **divide** the x-coordinates by k.
	- You’re **compressing** the inputs. For every unit increase in $x$, the *input* to the function increases by more than one unit because of the multiplication by $k$. This makes the graph get "compressed" horizontally.
- **If $0<k<1$**: This causes a **horizontal stretch** by a factor of $\frac{1}{k}$​. You **divide** the x-coordinates by k.
	- You’re **stretching** the inputs. For every unit increase in $x$, the *input* to the function increases by less than one unit because $kx$ is less than $x$. This makes the graph appear "stretched" horizontally.
The division is done to counteract the multiplication effect inside.

Notice how the line never leaves our domain of $D:\{x<10\}$
![[Pasted image 20240828005502.png]]

This is from Desmos:
![[Pasted image 20240828010136.png]]
- the blue dotted line is the image that we should have originally for $a>1$ (climbing $log$).
- the red dotted line is reflection about the x-axis
- the black line is our function $g(x)$, a reflection about y-axis of the red dotted line
## Introduction to Solving Logarithms and Exponentials

Steps:
1. Look for [[#Solving Exponential Equations with Common Bases|common bases]] when you can.
2. For logs, write equation in exponential form.
3. For exponentials, write in log form.

$$\log_2 (2x+1)=3$$
$2^{3}=2x+1$
$8=2x+1$
$2x=7$
$x=\frac{7}{2}$
We *should* check if plugging $x$ in our argument makes it negative:
$2\cdot \frac{7}{2}+1>0$
$8>0$
We're good.

$$\log_3(x^2 +1)=2$$
$3^{2}=x^{2}+1$
$9=x^{2}+1$
$8=x^{2}$
$x=\pm\sqrt{8}$
$x=\pm2\sqrt{2}$
??? Should we eliminate the $-2\sqrt{2}$ right away? Not here, this is not the *base* (you can't have negative base).
Let's check if any of these 2 answers make our argument negative:
$(2\sqrt{2})^{2}+1>0$
$8+1>0$
$9>0$
and
$(-2\sqrt{2})^{2}+1>0$
$8+1>0$
$9>0$
So, both of our $x$ are completely valid answers.

$$\ln(-2x+1)=8$$
$e^{8}=-2x+1$
Note: $e^8\approx2,980.96$, but let's just simplify this instead:
$e^{8}-1=-2x$
$\frac{e^{8}-1}{-2}=x$
$\frac{1-e^{8}}{2}=x$
Professor Leonard says we should only approximate after getting the simplified form, since plugging $e^8\approx2,980.96$ in the beginning, would make you answer further and further away from the exact solution.
Let's check our domain:
$-2(\frac{1-e^{8}}{2})+1>0$
$-(1-e^{8})+1>0$
$e^{8}-1+1>0$
$e^{8}>0$
That checks... but wait...
So $-2(\frac{1-e^{8}}{2})+1=e^{8}$. We can write this as $\ln e^{8}=8\to e^{8}=e^{8}$, it works! We wouldn't have got this kind of result if we approximated.

$$\ln e^{2x} =8$$
$e^{8}=e^{2x}$
$8=2x$
$x=4$
You can actually cancel this since the base and the base of our argument is the same. 
$\cancel{\ln_{e}e}^{2x}=8$
$2x=8$
This is one of the [[#Properties of Logarithms|properties of logarithms]] that we'll see soon.

$$\log_6 36=5x+4$$
$6^{5x+4}=36$
$6^{5x+4}=6^{2}$
Common bases. We can also use properties of logarithm:
$\cancel{\log_{6}6}^{2}=5x+4$
Now the bases cancel and we get:
$5x+4=2$
$x=- \frac{2}{5}$
### More examples
$$\log_{x}(\frac{1}{8})=3$$
$x^{3}=\frac{1}{8}$
$\sqrt[3]{x^{3}}=\sqrt[3]{\frac{1}{8}}$
$x=\frac{1}{2}$

$$7^{2x+5}=8$$
$\log_{7}8=2x+5$
Don't bring out you calculator just yet. Leave the log as it so that our solution remains an *exact answer* (yes, this is an actual term in math).
$\log_{7}(8)-5=2x$
Put a parentheses over the argument here to avoid confusion.
$\frac{\log_{7}(8)-5}{2}=x$

$$5e^{0.2x}=7$$
Get your exponential isolated.
$e^{0.2x}=\frac{7}{5}$
$\ln (\frac{7}{5})=0.2x$
$\frac{ln(\frac{7}{5})}{0.2}=x$
Get rid of the decimal, multiplying $\frac{5}{5}$ to the left side:
$5\ln(\frac{7}{5})=x$

$$8\cdot 10^{2x-7} =3$$
$10^{2x-7} =\frac{3}{8}$
$\log (\frac{3}{8})=2x-7$
$\log(\frac{3}{8})+7=2x$
$\frac{\log(\frac{3}{8})+7}{2}=x$

$$4e^{x+1}=5$$
$e^{x+1}=\frac{5}{4}$
$\ln(\frac{5}{4})=x+1$
$x=\ln(\frac{5}{4})-1$

## Properties of Logarithms

There are 4 properties of logarithms.

1. Any log with argument 1, you'll get 0. 
$$\log_a 1=0$$
- any bases raised to 0 will equal to 1 ($a^{1}=0$)

$$\log_{a}a=1$$
- any bases raised to 1 will equal to that bases ($a^{1}=a$)

Extend this idea and we have:
$$\log_a a^r=r$$
- Imagine $\log_{a}a^{1}=1$
- Since the base of your argument and in your log is the same, they cancel each other.

Same idea here:$$a^{\log_a M}=M$$
- Rmb that logs and exps are inverse of one another. With the same base, they cancel one another out.
- We can rewrite this as: $\log_{a}M=log_{a}M$ (yep, they're the same thing)

Let's try some examples:
$$\log_2 2^{-13}=$$
Same base, they cancel each other:
$\log_2 2^{-13}=-13$

$$\log 10^{\frac{1}{3}}=$$
Same base (common log):
$\log 10^{\frac{1}{3}}=\frac{1}{3}$

$$\ln e^{-4}=$$
Same base (natural log):
$\ln e^{-4}=-4$

$$2^{\log_2 7}=$$
Exponents and logs are inverse of one another:
$2^{\log_2 7}=7$

$$10^{\log \frac{1}{4}}=$$
Same case here:
$10^{\log \frac{1}{4}}=\frac{1}{4}$

$$e^{ln 8}=$$
Same case here:
$e^{ln 8}=8$

Let's move on to another properties:
Logs mimic exponents rules. Rmb this?
$x^{m}\cdot x^{n}=x^{m+n}$
This property of logs are based on that model (not exactly):
2. If you have a *product* inside your argument, you can separate them with addition.
$$log_a (M\cdot N)=\log_a M+ \log_a N$$
This works both way for logs with the same bases: $\log_a M+ \log_a N=\log_a (M\cdot N)$.
Think about this statement in exponent form:
$a^{\log_a M+ \log_a N}=M\cdot N$
From exponent property of $x^{m}\cdot x^{n}=x^{m+n}$:
$a^{\log_{a}M}\cdot a^{\log_{a}N}=M \cdot N$
From our first property, which states the log and exp cancel each other:
$M\cdot N = M \cdot N$

This one is going to be the inverse of the previous property. Rmb this?
$\frac{x^{m}}{x^{n}}=x^{m-n}$
3. If you have a *fraction* inside your argument, you can separate them with subtraction.
$$log_{a} (\frac{M}{N})=\log_a M- \log_a N$$
This also works both way. Same idea here.
$a^{\log_{a} M- \log_{a} N}=\frac{M}{N}$
$\frac{a^{\log_{a}M}}{a^{\log_{a}N}}=\frac{M}{N}$
$\frac{M}{N}=\frac{M}{N}$

This one is a bit more abstract.
4. Power property
$$\log_a M^r =r\cdot \log_a M$$
Once again this works both ways.
Let's think about this:
$a^{r\cdot \log_{a}M}=M^{r}$
$(a^{r})^{\log_{a}M}=M^{r}$ or $(a^{\log_{a}M})^{r}=M^{r}$
Log and exponent cancel out:
$M^r=M^r$

### Examples

Let's try to simplify some examples:\
$$\log_5 (25x)$$
$\cancel{\log_5 (5}^2)+\log_5 (x)$
$\log_{5}x+2$
This is as simplified as we can go. Notice how much easier has this become to graph (we have a shift up by 2).

$$\ln(\frac{e}{x})$$
$\cancel{\ln(e)}-\ln(x)$
$1-\ln(x)$
$-\ln(x)+1$
- notice the shift up by 1 and a reflection about the x-axis here.

$$\ln(\frac{x}{e^x })$$
$\ln(x)-\cancel{\ln(e}^{x})$
$\ln(x)-x$

## How to Expand Logarithms

How do we use the [[#Properties of Logarithms]] to expand logarithms?
	Why do we want to do it? Well you'll use it in calculus. For a more practical reason, in computer science and data analysis, logarithms are often expanded to simplify computations or to improve numerical stability.

Let's see some examples:
$$ln(x^2\sqrt{1-x})$$
$ln(x^{2})+ln(\sqrt{1-x})$
$ln(x^{2})+ln((1-x)^{\frac{1}{2}})$
$2ln(x) + \frac{1}{2}ln(1-x)$
That's about all that we could expand.

$$log_5(\frac{\sqrt[3]{x^2 +1}}{x^2-1})$$
$log_5[(x^2+1)^{\frac{1}{3}}]-log_5(x^2-1)$
$\frac{1}{3}log_5(x^2+1)-log_5[(x+1)(x-1)]$
$\frac{1}{3}log_5(x^2+1)-[log_5(x-1)+log_5(x+1)]$
$\frac{1}{3}log_5(x^2+1)-log_5(x-1)-log_5(x+1)$

$$\log[\frac{x^3\sqrt{x+1}}{(x-2)^2(x-1)}]$$
$\log[\frac{x^3(x+1)^{\frac{1}{2}}}{(x-2)^2(x-1)}]$
$3\log x+ \frac{1}{2}\log(x+1)-[2\log(x-2)+\log(x-1)]$
$3\log x+ \frac{1}{2}\log(x+1)-2\log(x-2)-\log(x-1)$

$$ln[\frac{5x^2 \sqrt[3]{7-2x}}{4(x+1)^2}]$$
$ln[\frac{5x^2 (7-2x)^\frac{1}{3}}{4(x+1)^2}]$
$ln(5x^{2})+ ln(7-2x)^{\frac{1}{3}}-[ln(4)+ln(x+1)^{2}]$
$ln(5)+2ln(x)+ \frac{1}{3}ln(7-2x)-[ln(4)+2ln(x+1)]$
$ln(5)+2ln(x)+ \frac{1}{3}ln(7-2x)-ln(4)-2ln(x+1)$

$$log[\frac{(x-4)^2 }{x^2-9}]^\frac{2}{3}$$
$log[\frac{(x-4)^2 }{(x+3)(x-3)}]^\frac{2}{3}$
$\frac{2}{3}log[\frac{(x-4)^2 }{(x+3)(x-3)}]$
So do we have to distribute $\frac{2}{3}$ to all of the terms in our expanded log?
Think about it this way:
$log[\frac{(x-4)^ \frac{4}{3} }{(x+3)^{\frac{2}{3}}(x-3)^{\frac{2}{3}}}]$
So the answer is: yes, we have to. Back to here: $\frac{2}{3}log[\frac{(x-4)^2 }{(x+3)(x-3)}]$
$\frac{2}{3}\cdot \frac{2}{3} log(x-4)-[\frac{2}{3}log(x+3)+ \frac{2}{3}log(x-3)]$
$\frac{4}{3}log(x-4)-\frac{2}{3}log(x+3)- \frac{2}{3}log(x-3)$
Or you can (*should*, actually. it's better for you) expand inside the parentheses before distributing. Back to here: $\frac{2}{3}log[\frac{(x-4)^2 }{(x+3)(x-3)}]$
$\frac{2}{3}[2log(x-4)]-log(x+3)-log(x-3)$
$\frac{4}{3}log(x-4)-\frac{2}{3}log(x+3)- \frac{2}{3}log(x-3)$

## How to Combine Logarithms

$$\frac{1}{2}\log_3 x- 3 \log_3 x$$
$\log_{3}x^{\frac{1}{2}}-\log_{3}x^{3}$
$\log_{3}(\frac{x^{\frac{1}{2}}}{x^{3}})$
$\log_{3}(x^{\frac{1}{2}-3})$
$\log_{3}(x^{- \frac{5}{2}})$
$\log_3(\frac{1}{x^{\frac{5}{2}}})$
$\log_3(\frac{1}{\sqrt{x^5}})$
$\log_3(\frac{1}{x^{2}\sqrt{x}})$
$\log_3(\frac{1}{x^{2}\sqrt{x}}\cdot \frac{\sqrt{x}}{\sqrt{x}})$
$\log_3(\frac{\sqrt{x}}{x^{2}})$

$$\log_4(x^2-1)-5\log{4}(x+1)$$
$\log_{4}[(x-1)(x+1)]-5\log_{4}(x+1)$
$\log_{4}[(x-1)(x+1)]-\log_{4}(x+1)^5$
$\log_{4}(\frac{(x-1)(x+1)}{(x+1)^{5}})$
$\log_4(\frac{x-1}{(x+1)^{4}})$

$$\ln(\frac{x}{x-1})+\ln(\frac{x+1}{x})-\ln(x^2 -1)$$
$ln(\frac{\frac{x}{x-1}\cdot \frac{x+1}{x}}{x^{2}-1})$
$\ln(\frac{\frac{x+1}{x-1}}{(x+1)(x-1)})$
$\ln(\frac{\frac{x+1}{x-1}}{(x+1)(x-1)})$
$\ln(\frac{x+1}{x-1}\cdot \frac{1}{(x+1)(x-1)})$
$\ln[\frac{1}{(x-1)^{2}}]$

$$21\log_3\sqrt[3]{x}+\log_{3}9+2\log_3 x-\log_3 9$$
$7\log_{3}\sqrt[3]{x}^{3}+\log_{3}3^{3}+2\log_{3}x-\log_{3}3^{3}$
$7\log_{3}x+3+2\log_{3}x-3$
$7\log_{3}x+2\log_{3}x$
$9\log_{3}x$
$\log_{3}x^{9}$

$$2\log (x+1)- \frac{1}{4}\log (x-1) + \frac{3}{8}\log (2x+3)- \frac{1}{5} \log x - 4 \log 2 + \log 12$$
$\log (x+1)^{2}+ \log (2x+3)^{\frac{3}{8}}+ \log 12- \log (x-1)^{\frac{1}{4}} -  \log x^{\frac{1}{5}} - \log 2^{4}$
Since they're all log with the same base and separated by addition and subtraction, we can create a log with one huge fraction as argument.
$\log[\frac{(x+1)^{2} \cdot (2x+3)^{\frac{3}{8}} \cdot 12}{(x-1)^{\frac{1}{4}}\cdot x^{\frac{1}{5}} \cdot 2^{4}}]$
$\log[\frac{12(x+1)^{2}\sqrt[8]{(2x+3)^{3}}}{16\sqrt[4]{x-1}\sqrt[5]{x}}]$
$\log[\frac{3(x+1)^{2}\sqrt[8]{(2x+3)^{3}}}{4\sqrt[4]{x-1}\sqrt[5]{x}}]$
## How to Change the Base of Logarithm

$$\log_a b= \frac{\log_c b}{\log_c a}$$
- notice how your argument goes to the numerator and your base goes to the denominator
- from that $c$ can be anything (usually base 10 (common log) or base $e$ (natural log))
This works both way. Imagine this:
Say $\log_{a}b=x\implies a^{x}=b$
Put a log with base $c$ on both sides:
$\log_{c}(a^{x})=\log_{c}(b)$
$x\log_{c}(a)=\log_{c}(b)$
Solve for $x$:
$x=\frac{\log_{c}(b)}{\log_{c}(a)}$
Rmb that $\log_{a}b=x$
$\log_a b= \frac{\log_c b}{\log_c a}$
Notice how this work for any base $c$, as long as it is positive and not equal to 1.
	The change of base formula works because logarithms are essentially exponents. When we take the logarithm base $c$ of both sides, we're essentially **measuring the exponents required to reach a particular number** (in this case, $b$) from a specific base ($a$) using a different base ($c$).

Let's see some example:
$$\log_5 18$$
Let's make it base 10:
$\log_5 18=\frac{\log 18}{\log 5}\approx\frac{1.2552725051033060698037947012347}{0.69897000433601880478626110527551}\approx1.79$
Let's try with base $e$:
$\log_5 18=\frac{\ln 18}{\ln 5}\approx\frac{2.8903717578961646922077225953032}{1.6094379124341003746007593332262}\approx1.79$
Notice how they are the same, just different looks.

$$\log_{\sqrt{5}}7$$
$\log_{\sqrt{5}}7=\frac{\log 7}{\log \sqrt{5}}$

$$\log_{\pi}e$$
$\log_{\pi}e=\frac{\log e}{\log \pi}$
Not so interesting huh? Try it in base $e$.
$\log_{\pi}e=\frac{\ln e}{\ln \pi}=\frac{1}{\ln\pi}$

## Solving Logarithms with Common Bases

$$\text{If } \log_a x=\log_a y \text{ , then } x=y$$
Like in [[#Solving Exponential Equations with Common Bases|exponents]], this is only possible when we have logs with common bases. Usually, you would use exponentials to solve log equations.

For example:
$$\log_4 (x+2)=\log_4 8$$
Since we have logs with common bases:
$x+2=8$
$x=6$
Rmb how [[#Notes on Domain of Logarithms|inside of the argument for our log *cannot* be negative]]? You should check that.

$$3\log_2 x=-\log_2 27$$
$\log_{2}x^{3}=\log_{2}27^{-1}$
$x^{3}=27^{-1}$
$x^{3}=\frac{1}{27}$
$\sqrt[3]{x^{3}}=\sqrt[3]{\frac{1}{27}}$
$x=\frac{1}{3}$

$$\log_a (x-1)-\log_a (x+6) = \log_a (x-2)- \log_a (x+3)$$
$\log_a(\frac{x-1}{x+6})=\log_a(\frac{x-2}{x+3})$
$\frac{x-1}{x+6}=\frac{x-2}{x+3}$
$(x-1)(x+3)=(x-2)(x+6)$
$x^{2}+2x-3=x^{2}+4x-12$
$2x=9$
$x=\frac{9}{2}$
This value $x$ doesn't really make any of our arguments negative so we're good.

$$\log_3 x-2\log_3 5=\log_3 (x+1)- 2\log_3 10$$
$\log_{3}x-\log_{3}5^{2}=\log_{3}(x+1)-\log_{3}10^{2}$
$\log_{3}(\frac{x}{25})=\log_{3}(\frac{x+1}{100})$
$\frac{x}{25}=\frac{x+1}{100}$
$100x=25x+25$
$75x=25$
$x=\frac{1}{3}$
Can we just have everything on one side to get a big log and a constant (0 in this case) on another? Sure, let's try:
$\log_3 x-2\log_3 5-\log_3 (x+1)+ 2\log_3 10=0$
$\log_{3}x-\log_{3}5^{2}-\log_{3}(x+1)+\log_{3}10^{2}=0$
$\log_{3}x+\log_{3}10^{2}-\log_{3}5^{2}-\log_{3}(x+1)=0$
$\log_{3}(\frac{100x}{25(x+1)})=0$
$\log_{3}(\frac{4x}{x+1})=0$
What can we do with this? This is the basis of our next session: [[#Solving Logarithmic Equations with Exponentials]]. Try write this expression in exponential form:
$3^{0}=\frac{4x}{x+1}$
Notice how any $a^{0}=1$:
$1=\frac{4x}{x+1}$
$x+1=4x$
$\frac{1}{3}=x$
This is how we deal with logarithmic equations in general, with exponentials.


$$3(\log_7 x-\log_7 2)=2\log_7 4$$
$3\log_7 x-3\log_7 2=2\log_7 4$
$\log_{7} x^{3}-\log_{7} 2^{3}=\log_{7} 4^{2}$
$\log_{7}(\frac{x^{3}}{2^{3}})=\log_{7}4^{2}$
$\frac{x^{3}}{2^{3}}=4^{2}$
$x^{3}=16\cdot 8$
$x^{3}=128$
$\sqrt[3]{x^{3}}=\sqrt[3]{128}$
$x=4\sqrt[3]{2}$

## Solving Logarithmic Equations with Exponentials

Steps:
1. Get all logs on one side and constant on the other
2. Combine the logs
3. Write in exponential form

Say:$$\log (x+6)=1$$
Step 1 & 2 is already done for us, so start by writing in exponential form:
$10^{1}=x+6$
$x=4$
Checking our answer inside the argument and we found no Domain issue.

### More examples
$$3\log_2 (x-1)+\log_2 4=5$$
Step 1 is already done for us. Let's combine it:
$\log_{2}(x-1)^{3}+\log_{2}4=5$
We can actually simplify $\log_{2}4=2$ here and deduct from 5 but we like it the hard way.
$\log_{2}[(x-1)^{3}\cdot 4]=5$
$2^{5}=(x-1)^{3}\cdot4$
$\frac{32}{4}=(x-1)^{3}$
$8=(x-1)^{3}$
$\sqrt[3]{8}=\sqrt[3]{(x-1)^{3}}$
$2=x-1$
$x=3$
Notice how we held of distribution until step 3 to reduce the amount of work.
$x=3$ does not present any domain issues.

$$\log(2x+1)=1+\log(x-2)$$
$\log(2x+1)-\log(x-2)=1$
$\log(\frac{2x+1}{x-2})=1$
$10^{1}=\frac{2x+1}{x-2}$
$10(x-2)=2x+1$
$10x-20=2x+1$
$8x=21$
$x=\frac{21}{8}$
No domain issue with $x=\frac{21}{8}$. A close one is $x-2>0$ but $\frac{21}{8}>2$ anyway.

$$\log_6 (x+4)=1-\log_6 (x+3)$$
$\log_6 (x+4)+\log_6 (x+3)=1$
$\log_6[(x+4)(x+3)]=1$
$6^{1}=(x+4)(x+3)$
$6=x^{2}+7x+12$
$0=x^{2}+7x+6$
$0=(x+6)(x+1)$
So $x=-6$ and $x=-1$. $-1$ is likely fine, but $-6$ is probably going to present some domain issues, let's plug it in our original arguments to check:
$-6+4>0$, this is not true, thus *is* a domain issue.
$-6+3>0$, this is not true, thus *is* also a domain issue.
So $x$ cannot be $-6$. $x=-1$ is fine, thus it is our only working solution.

$$\log_4 (x^2-9)-\log_4(x+3)=3$$
$\log_{4}(\frac{x^{2}-9}{x+3})=3$
It helps to factor it now. This is not distribution which is sometimes unnecessary extra work. Factoring it now actually simplify the whole process as you'll see. 
$\log_{4}(\frac{(x+3)(x-3)}{(x+3)})=3$
$\log_{4}(x-3)=3$
$4^{3}=x-3$
$64=x-3$
$x=67$

$$\ln(x+1)-\ln(x)=2$$
$\ln(\frac{x+1}{x})=2$
$e^{2}=\frac{x+1}{x}$
 $xe^{2}=x+1$
 $(e^{2}-1)x=1$
 $x=\frac{1}{e^{2}-1}$

$$\log_9 (7x-5)=\log_3 (x+1)$$
$\frac{\log_{3}(7x-5)}{\log_{3}(9)}=\log_{3}(x+1)$
$\frac{\log_{3}(7x-5)}{2}=\log_{3}(x+1)$
 $\log_3(7x-5)=2\log_{3}(x+1)$
$\log_3(7x-5)-\log_{3}(x+1)^{2}=0$
$\log_{3}(\frac{7x-5}{(x+1)^{2}})=0$
$3^{0}=\frac{7x-5}{(x+1)^{2}}$
$(x+1)^{2}=7x-5$
$x^{2}+2x+1=7x-5$
$x^{2}-5x+6=0$
$(x-3)(x-2)=0$
So $x=3, x=2$. Checking our domain, these 2 solution cannot make our argument 0 or negative. We're good.

$$\log_{16}  x+\log_4 x+\log_2 x=7$$
$\frac{\log_{2}(x)}{\log_{2}16}+\frac{\log_{2}(x)}{\log_{2}4}+\log_{2}x=7$
$\frac{\log_{2}(x)}{4}+\frac{\log_{2}(x)}{2}+\log_{2}x=7$
$4\cdot(\frac{\log_{2}(x)}{4}+\frac{\log_{2}(x)}{2}+\log_{2}x)=4\cdot7$
$\log_{2}(x)+2\log_{2}(x)+4\log_{2}(x)=28$
$\log_{2}(x)+\log_{2}(x)^{2}+4\log_{2}(x)^{4}=28$
$\log_{2}(x\cdot x^{2} \cdot x^{4})=28$
$\log_{2}(x^{7})=28$
$2^{28}=x^{7}$
$\sqrt[7]{(2^{4})^{7}}=\sqrt[7]{x^{7}}$
$2^{4}=x$
$x=16$

$$2(\log_4 x)^2+3\log_8 x=\log_2 16$$
$2(\frac{\log_{2}x}{\log_{2}4})^{2}+ \frac{\log_{2}x^{3}}{\log_{2}8}- \log_{2}(16)=0$
This seems harder than it should be, let's try again:
$2\cdot(\frac{\log_{2}x}{\log_{2}4})^{2}+ 3\cdot\frac{\log_{2}x}{\log_{2}8}- \log_{2}(16)=0$
$2\cdot(\frac{(\log_{2}x)^{2}}{2^{2}})+ 3\cdot\frac{\log_{2}x}{3}- \log_{2}(16)=0$
$\cancel{2}\cdot(\frac{(\log_{2}x)^{2}}{\cancel{4}})+ \cancel{3}\cdot\frac{\log_{2}x}{\cancel{3}}- \log_{2}(16)=0$
$(\frac{(\log_{2}x)^{2}}{2})+ \log_{2}x- \log_{2}(16)=0$
Notice how, in the first term, we have the entire log squared instead of just the argument ($(\log_{2}x)^{2}$ instead of $\log_{2}x^{2}$). So we *cannot* bring the power 2 out front ($2\cdot\log_{2}x$), we *cannot* bring out the denominator ($\frac{1}{2}\cdot(\log_{2}x)^{2}$). Those will break the order of operations. We can, however, multiply the whole thing by 2 to get rid of the denominator of the first term:
$2\cdot((\frac{(\log_{2}x)^{2}}{2})+ \log_{2}x- \log_{2}(16))=0$
Let's change simplify $\log_{2}16$ first:
$2\cdot((\frac{(\log_{2}x)^{2}}{2})+ \log_{2}x- 4)=0$
$(\log_{2}x)^{2}+2\log_{2}x-8=0$
We can substitute $\log_{2}x$ with $a$:
$a^{2}+2a-8=0$
$(a+4)(a-2)=0$
By zero product property, $a=-4,a=2$.  Since $a=\log_{2}x$:
$-4=\log_{2}x$
$2^{-4}=x$
$\frac{1}{16}=x$
We don't seem to have any domain issue with this solution.
$2=\log_{2}x$
$2^{2}=x$
$x=4$
No domain issue for this one either.
So, our solution is $x=4, x=\frac{1}{16}$


$$\log_2 x=3-\log_6 x$$
$\log_{2}x+\log_{6}x=3$
$\log_{2}x+\frac{\log_{2}x}{\log_{2}6}=3$
Notice how changing the base doesn't work nearly as nice here. I've been advised to pick natural base or common base for this kind of case. Let's try natural base:
$\frac{\ln x}{\ln 2}+\frac{\ln x}{\ln 6}=3$
Firstly, let's get a common denominator:
$(\frac{\ln x}{\ln 2}\cdot\frac{ln 6}{ln 6})+(\frac{\ln x}{\ln 6}\cdot\frac{\ln 2}{\ln 2})=3$
$\frac{\ln x \cdot \ln 6}{\ln 2 \cdot \ln 6}+\frac{\ln x \cdot \ln 2}{\ln 2 \cdot \ln 6}=3$
$\frac{\ln x\cdot \ln 6+\ln x\cdot \ln 2}{\ln 2 \cdot \ln 6}=3$
Notice the $\ln x$ as a factor in the numerator here:
$\frac{\ln x(\ln 6+\ln 2)}{\ln 2 \cdot \ln 6}=3$
$\frac{\ln x(\ln (6\cdot 2))}{\ln 2 \cdot \ln 6}=3$
$\frac{\ln x\cdot\ln 12}{\ln 2 \cdot \ln 6}=3$
$\ln x\cdot\ln 12=3(\ln 2 \cdot \ln 6)$
$\ln x=\frac{3(\ln 2 \cdot \ln 6)}{{\ln 12}}$
$\ln x=\frac{3\ln2\ln6}{\ln12}$
We can't really simplify any further. So, in exponential form:
$e^{\frac{3\ln2\ln6}{\ln12}}=x$
That solves for $x$. As cryptic as $\frac{3\ln2\ln6}{\ln12}$ looks, it is a constant. We can plug this in a calculator and get a number out of it.

## Solving Exponential Equations with Logarithms

There are 4 ways to do it, but in general, we:
1. isolate exponential
2. use logs

For example:
$$8\cdot3^{x+1}=5$$
**First way:**
Isolate your exponents on one side and constant on the other:
$3^{(x+1)}=\frac{5}{8}$
$\log_{3}(\frac{5}{8})=x+1$
$\log_{3}(\frac{5}{8})-1=x$
This is as simplified as we can go.  Just put $\log_{3}(\frac{5}{8})-1$ and you'll get an exact solution. If your calculator don't have log base 3 then we can convert this to common base:
$\frac{\log \frac{5}{8}}{\log 3}-1=x$

**Second way**
Isolate your exponents on one side and constant on the other:
$3^{(x+1)}=\frac{5}{8}$
We can convert this to base 10 right away by putting a log over both side of the equation:
$\log 3^{(x+1)}=\log (\frac{5}{8})$
$(x+1)\log 3=\log (\frac{5}{8})$
The parentheses over $x+1$ here is very important as you can get confused with $x+1\log 3$ and this will mess up the whole process.
$x+1=\frac{\log (\frac{5}{8})}{\log (3)}$
$x=\frac{\log (\frac{5}{8})}{\log (3)}-1$
Same solution as above. Let's come back here for a moment:
$(x+1)\log 3=\log (\frac{5}{8})$
What if we distribute:
$x\cdot\log 3+\log 3=\log(\frac{5}{8})$
$x\cdot\log 3=\log(\frac{5}{8})-\log 3$
$x=\frac{\log(\frac{5}{8})-\log 3}{\log 3}$
$x=\frac{\log(\frac{5}{8})}{\log 3}-\frac{\log 3}{\log 3}$
$x=\frac{\log(\frac{5}{8})}{\log 3}-1$
Same thing here.

**Third way**
Isolate your exponents on one side and constant on the other:
$3^{(x+1)}=\frac{5}{8}$
This method is pretty much the same as the previous method, except that we use *natural log*. This is very common for people. You know, one less letter to write:
$\ln 3^{(x+1)}=\ln (\frac{5}{8})$
$(x+1)\ln 3=\ln (\frac{5}{8})$
Once again, we have a choice to distribute or just divide here.
$x+1=\frac{\ln (\frac{5}{8})}{\ln (3)}$
$x=\frac{\ln (\frac{5}{8})}{\ln (3)}-1$

**Fourth method**
Same thing here:
$3^{(x+1)}=\frac{5}{8}$
We can put log base 3 on both side. Why log base 3? Let's see:
$\log_{3}3^{(x+1)}=\log_{3}(\frac{5}{8})$
Notice how we can cancel the log on the left term:
$x+1=\log_{3}(\frac{5}{8})$
$x=\log_{3}(\frac{5}{8})-1$
## More examples
$$2^{x+1}=5^{1-2x}$$
We can put a natural log or common log on both sides, let's try natural log:
$\ln2^{x+1}=\ln5^{1-2x}$
$(x+1)\ln2=(1-2x)\ln5$
I think we have to distribute here since we have $x$ on both sides (rmb, we want to solve for $x$):
$(x\cdot\ln2)+\ln2=\ln5-(2x\cdot\ln5)$
$x\ln2+2x\ln5=\ln5-\ln2$
$x(\ln2+2\ln5)=\ln5-\ln2$
$x=\frac{\ln5-\ln2}{\ln2+2\ln5}$
$x=\frac{\ln5-\ln2}{\ln2+\ln25}$
This is as simple as we could go.

$$e^{x+3}=\pi^x  $$
An obvious choice here is to put a natural log on both side:
$\ln(e)^{x+3}=\ln(\pi)^x$
$x+3=x\cdot\ln\pi$
$\frac{x+3}{x}=\ln\pi$
$\frac{x}{x}+ \frac{3}{x}=\ln\pi$
$1+ \frac{3}{x}=\ln\pi$
$\frac{3}{x}=\ln\pi-1$
$3=x(\ln\pi-1)$
$x=\frac{3}{\ln\pi-1}$
Notice that I didn't group together the natural logs first, that's actually a mistake but we still got the correct solution. Let's try it the right way:
From: $x+3=x\cdot\ln\pi$
$x-x\ln\pi=-3$
$x(1-\ln\pi)=-3$
$x=\frac{-3}{1-\ln\pi}$
Different answer? Not really we can further simplify this, taking out the negative:
$x=\frac{-1\cdot 3}{-1\cdot(\ln\pi-1)}$
$x=\frac{3}{\ln\pi-1}$
This really shows how, with logarithms and exponentials, one person's solution can look *very* different from another due to the manipulation of properties. But just because they just look different doesn't mean that they are incorrect.

Let's think about the possibility of domain issues arising from putting log on both sides for a moment. 
	Rmb, that we are simply using log to solve exponential equations, of which has the range of $(0,\infty)$. This means that no matter what value $x$ takes, the output of an exponential function is always a positive number.
	Since logs are inverse function of exponentials, their *Domain* are exactly the *Range of exponentials*. This is why applying logarithms to both sides of an equation involving exponentials, we don’t introduce domain issues because both sides of the equation are positive. This matches the domain requirement of logarithmic functions, which is $(0, \infty)$.

$$2^{2x}+2^{x+2}-12=0$$
Putting logs on both side doesn't really help our case here $\log(2^{2x}+2^{x+2}-12)=0$. When we meet this kind of situation, think *substitution*. Think about how we *want* our exponents to look like (in this case $2^{x}$):
$(2^{x})^{2}+(2^{2}\cdot2^{x})-12=0$
$(2^{x})^{2}+4\cdot2^{x}-12=0$
We can now substitute $u=2^{x}$:
$u^{2}+4u-12=0$
$(u+6)(u-2)=0$
So $u=-6,u=2$.
Where $u=-6$:
$2^{x}=-6$
$\log_{2}(-6)=x$
$x=\frac{\ln(-6)}{\ln(2)}$
Notice how the argument we have -6? This is not a valid solution. Actually for any $x$, $2^{x}$ *cannot* output a negative number since the range of exponential is $(0,\infty)$. So, this range issue become the domain issue for our log.

Where $u=2$:
$2^{x}=2$
$\log_{2}(2)=x$
$x=1$
This is our only valid solution.

$$2\cdot49^x +11\cdot7^x +5=0$$
$2\cdot7^{2x}+11\cdot7^{x}+5=0$
$2\cdot(7^{x})^{2}+11\cdot7^{x}+5=0$
Substitute $7^{x}=u$:
$2u^{2}+11u+5=0$
$(u+5)(2u+1)=0$
So $u=-5, u= \frac{1}{2}$.
Rmb, $7^{x}$ cannot output a 0 or a negative number, so $u=-5$ is invalid.
Where $u=\frac{1}{2}$:
$\frac{1}{2}=7^{x}$
$\log_{7}(\frac{1}{2})=x$
For those of you without a proper calculator.
$\frac{\ln(\frac{1}{2})}{\ln7}=x$

$$3^x -14\cdot3^{-x}=5$$
$3^{x}-14\cdot(3^{x})^{-1}=5$
Substitute $u=3^{x}$:
$u-14(\frac{1}{u})=5$
$\frac{u^{2}}{u}- \frac{14}{u}=5$
$\frac{u^{2}-14}{u}=5$
$u^{2}-14=5u$
$u^{2}-5u-14=0$
$(u-7)(u+2)=0$
$u=-2$ is invalid due to domain issues.
Where $u=7$:
$3^{x}=7$
$\log_{3}(7)=x$

## Review of Compound Interest

This is one of the example how exponentials and logarithms can be applied in real life (finance).

So, compound interest (finite compounding):
$$A=P(1+ \frac{r}{n})^{n\cdot t}$$
or for continuously (continuous compounding):
$$A=Pe^{r\cdot t}$$
whereas:
- $n$ is number of compounds in 1 year.
- $A$ is the amount (future value). 
- $P$ is the principle amount (present value).
- $r$ is the rate of interest (always written as decimals).
- $t$ is number of years.

Note on $r$:
The $r$ used in above equations are *nominal interest rate* which is the stated interest rate on an investment or loan, not accounting for the effect of compounding within the year. 
	For example, if a bank offers an annual interest rate of 6% compounded quarterly, 6% is the nominal rate. This rate does not reflect the true amount of interest that will be earned or paid because it doesn't account for the compounding that occurs within the year.
[[#Effective Rate aka. Annual Yield|Effective interest rate]], which accounts for compounding within the year, will be discussed later.

The variable $n$ represents how often the interest is compounded in a year.

| Frequency   | n   |
| ----------- | --- |
| Annual      | 1   |
| Semi-Annual | 2   |
| Quarterly   | 4   |
| Monthly     | 12  |
| Weekly      | 52  |
| Daily       | 365 |
Notice how in $A=P(1+ \frac{r}{n})^{n\cdot t}$, as n increases, $\frac{r}{n}$ becomes smaller, but the exponent $n⋅t$ grows. This results in more frequent application of a smaller interest rate, which leads to compounding

Notice how $n$ just completely disappeared in the continuous compound formula: $A=Pe^{r\cdot t}$. Why? This will be explained in Calculus, but for now, imagine $(1+ \frac{1}{n})^{n}$  as $n\to\infty$. No idea? Me too! But as $n\to\infty$, $(1+ \frac{1}{n})^{n}$ this ends up being $e$. That's crazy.

For example:
$3,000 invested at 9.25% compounded monthly for 2 and a half years. What is the future value of this investment?
$A=3000\cdot(1+ \frac{0.0925}{12})^{12\cdot2.5}$
Notice how $n\cdot t$ just represent the amount of time you get to compound within that period, which is $30$ in this case.
$A\approx3,777.17$
So, after 2 and a half years, your investment will become $3,777.17.

Now what if this is compounded continuously instead?
$A=3000e^{0.0925\cdot2.5}$
$A\approx3780.52$
This is what you get if interest are compounded every infinitesimal seconds, minutes, hours, days, and so on... In general, continuous compounding will yield a higher return than others.
### More examples
How much should be invested at 8.5% compounded daily to earn $800$ in $3 \frac{1}{4}$ years?
$800=P(1+ \frac{0.085}{365})^{365\cdot3.25}$
Solve for $P$:
$P\approx606.92$
So you should invest roughly $606.92 to earn $800$ in $3 \frac{1}{4}$ years.

If instead of daily, we compound continuously:
$A=Pe^{r\cdot t}$
$800=Pe^{0.085\cdot3.25}$
$P\approx606.90$
Notice that this is slightly lessor than if it was compounded daily. Rmb, that this is the principal amount, *not* the interest. We need a lessor amount to achieve $800 in $3 \frac{1}{4}$ years because we compounded quicker.

How long does it take to double an investment at 4.5% compounded quarterly?
$A=P(1+ \frac{r}{n})^{n\cdot t}$
Now we don't really care what $P$ or $A$ is, just the amount of time it takes ($t$) to double our investment, so:
$2=1(1+ \frac{0.045}{4})^{4\cdot t}$
$2=1.01125^{4\cdot t}$
In log terms:
$\log_{1.01125}2=4t$
$\frac{\log_{1.01125}2}{4}=t$
For those without a proper calculator:
$\frac{\frac{\ln 2}{\ln 1.01125}}{4}=t$
$\frac{1}{4}\cdot(\frac{\ln 2}{\ln 1.01125})=t$
$t=\frac{\ln 2}{4\ln 1.01125}\approx15.49$
Roughly, it will take 15.49 years.

What if this was compounded continuously instead:
$A=Pe^{r\cdot t}$
$2=1e^{0.045\cdot t}$
Put a natural log on both sides:
$\ln 2=\ln e^{0.045\cdot t}$
$\ln2=0.045t$
$t=\frac{\ln2}{0.045}$
$t\approx15.40$
Roughly, it will take 15.4 years. This take lessor time because we compounded quicker.
### Effective Rate aka. Annual Yield
Effective Rate aka. Annual Yield considers the compounding effect and provides the actual rate that would yield the same amount of interest as the nominal rate when compounded according to the frequency.
	The more frequent the compounding, the higher the effective interest rate compared to the nominal rate.

Table below show a comparison of interest earned over 5 years with both nominal and effective rates for a $100 investment at 12% interest.

| Year | Nominal Rate | Nominal Amount After Year | Nominal Interest Earned | Effective Rate | Effective Amount After Year | Effective Interest Earned |
|------|--------------|---------------------------|-------------------------|----------------|-----------------------------|---------------------------|
| 1    | 12.00%       | $112.00                   | $12.00                  | 12.68%         | $112.68                     | $12.68                    |
| 2    | 12.00%       | $125.44                   | $25.44                  | 12.68%         | $126.97                     | $26.97                    |
| 3    | 12.00%       | $140.49                   | $40.49                  | 12.68%         | $143.08                     | $43.08                    |
| 4    | 12.00%       | $157.35                   | $57.35                  | 12.68%         | $161.22                     | $61.22                    |
| 5    | 12.00%       | $176.23                   | $76.23                  | 12.68%         | $181.67                     | $81.67                    |
Notice that the difference between nominal and effective rates arises from the **compounding** frequency. The nominal rate of 12% simply states the annual rate without compounding, while the effective rate (12.68%) accounts for compounding monthly, which results in slightly more interest.

Here's the formula for effective rate:
$$r_e=(1+ \frac{r}{n})^n -1$$
- Notice how there is no $P$ here. Consider $P=1$, our concerns are solely on the rate here. Also the $-1$ is to subtract the $P=1$ there to get only the interest earned (not the whole amount).
- Notice that there is no $t$ here either. We do not care what happens in year 2, just how much we effectively earned in a year with a certain compounding frequency $n$.
For continuous effective rate:$$r_e=e^r -1$$
Notice how both of these are just stripped-down versions of our formula for [[#Review of Compound Interest|compound interest]].

For example:
Find effective rate for 9.75% compounded monthly.
$r_{e}=(1+ \frac{r}{n})^{n}-1$
$r_{e}=(1+ \frac{0.0975}{12})^{12}-1$
$r_{e}\approx1.102-1$
$r_{e}\approx0.102$
$r_{e}\approx$ 10.2%
Notice how this is slightly higher than 9.75% nominal rate we're given. We can write this with our finite compounding formula, just to see the resemblance:
$A=P(1+ \frac{r}{n})^{n\cdot t}$
Set $P=1$ and $t=1$:
$A=1\cdot(1+ \frac{0.0975}{12})^{12\cdot 1}$
- Notice how $P$ and $t$ here doesn't really have to be written
$A=(1+ \frac{0.0975}{12})^{12}$
Same thing. If we introduce the $-1$ to subtract the principal amount, this become *effectively* the effective rate formula (pun intended).

What if it was compounded continuously:
$r_{e}=e^{r}-1$
$r_{e}=e^{0.0975}-1$
$r_{e}\approx0.1024$
This is 10.24%. Once again, slight higher than its finite counter part.
## Exponential Growth and Decay

aka. *Natural* Growth and Decay. This is how we use exponential equations to model population growth and decline, and many more science-y stuff. 
$$A(t)=A_0e^{k\cdot t}$$
- $A_{0}$ = Initial Amount
- $t$ = A time period
- $A(t)$ = Amount after "t"
- $k$ is the rate
	- $k>0$ means growth e.g. with base 2, and $k$ is positive: $2, 4, 8,  ...$
	- $k<0$ means decay e.g. with base 2, and $k$ is negative: $\frac{1}{2},\frac{1}{4},\frac{1}{8},...$

Notice how similar this is to the formula in [[#Review of Compound Interest]].

For example:
$C(t)=100e^{0.045\cdot t}$
We're given a model of bacteria growth, with a starting population at 100 and the rate of 4.5% *per hour*. Notice that $k>0$, indicating growth.

What is the amount after 5 days?
Notice the unit of time given in the question is hours, not days. So convert that first: $24\cdot5=120$
$C(5)=100e^{0.045\cdot 120}$
$C(5)\approx22,140.64$ Units

How long to reach 140?
$140=100e^{0.045\cdot t}$
$1.4=e^{0.045\cdot t}$
$\ln 1.4= \ln e^{0.045\cdot t}$
$\ln 1.4 = 0.045\cdot t$
$t=\frac{\ln 1.4}{0.045}$
$t\approx7.48$ Hours

How long to double?
$200=100e^{0.045\cdot t}$
$2=e^{0.045\cdot t}$
$\ln 2= \ln e^{0.045\cdot t}$
$t=\frac{\ln 2}{0.045}$
$t\approx 15.40$ Hours

Find a formula for a population of bacteria that doubles every 3 hours:
$$A(t)=A_0 e^{k\cdot t}$$
Let's plug some numbers in:
$2=1\cdot e^{k\cdot 3}$
$2=e^{3k}$
Now let's solve for k:
$\ln 2= \ln e^{3k}$
$\ln2 =3k$
$k=\frac{\ln2}{3}$
$k\approx0.23$ or 23%

### More examples
Half-life of radium is 1690 years. If 20g are present now. How much will be there in 50 years?
This is supposed to be some kind of an exponential decay function. Think $k<0$.
$A(t)=A_{0}e^{k\cdot t}$
We should start with solving for $k$.
Since half-life refers to the halving after certain amount of time, if we started with 1g, we will be left with $\frac{1}{2}$ after 1690 years.
$\frac{1}{2}=1\cdot e^{k\cdot 1690}$
$\frac{1}{2}=e^{k\cdot 1690}$
$ln \frac{1}{2}=1690k$
$k\approx-0.00041$
So: $A(t)=20e^{-0.00041t}$
$A(50)=20e^{-0.00041\cdot50}$
$A(50)\approx19.59g$

C-14 has a half-life of 5730 years. If a dead tree has 30% of the C-14 it originally did. When did the tree died?
$A(t)=A_{0}e^{k\cdot t}$
Once again, it seems like an exponential decay function. Think $k<0$.
Let's think about the $k$ for C-14 first:
$A(t)=A_{0}e^{k\cdot t}$
$\frac{1}{2}=e^{5730k}$
$\ln(\frac{1}{2})=5730k$
$k\approx-0.000121$
So to solve for $t$ for the tree tragic death:
$A(t)=A_{0}e^{k\cdot t}$
$0.3=1\cdot e^{-0.000121\cdot t}$
$\ln 0.3=-0.000121t$
$t\approx9950.19$ years.
The tree died around 9,950 years ago.  The rounding on $k$ really did a number on our final solution, but you know, it's not that bad.

Next topic relates to Newton's law of cooling, which says how long it is going to take if something of a different temperature ambience will reach a certain temperature:
$$u(t)=T+(u_0 -T)e^{k\cdot t}$$
- $T$ = ambient temperature
- $u_0$ = initial temperature
- $u(t)$ = temperature after "t"

Say,
A turkey comes out of the oven at $100^{\circ}C$ and is $80^{\circ}C$ in 5 minutes. When will it be $50^{\circ}C$ so that I won't burn my fingers when I cut it? I keep my house at $30^{\circ}C$.
First, let's solve for $k$:
$80=30+(100-30)e^{k \cdot 5}$
$80=30+70e^{5k}$
$50=70e^{5k}$
$\frac{5}{7}=e^{5k}$
$\ln(\frac{5}{7})=5k$
$k\approx-0.0673$
Now we can solve for $t$ for how long it will take to reach $50^{\circ}C$.
$50=30+70e^{-0.0673t}$
$\frac{2}{7}=e^{-0.0673t}$
$\ln(\frac{2}{7})=-0.0673t$
$t\approx18.61$ mins.
Notice that this is much longer than the $100^{\circ}C$ to $80^{\circ}C$ within only 5 minutes. However, this make sense if we understand that this is exponential decay, meaning that the turkey gets colder slower and slower as time passes.

Theoretically, the turkey will never reach $30^{\circ}C$ (although, in reality, they will). Notice the +30 in $u(t)=30+70e^{kt}$, this is a *vertical shift up*. This means that we'll have a horizontal asymptote at $y=30$.
## Introduction to Sequences

A *sequence* is a list of numbers given by a formula and determined by the index of each term.

For example:
$$a_n=n^2 +1$$
Whereas $n$ is the index, and indexes are *natural numbers* e.g. 1,2,3,... You should be told where to start, in this case we start with $n=1$ (0 is also a natural number, we were just told to start at 1 here).
- $a_{1}=(1)^{2}+1=2$
- $a_{2}=(2)^{2}+1=5$
- $a_{3}=(3)^{2}+1=10$
- $a_{4}=(4)^{2}+1=17$
- $a_{5}=(5)^{2}+1=26$
- and so on...
So, $a_{n}=\{2,5,10,17,26,...,(n^{2}+1)\}$
- the $(n^{2}+1)$ is called the *general term*.

More example:
$$b_n =\frac{n}{3^n}$$
Starting at $n=1$:
- $b_{1}=\frac{1}{3^{1}}=\frac{1}{3}$
- $b_{2}=\frac{2}{3^{2}}=\frac{2}{9}$
- $b_{3}=\frac{3}{3^{3}}=\frac{3}{27}=\frac{1}{9}$
- $b_{4}=\frac{4}{3^{4}}=\frac{4}{81}$
- $b_{5}=\frac{5}{3^{5}}=\frac{5}{243}$
So, $b_{n}=\{\frac{1}{3},\frac{2}{9},\frac{1}{9},\frac{4}{81},\frac{5}{247},...,\frac{n}{3^{n}}\}$

More examples:
$$a_n =(-1)^{n-1}(\frac{n}{2n-1}) $$
Starting at $n=1$:
- $a_{1}=(-1)^{1-1}(\frac{1}{2(1)-1})=1$
- $a_{2}=(-1)^{2-1}(\frac{2}{2(2)-1})=- \frac{2}{3}$
- $a_{3}=(-1)^{3-1}(\frac{3}{2(3)-1)})=\frac{3}{5}$
- $a_{4}=(-1)^{4-1}(\frac{4}{2(4)-1})=- \frac{4}{7}$
- $a_{5}=(-1)^{5-1}(\frac{5}{2(5)-1})=\frac{5}{9}$
Notice how we are alternating between negative and positive, this is due to the $(-1)^{n-1}$ whereas if $n$ is even $n-1$ will become odd, making the $(-1)$ retain its negative sign, and vice versa for if $n$ is odd.
Looking at the sequence alone, we can somewhat deduct what $a_{6}$ will be without any calculation.
- the numerator is just the index.
- the denominator is a sequence of odd numbers
- the signs are always alternating between + and -
Thus, $a_{6}$ should be $- \frac{6}{11}$. Testing this: $a_{6}=(-1)^{6-1}(\frac{6}{2(6)-1})=- \frac{6}{11}$, so our guess was right this time.
So, $a_{n}=\{1, - \frac{2}{3}, \frac{3}{5}, - \frac{4}{7}. \frac{5}{9},...,[(-1)^{n-1}(\frac{n}{2n-1})]\}$.

What if we have the reverse of the above: we are given a sequence and we are tasked determine the general term.

For example:
$$a_{n} =1,\frac{1}{2},\frac{1}{3},\frac{1}{4},\frac{1}{8},...$$
For this kind of cases, it would be beneficial for us to write them in *the same form* e.g. in this case, most of the term are fractions except for the first term, so we should re-write that as fraction too to identify the patterns.
$a_{n}=\frac{1}{1},\frac{1}{2},\frac{1}{4},\frac{1}{8},...$
- notice that the numerators are always just 1
- the denominators doubled every term. We can also view the denominator as a sequence of $2^n$.
We can rewrite this as:
$a_{n}=\frac{1}{2^{0}},\frac{1}{2^{1}},\frac{1}{2^{2}},\frac{1}{2^{3}},...$
- notice that the power on the denominator is always exactly $n-1$.
Thus, we write the general term as:
$$a_n= \frac{1}{2^{n-1}}  $$

Next example:
$$b_n =2,-4,6,-8,10,...$$
These are all even numbers with alternating signs. Let's try to re-write this in term of 2:
$b_{n}=(1)2,(-2)2,(3)2,(-4)2,(5)2,...$
Okay, let's deal with what's inside the parentheses next. I imagine that alternating sign must be some kind of negative number e.g. $(-1)$ powered by odd or even number.
- $a_{1}=(-1)^{2}\cdot 1\cdot 2=2$
- $a_{2}=(-1)^{3}\cdot 2\cdot2=-4$
- $a_{3}=(-1)^{4}\cdot 3\cdot2=6$
- $a_{4}=(-1)^{5}\cdot4\cdot2=-8$
- $a_{5}=(-1)^{6}\cdot5\cdot2=10$
Notice that the power over $(-1)$ is just $n-1$.
Thus, $b_{n}=(-1)^{n+1}(2n)$.
With this we can easily figure out $b_{50}$: $b_{50}=(-1)^{50-1}\cdot50\cdot2=-100$.

Next example:
$$a_{n} =- \frac{2}{3},\frac{4}{9},- \frac{8}{27}, \frac{16}{81},...$$
- Notice the alternating signs (although this one starts with a negative). 
- The numerator is just a sequence of power of 2
- The denominator is just a sequence of power of 3
$a_{n}=(-1)^{n} \frac{2^{n}}{3^{n}}$
Let's try it out with a few number:
- $a_{1}=(-1)^{1} \frac{2^{1}}{3^{1}}= -\frac{2}{3}$
- $a_{2}=(-1)^{2} \frac{2^{2}}{3^{2}}=\frac{4}{9}$
- $a_{3}=(-1)^{3} \frac{2^{3}}{3^{3}}=- \frac{8}{27}$
This seems good. Let's simplify our general term a bit:
$a_{n}=(- \frac{2}{3})^{n}$

Next example:
$$b_n =1,3,5,7,9,...$$
$b_n=n+2$? No, this only works *recursively* (notice how $b_{4}=4+2=6$). It can be written recursively as $b_{n}=b_{n-1}+2$. Let's try it without using recursive term. We can look at it from the viewpoint of even numbers:
$b_{n}=(2-1),(4-1),(6-1),(8-1),(10-1),...$
$b_{n}=[2(1)-1],[2(2)-1],[2(3)-1],[2(4)-1],[2(5)-1],...$
$b_{n}=2n-1$
Say, what $b_{100}$?
If we used the recursive formula $b_{n}=b_{n-1}+2$, then:
$b_{100}=b_{99}+2$
Notice the amount of work we have to do backwards to get to $b_{100}$. Instead we can use our defined general term:
$b_{100}=2(100)-1=199$
This is not to say that the recursive formula is useless. Both are equally true and have different uses. ^e5c8f2
## Introduction to Series and Summation Notation

*Series* adds the terms of a [[#Introduction to Sequences|sequence]]. 

$$\sum_{k=1}^{n} \frac{k^{2}}{2}=$$
Before solving this let's understand the notations:
- $\sum\limits$ stands for sum
- $k=1$ is where you start
- $n$ is where to end
$\sum_\limits{k=1}^{n} \frac{k^{2}}{2}=\frac{1^{2}}{2}+ \frac{2^{2}}{2}+ \frac{3^{2}}{2}+ ... + \frac{n^{2}}{2}$
If, instead of $n$, we have 3, then it would simply be:
$\sum_\limits{k=1}^{n} \frac{k^{2}}{2}=\frac{1^{2}}{2}+ \frac{2^{2}}{2}+ \frac{3^{2}}{2}$

$$\sum_\limits{k=0}^{n-1} (2k+1)=$$
$\sum_\limits{k=0}^{n-1} (2k+1)=(2\cdot0+1)+ (2\cdot1+1)+ (2\cdot2+2)+ ... +[2\cdot(n-1)+1]$
We can simplify this as:
$\sum_\limits{k=0}^{n-1} (2k+1)=1+3+5+ ... +(2n-1)$
Rmb, our [[#^{e5c8f2|sequence for odd number]] in the previous section? This looks the exact same thing. But this one started at 0 instead of 1. So:
$$\sum_{k=0}^{n-1} (2k+1)=\sum_{k=1}^n (2k-1)$$
This says that you can manipulate one series into another by changing where you start ($k$) and where you stop ($n$), and it might change the sequences that you are working with.

Like in sequences, we can go backwards, for example:
$2-4+8-...-256$
Try to put them in common term:
- $a_{1}=2$
- $a_{2}=-4$
- $a_{3}=8$
- ...
- $a_{k}=-256$
Notice that this is a finite series, ending at $k$. We also need to find $k$ to complete the whole series notation (we already know the starting point at $k=1$).
- $a_{1}=1\cdot2^{1}$
- $a_{2}=-1\cdot 2^{2}$
- $a_{3}=1\cdot2^{3}$
- ...
- $a_{k}=-1\cdot 2^{8}$
Notice that our $k=8$. We can write this as:
$$\sum_{k=1}^{8} (-1)^{k-1}2^{k}$$
If we were not given the last term, say: $2-4+8-...$ Then our series can be written as: $\sum_\limits{k=1}^{n} (-1)^{k-1}2^{k}$
- notice that we used $n$ as an ending term there instead of 8.

We don't really have to add everything up manually as we did above. We have *formulas* for it, which were proven by [[#Proof by Mathematical Induction|mathematical induction]] (which we will learn later):
$$\sum_{k=1}^{n}C=C\cdot n$$
Where did that come from!? Think about it this way:
$$\sum_{k=1}^{n}1=n$$
Say:
$\sum_\limits{k=1}^{7}1=1+1+1+1+1+1+1$
$\sum_\limits{k=1}^{7}1=7$
Notice how this is a repeated addition of the same number 7 times. That's just multiplication!
Let's try another example:
$\sum_\limits{k=1}^{7}5=5+5+5+5+5+5+5$
$\sum_\limits{k=1}^{7}5=35$
This is where $\sum_{k=1}^{n}C=C\cdot n$ come from.
$\sum_\limits{k=1}^{n}C=\sum_\limits{k=1}^{n}C\cdot1$
$\sum_\limits{k=1}^{n}C=C\cdot\sum_{k=1}^{n}1$
We know that $\sum_{k=1}^{n}1=n$, so:
$\sum_\limits{k=1}^{n}C=C\cdot n$

Say we have term $k$:
$$\sum_{k=1}^{n}k=\frac{n(n+1)}{2}$$
What if we can't simplify to $k$:
$$\sum_{k=1}^{n}k^2 =\frac{n(n+1)(2n+1)}{6}$$
$$\sum_{k=1}^{n}k^3 =[\frac{n(n+1)}{2}]^2 $$ ^c8851d

For example:
$$\sum_{k=1}^{12}(k^{3}-4k^{2}+5k+7)$$
Before doing this, note that **we can separate the series by addition, subtraction, and multiplication**. 
	Why? Series are just addition, and addition is *commutative* ($a+b=b+a$), and *associative* ($(a+b)+c=a+(b+c)$) 
This mean that we can break this down into smaller chunks and use formulas to solve them separately.
$\sum_\limits{k=1}^{12}k^{3}-\sum_\limits{k=1}^{12}4k^{2}+\sum_\limits{k=1}^{12}5k+\sum_\limits{k=1}^{12}7$
We can actually also bring the coefficient out front, like so:
$\sum_\limits{k=1}^{12}k^{3}-4\sum_\limits{k=1}^{12}k^{2}+5\sum_\limits{k=1}^{12}k+\sum_\limits{k=1}^{12}7$
	Let's think about this:
	$\sum_\limits{k=1}^{3}5k=5(1)+5(2)+5(3)$
	Notice that the 5 is *factorable*:
	$\sum_\limits{k=1}^{3}5k=5(1+2+3)$
	Rewriting this:
	$\sum_\limits{k=1}^{3}5k=5\sum_{k=1}^{3}k$
Let's list out our terms:
- $\sum_\limits{k=1}^{12}k^{3}=[\frac{12(12+1)}{2}]^{2}=6084$
- $-4\sum_\limits{k=1}^{12}k^{2}=-4\cdot\frac{12(12+1)(2(12)+1)}{6}=-2600$
- $5\sum_\limits{k=1}^{12}k=5\cdot\frac{12(12+1)}{2}=390$
- $\sum_\limits{k=1}^{12}7=7\cdot12=84$
Adding these up:
$\sum_\limits{k=1}^{12}(k^{3}-4k^{2}+5k+7)=6084-2600+390+84=3958$

Next example:
$$\sum_{k=4}^{24}k^3$$
Notice the $k=4$ below. They don't match with our formula and thus *they don't work*. So what now? Imagine if we have $k=1$ exactly like in our formula:
$\sum_\limits{k=1}^{24}k^3$
Comparing this to our problem, what is the *difference* between $\sum\limits_{k=1}^{24}k^3$ and $\sum_\limits{k=4}^{24}k^3$? In the latter, we don't have the first term, the second term, and the third term ($k=1,2,3$), and that's exactly $\sum\limits_{k=1}^{3}k^3$. 
Thus:
$$\sum_{k=4}^{24}k^3=\sum_{k=1}^{24}k^3-\sum_{k=1}^{3}k^3$$
So:
$\sum\limits_{k=4}^{24}k^3=[\frac{24(24+1)}{2}]^{2}-[\frac{3(3+1)}{2}]^{2}$
$\sum\limits_{k=4}^{24}k^3=90,000-36=89,964$

## Arithmetic Sequences

This is a sequence where the difference between any 2 sequential terms is constant (called the common difference "d"). 
	This simply means adding the same number over and over.

Arithmetic sequences can always be written as:
$$a_n=a_1+(n-1)d$$
- $a_{1}$ is simply where to start
- $(n-1)$ is how many $d$ to add
	- say we want $a_{100}$ or the 100 term, it would be $a_{1}+99d$, since $a_1$ already count as one.

For example:
$$2,6,10,14,18,...$$
$d$ in this case is 4.
$a_{n}=2+(n-1)4$
$a_{n}=2+4n-4$
$a_{n}=4n-2$
This is really nice and simplified. We can easily find $a_{19450232}$ with this.
$$1,3,5,7,9,...$$
$d$ in this case is 2.
$a_n=1+(n-1)2$
$a_{n}=1+(2n-2)$
$a_{n}=2n-1$
Rmb [[#^{e5c8f2|this one]]? This is the *exact* same sequence. Notice how our knowledge of arithmetic sequence greatly reduces the amount of work we have to do.

### More examples
 The eighth term of an arithmetic sequence is 75. The twentieth term is 39. Find the formula and the twelfth term.
$a_n=a_1+(n-1)d$
From this formula, we must find:
- $a_{1}$
- $d$
We know the eighth term:
$75=a_{1}+(8-1)d$
$75=a_{1}+7d$
$a_{1}=75-7d$
We also know the twentieth term:
$39=a_{1}+(20-1)d$
Replace $a_{1}=75-7d$ here:
$39=(75-7d)+19d$
$39=75+12d$
$-36=12d$
$d=-3$
Replace $d=-3$ in $a_{1}=75-7d$:
$a_{1}=75-7(-3)$
$a_{1}=75+21=96$
So:
$a_n=96+(n-1)(-3)=96-3n+3$
$a_{n}=99-3n$
To find the twelfth term:
$a_{12}=99-3(12)$
$a_{12}=99-36$
$a_{12}=63$
## Arithmetic Series

For some $S_{n}=a_{1}+a_{2}+...+a_{n}$ :
$$\sum_{k=1}^{n}[a_1 +(k-1)d]=\frac{n}{2}(a_1+a_n)$$
- notice how this is the same as how we defined the [[#Arithmetic Sequences]].

For example:
$$60+64+68+72+...+120$$
- $a_1=60$
- $d=4$
- $a_n=120$
Our arithmetic *sequence* would be: 
$a_n=a_1+(n-1)d$ 
$a_n=4n+56$
Notice how we could solve for $n$ here, so:
$120=60+(n-1)4$
$16=n$
We can write our arithmetic *series* as:
$\sum\limits_{k=1}^{16}(4k+56)=\frac{16}{2}(60+120)$
$\sum\limits_{k=1}^{16}(4k+56)=8(180)$
$\sum\limits_{k=1}^{16}(4k+56)=1440$

Next example:
$$2+4+6+...+2n$$
- $a_1=2$
- $d=2$
- $a_n=2n$
Our arithmetic *sequence* would be: 
$a_n=a_1+(n-1)d$ 
$a_n=2+(n-1)2$
$a_n=2n$
Our arithmetic sequence is somehow the exact same as the $n$-th term of our sequence.  
We can write this as:
$\sum\limits_{k=1}^{n}2k=\frac{n}{2}(a_1+a_n)$
$\sum\limits_{k=1}^{n}2k=\frac{n}{2}(2+2n)$
$\sum\limits_{k=1}^{n}2k=\frac{n}{2}2(1+n)$
$\sum\limits_{k=1}^{n}2k=n(n+1)$
Here's the cool part:
$2\cdot\sum\limits_{k=1}^{n}k=n(n+1)$
$\sum\limits_{k=1}^{n}k=\frac{n(n+1)}{2}$
[[#^c8851d|Don't this looks familiar...]]
## Geometric Sequences

Geometric Sequences refers to a sequence where the ratio between any 2 successive terms is constant (common ratio).

All geometric sequences can be written as:
$$a_n =a_1r^{n-1}$$
- notice the similarities and differences with: $a_{n}=a_{1}+(n-1)d$

For example:
$$2,-6,18,-54,162,...$$
- Notice that the common ratio here is $-3$
This can be written as $a_{n}=2\cdot3^{n-1}$.

### More examples
Let's look at another one:
$$2,9,16,23,30,...$$
- This doesn't seem like a geometric sequence... Let's check it:
	$\frac{9}{2}=\frac{16}{9}$ is not true. This does not have a common ratio and thus not a geometric sequence.
- This, however, seems like an [[#Arithmetic Sequences]].
	$9-2=16-9=7$. We have a common difference of $d=7$.
This can be written as: $a_{n}=2+(n-1)7=7n-5$.

Another one:
$$1,2,4,7,11,16,22,...$$
This is neither arithmetic nor geometric sequence. We have neither common difference nor common ratio between the terms.

Another one:
$$7,14,28,56,...$$
- The common ratio here is $\frac{14}{7}=\frac{28}{14}=\frac{56}{28}=2$
We can write this as: $a_{n}=7(2)^{n-1}$

Another one:
$$-3,1,- \frac{1}{3},\frac{1}{9},...$$
- The common ratio here is: $\frac{1}{-3}=\frac{- \frac{1}{3}}{1}= \frac{\frac{1}{9}}{- \frac{1}{3}}=- \frac{1}{3}$
This can be written as: $a_{n}=-3(- \frac{1}{3})^{n-1}$, or simplified as: $a_n=(-3)^{n-2}$

What if we're given only a term and a common ratio. Say:
$$a_6=243, r=-3$$
$243=a_{1}(-3)^{6-1}$
Notice how we can solve for $a_1$ here:
$a_{1}=-1$
So:
$a_{n}=-1(-3)^{n-1}$

What if we're only given two terms form a sequence. Say:
$a_{3}=\frac{1}{3},a_{6}=\frac{1}{81}$
$a_{6}=a_{3}(r)^{6-3}$
Notice how we modelled this from this: $a_n =a_1r^{n-1}$.
$\frac{1}{81}=\frac{1}{3}r^{3}$
$\frac{3}{81}=r^{3}$
$\frac{1}{27}=r^{3}$
$\sqrt[3]{\frac{1}{27}}=\sqrt[3]{r^{3}}$
$r=\frac{1}{3}$
Solve for $a_{1}$:
$\frac{1}{3}=a_{1}(\frac{1}{3})^{3-1}$
$\frac{1}{3}=a_{1}(\frac{1}{9})$
$a_{1}=3$
We can write this as: $a_{n}=3(\frac{1}{3})^{n-1}$ or as $a_{n}=3^{n-2}$.
## Geometric Series

$$\sum\limits_{k=1}^{n}a_1 r^{k-1}=\frac{a_1}{1-r}(1-r^n)$$

For example:
$$\frac{3}{9}+ \frac{3^{2}}{9}+ \frac{3^{3}}{9}+...+ \frac{3^{n}}{9}$$
Notice our last term has an $n$ in it, which means that the sequence is *given* to us: $a_{n}=\frac{3^n}{9}$
We can write this as:
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}$
But this doesn't look like the given formula at all, can we really use this? We can, and to prove that, we must separate the term $\frac{3^{k}}{9}$ into $a_{1}$ and $r$, and turn the power $k$ to $k-1$:
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}\to\sum\limits_{k=1}^{n}a_1 r^{k-1}$
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}$
$\sum\limits_{k=1}^{n} \frac{1}{9}\cdot3^{k}$
$\sum\limits_{k=1}^{n} \frac{1}{9}\cdot3\cdot3^{k-1}$
$\sum\limits_{k=1}^{n} \frac{3}{9}(3)^{k-1}$
Notice this is now exactly in the same format as $\sum\limits_{k=1}^{n}a_1 r^{k-1}$.
Now that we can use formula without guilt:
$\sum\limits_{k=1}^{n}a_1 r^{k-1}=\frac{a_1}{1-r}(1-r^n)$
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}=\frac{\frac{3}{9}}{1-3}(1-3^n)$
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}=-\frac{3}{18}(1-3^n)$
$\sum\limits_{k=1}^{n} \frac{3^{k}}{9}=-\frac{1}{6}(1-3^n)$

What if we have $n=12$:
$\sum\limits_{k=1}^{12} \frac{3}{9} 3^{k-1}=-\frac{1}{6}(1-3^12)\approx88573.34$
### Infinite Geometric Series

Is there a time where an *infinite* geometric series adds up to a *finite* number? Yes, but only in few cases. The case where it adds up to a finite number is called *convergence*, else it is called *divergence* where the number goes to $-\infty$ or $\infty$. Only 2 cases are possible, an infinite series:
- will have a finite sum (*converge*), if: $-1<r<1$ or $|r|<1$
- will have an infinite sum (*diverge*), if: $|r|\geq1$

Think about it this way:
$$\sum\limits_{k=1}^{n}a_1 r^{k-1}=\frac{a_1}{1-r}(1-r^n)$$
We're thinking about what would happen to this series as $n\to\infty$. 

Say we have $r=2$:
$\frac{a_{1}}{1-2}(1-2^{n})$
Focus on the $(1-2^{n})$. If $n=\infty$ then $(1-2^\infty)$, is very near $\infty$.
This is called a *divergence*.

But what if $r<1$, say we have $r=\frac{1}{2}$:
$\frac{a_{1}}{1- \frac{1}{2}}(1- \frac{1}{2}^{n})$
Focus on the $(1- \frac{1}{2}^{n})$. Now think about what $n=\infty$ does to $\frac{1}{2}$:
$(\frac{1}{2})^\infty=\frac{1^{\infty}}{2^{\infty}}=\frac{1}{2^{\infty}}$
Now this number, $\frac{1}{2^{\infty}}$, is very very very close to zero. So $(1-\frac{1}{2^{\infty}})$ is pretty much $(1-0)$, since it diminishes in size indefinitely. From this, we can see how infinite series can sums up to a finite number rather than an infinite one.
This is called a *convergence*.

For example:
$\sum\limits_{k=1}^{\infty}8( \frac{1}{3})^{k-1}=$
- $r=\frac{1}{3}$
- $a_{1}=8$
$r=\frac{1}{3}$ is between -1 and 1, meaning that this is a *convergence*. 
Let's write this using our equation:
$\sum\limits_{k=1}^{\infty}8( \frac{1}{3})^{k-1}=\frac{8}{1-(\frac{1}{3})}(1- (\frac{1}{3})^\infty)$
$\sum\limits_{k=1}^{\infty}8( \frac{1}{3})^{k-1}=12(1- (\frac{1}{3})^\infty)$
Remember than $(\frac{1}{3})^\infty$ ends up being 0 so:
$\sum\limits_{k=1}^{\infty}8( \frac{1}{3})^{k-1}=12(1-0)$
$\sum\limits_{k=1}^{\infty}8( \frac{1}{3})^{k-1}=12$
So we have here a *finite* number as a result of *infinite* series (it converges). That's crazy!
### More examples
$$\sum\limits_{k=1}^{\infty} \frac{1}{2}(3)^{k-1}=$$
- $r=3$
- $a_{1}=\frac{1}{2}$
$|3|>1$, so this will diverge.
$\sum\limits_{k=1}^{\infty} \frac{1}{2}(3)^{k-1}= \frac{\frac{1}{2}}{{1-3}}(1-3^{\infty})$
$\sum\limits_{k=1}^{\infty} \frac{1}{2}(3)^{k-1}= -1(1-3^{\infty})$
$\sum\limits_{k=1}^{\infty} \frac{1}{2}(3)^{k-1}= 3^{\infty}-1$
Still $3^{\infty}-1$ is just some sort of $\infty$.

$$\sum\limits_{k=1}^{\infty}3(- \frac{2}{3})^{k-1}=$$
- $r=- \frac{2}{3}$
- $a_{1}=3$
Notice that $r=-\frac{2}{3}$ is within -1 and 1. So it will converge:
$\sum\limits_{k=1}^{\infty}3(- \frac{2}{3})^{k-1}=\frac{3}{1-(- \frac{2}{3})}(1-(- \frac{2}{3})^{\infty})$
Since $(1-(- \frac{2}{3})^{\infty})=(1-0)$, we can disregard it.
$\sum\limits_{k=1}^{\infty}3(- \frac{2}{3})^{k-1}=\frac{9}{5}$

$\sum\limits_{k=1}^{\infty} \frac{1}{9}(- \frac{5}{4})^{k-1}=$
- $r=- \frac{5}{4}$
- $a_{1}=\frac{1}{9}$
This will diverge, since $|r|\geq1$. We will stop here since we cannot really get a finite solution anyway (but this will go to $-\infty$).

$$\sum\limits_{k=1}^{\infty}3(\frac{2}{3})^{k}=$$
Notice that the parentheses is powered by $k$ instead of $k-1$, we should re-arrange this first to make it fit the formula:
$\sum\limits_{k=1}^{\infty}3\cdot \frac{2}{3} (\frac{2}{3})^{k-1}$
$\sum\limits_{k=1}^{\infty}2(\frac{2}{3})^{k-1}$
- $r=\frac{2}{3}$
- $a_{1}=2$
So:
$\sum\limits_{k=1}^{\infty}3(\frac{2}{3})^{k}=\frac{2}{1-(\frac{2}{3})}$ or $\sum\limits_{k=1}^{\infty}3(\frac{2}{3})^{k}=\frac{3(\frac{2}{3})}{1-(\frac{2}{3})}$
$\sum\limits_{k=1}^{\infty}3(\frac{2}{3})^{k}=6$
## Proof by Mathematical Induction

Induction is the idea of proving one thing will prove the next one, then the entire thing become proven (like domino effect).
![[Pasted image 20240902205135.png]]
Steps:
1. Show that at least 1 term is *true* e.g. the 1st term.
2. Assume that it is true for some other number e.g. the $k$-th term.
	Assume means treating it as fact.
3. Prove the "next one" e.g. the $k+1$-th term.

Let's see with an example:
$$1+3+5+...+(2n-1)=n^{2}$$
Going through the steps:
1. Show that at least 1 term is *true* e.g. the 1st term.
$n=1:$  $1=1^{2}$
$n=2 :$  $1+3=2^{2}$
$n=3 :$  $1+3+5=3^{2}$
$n=4 :$  $1+3+5+7=4^{2}$
This all *true*, but does this proves $1+3+5+...+(2n-1)=n^{2}$? No, we've only proved it for some finite values.
Induction is for proving that the next one ($n=5,n=6,...$) will *always be true*.
2. Assume that it is true for some other number e.g. the $k$-th term.
$n=k :$ 
$1+3+5+...+(2k-1)=k^{2}$
$k$ here is just some other term past 1. We assume that this is a fact and proceed to the next and most important step.
3. Show for $n=k+1$
If we show that this is *true*, this means that the next one will always be true (thus the domino effect).
$n=k+1 :$ 
$1+3+5+...+(2k-1)+[2(k+1)-1]=(k+1)^{2}$
Since we know that $1+3+5+...+(2k-1)=k^{2}$ is true, we can substitute it here:
$k^{2}+[2(k+1)-1]=(k+1)^{2}$
$k^{2}+2k+1=k^{2}+2k+1$
This is *true* and it will hold true for any next term. Notice how $k$ can be anything and this will still be true.

$$1+5+9+...+(4n-3)=2n^2 -n$$
1. Prove the first term (if $n=1$)
$1=2(1)^{2}-1$
$1=1$
This is *true*. 
This is unnecessary but let's do a few more just to get the hang of it:
$n=2:$ $1+5=2(2)^2-2$
$6=6$
This is *true*.
$n=3:$ $1+5+9=2(3)^2-3$ 
$15=15$
This is also *true*. Let's proceed.
2. Assume that it is true for some other number 
$1+5+9+...+(4k-3)=2k^{2}-k$
3. Show for $n=k+1$
$1+5+9+...+(4k-3)+[4(k+1)+1]=2(k+1)^{2}-(k+1)$
Since we know that $1+5+9+...+(4k-3)=2k^{2}-k$:
$2k^{2}-k+[4(k+1)-3]=2(k+1)^{2}-(k+1)$
$2k^{2}+3k+1=2k^{2}+3k+1$
This is *true*. 

This technique is very good for proving series and problems in Calculus.