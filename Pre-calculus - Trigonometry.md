## Introduction to Angles

Angles occur at any time 2 rays share a common origin (*vertex*). There is an *angle* between them.
	Note: Angles ($\theta$) are positive is measured *counter-clockwise*.

![[Pasted image 20240903192933.png]]
- notice the counter-clockwise direction here.

![[Pasted image 20240903193140.png]]
- in this case, our terminal side sits exactly at where our initial side is.
- this is a full rotation aka. $360\degree$.
- if we measure this *clockwise*, it would be $0\degree$. this is a full rotation is written as $0\degree/360\degree$. 

![[Pasted image 20240903193814.png]]
- this is $\frac{1}{4}$ (a *quadrant*) of a full rotation aka. $\frac{360}{4}=90\degree$.

![[Pasted image 20240903194118.png]]
- this is half of a full rotation aka. $180\degree$. 

![[Pasted image 20240903194241.png]]
- this is $\frac{3}{4}$ of a full rotation aka. $270\degree$.

This is how our quadrants are located.
![[Pasted image 20240903203006.png]]
- this will help us determine the signs of trigonometry functions.

If we measure this clockwise, we would get a negative angle. Since $\theta$ is already used for counter-clockwise measurement, we'll call this direction $\alpha$.
![[Pasted image 20240903203233.png]]

![[Pasted image 20240903203322.png]]

![[Pasted image 20240903203414.png]]
### More examples
![[Pasted image 20240903204449.png]]

## Converting Degrees, Minutes, and Seconds

*Minutes* and *seconds* are **fractions** of a degree.
$$1\text{ Revolution}=360\degree$$
- $1\degree=60\text{ minutes} (60')$ 
	- $1\degree=60'$ or $1'=\frac{1}{60}\degree$
- $1' = 60 \text{ seconds } (60'')$ 
	- $1'=60''$ or $1''=\frac{1}{60}'$ or $1''=\frac{1}{60}\cdot \frac{1}{60}\degree$ 

For example:
$$61\degree 42' 21''$$
To convert this to degree:
1. 42 minutes to degree
$42'=42\cdot \frac{1}{60}\degree=\frac{42}{60}\degree$
2. 21 seconds to degree
$21''=21\cdot \frac{1}{60}\cdot \frac{1}{60}\degree=\frac{21}{3600}\degree$
3. sums everything:
$61\degree+ \frac{42}{60}\degree+ \frac{21}{3600}\degree=61.70583\degree$
Notice how the $42'21''$ is just $0.70583\degree$. They are very very small units. 
In fact:
- $1'\approx0.0166666667$
- $1''\approx0.000277778$

More example:
$$101\degree3'51''$$
$101\degree+(3\cdot \frac{1}{60})\degree+(51\cdot \frac{1}{60}\cdot \frac{1}{60})\degree=101.0641667\degree$ 

Let's do some examples in reverse:
$$18.255\degree$$
$18\degree$ is just $18\degree$. And $.255\degree$ is some *fraction*. Think about it this way:
$18\degree+0.255\degree$
$18\degree+(0.255\cdot1\degree)$
We know that 1 degree = 60 minutes:
$18\degree+(0.255\cdot60')$
$18\degree+15.3'$
Same as before, $15'$ is just $15'$. And $.3'$ is some fraction.
$18\degree+15'+0.3'$
$18\degree+15'+(0.3\cdot 1')$
We know that 1 minutes = 60 seconds:
$18\degree+15'+(0.3\cdot 60'')$
$18\degree+15'+18''$
We can rewrite this as:
$18\degree15'18''$

More example:
$$29.411\degree$$
$29\degree+0.411\degree$
$29\degree+(0.411\cdot60')$
$29\degree+24.66'$
$29\degree+24'+0.66'$
$29\degree+24'+(0.66\cdot60'')$
$29\degree+24'+39.6''$
$29\degree24'39.6''$
With seconds, typically, we're going to round this.
$29\degree24'40''$
The rounding at the end make $29.411\degree$ more accurate than $29\degree24'40''$.
## Introduction to Radians

A **radian** is the central angle needed on any circle to make the *arc* subtended (cut) equal to the radius.
![[Pasted image 20240904232459.png]]
![[Pasted image 20240904232545.png]]
- $\alpha$ is just an angle that makes the *arc* ($=4$) equal to the *radius* ($=4$).

Say we have a circle:
![[Pasted image 20240904233047.png]]
By definition the angle $\alpha=1 \text{ Radian}$.  
![[Pasted image 20240904233101.png]]
Notice that we have another arc on the other side. Understand that $r$ will still be $r$.
![[Pasted image 20240904233254.png]]
But the another arc here is not equal to $r$. Let's call it $S$ (notice that $S\neq r$), and the angle $\theta$ (notice that $\theta \neq \alpha$). 
![[Pasted image 20240904233421.png]]
The difference between two arcs and two angles above are *proportional*. We can put them into relationship:
$$\frac{r}{\alpha}=\frac{S}{\theta}$$
We know that $\alpha = 1 \text{ Radian}$.
$\frac{r}{1 RAD}=\frac{S}{\theta}$
Multiply both sides by $\theta$:
$S=\frac{r\cdot\theta}{1 RAD}$
Notice that the arcs ($S$ and $r$) have some unit of length e.g. mm, cm, m, ft, etc. By unit conversion, we want $\theta$ to have a unit of Radian so that we can eliminate it from our equation. 
This is why we have the equation: $$S=r\cdot\theta \text{ ,when } \theta \text{ is in radian}$$![[Pasted image 20240904234533.png]]

Notes on how degree vs radians are measured: 
- A *degree* is always $\frac{1}{360}$ of a circle.
- A *radian* is the angle made at the center of a circle by an arc equal to the radius wrapped around the circumference.

For example:
$$r=6ft\text{ , } \theta=\frac{1}{3}RAD$$
$S=6\text{ ft}\cdot \frac{1}{3}RAD$
The real equation is:
$S=\frac{r\cdot\theta}{1 RAD}$
$S=\frac{6\text{ ft}\cdot \frac{1}{3}RAD}{1RAD}$
We can eliminate the Radian unit now, leaving only the $ft$ which is a unit of length for the arc.
$S=\frac{6\text{ ft}\cdot \frac{1}{3}\cancel{RAD}}{1\cancel{RAD}}$
$S=2ft$
This illustrate why we need $\theta$ to be in Radian.

$$r=12m\text{ , } S=16m$$
Notice how $S>r$ in this case. So, our $\theta$ should be proportionally larger than 1 Radian.
$S=r\cdot\theta$
$16m=12m\cdot\theta$
$\theta=\frac{16m}{12m}$
$\theta=\frac{16\cancel{m}}{12\cancel{m}}$
$\theta=\frac{4}{3}RAD$
The unit here is *Radian*. Rmb, we have a denominator of 1 Radian hidden away + the formula only works when $\theta$ is in Radian anyway.
## Converting Radians and Degrees

Both units are very important and we should be comfortable with using both of them and converting to and from them.
To recap:
![[Pasted image 20240905004723.png]]
Funny idea: what if we have $\theta=360\degree$?
![[Pasted image 20240905004935.png]]
The arc or $S$ will become a full circumference of a circle.
![[Pasted image 20240905005102.png]]
Circumference of a circle $=2\pi r$
We see that $S=2\pi r$, so:
$S=r\cdot\theta$
$2\pi r=\frac{r\cdot\theta}{1RAD}$
Cancel $r$ from both side:
$2\pi RAD=\theta$
![[Pasted image 20240905005555.png]]
Now look at this Radian measure with a bunch of $\pi$:
![[Pasted image 20240905005440.png]]
- Because the full circumference is $2\pi r$, hence we get the central angle of $2\pi$. Anything that has a *smaller* angle will have a *proportionally smaller* arc length.

Now:
- We now know that 1 full revolution of a circle has $2\pi$ Radians. 
- We also know that 1 full revolution of a circle has $360\degree$. 
So $2\pi RAD=360\degree$. This equality allow us to convert between the two.
$\frac{2\pi RAD}{360}=1\degree$
$\frac{\pi}{180}RAD=1\degree$
Or
$1 RAD=\frac{360\degree}{2\pi}$
$1RAD=\frac{180}{\pi}\degree$
Now we have a Radian definition in degree ($1RAD=\frac{180}{\pi}\degree$) and a degree definition in Radian ($1\degree=\frac{\pi}{180}RAD$).

Let's see some example:
$$60\degree\to$$
$2\pi { RAD}=360\degree$
$\frac{2\pi RAD}{360}=1\degree$
Multiply by 60 on both side:
$60\degree=\frac{\pi}{3}$
Try to imagine this in your head for all such conversions:
$\pi RAD=180\degree$
![[Pasted image 20240905012144.png]]
Since $\pi$ is divided by 3, from counter-clockwise:
![[Pasted image 20240905012337.png]]


$$150\degree\to$$
$\frac{2\pi RAD}{360}=1\degree$
Multiply by 150 on both side:
$\frac{300\pi}{360}RAD=150\degree$
$\frac{5\pi}{6}RAD=150\degree$
Once again, try to imagine this in your head:
$\pi RAD=180\degree$
![[Pasted image 20240905012144.png]]
Since $\pi$ is divided into 6 parts, we count 5 out of 6 part:
![[Pasted image 20240905012711.png]]
$$-45\degree\to$$
$\frac{2\pi RAD}{360}=1\degree$
Multiply by -45 on both side:
$- \frac{90\pi}{360}RAD=-45\degree$
$- \frac{\pi}{4}RAD=-45\degree$
Imagine this:
Since we have a negative sign, we are measuring this *clockwise*.
![[Pasted image 20240905012852.png]]
We count 1 out of 4 parts:
![[Pasted image 20240905012947.png]]

$$107\degree\to$$
$\frac{2\pi RAD}{360}=1\degree$
Multiply by 107 on both side:
$\frac{314\pi}{360}RAD=107\degree$
$\frac{157\pi}{180}RAD=107\degree$
That would be in quadrant two. We're not going to cut the circle into 180 parts but do try to imagine it as a 157 out of 180 part of this:
![[Pasted image 20240905012144.png]]

Let's try this backwards, from radian to degree:
$$\frac{\pi}{6}RAD\to$$
Rmb that:
$1RAD=\frac{360}{2\pi}\degree$
$1RAD=\frac{180}{\pi}\degree$
So:
$\frac{\pi}{6}RAD=\frac{\pi}{6}\cdot \frac{180}{\pi}\degree$
$\frac{\pi}{6}RAD\to30\degree$
Once again imagine this as 1 out of 6 part of a $180\degree$ angle.

$$\frac{3\pi}{2}RAD\to$$
$\frac{3\pi}{2}RAD\to \frac{180\degree}{\pi}\cdot\frac{3\pi}{2}$
$\frac{3\pi}{2}RAD\to 270\degree$
Fun fact: $90\degree,180\degree,270\degree,360\degree$ or $0\degree$ do not lie in any quadrant. It lies on the x- or y-axis.

$$- \frac{3\pi}{4}RAD\to$$
$- \frac{3\pi}{4}RAD\to \frac{180\degree}{\pi}\cdot - \frac{3\pi}{4}$
$- \frac{3\pi}{4}RAD\to -135\degree$
This would be in quadrant three.
### More examples
$\frac{7\pi}{3}RAD\to$
Before any actual calculation, let's think about this:
We have a $\pi$ divided into 3 parts:
![[Pasted image 20240905014428.png]]
But we count 7 of it? That's weird, but okay.
![[Pasted image 20240905014519.png]]
This is 6 time. We want to do one more, let's denote it with a darker red since it is counted twice:
![[Pasted image 20240905014556.png]]
There. So $\frac{180\degree}{3}\cdot 7$ should be equal to $420\degree$. We're in the first quadrant. 
For a more traditional calculation:
Rmb that,
$1 RAD=\frac{180}{\pi}\degree$
$\frac{7\pi}{3}RAD=\frac{180}{\pi}\degree\cdot \frac{7\pi}{3}$
$\frac{7\pi}{3}RAD=420\degree$

$$4RAD\to$$
Notice that we don't really have a $\pi$ like we usually do for Radian. 
We know that:
$1 RAD=\frac{180}{\pi}\degree$
$4RAD=\frac{720}{\pi}\degree$
Notice how this is going to be a decimal since $\pi\approx3.14$ is the denominator and there is no other $\pi$ to cancel it out. This is going to be the case for all Radians without $\pi$.
Using the calculator:
$4RAD\approx229.18$
![[Pasted image 20240905015539.png]]
That's approximately where $4RAD$ would be, in the third quadrant.
## Area of a Sector, Angular Velocity, Applications

Let's see some example of *the applications of angles*:

I live at $48.685701\degree$ latitude. I have to travel to a city at $43.6602646\degree$ latitude (both are at the same longitude). How far are the cities if $r=3960$ miles? Assume that the Earth is a perfect sphere.
![[Pasted image 20240905170633.png]]
![[Pasted image 20240905172639.png]]
To find the $\theta$, we simply find the difference between the angles of the two cities:
$\theta=48.685701\degree-43.6602646\degree$ 
$\theta=5.083055\degree$
$S=r\cdot\theta$
$S=3,960 mi.\cdot 5.083055\degree$
Wait... $S=r\cdot\theta$ only works if $\theta$ is in radian, we should first convert:
$\frac{2\pi}{360}=1\degree$
$5.083055\degree=0.08871604581 RAD$
Plugging this back in:
$S=3,960 mi.\cdot 0.08871604581 RAD$
$S=351.3155414 mi.$
So the cities are roughly 351.32 miles apart.
### Area of a Sector

Think about it this way:
What is the *total area* in 1 revolution of a circle? That's $\pi r^{2}$. 
What's the *angle*? $360\degree$ or $2\pi$ radians.

What if we don't want a full circle but a certain *sector* of the circle? Same concept as for the [[#Introduction to Radians|arc]], it's *proportional*:
$$\frac{A}{\theta}=\frac{\pi r^{2}}{2\pi}$$
- $A$ denotes the area of the sector.
- $\theta$ denotes the angle of the sector.
- The $2\pi$ is in *Radian* (this is important, and the reason why we can't use degree).
Notice how we can cancel the $\pi$ (we couldn't have done this with *degree*):
$$\frac{A}{\theta}=\frac{r^{2}}{2}$$
Multiplying both sides by $\theta$:
$$A= \frac{1}{2}r^{2}\theta$$
This only works if $\theta$ is in radians (since we used radian in the original equation).
![[Pasted image 20240905174105.png]]

For example:
$$r=3m, \theta=120\degree$$
First convert $\theta$ to radian:
Think of it as $\frac{2}{3}$ of $\pi$ or $180\degree$. 
$120\degree=\frac{2\pi}{3}Rad$
Now:
$A=\frac{1}{2}r^{2}\theta$
Note that the $\frac{1}{2}$ here is actually $\frac{1}{2Rad}$. Just to make sure that sinks in.
$A=\frac{1}{2}\cdot3^{2}\cdot \frac{2\pi}{3}$
$A=3\pi \text{  }m^{2}$ or $9.425\text{  }m^{2}$
$$r=6m, A=8m^{2}$$
$A=\frac{1}{2}r^{2}\theta$
$8m^{2}=\frac{1}{2 Rad}(6m)^{2}\theta$
$\frac{8m^{2}Rad}{18m^{2}}=\theta$
$\frac{4}{9}Rad=\theta$
### Angular Velocity

Think about how fast we're going as we're standing on Earth (which is moving, as far as I know).
- Think about how fast our angle is changing (thus, angular velocity), and in which direction.
- How fast our linear velocity change depends on where we are on the sphere. The *closer* we are to the axis of rotation, the faster we move and vice versa.
![[Pasted image 20240905224105.png]]
- notice that "ME" is on a *minor* circle.
	A minor circle because it it perpendicular to the x-axis but *do not* go through the center (it's not the biggest cut of circle possible). 
	Every *latitude*, that is not the *equator*, is a *minor* circle.
	Every *longitude* is a great circle, as they all goes through the center.

Angular Velocity:
$$ω=\frac{\theta}{t}$$
- *angular velocity* ($ω$) compares the *angle* ($\theta$) that we are sweeping out, with *time* ($t$) it takes to sweep out that angle.

Linear Velocity:
$$V=\frac{S}{t}$$
Linear Velocity ($V$) is compares the arc length ($S$) that is swept out, with *time* ($t$) it takes to sweep out that arc length.  
Rmb that: $S=r\cdot\theta$ ,if $\theta$ is in radian. So replacing the $S$:
$$V=\frac{r\cdot\theta}{t}$$
Now, rmb that: $ω=\frac{\theta}{t}$. So replacing the $ω$ here:
$$V=r\cdotω$$

Let's start with 1 revolution (1 full circle):
$\omega=\frac{2\pi RAD}{t}$
Now, how much time does it take for the Earth to rotate itself 1 full time? That'll be a day or 24 hours.
$\omega=\frac{2\pi RAD}{24hr}$
Notice that wherever we are on the sphere, the angle needed to rotate back to where we started is $2\pi$ radians. It will also take 24 hours regardless of where you are. However, you do move faster if you are near the equator.
$\omega=\frac{\pi}{12}$ Radian/Hour.

Say that we are 3000 miles away from the axis of rotation.
![[Pasted image 20240905230457.png]]
$V=r\cdot\omega$
$V=3,000mi\cdot \frac{\pi}{12} RAD/Hr$ 
Rmb that we replaced this $S=r\cdot\theta$ in this $V=\frac{S}{t}$. But  $S=r\cdot\theta$ is, in fact, $S=\frac{r\cdot\theta}{1RAD}$, but the denominator is hidden. The hidden radian unit will cancel the $RAD/Hr$ and we will get:
$V=785$ Miles/Hr.
That's the speed that we are moving due to Earth's rotation.

## Trigonometric Functions and the Unit Circle

*Trigonometric Functions* (we'll call it trig functions from now) relate an *angle* to two sides of a *right triangle*.
If we can define the way an angle relate to two sides on a right triangle, the angles will *not change* if we make a larger triangle of the same scale aka. similar triangle (Size doesn't matter, ratio does).  
![[Pasted image 20240905232014.png]]
- **Opposite** refers to the side *opposite* of the angle.
- **Hypotenuse** is the longest side.
- **Adjacent** is just a side guy.

The $sine$ function relates the *opposite* with the *hypotenuse*:
$$sin\theta=\frac{opposite}{hypotenuse}$$
$sin$ use the $y$-axis idea to define the relationship between two sides:
![[Pasted image 20240905233246.png]]

The $cosine$ function relates the *adjacent* with the *hypotenuse*:
$$cos\theta=\frac{adjacent}{hypotenuse}$$
$cos$ use the $x$-axis idea:
![[Pasted image 20240905233400.png]]

The $tangent$ function relates the *opposite* with the *adjacent*:
$$tan\theta=\frac{opposite}{adjacent}$$
Interestingly, $\frac{sin\theta}{cos\theta}=tan\theta$.
$\frac{\frac{opposite}{hypotenuse}}{\frac{adjacent}{hypotenuse}}=tan\theta$
$\frac{opposite}{\cancel{hypotenuse}}\cdot\frac{\cancel{hypotenuse}}{adjacent}=tan\theta$
$tan\theta=\frac{opposite}{adjacent}$
$tan$ relates $sin$ and $cos$ by taking the $y$ and divide by $x$:
![[Pasted image 20240905233533.png]]

Try imagine a bigger triangle of the same scale:
![[Pasted image 20240905233802.png]]
Notice that:
- $\frac{a}{c}=\frac{d}{e}=sin\theta$
- $\frac{b}{c}=\frac{f}{e}=cos\theta$
- $\frac{a}{b}=\frac{d}{f}=tan\theta$
Notice the proportionality of the whole thing. $sin,cos,tan$ simply gives the relationship between angles ($\theta$) and the sides.

So if the size of the triangle does not matter, why don't we make it easy and make a radius of one? This idea is called a unit circle:
![[Pasted image 20240905234418.png]]
Let's create another point here with an arc length $t$:
![[Pasted image 20240905235546.png]]
- if $t$ is *positive* then the arc sweep counter-clockwise.
- if $t$ is *negative* then the arc sweep clockwise.
- each $t$ creates a unique point $(x,y)$ on unit circle and a unique angle ($\theta$).
- the radius (hypotenuse) is always 1.

Rmb our formula: $S=r\cdot\theta$, if $\theta$ is in radian. Since $t$ is the arc length:
$t=r\cdot\theta$
The unit circle will always have $r=1$:
$$t=\theta$$
If the radius is 1, numerically, your *arc length* will always equal to your *central angle*.
	If this was not a unit circle, this would also no longer be true.

So, here's *another* way to look at trig functions:
Trigonometric functions relate arc length or central angle to the point $(x,y)$ *on* the circle. 
![[Pasted image 20240906004314.png]]
	I snipped this instead of writing down because I want to capture the fact that they are *reciprocal* of one another e.g. sine and cosecant.
	What's the difference between $\sin t$ and $\sin\theta$? None, not in a unit circle where they are equal. Same for all the other trig functions. I'm going to use $t$ from now on but note that they will be the same in this context.

Let's go through each of these one-by-one. Looking at the *sine* first:
![[Pasted image 20240906004743.png]]
notice that $\sin t$ and $\sin\theta$ is just $y$ in a unit circle
- Rmb that $\sin t=\frac{opposite}{hypotenuse}$.
- Notice that the hypotenuse is just the radius of the circle (in a unit circle, $r=1$).
- So: $\sin t \text{ or } \sin\theta=\frac{y}{1}=y$.
- See how it is a $y$-axis idea?

For cosine the same idea applies:
- Rmb that $\cos t=\frac{adjacent}{hypotenuse}$.
- So: $\cos t \text{ or } \cos\theta=\frac{x}{1}=x$.
- See how it is a $x$-axis idea?

For tangent:
- Rmb that $\tan t=\frac{opposite}{adjacent}$.
- Also, $\tan t=\frac{\sin t}{\cos t}$ .
- So: $\tan t=\frac{y}{x}$.

Now we're going to talk about the reciprocals.
Reciprocal of *sine* is **cosecant**:
- Rmb that $\sin t=\frac{opposite}{hypotenuse}$. 
- **Cosecant** is simply the reciprocal of that, $\csc t=\frac{hypotenuse}{opposite}$.
- So: $\csc t=\frac{1}{y}$.

Reciprocal of *cosine* is **secant**:
- Rmb that $\cos t=\frac{adjacent}{hypotenuse}$.
- **Secant** is then $\sec t=\frac{hypotenuse}{adjacent}$
- So: $\sec t=\frac{1}{x}$

Reciprocal of *tangent* is **cotangent**:
- Rmb that $\tan t=\frac{opposite}{adjacent}$.
- Also, $\tan t=\frac{\sin t}{\cos t}$ .
- **Cotangent** is then $\cot t=\frac{adjacent}{opposite}=\frac{\cos t}{\sin t}$
- So: $\cot t=\frac{x}{y}$.

![[Pasted image 20240906010017.png]]

Let's look at some examples of quadrant angles e.g. $0\degree,90\degree,180\degree$ and so on.
![[Pasted image 20240906011014.png]]
$$\theta=0$$
Notice how if $\theta=0$ our $(x,y)$ point will lies exactly at $(1,0)$. So:
- $sin0=y=0$
- $cos0=x=1$
- $tan0=\frac{y}{x} =\frac{0}{1}=0$
- $csc0=\frac{1}{0}=\text{undefined}$
- $sec0= \frac{0}{1}=0$
- $cot0=\frac{x}{y}=\frac{1}{0}=\text{undefined}$
$$\theta=\frac{\pi}{2}$$
Notice how if $\theta=\frac{\pi}{2}$ our $(x,y)$ point will lies exactly at $(0,1)$. So:
- $sin\frac{\pi}{2}=1$
- $cos\frac{\pi}{2}=0$
- $tan\frac{\pi}{2}=\text{undefined}$
- $csc\frac{\pi}{2}=\frac{0}{1}=0$
- $sec\frac{\pi}{2}=\frac{1}{0}=\text{undefined}$
- $cot\frac{\pi}{2}=\frac{x}{y}=\frac{0}{1}=0$
	- Notice how and why is not *undefined*.
$$\theta=\pi$$
Notice how if $\theta=\pi$ our $(x,y)$ point will lies exactly at $(-1,0)$. So:
- $sin\pi=0$
- $cos\pi=-1$
- $tan\pi=\frac{0}{-1}=0$
- $csc\pi=\frac{1}{0}=\text{undefined}$
- $sec\pi=\frac{1}{-1}=-1$
- $cot\pi=\frac{-1}{0}=\text{undefined}$
$$\theta=\frac{3\pi}{2}$$
Notice how if $\theta=\frac{3\pi}{2}$ our $(x,y)$ point will lies exactly at $(0,-1)$. So:
- $sin\frac{3\pi}{2}=-1$
- $cos\frac{3\pi}{2}=0$
- $tan\frac{3\pi}{2}=\frac{-1}{0}=\text{undefined}$
- $csc\frac{3\pi}{2}=\frac{0}{-1}=0$
- $sec\frac{3\pi}{2}=\frac{1}{0}=\text{undefined}$
- $cot\frac{3\pi}{2}=\frac{0}{-1}=0$

Notice how the trig functions and quadrant interacts e.g. notice that for quadrant one and two, sine is always positive since they relates to $y$-axis. There are some periodicity to them and we'll study this later.

For another example:
$$(- \frac{1}{2},\frac{\sqrt{3}}{2})$$
We can verified that this point is in the unit circle by using the Pythagorean Theorem:
$a^{2}+b^{2}=c^{2}$
$(- \frac{1}{2})^{2}+(\frac{\sqrt{3}}{2})^{2}=c^{2}$
$\frac{1}{4}+ \frac{3}{4}=c^{2}$
$c^{2}=1$
$c=1$
The hypotenuse is equal to 1, which is the same as the radius of a unit circle.
Notice that the $x$ value is negative and the $y$ value is positive. The point is in quadrant two. We can infer something from this:
- sine will be positive ($y$)
- cosine will be negative ($x$)
- tangent will be negative ($\frac{y}{x}$)
![[Pasted image 20240906013009.png]]
- $sin\theta=\frac{\sqrt{3}}{2}$
- $cos\theta=- \frac{1}{2}$
- $tan\theta=\frac{\frac{\sqrt{3}}{2}}{-\frac{1}{2}}=\frac{\sqrt{3}}{2}\cdot- \frac{2}{1}=-\sqrt{3}$
- $csc\theta=\frac{2}{\sqrt{3}}=\frac{2\sqrt{3}}{3}$
- $sec\theta=-2$
- $cot\theta=\frac{- \frac{1}{2}}{\frac{\sqrt{3}}{2}}=- \frac{1}{2}\cdot \frac{2}{\sqrt{3}}=- \frac{1}{\sqrt{3}}=- \frac{\sqrt{3}}{3}$
Notice how signs *don't* change with reciprocation.

## How to Use the Unit Circle in Trigonometry
![[Pasted image 20240906192223.png]]
- Because the radius is 1, we can relate arc length or angles (in radian) to sine ($y$) and cosine ($x$) very easily.

Let's look at some of the examples:
$$\theta=\frac{2\pi}{3} \text{ or } 120\degree$$
Find sine and cosine first, then tangent, then the reciprocal of those three (cosecant, secant, cotangent).
With $\theta=\frac{2\pi}{3} \text{ or } 120\degree$, we know that this would be in quadrant two: $x$ value is *negative* and $y$ value is *positive*.
We can use the idea of *reference angle*, which is is the angle made with the *nearest* part of the x-axis, to help determine the $(x,y)$ for $120\degree$.
![[Pasted image 20240906193355.png]]
Notice how in:
- Quadrant one, the reference angle = angle
- Quadrant two, the reference angle = $180\degree$ - angle
- Quadrant three, the reference angle = angle - $180\degree$
- Quadrant four, the reference angle = $360\degree$ - angle
Since we're in quadrant two: $180\degree-120\degree=60\degree$. This is our reference angle. 
	The reference angle helps you determine the trigonometric values by relating the given angle to a *common* acute angle whose trig values you know. ![[Pasted image 20240906195422.png]]
The **magnitude** of the sine, cosine, and tangent of an angle is the same as the magnitude of those functions for its reference angle.
	The reason why they are the same is due to the symmetry of the unit circle.
	![[Pasted image 20240906194421.png]]
	Notice the two they are similar triangle, only on different quadrant.
Since we know that $\frac{\pi}{3}$ is our reference angle and $(cos \frac{\pi}{3}, sin \frac{\pi}{3})=(\frac{1}{2},\frac{\sqrt{3}}{2})$, the magnitude of $(cos \frac{2\pi}{3}, sin \frac{2\pi}{3})$ will be the same, differing only in the signs.
So: $(cos \frac{2\pi}{3}, sin \frac{2\pi}{3})=(- \frac{1}{2},\frac{\sqrt{3}}{2})$, since it is in quadrant two.
We can skip these steps by referring to the *unit circle* (see how useful it is!)
So, back to our trig functions:
$sin \frac{2\pi}{3}=\frac{\sqrt{3}}{2}$
$cos\frac{2\pi}{3}=- \frac{1}{2}$
$tan\frac{2\pi}{3}=-\sqrt{3}$
Now their reciprocals:
$csc\frac{2\pi}{3}=\frac{2}{\sqrt{3}}=\frac{2\sqrt{3}}{3}$
$sec\frac{2\pi}{3}=-2$
$cot\frac{2\pi}{3}=- \frac{\sqrt{3}}{3}$ ^a3e5e9

$$\theta=\frac{8\pi}{3} \text{ or } 480\degree$$
Think $\frac{4}{3}\cdot2\pi\to 1+ \frac{1}{3}\cdot2\pi$. 
Rmb that $2\pi$ is a full revolution, $1+ \frac{1}{3}$ tells us that we have 1 full revolution ($360\degree$) and a $\frac{1}{3}$ of a full revolution ($120\degree$). So what we have will be equivalent to $120\degree$ (the leftover from a full revolution). Since this is done in the example above we'll skip this.

$$\theta=\frac{\pi}{4} \text{ or } 45\degree$$
Let's use the unit circle this time around.
$sin \frac{\pi}{4}=\frac{\sqrt{2}}{2}$
$cos\frac{\pi}{4}=\frac{\sqrt{2}}{2}$
$tan\frac{\pi}{4}=1$
$csc\frac{\pi}{4}=\frac{2}{\sqrt{2}}=\frac{2\sqrt{2}}{2}=\sqrt{2}$
$sec\frac{\pi}{4}=\frac{2}{\sqrt{2}}=\frac{2\sqrt{2}}{2}=\sqrt{2}$
$cot \frac{\pi}{4}=1$

$$\theta=\frac{7\pi}{6} \text{ or } 210\degree$$
Think $(1+ \frac{1}{6})\cdot\pi$. That would be $180\degree+30\degree$ or $\pi+ \frac{\pi}{6}$. This would be in quadrant three (negative $x$ and negative $y$). With $\frac{\pi}{6}$ being our reference angle:
With the angle of $30\degree$, I imagined that the $y$-side would be shorter than the $x$-side.
$sin \frac{7\pi}{6}=\frac{1}{2}$
$cos\frac{7\pi}{6}=\frac{\sqrt{3}}{2}$
$tan\frac{7\pi}{6}=\frac{1}{\sqrt{3}}=\frac{\sqrt{3}}{3}$
$csc\frac{7\pi}{6}=2$
$sec\frac{7\pi}{6}=\frac{2}{\sqrt{3}}=\frac{2\sqrt{3}}{3}$
$cot\frac{7\pi}{6}=\frac{3}{\sqrt{3}}=\sqrt{3}$

$$\theta=\frac{5\pi}{3} \text{ or } 300\degree$$
Think $(1+ \frac{2}{3})\cdot\pi$. That's $180\degree+ 120\degree$. This would be in quadrant four ($x$ is positive and $y$ is negative). Notice that $120\degree$ is our reference angle which is the same as our first example, only different in signs.
$sin \frac{5\pi}{3}=-\frac{\sqrt{3}}{2}$
$cos\frac{5\pi}{3}= \frac{1}{2}$
$tan\frac{5\pi}{3}=-\sqrt{3}$
$csc\frac{2\pi}{3}=-\frac{2\sqrt{3}}{3}$
$sec\frac{2\pi}{3}=2$
$cot\frac{2\pi}{3}=- \frac{\sqrt{3}}{3}$

Let's see an example of negative angle:
$$\theta=-\frac{3\pi}{4} \text{ or } -135\degree$$
This is equivalent to $360\degree-135\degree=225\degree$ or $2\pi- \frac{3\pi}{4}=\frac{5\pi}{4}$. This would land us in quadrant three. Notice that our reference angle is $45\degree$. 
$sin \frac{3\pi}{4}=-\frac{\sqrt{2}}{2}$
$cos\frac{3\pi}{4}=- \frac{\sqrt{2}}{2}$
$tan\frac{3\pi}{4}=1$
$csc\frac{3\pi}{4}=-\sqrt{2}$
$sec\frac{3\pi}{4}=-\sqrt{2}$
$cot\frac{3\pi}{4}=1$

Let's try some more examples:
$$tan6\pi=$$
This is 3 full revolution ($3\cdot2\pi$), so the angle is equivalent to $0\degree$. In a unit circle, this would be $(1,0)$.
$tan6\pi=\frac{sin6\pi}{cos6\pi}=\frac{0}{1}=0$

$$sec(-\pi)=$$
That's just $180\degree$ clock wise. In a unit circle, the point would be $(-1,0)$. $sec$ is a reciprocal of $cos$.
$sec(-\pi)=\frac{1}{cos(-\pi)}=\frac{1}{-1}=-1$

$$sin(45\degree)+cos(60\degree)=$$
They're all common angles.
$sin(45\degree)+cos(60\degree)=\frac{\sqrt{2}}{2}+ \frac{1}{2}=\frac{1+\sqrt{2}}{2}$

$$csc(45\degree)tan(60\degree)=$$
$csc(45\degree)=\frac{1}{sin(45\degree)}=\sqrt{2}$
$tan(60\degree)=\frac{sin(60\degree)}{cos(60\degree)}=\frac{\frac{\sqrt{3}}{2}}{\frac{1}{2}}=\sqrt{3}$
$csc(45\degree)tan(60\degree)=\sqrt{2}\cdot\sqrt{3}=\sqrt{6}$

$$3csc(\frac{\pi}{3})+cot(\frac{\pi}{4})=$$
$csc(\frac{\pi}{3})=\frac{1}{sin(\frac{\pi}{3})}=\frac{1}{\frac{\sqrt{3}}{2}}=\frac{2\sqrt{3}}{3}$ 
$cot(\frac{\pi}{4})=\frac{cos(\frac{\pi}{4})}{sin(\frac{\pi}{4})}=\frac{\frac{\sqrt{2}}{2}}{\frac{\sqrt{2}}{2}}=1$
$3csc(\frac{\pi}{3})+cot(\frac{\pi}{4})=3(\frac{2\sqrt{3}}{3})+1=1+2\sqrt{3}$

$$sin \frac{11\pi}{2}=$$
Think $\pi\cdot(5+ \frac{1}{2})$. That's 5 half revolution (or 2 and a half full revolutions or $720\degree+180\degree=900\degree$) plus $\frac{\pi}{2}$ or $90\degree$ . The leftover from full revolutions are $180\degree+90\degree=270\degree$, at which would be at $(0,-1)$ in a unit circle.
$sin \frac{11\pi}{2}=-1$

$$2sin(\frac{\pi}{4})+3tan(\frac{\pi}{4})=$$
$sin(\frac{\pi}{4})=\frac{\sqrt{2}}{2}$
$tan(\frac{\pi}{4})=1$
$2(\frac{\sqrt{2}}{2})+3(1)=3+\sqrt{2}$

In the above examples, we have the unit circle for reference since they're all fairly common angles. What if the world wasn't so kind to us?
$$sin28\degree$$
How do we even locate this? We know that this is in quadrant one but that's about it. Use a calculator (and make sure you use the right mode: Radian vs Degree).
	In your scientific calculator, press "shift" then "setup".
$sin28\degree\approx0.47$
	Notice how $sin30\degree=\frac{1}{2}=0.5$.

$$sin1\degree$$
$sin1\degree\approx0.02$
Rmb that $sin$ is a $y$-axis idea and $1\degree$ is just very slightly above the $x$-axis.

$$cot \frac{\pi}{12}$$
That's around $15\degree=\frac{1}{3}\cdot45\degree=\frac{1}{3}\cdot \frac{\pi}{4}$. Don't think we need a calculator for this one.
$cot \frac{\pi}{4}=1$
$\frac{1}{3}\cdot cot \frac{\pi}{4}=\frac{1}{3}\approx0.33$
Let's check if this is true:
$cot(\frac{\pi}{12})\approx3.73$
Well that's completely off the mark. I just went and invented my own math.
	$\frac{1}{3}\cdot cot \frac{\pi}{4}=\frac{1}{3}$ would work if cotangent *is* a linear function. It is not.

Note:  $tan^{-1}$ in your calculator is not $cot$, but the *inverse* of $tan$ function.

$$sin1$$
Notice that there is no $\degree$ sign here, this is a radian.
$sin1\approx0.84$

$$(-3,4)$$
This is clearly not in the unit circle. 
![[Pasted image 20240906213044.png]]
We can use Pythagoras Theorem to find the hypotenuse:
$(-3)^{2}+(4)^{2}=c^{2}$
$9+16=c^{2}$
$c=5$
We can now find our trig functions:
$sin\theta=\frac{4}{5}$
$cos\theta=-\frac{3}{5}$
$tan\theta=-\frac{4}{3}$
$csc\theta=\frac{5}{4}$
$sec\theta=- \frac{5}{3}$
$cot\theta=- \frac{3}{4}$
## Basic Properties of Trigonometric Functions

![[Pasted image 20240906213637.png]]
Working in a unit circle:

| Trig        | Output        | Reciprocal  | Output        |
| ----------- | ------------- | ----------- | ------------- |
| $sin\theta$ | $y$           | $csc\theta$ | $\frac{1}{y}$ |
| $cos\theta$ | x             | $sec\theta$ | $\frac{1}{x}$ |
| $tan\theta$ | $\frac{y}{x}$ | $cot\theta$ | $\frac{x}{y}$ |
From this, let's think about the [[Pre-calculus - College Algebra#Features of Graphs, Domain, Range|Domain and Range]] of these trig functions:

| $f(\theta)$ | Domain ($\theta$)                                            | Range ($f(\theta)$)                                 |
| ----------- | ------------------------------------------------------------ | --------------------------------------------------- |
| $sin\theta$ | All Real Numbers                                             | $[-1,1]$ or $-1\leq y \leq 1$                       |
| $cos\theta$ | All Real Numbers                                             | $[-1,1]$ or $-1 \leq x \leq 1$                      |
| $tan\theta$ | $\theta\neq \frac{\pi}{2},\frac{3\pi}{2},\frac{5\pi}{2},...$ | $(-\infty,\infty)$ or $-\infty <\frac{y}{x}<\infty$ |
| $csc\theta$ | $\theta\neq 0, \pi, 2\pi,...$                                | $(-\infty,-1]\cup[1,\infty)$ for $\frac{1}{y}$      |
| $sec\theta$ | $\theta\neq \frac{\pi}{2},\frac{3\pi}{2},\frac{5\pi}{2},...$ | $(-\infty,-1]\cup[1,\infty)$ for $\frac{1}{x}$      |
| $cot\theta$ | $\theta\neq 0, \pi, 2\pi,...$                                | $(-\infty,\infty)$ or $-\infty <\frac{x}{y}<\infty$ |
- Notice how the domain is not $x$, and the range is not $y$ here, unlike what we're used to in college algebra. Think input and output instead of simply $x$ and $y$.
- For *tangent*, being $\frac{y}{x}$:
	- notice how as $y$ get closer and closer to 1, $x$ get closer and closer to 0. This would make tangent ($\frac{y}{x}$) bigger and bigger up to $\infty$. This would make tangent ($\frac{y}{x}$) bigger and bigger up to $\infty$. 
	- The same principle applies in quadrant two and four where $x$ and $y$ are of different signs, making it $-\infty$. 
	This same idea applies to *cotangent* ($\frac{x}{y}$).
- For *cosecant*, being $\frac{1}{y}$:
	- as $y\to1$, $\frac{1}{y}$ approaches $\frac{1}{1}$ or $1$.
	- as $y\to0$ from the positive side, $\frac{1}{y}$ approaches $\infty$.
	- and vice versa for negative numbers ($\frac{1}{y}$ can approaches $-\infty$ or $-1$). 
	Mind you that they approaches 1 or -1, but *never* equal due to the domain issue.
	This same idea applies to *secant* ($\frac{1}{x}$).

This [interactive graph](https://www.geogebra.org/m/azzwxBPC) is very intuitive for understanding the domain and range of sine and cosine.

### Periods

Let's bring back our unit circle:
![[Pasted image 20240906192223.png]]
- There are some repeated patterns or *periodicity* here. Let's look at $sin\theta$ first.
	- Notice how as $\theta$ increase from $\frac{\pi}{6}$ up to $\frac{5\pi}{6}$, increase by $\frac{5\pi}{6}- \frac{\pi}{6}= \frac{4\pi}{6}$, the $sin\theta$ or $y$ coordinates repeats itself ($\frac{1}{2} \to \frac{1}{2}$). However, this is NOT periodicity. 
	![[Pasted image 20240906223708.png]]
		- Why? If this was a period, then say we increase the $\pi$ by $\frac{4\pi}{6}$ and would still get the same output of $sin\theta$. 
		![[Pasted image 20240906223737.png]]
		This is *not* the case. So $\frac{4\pi}{6}$ is not a period of *sine*.
	- What is want is: every single output (in case of $sin\theta$, then $y$) is repeated on this particular interval of an angle.
- For cosine, let's use the unit circle to help:
	![[Pasted image 20240906224230.png]]
	See how they are not of the same interval? Since not every single output is repeated on the same interval, we can safely say that the period is one full rotation or $2\pi$.
- For tangent:
	The period is $pi$:![[Pasted image 20240906224717.png]]
	We can check this with another number:
	$tan(\frac{\pi}{3})=\sqrt{3}$ and $tan(\frac{4\pi}{3})=\sqrt{3}$. Every single output is repeated on the interval of $pi$.
- For *cosecant* and *secant*, as they relate to *sine* and *cosine*, they share the same period.
- For *cotangent*, as they relate to *tangent*, they share the same period.

In summary:

| $f(\theta)$ | Period |
| ----------- | ------ |
| $sin\theta$ | $2\pi$ |
| $cos\theta$ | $2\pi$ |
| $tan\theta$ | $\pi$  |
| $csc\theta$ | $2\pi$ |
| $sec\theta$ | $2\pi$ |
| $cot\theta$ | $\pi$  |
From this we can say that:
$$sin(\theta+2\pi k)=sin\theta$$
$$cos(\theta+2\pi k)=cos\theta$$
$$tan(\theta+\pi k)=tan\theta$$
$$csc(\theta+2\pi k)=csc\theta$$
$$sec(\theta+2\pi k)=sec\theta$$
$$cot(\theta+\pi k)=cot\theta$$
Isn't this cool? This just says that for some $\theta$ + the period of the trig function will have the same output as the trig function of $\theta$. This will be the basis of *trigonometric identities*.

Let's try using these:
$$sin(\frac{19\pi}{2})=$$
We can keep subtracting $2\pi$ from $\frac{19\pi}{2}$:
$\frac{19\pi}{2}-2\pi\to \frac{15\pi}{2}-2\pi \to \frac{11\pi}{2} -2\pi \to \frac{7\pi}{2}-2\pi \to \frac{3\pi}{2}$
So, since 2 are subtracted 4 times:
$sin(\frac{3\pi}{2}+2\pi4)=sin(\frac{3\pi}{2})$ 
Now we only need to know what is $sin(\frac{3\pi}{2})$:
$sin(\frac{3\pi}{2})=-1$
Notice how this is very close to the idea of [[#^a3e5e9|reference angle]] discussed in the previous section.

$$csc(\frac{9\pi}{2})=$$
Understand that we can ignore the $\pi$ for now
$\frac{9}{2}-2\to \frac{5}{2}-2 \to \frac{1}{2}$
$csc(\frac{\pi}{2}+2\pi2)=csc(\frac{\pi}{2})$
$csc(\frac{\pi}{2})=1$

$$tan(\frac{19\pi}{6})$$
$\frac{19}{6}-2\to \frac{7}{6}$ 
$tan(\frac{7\pi}{6}+2\pi)=tan(\frac{7\pi}{6})$
$\frac{7\pi}{6}$ is in quadrant three (negative $x$ and negative $y$). Rmb that $(cos(\frac{7\pi}{6}),sin(\frac{7\pi}{6}))=(- \frac{\sqrt{3}}{2}, -\frac{1}{2})$
$tan(\frac{7\pi}{6})=\frac{\sqrt{3}}{3}$
Notice that we could do more subtraction:
$\frac{19}{6}-2\to \frac{7}{6}-1 \to \frac{1}{6}$
Since we do a full rotation $\frac{3}{2}$ times, $k=\frac{3}{2}$.
$tan(\frac{\pi}{6}+ 2\pi\frac{3}{2})=tan(\frac{\pi}{6})$
$tan(\frac{\pi}{6})$ will still equal $\frac{\sqrt{3}}{3}$.

$$sin(\frac{9\pi}{4})$$
$\frac{9}{4}-2\to\frac{1}{4}$
$sin(\frac{\pi}{4})=\frac{\sqrt{2}}{2}$

$$cot(\frac{17\pi}{4})$$
$\frac{17}{4}-2\to \frac{9}{4}-2 \to \frac{1}{4}$
$cot(\frac{\pi}{4})=1$

$$cos(420\degree)$$
$420\degree\to 360\degree+60\degree \to 2\pi+ \frac{\pi}{3}$
$cos(\frac{\pi}{3})= \frac{1}{2}$

$$sec(540\degree)$$
$540\degree \to 360\degree +180\degree\to 2\pi+\pi$
$sec(\pi)=\frac{1}{-1}=-1$

Professor Leonard has a *special trick* for us, for how to simplify when we have some $\theta$ over a full revolution of a circle ($>2\pi$). 
	Keep in mind that the period of $sin,cos,sec,csc$ is $P\cdot2\pi$, and $tan,cot$ is $P\cdot\pi$.
For example:
$$sin(\frac{11\pi}{2})$$
We divide $\theta$ by the period ($2\pi$ for $sin$). 
So with $\frac{11\pi}{2}\to \frac{11\pi}{2}\cdot \frac{1}{2\pi}$. Think $\frac{11}{4}$:
![[Pasted image 20240907000129.png]]
- the remainder in fraction form ($\frac{3}{4}$) tells how far it goes past the full revolution.
- the quotient tells how many times it does the full revolution (thus, it doesn't matter).
Think $\frac{8}{4}+ \frac{3}{4}=2+ \frac{3}{4}$. 
We are simply dividing our $\theta$ by our *period*. The intention is to **remove full revolutions** from the angle to get an equivalent angle within a single revolution (between $0$ and $2\pi$).
So we're left with $\frac{3}{4}$, which mean we went $\frac{3}{4}$ of the full revolution, but this is not in radian. So, $\frac{3}{4}\cdot2\pi=\frac{3\pi}{2}$.
So:
$sin(\frac{11\pi}{2})=sin(\frac{3\pi}{2})$

$$tan(6\pi)$$
Think $6\pi\cdot \frac{1}{\pi}$. Notice that we used $\pi$ instead of $2\pi$ here because $\pi$ is the period of tangent and cotangent.
We're left with $\frac{6}{1}$. The remainder here is $\frac{0}{1}$ or just 0.
$tan(6\pi)=tan(0)$

$$cos(\frac{8\pi}{3})$$
Think $\frac{8\pi}{3}\cdot \frac{1}{2\pi}= \frac{4}{3}$. The remainder here is $\frac{1}{3}$. In radian, this is $\frac{2\pi}{3}$.
$cos(\frac{8\pi}{3})=cos(\frac{2\pi}{3})$

$$sin(\frac{19\pi}{4})$$
Think $\frac{19\pi}{4}\cdot \frac{1}{2\pi}= \frac{19}{8}$. The remainder here is $\frac{3}{8}$. In radian, this is $\frac{3\pi}{4}$
$sin(\frac{19\pi}{4})=sin(\frac{3\pi}{4})$

$$tan(\frac{19\pi}{6})$$
Think $\frac{19\pi}{6}\cdot \frac{1}{\pi}=\frac{19}{6}$. The remainder here is $\frac{1}{6}$. We will multiply back the $\pi$ here instead of $2\pi$: $\frac{\pi}{6}$.
$tan(\frac{19\pi}{6})=tan(\frac{\pi}{6})$

$$cot(\frac{17\pi}{4})$$
Think $\frac{17\pi}{4}\cdot \frac{1}{\pi}= \frac{17}{4}$. The remainder here is $\frac{1}{4}$. In radian, $\frac{\pi}{4}$.

$$csc(\frac{9\pi}{2})$$
Think $\frac{9\pi}{2}\cdot \frac{1}{2\pi}=\frac{9}{4}$. The remainder here is $\frac{1}{4}$. In radian, $\frac{\pi}{2}$.
$csc(\frac{9\pi}{2})=csc(\frac{\pi}{2})$

## Reciprocal Identities in Trigonometry
![[Pasted image 20240907134935.png]]

For practice:
$$sin\theta= \frac{4}{5},cos\theta=- \frac{3}{5}$$
What's $csc\theta,sec\theta, tan\theta, cot\theta$?
The important part here is determining the quadrant (and the signs) from given information. $sin\theta$ or $y$ is positive, and $cos\theta$ or $x$ is negative. We should be in *quadrant two*.
We can think of $sin\theta=\frac{4}{5}$ (and other trig functions) as being a triangle $\frac{opposite}{hypotenuse}=\frac{4}{5}$. This one doesn't seem like it would be in a unit circle. We can think of it as being in a unit circle: $\frac{opposite}{hypotenuse}=\frac{\frac{4}{5}}{1}=\frac{0.8}{1}=\frac{4}{5}$. Notice how it does not really matter since trig functions only represent the *relationship*.
	Remember that $sin\theta$ has a [[#Basic Properties of Trigonometric Functions|Range]] of $[-1,1]$ and $\frac{4}{5}=0.8$ is within that interval. 
$csc\theta=\frac{5}{4}$, $sec\theta=- \frac{5}{3}$, $tan\theta= - \frac{4}{3}$, $cot\theta= - \frac{3}{4}$. ^ef6c88

$$sin\theta=\frac{\sqrt{3}}{2}, cos\theta=\frac{1}{2}$$
What's $csc\theta,sec\theta, tan\theta, cot\theta$?
Both $x$ and $y$ are *positive*, this must be in quadrant one. Also, this is clearly in the unit circle. $\theta$ is $\frac{\pi}{3}$. 
$csc\theta=\frac{2}{\sqrt{3}}=\frac{2\sqrt{3}}{3}, sec\theta=2, tan\theta=\sqrt{3}, cot\theta=\frac{\sqrt{3}}{3}$.

Here's a takeaway from this: You need at least 2 trig functions or 1 trig functions and the quadrant to know the signs of your $x$ and $y$.

Let's expand more on the idea on why it [[#^ef6c88|doesn't really matter if we're in the unit circle of not]]:
![[Pasted image 20240907141402.png]]
For example:
$$sin\theta= \frac{12}{13}$$
- with the information we're given:
	- $y=12$.
	- $r=13$, clearly this is not a unit circle.
	- $x$ is not given.
- would it matter if we think of this as:
	- $y=\frac{12}{13}$
	- $r=1$, this is in a unit circle.
	![[Pasted image 20240907142021.png]]
	No, it does not. Notice how the angle doesn't change (they are similar triangle).
However, to find $x$, we need to do a Pythagorean Theorem. Which one do you think looks nicer?
$x^{2}+12^{2}=13^{2}$ or $x^{2}+(\frac{12}{13})^{2}=1^{2}$
Personally, dealing with whole number is easier for me. But that's the only difference and why we would pick one over another. So:
$x^{2}+12^{2}=13^{2}$
$x^{2}+144=169$
$x^{2}=25$
$\sqrt{x^{2}}=\sqrt{25}$
Rmb, when you put on a square root on your workings, don't forget the $\pm$ sign.
$x=\pm5$
So we know that $x$ is 5 but with what sign. Does this make sense?
![[Pasted image 20240907142942.png]]
- The scaling is very off here, but get that this is *why* we have $\pm5$.
- This is why, given with only one trig function, we need a quadrant to determine the signs.
The voices in my head tell me that $\theta$ is in *quadrant two* (negative $x$ and positive $y$).
This means that $x=-5$ and $cos\theta=-\frac{5}{13}$.

Now we can even figure out the $csc\theta,sec\theta, tan\theta, cot\theta$, if we want to.
$csc\theta=\frac{13}{12},sec\theta=-\frac{13}{5},tan\theta=-\frac{12}{5}, cot\theta=-\frac{5}{12}$.

$$sec\theta=2, sin\theta<0$$
That's a weird one. But we can figure out $cos\theta$:
$cos\theta=\frac{1}{2}$
That's a familiar number. Note that we must be in either quadrant one or four, since our $x$ is positive. $sin\theta<0$ says that $y$ is negative. So we must be in quadrant four.
$x^{2}+y^{2}=r^{2}$
$1^{2}+y^{2}=2^{2}$
$y^{2}=3$
$\sqrt{y^{2}}=\pm\sqrt{3}$
$y=\pm\sqrt{3}$
Since we know that $sin\theta<0$, $y$ must be $-\sqrt{3}$.
So: $sin\theta=- \frac{\sqrt{3}}{2}$
Referring to the unit circle, we know that $\theta=\frac{5\pi}{3}$ or $300\degree$. Now, we can figure the rest of the trig functions:
$csc\theta=- \frac{2\sqrt{3}}{3}, tan\theta=-\sqrt{3}, cot\theta=- \frac{\sqrt{3}}{3}$.

## Pythagorean Identities for Trigonometric Functions

Think [[Pre-calculus - College Algebra#Properties of Functions - Even vs Odd|even vs odd]] but for trig functions.
- *even*: symmetry about the $y$ axis (opposite input gives the same output)
- *odd*: symmetry about the origin, or rotation $180\degree$ (opposite input gives the opposite output)
Rmb: with trig functions, inputs are angle and outputs are $(x,y)$ coordinates.
![[Pasted image 20240906192223.png]]
- "$x$"
	- Look at $cos(-\theta)$
		- notice how opposite input (say, $\frac{\pi}{6}$ and $- \frac{\pi}{6}$ or $\frac{11\pi}{6}$) gives the same output (the $x$ coordinate, which is $cos(\frac{\pi}{6})=\frac{\sqrt{3}}{2}$ and $cos(- \frac{\pi}{6})=\frac{\sqrt{3}}{2}$ ).
		- This means that $cos(-\theta)=cos(\theta)$, making it an *even* function.
	- What about secant? Think $sec(-\theta)$. 
		- Secant is the *reciprocal* of cosine. Say, $sec(\frac{\pi}{6})=\frac{2}{\sqrt{3}}=sec(- \frac{\pi}{6})$.
		- So, $sec(-\theta)=sec(\theta)$. This is also an *even* function.
		- This is only true when secant $sec(-\theta)$ or $sec(\theta)$ is not undefined (divided by 0).
- "$y$"
	- Look at $sin(-\theta)$.
		- Notice how $sin(\frac{\pi}{6})=\frac{1}{2}$ but $sin(- \frac{\pi}{6})= - \frac{1}{2}$. Opposite input gives the opposite output.
		- So, $sin(-\theta)=-sin(\theta)$. This is the definition of *odd* function.
	- Look at $csc(\theta)$.
		- Since it is the reciprocal of sine. $csc(-\theta)=-csc(\theta)$ 
		- This is also an *odd* function. 
- $\frac{y}{x}$ or $\frac{x}{y}$
	- Look at $tan(-\theta)$.
		- Tangent takes an even function and divide it with an odd function. Say, $tan(- \frac{\pi}{6})=-\sqrt{3}$ and $tan(\frac{\pi}{6})=\sqrt{3}$. This shows that odd prevails. 
		- $tan(-\theta)=-tan(\theta)$
	- Look at $cot(-\theta)$
		- This is just a reciprocal of tangent. $cot(-\theta)=-cot(\theta)$.
		- This is also an *odd* function.

To summarize:

| Even $f(-\theta)=f(\theta)$ | Odd $f(-\theta)=-f(\theta)$ |
| --------------------------- | --------------------------- |
| $cos(-\theta)=cos(\theta)$  | $sin(-\theta)=-sin(\theta)$ |
| $sec(-\theta)=sec(\theta)$  | $csc(-\theta)=-csc(\theta)$ |
|                             | $tan(-\theta)=-tan(\theta)$ |
|                             | $cot(-\theta)=-cot(\theta)$ |
- notice how functions related to $x$ coordinate are even functions, while functions related to $y$ coordinate are odd functions.
- Tangent and cotangent are also odd functions.

For example:
$$cos(-30\degree)=cos(30\degree)$$
$cos(30\degree)=\frac{\sqrt{3}}{2}$
$$sin(-60\degree)=-sin(60\degree)$$
$-sin(60\degree)=- \frac{\sqrt{3}}{2}$
$$csc(- \frac{\pi}{6})=-csc(\frac{\pi}{6})$$
$-csc(\frac{\pi}{6})=-2$
$$sec(-30\degree)=sec(30\degree)$$
$sec(30\degree)=\frac{2\sqrt{3}}{3}$
$$tan(- \frac{\pi}{4})=-tan(\frac{\pi}{4})$$
$-tan(\frac{\pi}{4})=-1$

Let's take a look at the equation of a circle:
$$x^{2}+y^{2}=r^{2}$$
However, in a unit circle, since $r=1$:
$$x^{2}+y^{2}=1^{2}$$
Let's focus on the one in a unit circle:
We know that $sin\theta=y$ and $cos\theta=x$. So:
$(cos\theta)^{2}+(sin\theta)^{2}=1$
Notice how this is not written as $cos\theta^{2}+sin\theta^{2}$, since this looks like the angle being squared instead of the whole thing. We can however write it as:
$$cos^{2}\theta+sin^{2}\theta=1$$
This is the idea behind the **Pythagorean Identities**. We can manipulate this as:
- $sin^{2}\theta=1-cos^{2}\theta$
- $cos^{2}\theta=1-sin^{2}\theta$
![[Pasted image 20240907221845.png]]
Let's go through these:
$sin^{2}\theta+cos^{2}\theta=1$
Let's try dividing all the terms by $sin^{2}\theta$:
$\frac{sin^{2}\theta}{sin^{2}\theta}+ \frac{cos^{2}\theta}{sin^{2}\theta}=\frac{1}{sin^{2}\theta}$
This simplifies to:
$$1+cot^{2}\theta=csc^{2}\theta$$
- We can manipulate this as:
	- $cot^{2}\theta=csc^{2}\theta-1$
	- $csc^{2}\theta-cot^{2}\theta=1$

Another one:
$sin^{2}\theta+cos^{2}\theta=1$
However, this time, divide by $cos^{2}\theta$:
$\frac{sin^{2}\theta}{cos^{2}\theta}+ \frac{cos^{2}\theta}{cos^{2}\theta}=\frac{1}{cos^{2}\theta}$
This simplifies to:
$$tan^{2}\theta+1=sec^{2}\theta$$
- We can manipulate this as:
	- $tan^{2}\theta=sec^{2}\theta-1$
	- $sec^{2}\theta-tan^{2}\theta=1$

For example:
$$tan(- \frac{37\pi}{4})$$
Let's reduce the angle down to within $[0,2\pi]$:
Since tangent has a period of $\pi$, $-\frac{37\pi}{4}\cdot \frac{1}{\pi}=-\frac{37}{4}$. This has a remainder of $-\frac{1}{4}$. Multiply back the $\pi$, and we get $- \frac{\pi}{4}$. 
We know that $tan(-\theta)=-tan(\theta)$. So:
$tan(- \frac{\pi}{4})=-tan(\frac{\pi}{4})=-1$

$$sin^{2}(40\degree)+cos^{2}(40\degree)$$
This looks familiar. $cos^{2}\theta+sin^{2}\theta=1$, regardless of what $\theta$ is. So:
$sin^{2}(40\degree)+cos^{2}(40\degree)=1$

$$sec^{2}(18\degree)-tan^{2}(18\degree)$$
This looks familiar. $sec^{2}\theta-tan^{2}\theta=1$, regardless of what $\theta$ is. So:
$sec^{2}(18\degree)-tan^{2}(18\degree)=1$

$$tan(\frac{\pi}{4})- \frac{sin(\frac{\pi}{4})}{cos(\frac{\pi}{4})}$$
$tan(\frac{\pi}{4})-tan(\frac{\pi}{4})=0$

$$sec(- \frac{\pi}{18})cos(\frac{37\pi}{18})$$
Let's reduce the angle down first:
$\frac{-\pi}{18}$ is already small, so that's fine. The other one should be reduced: $\frac{37\pi}{18}\cdot \frac{1}{2\pi}=\frac{37}{36}$. This has a remainder of $\frac{1}{36}$. We multiply back the $2\pi$, to be $\frac{1}{36}\cdot2\pi=\frac{\pi}{18}$.
So,$cos(\frac{37\pi}{18})=cos(\frac{\pi}{18})$.
We know that secant is an even function so:
$sec(- \frac{\pi}{18})=sec(\frac{\pi}{18})=\frac{1}{cos(\frac{\pi}{18})}$
So:
$\frac{1}{\cancel{cos(\frac{\pi}{18})}}\cdot \cancel{cos(\frac{\pi}{18})}=1$

$$\frac{sin(-20\degree)}{cos(380\degree)}+tan(20\degree)$$
We know that $cos(380\degree)=cos(20\degree)$, since $360\degree$ is the period of cosine.
We know that $sin(-20\degree)=-sin(20\degree)$, since it is an odd function.
Putting those together, we have $- sin\frac{20\degree}{cos(20\degree)}=-tan(20\degree)$.
So:
$-tan(20\degree)+tan(20\degree)=0$

## The Graphs of Sine and Cosine

I think this [interactive graph](https://www.geogebra.org/m/azzwxBPC) on GeoGebra is one of the best way to learn this intuitively. But below is an additional note on the back-end of it all.
### Graph of Sine
Most of the confusion here come from confusing between input and output with $x$ and $y$, since we used them interchangeably in college algebra.
- Our input for sine is angle or $\theta$, as seen in the $x$-axis here.
- Our output is the $y$ coordinate *on the unit circle*. 
![[Pasted image 20240907231019.png]]
Comparing this to the unit circle:
![[Pasted image 20240907231304.png]]
- note that the $(x,y)$ coordinate jotted down in the sine graph is a reference point to the unit circle, NOT the coordinate of the graph itself e.g. $(0,1)$ is actually $(\frac{\pi}{2},1)$.
- $x$ (represent arc length or angle) is a real number line, it goes on forever $(-\infty,\infty)$.
- $f(x)$ can only be within $[-1,1]$.

Let's summarize:
- **Domain**: All real numbers.
- **Range**: $[-1,1]$
- Sine function is an **odd function**.
	![[Pasted image 20240907231902.png]]
	This is how it'll look if we extend the graph to $-x$. Notice how we can find symmetry if the graph is rotated $180\degree$.
- **Period**: $2\pi$
	![[Pasted image 20240907232253.png]]
	Notice how all output repeats itself uniformly only after $2\pi$.
- **$x$-intercept**: $\pi, 2\pi, 3\pi, ...$ or every $k\pi$, with $k$ being a whole number.
	- Notice how $x$-intercepts are always *crosses*, not *bounces*.
	- Sine crosses $x$-axes at the *end* and the *center* of a period ($2\pi$), and peaks at *quarters* of period.
Let's note our **key points**:
- $(0,0)$
- $(\frac{\pi}{2},1)$
- $(\pi,0)$
- $(\frac{3\pi}{2},-1)$
- $(2\pi,0)$
See how sine crosses $x$-axes at the *end* and the *center* of a period ($2\pi$), and peaks at quarters of period?
### Graph of Cosine
To align our understanding (Don't get this confused!):
- Our input for sine is angle or $\theta$, as seen in the $x$-axis here.
- Our output is the $x$ coordinate *on the unit circle*. 
![[Pasted image 20240907234302.png]]
Comparing this to the unit circle:
![[Pasted image 20240907234844.png]]
- Once again, note that the $(x,y)$ coordinate jotted down in the cosine graph is only a reference point to the unit circle.
- $x$ (represent arc length or angle) is a real number line, it goes on forever $(-\infty,\infty)$.
- $f(x)$ can only be within $[-1,1]$.
- Notice that this looks very similar to the [[#Graph of Sine|sine graph]]. In fact, it is just sine graph *phase shifted*.

Let's summarize:
- Domain: All real numbers.
- Range: $[-1,1]$
- Cosine graph is an **even function**.
	![[Pasted image 20240907235326.png]]
	Expanded, this is how cosine looks. Notice the symmetry about the $y$-axis.
- **Period**: $2\pi$
- **$x$-intercept**: $\frac{\pi}{2}, \frac{3\pi}{2}, \frac{5\pi}{2},...$ or every $\frac{\pi}{2}+k\pi$, with $k$ being a whole number.
	- Cosine crosses $x$-axes at the *quarter* of a period ($2\pi$), and peaks at the *end* or the *center* of period.
	- See how this is the opposite of what we have with sine?

Let's note our **key points**:
- $(0,1)$
- $(\frac{\pi}{2},0)$
- $(\pi,-1)$
- $(\frac{3\pi}{2},0)$
- $(2\pi,1)$
## Graphing Transformation with Sine and Cosine

See this [interactive graph](https://www.geogebra.org/m/UtrFEW4k) showing $sin,cos,tan$ transformations. 

$$y=Asin(\omega x)+B$$
$$y=Acos(\omega x)+B$$
Steps:
1. Period: $T=\frac{2\pi}{\omega}$
2. $B$ = vertical shift
3. Mark $x$-intercepts.
4. Multiply **key points** by $A$ (Amplitude = $|A|$)

For example:
$$y=3sin x$$
1. Determine the period. In this case, $\omega=1$, so the period is still $2\pi$.
	First thing to do, when we got our period (that came off wrong), is to mark down your period, then cut it in half ($2\pi$, cut down is $\pi$).
	![[Pasted image 20240908142514.png]]
	Since the key points of sine graph are in the quarters, the center, and the end of the period, we'll cut each of the portion in half again.
	![[Pasted image 20240908142711.png]]
2. No vertical shift.
3. Mark $x$-int.
	![[Pasted image 20240908142731.png]]
	With a sine graph, x-intercepts would be at every multiples of $\pi$ (or $k\pi$). However, transformed, this may not be the case. What *is the case* is that $x$-intercepts happen at *the beginning, the end, and the center* of your period.
4. Multiply **key points** by $A$ (Amplitude = $|A|$)
	Since we've already marked down our $x$-intercept, we're left with:
	Key points:
	- $(\frac{\pi}{2},1)\to(\frac{\pi}{2},3)$
	- $(\frac{3\pi}{2},-1)\to(\frac{3\pi}{2},-3)$
![[Pasted image 20240908143327.png]]![[Pasted image 20240908143622.png]]

$$y=-4cosx$$
1. Period: $T=2\pi$ (since $\omega=1$).
	![[Pasted image 20240908143819.png]]
2. No vertical shift.
3. Mark down $x$-intercepts.
	![[Pasted image 20240908143928.png]]
4. Key points:
	- $(0,1)\to(0,-4)$
	- $(\pi,-1)\to(\pi,4)$
	- $(2\pi,1)\to(2\pi,-4)$
	![[Pasted image 20240908144127.png]]
![[Pasted image 20240908144155.png]]![[Pasted image 20240908144241.png]]

$$y=sin(3x)$$
1. Period: $T=\frac{2\pi}{3}$.
	The $x$-axis should have a tick marks of: $0,\frac{\pi}{6}, \frac{\pi}{3}, \frac{\pi}{2}, \frac{2\pi}{3}$.
	Notice how $\omega>1$, *compresses* the graph horizontally.
2. No vertical shift.
3. Mark $x$-intercept.
	Rmb, sine graph has $x$-intercepts at the ends, and the center of your period. 
4. Key points:
	- $(\frac{\pi}{6},1)$
	- $(\frac{\pi}{2},-1)$
	Peaks happen at the quarter for sine functions. Why aren't we multiplying anything? Because we've already dealt with the horizontal compression since step one.
With x-axis up to $\frac{2\pi}{3}$:
![[Pasted image 20240908145729.png]]
With x-axis up to $2\pi$:
![[Pasted image 20240908145724.png]]
	See the horizontal compression?

What if we have $y=sin(-3x)$ instead?
Understand that sine is an *odd* function, so: $sin(-\theta)=-sin(\theta)$.
- We are not factoring out the $-1$ here, just using the property of odd functions (don't get this confused!)
So: $y=-sin(3x)$.
- We'll still has $\omega=3$, resulting in period of $T=\frac{2\pi}{3}$.
- However, $A=-1$ which is a reflection about $y$-axis.
![[Pasted image 20240908150306.png]]

$$y=cos(-2x)$$
1. Period: 
	Since cosine is an *even* function: $cos(-\theta)=cos(\theta)$. Opposite input gives the same output.
	$cos(-2x)=cos(2x)$
	From the latter, our period is $T=\frac{2\pi}{2}=\pi$.
	Our x-axis should have the following tick marks: $0, \frac{\pi}{4},\frac{\pi}{2}, \frac{3\pi}{4}, \pi$.
2. No vertical shift.
3. $x$-intercept.
	Cosine function has $x$-intercepts at the quarters. So, at $\frac{\pi}{4}, \frac{3\pi}{4}$.
4. Key points:
	- $(0,1)$
	- $(\frac{\pi}{2},-1)$
	- $(\pi,1)$
![[Pasted image 20240908152118.png]]

$$y=-2sin(\frac{x}{8})$$
1. Period.
	$\omega=\frac{1}{8}$. So, $T=\frac{2\pi}{\frac{1}{8}}=16\pi$. Notice how $0<\omega<1$, would horizontally stretch the graph.
	So the tick marks on our $x$-axis would be: $0,4\pi,8\pi,12\pi,16\pi$.
2. No vertical shift.
3. $x$-intercept.
	Sine functions have $x$-intercepts at the ends, and the center of the period. So: $0, 8\pi, 16\pi$.
4. Key points:
	- $(4\pi,1)\to(4\pi,-2)$
	- $(12\pi,-1)\to(4\pi,2)$
![[Pasted image 20240908153503.png]]
	Notice the **horizontal stretch** and a **vertical stretch**.

$$y=3cos(4x)+1$$
1. Period:
	$\omega=4$. So, $T=\frac{2\pi}{4}=\frac{\pi}{2}$.
	So, our $x$-axis tick marks should be: $0,\frac{\pi}{8},\frac{\pi}{4},\frac{3\pi}{8},\frac{\pi}{2}$.
2. Vertical shift.
	We have a vertical shift up of $1$.
	![[Pasted image 20240908154504.png]]
3. Mark $x$-intercepts.
	Since cosine has its $x$-intercepts at the quarter of the period. So, at $\frac{\pi}{8}, \frac{3\pi}{8}$.
	![[Pasted image 20240908154731.png]]
4. Key points:
	- $(0,1)\to(0,3)$
	- $(\frac{\pi}{4},-1)\to(\frac{\pi}{4},-3)$
	- $(\frac{\pi}{2},1\to(\frac{\pi}{2},3)$
	Note that these are only reference points and we have to adjust them for the vertical shift.
	![[Pasted image 20240908155136.png]]
![[Pasted image 20240908155205.png]]
![[Pasted image 20240908155420.png]]

### More examples
$$y=4sin(\frac{\pi}{2}x)-2$$
1. Period.
	$\omega=\frac{\pi}{2}$, so $T=\frac{2\pi}{\frac{\pi}{2}}=4$.
	Since $\pi$ is cancelled, our $x$-axis would have: $0,1,2,3,4$.
2. Vertical shift.
	We have a vertical shift down by 2.
3. $x$-intercept.
	With sine function, we have $x$-intercepts at the ends and the center of our period. So, at: $0,2,4$.
4. Key points:
	- $(1,1)\to(1,4)$
	- $(3,-1)\to(3,-4)$
![[Pasted image 20240908170221.png]]
![[Pasted image 20240908170339.png]]

$$y=-3cos(\frac{\pi}{4}x)+2$$
1. Period.
	With $\omega=\frac{\pi}{4}$, $T=\frac{2\pi}{\frac{\pi}{4}}=8$.
	Understand that $\frac{\pi}{4}<1$, so this is a *horizontal stretch*.
	Since $\pi$ is cancelled, our $x$-axis would have: $0,2,4,6,8$.
2. Vertical shift.
	We have a vertical shift up by 2.
3. $x$-intercept.
	Cosine has x-ints at the quarters of the period. So, at: $2,6$.
4. Key points:
	- $(0,1)\to(0,-3)$
	- $(2,-1)\to(2,3)$
	- $(8,1)\to(8,-3)$
![[Pasted image 20240908171217.png]]

$$Amp.=3, T=4\pi$$
- $Amp.$ stands for Amplitude or $|A|$.
- $T$ stands for period.
Find $y=Asin(\omega x)$
Working this backwards:
$|A|=3$
$|A|=\pm3$
We don't know if the graph is reflected or not. In such case, just assume $A=Amp.$
$4\pi=\frac{2\pi}{\omega}$
$\omega=\frac{1}{2}$
From that, we got:
$y=3sin(\frac{x}{2})$
![[Pasted image 20240908172007.png]]

## How to Graph Tangent and Cotangent

See [this](https://www.geogebra.org/m/f72Ddztf) interactive graph for *tangent* and [this](https://www.geogebra.org/m/ueUcqGNG) for *cotangent*.
### Graph of Tangent

$$tan\theta=\frac{y}{x}$$
- Rmb that, in a unit circle, if $\theta=0,\pi,2\pi,...$ or $k\pi$ ($k$ being whole number), $x$ will equal to 1 or -1 and $y$ will equal to 0, making those angles the $x$-intercepts.
	![[Pasted image 20240908185826.png]]
- Now, with tangent and cotangent, we can have some *undefined* output with $x=0$, which happens at $\theta=\frac{\pi}{2}, \frac{3\pi}{2},...$  or $\frac{\pi}{2}+k\pi$. 
	- These are [[Pre-calculus - College Algebra#Finding Vertical Asymptotes of Rational Functions|vertical asymptotes]] (tangent and cotangent are rational functions).
	![[Pasted image 20240908191102.png]]
- As we know, there are a few ways the graph interact with vertical asymptotes, as governed by the multiplicity:
	With $tan\theta=\frac{y}{x}$, get that this an *odd* multiplicity on the vertical asymptote.![[Pasted image 20240818142530.png]]
	We only need to find, which direction of odd multiplicity.
	We know that $tan(\frac{\pi}{4})=1$ and that is an odd function, so $tan(- \frac{\pi}{4})=-tan(\frac{\pi}{4})=-1$:
	
	With this we can sketch the direction of the graph:
	![[Pasted image 20240908191020.png]]
- Notice that we always have something + $k\pi$ for some repeated output e.g. $y=0$, $y=undefined$. This is because tangent has a period of $\pi$ (instead of $2\pi$.) So, from the above, the pattern repeats with every period:
	![[Pasted image 20240908191330.png]]
	- notice that, for every period, $x$-intercept sits at the center, vertical asymptotes is at the end of the period. The 1 and -1 is at quarters of the period.
	Let's take another look at the unit circle to see why the period for tangent is $\pi$:![[Pasted image 20240908191424.png]]
	- Notice how in quadrant one we have $\frac{+y}{+x}$, and in quadrant three we have $\frac{-y}{-x}$. In both of these quadrants, they will output a *positive* tangent.
	- In quadrant two we have $\frac{+y}{-x}$, and in quadrant four we have $\frac{-y}{+x}$. In both of these quadrants, they will output a *negative* tangent.
![[Pasted image 20240908191926.png]]
- This looks a lot like *cubic* functions.

Let's summarize:
- **Domain**: $x\neq \frac{\pi}{2}+k\pi$
- **Range**: $(\infty,\infty)$
- Tangent is an **odd** function.
- **Period**: $\pi$
- **Vertical Asymptote** @ *end* of period.
- **$x$-intercept** @ *center* of period.
- -1 and +1 @ *quarters* of period.
### Graph of Cotangent

$$cot\theta=\frac{x}{y}$$
- Rmb that cotangent is a reciprocal of tangent: $\frac{0}{1}\to \frac{1}{0}$ and $\frac{1}{0}\to \frac{0}{1}$. This means that the $x$-intercepts in tangent become vertical asymptotes (undefined) in cotangent, and vertical asymptotes in tangent becomes $x$-intercepts in cotangent.
	- $\theta=0,\pi,2\pi,...$ or $k\pi$ are the vertical asymptotes.
	- $\theta=\frac{\pi}{2}, \frac{3\pi}{2},...$  or $\frac{\pi}{2}+k\pi$ are the $x$-intercepts.
	![[Pasted image 20240908200350.png]]
- Note that $cot(\frac{\pi}{4})=tan(\frac{\pi}{4})=1$ and $cot(-\frac{\pi}{4})=tan(-\frac{\pi}{4})=-1$ ($\frac{1}{1}$ still reciprocates to $1$.) 
	![[Pasted image 20240908200656.png]]
	The points are the same as in tangent, but the vertical asymptotes and $x$-intercepts moved. 
![[Pasted image 20240908200846.png]]

In summary:
- **Domain**: All real numbers
- **Range**: $(-\infty,\infty)$
- Cotangent is an **odd** function.
- Period: $\pi$
- **Vertical Asymptote** @ *end* of period.
- **$x$-intercept** @ *center* of period.
- **+1 and -1** @ *quarters* of period (but they are in reverse order compared to tangent, which has -1 then +1 from left to right, due to the changes to V.A.s and x-intercepts).
## Graphing Transformation with Tangent and Cotangent

$$y=Atan(\omega x)+B$$
$$y=Acot(\omega x)+B$$
- Period: $T=\frac{\pi}{\omega}$.
	- tangent has angle of 0 in the center of period ($x$-intercepts).
	- cotangent "starts" at angle of 0.
- V.A.s at the ends of period.
- Key points (-1, +1) at the quarters of period.
For examples:
$$y=3tanx$$

Period: $T= \frac{\pi}{1}=\pi$.
With tangent, although we have a period of $\pi$, the graph centers around "0" or the $y$-axis. If we went from $(-\pi,\pi)$ as we did with sine and cosine, that would total 2 periods ($\pi+(-\pi)=2\pi$) instead of desired 1. So, we divide what we got by 2 and we'll have tick marks to the right ($\frac{\pi}{2}$) and to the left ($- \frac{\pi}{2}$) ($\frac{\pi}{2}-(- \frac{\pi}{2})=\pi$).
![[Pasted image 20240908203903.png]]
Now we can add some key features:
Rmb that, for tangent, we have V.A.s at the *ends* of the period.
![[Pasted image 20240908204106.png]]
Rmb that tangent *climbs* within its period ($tan(- \frac{\pi}{4})=-1$ and $tan(\frac{\pi}{4})=1$).
![[Pasted image 20240908204346.png]]
Rmb that tangent has its $x$-intercepts at the *center* of its period.
 ![[Pasted image 20240908204439.png]]
 However, we have $A=3$ which would vertically stretch the graph. Let's mark our key points:
 - $(- \frac{\pi}{4},-1)\to (- \frac{\pi}{4},-3)$
 - $(\frac{\pi}{4},1)\to (\frac{\pi}{4},3)$
Since there is no vertical or horizontal shift, we can use this as actual coordinates.
 ![[Pasted image 20240908204901.png]]
 Repeating this with other periods:
 ![[Pasted image 20240908205016.png]]
![[Pasted image 20240908210716.png]]

$$y=-2tan(3x)+1$$
1. Period.
	$T=\frac{\pi}{3}$ (the denominator of 3 horizontally compresses the graph). Divide that by 2 and we have $- \frac{\pi}{6}$ on the left and $\frac{\pi}{6}$ on the right.
	 ![[Pasted image 20240908205805.png]]
	 Add V.A.s:
	 ![[Pasted image 20240908205902.png]]
2. Vertical shift.
	We have a vertical shift of +1.
	![[Pasted image 20240908205946.png]]
3. $x$-intercepts.
	For tangent, these will sit on the middle of the period.
	![[Pasted image 20240908210058.png]]
4. Key points:
	Rmb that tangent *climbs* (-1 then +1) but since $A=-2$, there will be a reflection.
	- $(-\frac{\pi}{12},-1)\to(-\frac{\pi}{12},2)$
	- $(\frac{\pi}{12},1)\to(\frac{\pi}{12},-2)$
	Rmb that these points are only relative to our new origin, which was shifted up by 1.
	![[Pasted image 20240908210338.png]]
![[Pasted image 20240908210523.png]]
![[Pasted image 20240908211030.png]]

$$y=3cot(\frac{1}{2}x)-2$$
Let's go through these one quickly:
1. Period
	$T=\frac{\pi}{\frac{1}{2}}=2\pi$.
	Rmb that cotangent starts at 0, much like sine and cosine. This is not some math law, it just helps us see the graph the make it easy to sketch.
	So think $0$ as the beginning of period and $2\pi$ at the end of period.
	![[Pasted image 20240908213107.png]]
	Adding our V.A.s:
	![[Pasted image 20240908213148.png]]
2. Vertical shift.
	We have a shift down by 2.
	![[Pasted image 20240908213212.png]]
1. $x$-intercepts.
	These are at the center of our period. 
	![[Pasted image 20240908213316.png]]
4. Key points:
	Rmb that cotangent falls (+1 then -1 from left-to-right)
	- $(-\frac{\pi}{2},1)\to(-\frac{\pi}{2},3)$
	- $(\frac{\pi}{2},-1)\to(\frac{\pi}{2},-3)$
![[Pasted image 20240908213540.png]]
![[Pasted image 20240908214816.png]]

$$y=-cot(\frac{\pi}{4}x)+1$$
1. Period.
	$T=\frac{\pi}{\frac{\pi}{4}}=4$. This is a slight horizontal stretch ($\frac{\pi}{4}<1$).
	Rmb that cotangent starts at 0.
1. Vertical shift.
	We have a shift up by 1.
3. $x$-intercept.
	At the center of the period (in this case, at $x=2$). 
4. Key points:
	With $A=-1$, and cotangent being a falling graph.
	- $(1,1)\to(1,-1)$
	- $(3,-1)\to(3,1)$
![[Pasted image 20240908215706.png]]
## How to Graph Cosecant and Secant

Since they are reciprocals of [[#The Graphs of Sine and Cosine|sine and cosine]], they will relate a lot to one another.
### The Graph of Cosecant

Let's look at the graph of sine first:
![[Pasted image 20240909181346.png]]
Let's look at the peaks first:
$sin(\frac{\pi}{2})=1$, so $csc(\frac{\pi}{2})=\frac{1}{1}=1$
$sin(- \frac{\pi}{2})=-1$, so $csc(\frac{-\pi}{2})=\frac{1}{-1}=-1$
$sin(\frac{3\pi}{2})=-1$, so $csc(\frac{3\pi}{2})=\frac{1}{-1}=-1$
$sin(-\frac{3\pi}{2})=1$, so $csc(-\frac{3\pi}{2})=\frac{1}{1}=1$
![[Pasted image 20240909181717.png]]
Next, let's look at the $x$-intercept of sine:
$sin(0)=0$, so $csc(0)=\frac{1}{0}=undefined$. That's a vertical asymptote.
$sin(\pi)=0$, so $csc(\pi)=\frac{1}{0}=undefined$. 
In fact, wherever in the sine function is the $x$-intercepts located (every $k\pi$), there would be a vertical asymptote in the cosecant function:
![[Pasted image 20240909182209.png]]
The only thing left that we should to consider here are when $sin(\theta)= \frac{1}{2}$.
$sin(\frac{\pi}{6})=\frac{1}{2}$, so $csc(\frac{\pi}{6})=\frac{2}{1}=2$
$sin(-\frac{\pi}{6})=-\frac{1}{2}$, so $csc(-\frac{\pi}{6})=-\frac{2}{1}=-2$
$sin(\frac{5\pi}{6})=\frac{1}{2}$, so $csc(\frac{5\pi}{6})=\frac{2}{1}=2$
$sin(-\frac{5\pi}{6})=-\frac{1}{2}$, so $csc(-\frac{5\pi}{6})=-\frac{2}{1}=-2$
And so on...
![[Pasted image 20240909183122.png]]
And there we have it:
![[Pasted image 20240909183236.png]]
Without the sine graph:
![[Pasted image 20240909183332.png]]
- Notice how the line does not cross the 1 or -1 at all. This is because cosecant is based on $\frac{1}{sin(x)}$, and that the output of $sin(x)$ is always within $[-1,1]$. 

Let's summarize:
- **Domain**: $x\neq k\pi$
- **Range**: $(-\infty,-1]\cup[1,\infty)$
- **Period**: $2\pi$
- **Key points**:
	Rmb that all vertical asymptotes is on the $x$-intercepts of $sinx$. It is encouraged that we draw $sinx$ *first* before drawing the $cscx$.
### Graph of Secant

Rmb that cosine is a phase shifted version of sine, so secant is also a phase shifted version of cosecant too.
![[Pasted image 20240909184157.png]]
Similar to what we have in cosecant, reciprocal of $\frac{1}{1}$ or $- \frac{1}{1}$ will still be $1$ and $-1$ respectively.
![[Pasted image 20240909184323.png]]
The $x$-intercepts means that the output is 0. So the reciprocal of that is *undefined* or a vertical asymptote.
![[Pasted image 20240909184538.png]]
We also want to look where $cosx=\frac{1}{2}$.
$cos(\frac{\pi}{3})=\frac{1}{2}$, so $sec(\frac{\pi}{3})=2$
$cos(\frac{\pi}{3})=\frac{1}{2}$, so $sec(\frac{\pi}{3})=2$
And since this is an even function:
$cos(-\frac{\pi}{3})=\frac{1}{2}$, so $sec(-\frac{\pi}{3})=2$
![[Pasted image 20240909185003.png]]
Completing our graph:
![[Pasted image 20240909185038.png]]
![[Pasted image 20240909185101.png]]

To summarize:
- **Domain**: $\frac{\pi}{2}+k\pi$
- **Range**: $(-\infty,-1]\cup[1,\infty)$
- **Period**: $2\pi$
- **Key points**:
	Rmb that all vertical asymptotes is on the $x$-intercepts of $\cos x$. It is encouraged that we draw $\sin x$ *first* before drawing the $\sec x$.
### Transformations with Cosecant and Secant

The general idea is, pretend that we are dealing with sine and cosine for now, then reciprocate it.
$$y=4sec(\frac{1}{2}x)$$
We'll first treat this as a cosine graph.
- Period
	$T=\frac{2\pi}{\frac{1}{2}}=4\pi$.
	Our $x$-axis should have: $0,\frac{\pi}{2},\frac{3\pi}{2},4\pi$.
- There is no vertical shift.
- $x$-intercepts.
	Secant does not have $x$-intercepts, but cosine does, and they sit on the quarters of period. So, at: $\frac{\pi}{2}$ and $\frac{3\pi}{2}$.
- Key points
	- $(0,1)\to(0,4)$
	- $(2\pi,-1)\to(2\pi,-4)$
	- $(4\pi,1)\to(4\pi,4)$
![[Pasted image 20240909200510.png]]
- Reciprocate
	- V.A.s at $\frac{\pi}{2}$ and $\frac{3\pi}{2}$.
	![[Pasted image 20240909200554.png]]
	![[Pasted image 20240909200716.png]]![[Pasted image 20240909200945.png]]

$$y=-2csc(\frac{2\pi}{3}x)-2$$
Treat this as a sine graph.
- Period.
	$T=\frac{2\pi}{\frac{2\pi}{3}}=3$.
	Our $x$-axis should have: $0,\frac{3}{4},\frac{3}{2},\frac{9}{4},3$.
- Vertical shift.
	This has a vertical shift down by 2.
- $x$-intercepts.
	These sit on the ends and the center of period. So, at: $0, \frac{3}{2}, 3$.
- Key points:
	- $(\frac{3}{4},1)\to(\frac{3}{4},-2)$
	- $(\frac{9}{4},-1)\to(\frac{9}{4},2)$
	![[Pasted image 20240909202421.png]]
- Reciprocate
	- $x\text{-ints}\to \text{Vertical Asymptotes}$
	![[Pasted image 20240909202608.png]]
![[Pasted image 20240909204915.png]]
## How to Graph Phase Shifts of Trigonometric Functions

*Phase shift* is a [[Pre-calculus - College Algebra#Analogy for Horizontal Shifting|horizontal shift]] along the $x$-axis for trig functions.
- $f(x-h)$ shift *right*.
- $f(x+h)$ shift *left*.
Steps:
1. Vertical shift.
2. Phase shift (coefficient of $x$ must be 1).
3. Period (*add* to phase shift).
4. Key points.

For examples:
$$y=3sin(2x-\pi)$$
We want to reduce the coefficient of $x$ to 1. So:
$y=3sin[2(x- \frac{\pi}{2})]$
1. We have no vertical shift.
2. Phase shift.
	We have a *right* shift by $\frac{\pi}{2}$.
3. Period.
	Since $\omega=2$, $T=\frac{2\pi}{2}=\pi$.
	![[Pasted image 20240909220509.png]]
	Treat the right shift as the new $y$-axis. This will get our *working* period.
	![[Pasted image 20240909220629.png]]
	Add the center and quarters:
	![[Pasted image 20240909220726.png]]
	Understand that this is a sine function, which will have $x$-intercepts at the ends and the center of period.
	![[Pasted image 20240909220825.png]]
- Key points:
	Only the $y$-coordinate is affected here by $A$, since we've already dealt with $\omega$ by scaling the $x$-axis.
	- $(\frac{3\pi}{4},1)\to(\frac{3\pi}{4},3)$
	- $(\frac{5\pi}{4},-1)\to(\frac{5\pi}{4},-3)$
![[Pasted image 20240909221016.png]]
![[Pasted image 20240909221342.png]]

$$y=2cos(4x+3\pi)+1$$
$y=2cos[4(x+\frac{3\pi}{4})]+1$
- Vertical shift.
	We have a shift up by 1.
- Phase shift.
	We have left shift by $\frac{3\pi}{4}$.
- Period.
	$T=\frac{2\pi}{4}=\frac{\pi}{2}$
	![[Pasted image 20240909222032.png]]
	Add the tick marks and shift up by 1.
	![[Pasted image 20240909222254.png]]
	There we have our new axes.
	With cosine function, the $x$-ints sit at the quarters![[Pasted image 20240909222400.png]]
- Key points:
	- $(- \frac{3\pi}{4},1)\to(- \frac{3\pi}{4},2)$
	- $(- \frac{\pi}{2},-1)\to(- \frac{\pi}{2},-2)$
	- $(- \frac{\pi}{4},1)\to(- \frac{\pi}{4},2)$
![[Pasted image 20240909223016.png]]
![[Pasted image 20240909223354.png]]
### More examples

$$y=-3sin(-2x+ \frac{\pi}{2})$$
$y=-3sin[-2(x-\frac{\pi}{4})]$
Rmb that $sin(-\theta)=-sin(\theta)$.
$-3sin[-2(x-\frac{\pi}{4})]=-(-3)sin[2(x-\frac{\pi}{4})]$
Simplify this to:
$y=3sin[2(x- \frac{\pi}{4})]$
1. No vertical shift.
2. Phase shift.
	Right shift by $\frac{\pi}{4}$.
3. Period.
	$T=\frac{2\pi}{2}=\pi$
	![[Pasted image 20240909224854.png]]
4. Key points:
	- $(\frac{\pi}{2},1)\to(\frac{\pi}{2},3)$
	- $(\pi,-1)\to(\pi,-3)$
![[Pasted image 20240909225034.png]]
![[Pasted image 20240909225450.png]]
- Notice that $y=-3sin(-2x+ \frac{\pi}{2})=3sin[2(x- \frac{\pi}{4})]$.

$$y=2cos(-2\pi x-4)+3$$
$y=2cos[-2\pi(x+ \frac{2}{\pi})]+3$
Cosine is an even function: $cos(-\theta)=cos(\theta)$.
$y=2cos[2\pi(x+ \frac{2}{\pi})]+3$
1. Vertical shift.
	Shift up by 3.
2. Phase shift.
	Shift left by $\frac{2}{\pi}$.  Very awkward.
3. Period
	$T=\frac{2\pi}{2\pi}=1$.
	Be amazed by how Professor Leonard does this with *logic and facts*.
	![[Pasted image 20240909230607.png]]
4. Key points:
	- $(- \frac{2}{\pi},1)\to(- \frac{2}{\pi},2)$
	- $(\frac{1}{2} - \frac{2}{\pi},-1)\to(\frac{1}{2} - \frac{2}{\pi},-2)$
	- $(1- \frac{2}{\pi},1)\to(1- \frac{2}{\pi},2)$
![[Pasted image 20240909231006.png]]![[Pasted image 20240909231550.png]]
## Introduction to Inverse Trigonometric Functions

A function has an inverse if and only if it is [[Pre-calculus - College Algebra#One-to-One Functions|one-to-one]]. 
	We'll be needing this to solve a trig equation (like how we need log to solve exponentials and vice versa).

### Inverse of Sine
$$y=\sin x$$
![[Pasted image 20240910185353.png]]
Sine is *not* one-to-one function, the output repeats every period ($2\pi$). To make this one-to-one, we can cut part of it (restrict the Domain). The question now is: how do we cut this?
![[Pasted image 20240910185637.png]]
- We can cut this from the *peaks* (notice how inside the section cut by the red lines pass the *horizontal* line test). Rmb that $sin(\frac{\pi}{2})=1$ and $sin(- \frac{\pi}{2})=-1$, or the quarters of period. This is the domain of our cut section.
![[Pasted image 20240910190037.png]]
**Domain**: $[- \frac{\pi}{2},\frac{\pi}{2}]$
**Range**: $[-1,1]$
- notice that the range does not change since we cut from the peaks.
With [[Pre-calculus - College Algebra#Finding Inverse Functions|inverse functions]], your input and output *switches*, your domain and range *switches*.
Let's look at the key points:
- $(- \frac{\pi}{2},-1)\to(-1, - \frac{\pi}{2})$
- $(\frac{\pi}{2},1)\to(1, \frac{\pi}{2})$
![[Pasted image 20240910190836.png]]
- notice that it is a reflection across $y=x$ line.
Now the Domain and Range for the $sin^{-1}(x)$ function:
- **Domain**: $[-1,1]$
	- This mean you *cannot* have anything outside of this interval (you're cooked if you do).
- **Range**: $[- \frac{\pi}{2},\frac{\pi}{2}]$
Rmb, to find the equation for our inverse, we switch $x$ and $y$:
$y=\sin x$
$x=\sin y$
Then we solve for $y$. We cannot divide $\sin$ to both sides since it is a function (we can divide by $\sin y$ but that doesn't help our case). The inverse of sine is called $sin^{-1}$ (pronounced *sine inversed* or *arcsine*), so we simply apply this to both side:
$\sin^{-1}(x)=\sin^{-1}(\sin y)$
$\sin^{-1}(x)=y$

Rmb, what $x$ and $y$ represent in $y=sinx$:
- $x$ represent the angle.
- $y$ represent the coordinate on the unit circle.
The *inverse* is the opposite of that:
- $x$ represent the coordinate on the unit circle.
- $y$ represent the angle that gives you that coordinate.
### Inverse of Cosine
$$y=\cos x$$
![[Pasted image 20240910191920.png]]
- Clearly this is not a one-to-one function. The next step is to ask: how do we cut this?
	- The peaks are the obvious choice. However, in cosine, the peaks is at the ends and center of period: $cos(0)=1$, $cos(\pi)=-1$, and $cos(2\pi)=1$. We only need the period $[0,\pi]$ and that will be the Domain of our inverse function.
![[Pasted image 20240910192425.png]]
Zoomed in, we got:
![[Pasted image 20240910192450.png]]Let's summarize the info on this section of cosine:
- **Domain**: $[0,\pi]$
- **Range**: $[-1,1]$
- **Key points**:
	- $(0,1)$
	- $(\frac{\pi}{2},0)$
	- $(\pi,-1)$
So the inverse of this function would be:
$$y=\cos^{-1}x$$
![[Pasted image 20240910193022.png]]
- **Domain**: $[-1,1]$
- **Range**: $[0,\pi]$
- **Key points**:
	- $(1,0)$
	- $(0,\frac{\pi}{2})$
	- $(-1,\pi)$
### Inverse of Tangent
$$y=\tan x$$
![[Pasted image 20240910193835.png]]
We can cut this at the vertical asymptote and get a one-to-one function, say at $- \frac{\pi}{2}$ and $\frac{\pi}{2}$:
![[Pasted image 20240910193921.png]]
Let's summarize the info on this section of tangent:
- **Domain**: $(- \frac{\pi}{2},\frac{\pi}{2})$
	- notice how this is not $[- \frac{\pi}{2},\frac{\pi}{2}]$
- **Range**: $(-\infty,\infty)$
- **Key points**:
	- $(- \frac{\pi}{4},-1)$
	- $(0,0)$
	- $(\frac{\pi}{4},1)$
So the inverse of this function would be:
$$y=\tan^{-1}x$$
![[Pasted image 20240910195006.png]]
- **Domain**: $(-\infty,\infty)$
- **Range**: $(- \frac{\pi}{2},\frac{\pi}{2})$
- **Key points**:
	- $(-1,- \frac{\pi}{4})$
	- $(0,0)$
	- $(1,\frac{\pi}{4})$
## How to Use Inverse Trigonometric Functions

| Trig Function                  | What $x$ represents (Domain)                        | What $y$ represents (Range)       |
| ------------------------------ | --------------------------------------------------- | --------------------------------- |
| $y=\sin x$ (restricted domain) | Angle $[- \frac{\pi}{2}, \frac{\pi}{2}]$            | $y$ coordinate on the unit circle |
| $y=\cos x$ (restricted domain) | Angle $[0, \pi]$                                    | $x$ coordinate on the unit circle |
| $y=\tan x$ (restricted domain) | Angle $(- \frac{\pi}{2}, \frac{\pi}{2})$            | $\frac{y}{x}$ on the unit circle  |
| $y=\sin^{-1} x$                | $y$ coordinate on the unit circle $[-1,1]$          | Angle                             |
| $y=\cos^{-1} x$                | $x$ coordinate on the unit circle $[-1,1]$          | Angle                             |
| $y=\tan^{-1} x$                | $\frac{y}{x}$ on the unit circle $(-\infty,\infty)$ | Angle                             |

Recall the [[Pre-calculus - College Algebra#^6194e8|composition of function and its inverse]]:
- $f(f^{-1}(x))=x$
- $f^{-1}(f(x))=x$
So, for example:
$$\sin^{-1}(\sin x)$$
Does this cancel? Yes, only if $x$ is within the restricted Domain of $\sin x$, which is $[- \frac{\pi}{2}, \frac{\pi}{2}]$ (since $\sin x$ needs to output $[-1,1]$). When you see these kind of things, try to think $\sin x$ as not just $\sin x$, but as the domain-restricted $\sin x$.
$\sin^{-1}(\sin x)=x$
$$\cos^{-1}(\cos x)$$
Does this cancel? Yes, only if $x$ is within the restricted Domain of $\cos x$, which is $[0, \frac{\pi}{2}]$ (since $\cos x$ needs to output $[-1,1]$).
$\cos^{-1}(\cos x)=x$
$$\tan^{-1}(\tan x)$$
Does this cancel? Yes, only if $x$ is within the restricted Domain of $\tan x$, which is $[- \frac{\pi}{2}, \frac{\pi}{2}]$.
$\tan^{-1}(\tan x)=x$

Let's try the reverse:
$$\sin(\sin^{-1}x)$$
Does this cancel? Yes, only if $x$ is within the Domain of $[-1,1]$. 
	Rmb that $sin^{-1}x$ is an angle, simplified to $sin(\theta)$ which make sense. 
$\sin(\sin^{-1}x)=x$
$$\cos(\cos^{-1}x)$$
Does this cancel? Yes, only if $x$ is within the Domain of $[-1,1]$.
$\cos(\cos^{-1}x)=x$
$$\tan(\tan^{-1}x)$$
Does this cancel? Yes, and for any real number too, since the Domain of $\tan^{-1}x$ (which is also the range of $\tan x$) is $(-\infty,\infty)$.

Here's how to use it:
![[Pasted image 20240910205314.png]]
$$\sin^{-1}(0)=$$
With what value of $x$, will make $\sin x=0$? Well, there's $0, \pi, 2\pi,...$ However, the value of $x$ must also be on the restricted Domain of $[- \frac{\pi}{2}, \frac{\pi}{2}]$. There will be only one value left within that domain (since it is one-to-one), and that's 0. So:
$\sin^{-1}(sin0)=0$

$$\cos^{-1}(1)=$$
Cosine deal with $x$-coordinate. So at what angle will make $\cos x=1$ within the restricted Domain of $[0,\pi]$? That's $0$.
$\cos^{-1}(1)=0$

$$tan^{-1}(-1)=$$
What angle will make $\tan x=-1$ within the restricted Domain? That would be either in quadrant two or four where they have opposite signs in $x$ and $y$, but since our domain is restricted to $[- \frac{\pi}{2}, \frac{\pi}{2}]$, our solution must be on quadrant four.
$\tan^{-1}(-1)=-\frac{\pi}{4}$ (understand that it shouldn't be $\frac{7\pi}{4}$)

Let's go through the other quickly:
$$\cos^{-1}(-1)=$$
Rmb that $cos(\pi)=-1$
$cos^{-1}(-1)=\pi$

$$\tan^{-1}(0)=$$
$\tan^{-1}(0)=0$

$$\sin^{-1}(\frac{\sqrt{2}}{2})=$$
$\sin^{-1}(\frac{\sqrt{2}}{2})=\frac{\pi}{4}$

$$\cos^{-1}(- \frac{\sqrt{3}}{2})=$$
$\cos^{-1}(- \frac{\sqrt{3}}{2})=\frac{5\pi}{6}$

$$sin^{-1}(-\frac{\sqrt{3}}{2})=$$
$sin^{-1}(-\frac{\sqrt{3}}{2})=- \frac{\pi}{3}$

$$sin^{-1}(- \frac{\sqrt{2}}{2})=$$
$sin^{-1}(- \frac{\sqrt{2}}{2})=\frac{\pi}{4}$

$$tan^{-1}(\sqrt{3})=$$
Think $tan x=\frac{y}{x}$, so $\sqrt{3}=\frac{\frac{\sqrt{3}}{2}}{\frac{1}{2}}$.
$tan^{-1}(\sqrt{3})=\frac{\pi}{3}$

$$\tan^{-1}(\frac{\sqrt{3}}{3})=$$
That's $\frac{1}{\sqrt{3}}$, which you can get from $\frac{\frac{1}{2}}{\frac{\sqrt{3}}{2}}$.
$\tan^{-1}(\frac{\sqrt{3}}{3})=\frac{\pi}{6}$

$$sin^{-1}(\frac{1}{8})=$$
Is this in the unit circle? Yes. You can use your calculator for this (make sure it is in radian!).
$sin^{-1}(\frac{1}{8})\approx0.125$

$$\cos^{-1}(\frac{\sqrt{2}}{3})=$$
$\cos^{-1}(\frac{\sqrt{2}}{3})\approx1.08$

$$\tan^{-1}(-3)=$$
$\tan^{-1}(-3)\approx-1.25$

$$\cos^{-1}(\cos \frac{4\pi}{5})=$$
This fits in the Domain of $[0,\pi]$. So:
$\cos^{-1}(\cos \frac{4\pi}{5})=\frac{4\pi}{5}$

$$\sin^{-1}(\sin(-\frac{3\pi}{7}))=$$
This fits in the Domain of $[- \frac{\pi}{2},\frac{\pi}{2}]$. So:
$\sin^{-1}(\sin(-\frac{3\pi}{7}))=-\frac{3\pi}{7}$

$$\cos^{-1}(\cos(- \frac{\pi}{3}))=$$
Whoops. This does not fit in the the Domain of $[0,\pi]$. However, we know that cosine is an even function.
$cos(-\theta)=cos(\theta)$, so we have $\cos^{-1}(\cos(- \frac{\pi}{3}))=\cos^{-1}(\cos( \frac{\pi}{3}))$.
So:
$\cos^{-1}(\cos(- \frac{\pi}{3}))= \frac{\pi}{3}$

$$\cos^{-1}(\cos (- \frac{5\pi}{3}))=$$
We know that cosine is an even function so: $\cos^{-1}(\cos(- \frac{5\pi}{3}))= \cos^{-1}(\cos(\frac{5\pi}{3}))$
Even with that, the angle is still not within the Domain of $[0,\pi]$. However, from knowing the [[#Periods|period]] of cosine, we know that:
$cos(\theta+2\pi k)=cos\theta$
This says that: even when we have something *outside* of our Domain, we can still relate that to something *inside* of our Domain.
So:
$\frac{5\pi}{3}-2\pi=- \frac{\pi}{3}$
That's $cos(- \frac{\pi}{3})$, which we have done in the previous example. So:
$\cos^{-1}(\cos (- \frac{5\pi}{3}))=\frac{\pi}{3}$

$$\sin^{-1}(\sin(\frac{9\pi}{8}))$$
$\frac{9\pi}{8}$ is outside our Domain (third quadrant) of $[- \frac{\pi}{2},\frac{\pi}{2}]$. We can use the periodicity of trig functions to reduce this down to our desired Domain.
$\frac{9\pi}{8}-2\pi=-\frac{7\pi}{8}$  
That's not very helpful, let's instead use the idea of symmetry to help us:
![[Pasted image 20240910205314.png]]
- notice how there is symmetry of $y$-values about the $y$-axis e.g. $sin(\frac{7\pi}{6})=- \frac{1}{2}$ and $sin(\frac{11\pi}{6})=- \frac{1}{2}$ also. We can apply this idea to $\frac{9\pi}{8}$.
![[Pasted image 20240910225955.png]]
So:
$\sin(\frac{9\pi}{8})=\sin(- \frac{\pi}{8})$
$\sin^{-1}(\sin(\frac{9\pi}{8}))=- \frac{\pi}{8}$
We can also think of $\sin(\frac{9\pi}{8})$ as $\sin(\pi+ \frac{\pi}{8})$ and use the identity:
$$sin(\pi+\theta)=-sin(\theta)$$
	See this [link](https://www.youtube.com/watch?v=RNb-bC9aWvQ). 

$$\tan^{-1}(\tan \frac{4\pi}{5})$$
$\frac{4\pi}{5}$ is not within $[- \frac{\pi}{2},\frac{\pi}{2}]$. We can do the same thing as above, but I'll use a *reference angle* of $\frac{\pi}{5}$. Since, $\frac{4\pi}{5}$ is on quadrant two where $\frac{y}{x}$ is negative, we also want the tangent of the reduced angle to be negative. So, between $\frac{\pi}{5}$ (Q1) and $- \frac{\pi}{5}$ (Q4), we must pick $- \frac{\pi}{5}$ since in quadrant four we also have negative $\frac{y}{x}$. 
$\tan^{-1}(\tan \frac{\pi}{5})=-\frac{\pi}{5}$
![[Pasted image 20240910233007.png]]

$$\sin(\sin^{-1} \frac{1}{4})$$
$x$ is within the Domain of $[-1,1]$.
$\sin(\sin^{-1} \frac{1}{4})= \frac{1}{4}$

$$\cos(\cos^{-1}(- \frac{2}{3}))$$
$x$ is within the Domain of $[-1,1]$.
$\cos(\cos^{-1}(- \frac{2}{3}))=- \frac{2}{3}$

$$\tan(\tan^{-1}(-2))$$
$x$ is within the Domain of $(-\infty,\infty)$.
$\tan(\tan^{-1}(-2))=-2$

$$sin(sin^{-1}(-2))$$
Now $x$ is NOT within the Domain of $[-1,1]$. $sin(sin^{-1}(-2))$ says "give me an angle that has a $y$-coordinate of -2 on a unit circle". That's *crazy*! We can't do crazy. That's *undefined*.
$sin(sin^{-1}(-2))=\text{undefined}$

$$\cos(\cos^{-1}1.3)$$
Same thing here.
$\cos(\cos^{-1}1.3)=\text{undefined}$

The key point here is that, when composing trig function with its inverse, make sure you're working **inside of your domain** and [[#Introduction to Inverse Trigonometric Functions|understand where the domain comes from]].

## How to Find Inverse Trigonometric Functions

Before we can find an inverse, we must find Domain and Range *first*.
	If we can find the Domain and Range of our original function, we can easily find the Domain and Range of its inverse by switching it.

| Trig Function                  | What $x$ represents (Domain)             | What $y$ represents (Range)       |
| ------------------------------ | ---------------------------------------- | --------------------------------- |
| $y=\sin x$ (restricted domain) | Angle $[- \frac{\pi}{2}, \frac{\pi}{2}]$ | $y$ coordinate on the unit circle |
| $y=\cos x$ (restricted domain) | Angle $[0, \pi]$                         | $x$ coordinate on the unit circle |
| $y=\tan x$ (restricted domain) | Angle $(- \frac{\pi}{2}, \frac{\pi}{2})$ | $\frac{y}{x}$ on the unit circle  |
For example:
$$f(x)=5sin(x)+2$$
The function is sine. Rmb, that we can cut sine function for the interval $- \frac{\pi}{2}\leq x\leq \frac{\pi}{2}$. So that our Domain = $[- \frac{\pi}{2}, \frac{\pi}{2}]$. 
For the Range, think about the maximum and minimum value that this function could have. Since, max of sine is 1 and min is -1:
- max = $5(1)+2=7$
- min $=5(-1)+2-3$
Notice how the angle needed for these inputs cannot be outside of our Domain since we cut the section at the peaks. So, the Range $= [-3,7]$ or $-3\leq f(x)\leq7$.

Now we can find the inverse function:
$y=5sin(x)+2$
Replace $y$ with $x$ and vice versa:
$x=5sin(y)+2$
$\frac{x-2}{5}=sin(y)$
$sin^{-1}(\frac{x-2}{5})=sin^{-1}(sin(y))$
$sin^{-1}(\frac{x-2}{5})=y$
We can pronounce this as:
$f^{-1}(x)=sin^{-1}(\frac{x-2}{5})$
Now, this would not be possible if we are not working with a one-to-one function and restricted our Domain.

The Domain and Range of our inverse function can be found by switching what we have for the original function:
- $D:-3\leq x\leq7$
- $R:- \frac{\pi}{2}\leq f^{-1}(x) \leq \frac{\pi}{2}$
We can try plugging in the max and min value of our Domain:
- $f^{-1}(-3)=sin^{-1}(\frac{-3-2}{5})=sin^{-1}(-1)$
- $f^{-1}(7)=sin^{-1}(\frac{7-2}{5})=sin^{-1}(1)$
This correspond with original Domain for $sin^{-1}(x)$, which is $[-1,1]$.

$$f(x)=-tan(x+1)-3$$
A few notes to imagine the graph in our head:
- shift down by 3
- shift left by 1
- [[Pre-calculus - College Algebra#Introduction to Graph Transformation|reflected]] about the $x$-axis

This is where inequality notation comes in handy:
Notice the shift left by 1 $(x+1)$. Since our graph shifts, our vertical asymptotes shift, and since we cut at our vertical asymptote, we must also adjust our Domain according to that. 
$- \frac{\pi}{2}\leq x+1\leq \frac{\pi}{2}$
Subtract one from all sides and that's our Domain:
$D:- \frac{\pi}{2}-1< x< \frac{\pi}{2}-1$
For our Range, the vertical shift doesn't really matter since it is $(-\infty,\infty)$.
$R: -\infty<f(x)<\infty$

Now we can find the inverse function:
$y=-tan(x+1)-3$
$x=-tan(y+1)-3$
$x+3=-tan(y+1)$
$-x-3=tan(y+1)$
$tan^{-1}(-x-3)=tan^{-1}(tan(y+1))$
$tan^{-1}(-x-3)=y+1$
$tan^{-1}(-x-3)-1=y$
$f^{-1}(x)=tan^{-1}(-x-3)-1$
- notice the shift down by 1, reflection about the $y$-axis, shift left by 3.

Now we can find the Domain and Range of our inverse function:
$D: -\infty<x<\infty$
$R:- \frac{\pi}{2}-1< f^{-1}(x)< \frac{\pi}{2}-1$

$$h(x)=2cos(3x+2)-1$$
Notes on the graphing:
- shift down by 1
- vertical stretch by 2
- horizontal compression by 3
- shift left by $\frac{2}{3}$
Really rough sketch:
![[Pasted image 20240912001500.png]]

Domain:
$0\leq 3x+2\leq \pi$
$-2\leq3x\leq\pi-2$
$D: - \frac{2}{3}\leq x\leq \frac{\pi-2}{3}$ 
Range:
- Min: $2(-1)-1=-3$
- Max: $(2(1)-1)=1$
$R: -3\leq h(x) \leq 1$
See how it corresponds to our graph?

Find the inverse function:
$y=2cos(3x+2)-1$
$x=2cos(3y+2)-1$
$\frac{x+1}{2}=cos(3y+2)$
$cos^{-1}(\frac{x+1}{2})=cos^{-1}(cos(3y+2))$
$cos^{-1}(\frac{x+1}{2})=3y+2$
$cos^{-1}(\frac{x+1}{2})-2=3y$
$\frac{1}{3}\cdot(cos^{-1}(\frac{x+1}{2})-2)=y$
$y=\frac{1}{3}cos^{-1}(\frac{x+1}{2})- \frac{2}{3}$
$h^{-1}(x)=\frac{1}{3}cos^{-1}(\frac{x+1}{2})- \frac{2}{3}$
- notice the vertical compress, horizontal stretch, shift left by 1, shift down by $\frac{2}{3}$

Now, the Domain and Range of the inverse function:
$D: -3\leq x \leq 1$
$R: - \frac{2}{3}\leq h^{-1}(x)\leq \frac{\pi-2}{3}$
## How to Solve Basic Inverse Trigonometric Functions

Here is the idea:
$$sin(sin^{-1}x)=x$$
$$cos(cos^{-1}x)=x$$
$$tan(tan^{-1}x)=x$$
- Be *very* careful with what value inside the parentheses is:
	- $x$ should be $[-1,1]$ for sine and cosine, and all real number for tangent
	- $sin^{-1}x$ and $tan^{-1}x$ should output an *angle* within $[- \frac{\pi}{2}, \frac{\pi}{2}]$, and $cos^{-1}x$ should output an angle within $[0,\pi]$
- To solve for these type of equation, we should *isolate the variable*.

For example:
$$4sin^{-1}x=\pi$$
*Isolate the variable*:
$sin^{-1}x=\frac{\pi}{4}$
$sin(sin^{-1}x)=sin(\frac{\pi}{4})$
$x=sin(\frac{\pi}{4})$
Hey, we know what $sin(\frac{\pi}{4})$ is:
$x=\frac{\sqrt{2}}{2}$

$$3tan^{-1}x=\pi$$
$tan^{-1}x=\frac{\pi}{3}$
$tan(tan^{-1}x)=tan(\frac{\pi}{3})$
$x=tan(\frac{\pi}{3})$
$x=\sqrt{3}$

$$3cos^{-1}(2x)=2\pi$$
$cos^{-1}(2x)=\frac{2\pi}{3}$
$cos(cos^{-1}(2x))=cos(\frac{2\pi}{3})$
$2x=cos(\frac{2\pi}{3})$
$2x=- \frac{1}{2}$
$x=- \frac{1}{4}$

$$4cos^{-1}(x)-2\pi=2cos^{-1}(x)$$
$4cos^{-1}(x)-2cos^{-1}(x)=2\pi$
$2cos^{-1}(x)=2\pi$
$cos^{-1}(x)=\pi$
$cos(cos^{-1}(x))=cos(\pi)$
$x=-1$

## An In-depth Look at Using Inverse Trig Functions

$$\sin\theta=y\iff \sin^{-1}y=\theta$$
- This is **only valid if** \( $-\frac{\pi}{2} \leq \theta \leq \frac{\pi}{2}$ \). 
- The inverse sine function, ( $\sin^{-1}(y)$ ), returns an angle $( \theta )$ in this range.


$$\cos\theta=x\iff \cos^{-1}x=\theta$$
- This is **only valid if** $( 0 \leq \theta \leq \pi )$. 
- The inverse cosine function, $( \cos^{-1}(x) )$, returns an angle $( \theta)$ in this range.
$$\tan\theta=\frac{y}{x}\iff \tan^{-1} \frac{y}{x}=\theta$$
- This is **only valid if** $( -\frac{\pi}{2} < \theta < \frac{\pi}{2} )$. 
- The inverse tangent function, $( \tan^{-1}(\frac{y}{x})$, returns an angle $( \theta )$ within this open interval.

For example:
$$sin^{-1}(\frac{\sqrt{2}}{2})$$
This is saying: "Give me the *angle* (within my defined domain) that makes $y$-coordinate equal to $\frac{\sqrt{2}}{2}$ in the unit circle!"
This will output an angle:
$sin^{-1}(\frac{\sqrt{2}}{2})=\theta$
We know from the unit circle that this would be $\frac{\pi}{4}$, but we could show a bit more math to be more convincing:
$sin(sin^{-1}(\frac{\sqrt{2}}{2}))=sin(\theta)$
$sin\theta=\frac{\sqrt{2}}{2}$
$\theta=\frac{\pi}{4}$

$$cos(sin^{-1} \frac{\sqrt{2}}{2})$$
That's some weird looking stuff... However, rmb that $sin^{-1}(\frac{\sqrt{2}}{2})$ *is* an angle. Since we know that $sin^{-1}(\frac{\sqrt{2}}{2})=\frac{\pi}{4}$:
$cos(sin^{-1} \frac{\sqrt{2}}{2})=cos(\frac{\pi}{4})=\frac{\sqrt{2}}{2}$

$$tan(cos^{-1}(- \frac{\sqrt{3}}{2}))$$
Rmb that $cos^{-1}(- \frac{\sqrt{3}}{2})=\theta$. From the unit circle, this is $\frac{5\pi}{6}$. So:
$tan(\frac{5\pi}{6})=-\frac{\sqrt{3}}{3}$

$$sec(sin^{-1}(- \frac{1}{2}))$$
$sin^{-1}(- \frac{1}{2})=- \frac{\pi}{6}$.
$sec(- \frac{\pi}{6})=\frac{2}{\sqrt{3}}=\frac{2\sqrt{3}}{3}$

$$csc(tan^{-1}\sqrt{3})$$
$tan^{-1}\sqrt{3}=\frac{\pi}{3}$
$csc(\frac{\pi}{3})=\frac{2\sqrt{3}}{3}$

$$cot(cos^{-1}(- \frac{1}{2}))$$
$cos^{-1}(- \frac{1}{2})=\frac{2\pi}{3}$
$cot(\frac{2\pi}{3})=- \frac{\sqrt{3}}{3}$

$$sin(tan^{-1}(\frac{1}{2}))$$
$tan^{-1}(\frac{1}{2})=\theta$ ....wait, this is *not* in a unit circle. In cases like this, it's very beneficial to write this as:
$tan\theta=\frac{1}{2}$
We know that $tan\theta=\frac{y}{x}$. Let's write this as a right triangle:
![[Pasted image 20240912215404.png]]
- There are two triangle that would give out $tan\theta=\frac{1}{2}$? No. Rmb, we restricted our Domain specifically to disallow this.
![[Pasted image 20240912215555.png]]
Now, we still don't know what $\theta$ is specifically, but since we know the length of opposite, adjacent, and hypotenuse of the right triangle with angle $\theta$, we can solve any trig functions of $\theta$.
$sin\theta=\frac{opposite}{hypotenuse}=\frac{1}{\sqrt{5}}=\frac{\sqrt{5}}{5}$

$$tan(sin^{-1}(\frac{1}{3}))$$
Similar case as the above, we should draw a right triangle. With what we're given ($sin\theta=\frac{1}{3}$):
![[Pasted image 20240912220052.png]]
![[Pasted image 20240912220206.png]]
$tan\theta=\frac{1}{\sqrt{8}}=\frac{\sqrt{8}}{8}=\frac{\sqrt{2}}{4}$

$$cot(cos^{-1}(- \frac{\sqrt{3}}{3}))$$
Rmb, that the domain for one-to-one Cosine function is $[0,\pi]$ or quadrant one or two *only*. 
$cos\theta=\frac{-\sqrt{3}}{3}$
![[Pasted image 20240912221042.png]]
$cot\theta=\frac{-\sqrt{3}}{\sqrt{6}}=\frac{-\sqrt{18}}{6}=- \frac{\sqrt{2}}{2}$

$$sin(tan^{-1}(-3))$$
$tan\theta=\frac{-3}{1}=\frac{y}{x}$, that would be in quadrant four.
![[Pasted image 20240912221706.png]]
- However, if you want to think negative hypotenuse, just project it to the opposite quadrant e.g. if positive hypotenuse extend from origin to quadrant four, negative hypotenuse would extend to quadrant two.
$sin\theta=\frac{y}{r}=\frac{-3}{\sqrt{10}}=- \frac{3\sqrt{10}}{10}$

$$cos^{-1}(sin \frac{5\pi}{4})$$
$sin \frac{5\pi}{4}=- \frac{\sqrt{2}}{2}$
$cos^-1(-\frac{\sqrt{2}}{2})=\frac{3\pi}{4}$
Why $\frac{3\pi}{4}$ and not $\frac{5\pi}{4}$? Rmb, the Range for cosine inversed of $[0,\pi]$.

$$tan^{-1}(cot \frac{2\pi}{3})$$
$cot \frac{2\pi}{3}=-\frac{\sqrt{3}}{3}$
Rmb, $tan\theta=\frac{y}{x}$ (don't get confused with $cot$!):
$tan^{-1}(- \frac{\sqrt{3}}{3})=- \frac{\pi}{6}$

$$sin^{-1}(cos- \frac{7\pi}{6})$$
$\cos - \frac{7\pi}{6}=- \frac{\sqrt{3}}{2}$ 
Rmb that $cos(-\theta)=cos\theta$ (even function), so we can think of this as $cos \frac{7\pi}{6}$ too.
$sin^{-1}(- \frac{\sqrt{3}}{2})=- \frac{\pi}{3}$

$$csc^{-1}(- \frac{2\sqrt{3}}{3})$$
$csc(csc^{-1}(- \frac{2\sqrt{3}}{3}))=csc(\theta)$
$- \frac{2\sqrt{3}}{3}=csc\theta$
Since $sin\theta$ is a reciprocal of $csc\theta$, think:
$sin\theta=\frac{-3}{2\sqrt{3}}=\frac{-3\sqrt{3}}{6}=- \frac{\sqrt{3}}{2}$
Now what is $\theta$? Think back to:
$sin^{-1}(\frac{\sqrt{3}}{2})= \theta$
$\theta=- \frac{\pi}{3}$
Since $csc^{-1}$ has the same range ($- \frac{\pi}{2}\leq\theta\leq \frac{\pi}{2}$) as $sin^{-1}$, this is not too hard to do. 

$$sec^{-1}(-2)$$
$sec\theta=-2$
Since cosine is the reciprocal of secant:
$cos\theta=- \frac{1}{2}$ or $cos^{-1}(- \frac{1}{2})=\theta$
Referring to the unit circle and remember our range of $[0,\pi]$:
$\theta=\frac{2\pi}{3}$

$$sec^{-1}(-3)$$
$sec\theta=-3$
Since cosine is the reciprocal of secant:
$cos\theta=- \frac{1}{3}$ or $cos^{-1}(- \frac{1}{3})=\theta$
Now this doesn't seems to be on the unit circle. Drawing a right triangle here would not help us find the angle. We have to use our calculator (don't forget to put it in radian!). 
$\theta\approx1.91$ Radian

$$csc^{-1}(-4)$$
$csc\theta=-4$
Sine is the reciprocal of cosecant:
$sin\theta= - \frac{1}{4}$ or $sin^{-1}(- \frac{1}{4})=\theta$
$\theta\approx-0.25$ Radian

Now these would NOT work with cotangent and tangent. Rmb that:
$$\tan\theta=\frac{y}{x}\iff \tan^{-1} \frac{y}{x}=\theta$$
- Only if $- \frac{\pi}{2}<\theta< \frac{\pi}{2}$.
- $\cot^{-1}(\frac{x}{y})=\theta$, only if $0<\theta<\pi$.
	- Rmb that in the [[#Graph of Cotangent]], the V.A.s and $x$-intercepts switch with one another compared to tangent. 

$$cot^{-1}(\sqrt{3})$$
I know that I've hyped up about the difficulties involved with cotangent and tangent and their domains. But we're fine here.
$cot\theta=\sqrt{3}$ 
That's positive $\frac{x}{y}$. This must be either on quadrant one or quadrant three.
Let's think in tangent.
$tan\theta=\frac{1}{\sqrt{3}}=\frac{\sqrt{3}}{3}$
That's positive $\frac{y}{x}$. So quadrant one or three. 
Note that quadrant one ($0,\frac{\pi}{2}$) fits in both the range for cotangent of $0<\theta<\pi$ and for tangent of $\frac{\pi}{2}<\theta< \frac{\pi}{2}$. We can safely limit our focus on quadrant one. So what $\theta$ makes $cot\theta=\sqrt{3}$ and $tan\theta= \frac{1}{\sqrt{3}}$?
$\theta=\frac{\pi}{6}$

Now here's the real deal:
$$cot^{-1}(-2)$$
Since $cot^{-1}(-2)=\theta$, $cot\theta=-2$.
With a negative output from $\frac{x}{y}$, this would either be on quadrant two and four where only either $x$ or $y$ is negative.
Since $cot\theta=\frac{-2}{1}=\frac{x}{y}$, we have negative $x$ and positive $y$ and that's quadrant two. 
What if we use tangent?
	$tan\theta=\frac{1}{-2}=\frac{y}{x}$, negative $x$ and positive $y$, *quadrant two*. But wait... rmb, that the Domain for our one-to-one tangent is $- \frac{\pi}{2}<\theta< \frac{\pi}{2}$. That's restricted to *quadrant one and four*!
What if we think $cot\theta=\frac{2}{-1}$ instead?
	$cot\theta=\frac{2}{-1}=\frac{x}{y}$, we have positive $x$ and negative $y$. That's *quadrant four*. But wait! Rmb, that the Domain for our one-to-one cotangent is $(0,\pi)$, which is strictly in *quadrant one and two*.
That's why we *cannot* use tangent or its inverse to help us here. My calculator cannot help me, since mine got only $sin^{-1},cos^{-1}, tan^{-1}$. So, is it unsolvable? No. Since we know that one-to-one $cot\theta$ is possible in quadrant two, we can draw a right triangle:
![[Pasted image 20240912232101.png]]
What can we use to help us find a quadrant two angle? Not sine and not tangent. We can only use cosine here since its domain extend to quadrant two $0\leq 0\leq\pi$. We can think of this as:
$cos\theta=- \frac{2}{\sqrt{5}}=- \frac{2\sqrt{5}}{5}$ or $cos^{-1}(- \frac{2\sqrt{5}}{5})=\theta$.
We can put this in a calculator:
$\theta\approx2.68$ Radian
To be sure, $2.68$ is indeed $0\leq 2.68 \leq \pi$

To summarize:
- If $cot^{-1}(\frac{x}{y})=\theta$ is in quadrant one, you can use tangent and its inverse to help.
- Else, use cosine to help, since it has the exact same domain as inverse of cotangent.
## How to Solve Trigonometric Equations

Three things to understand about this:
- To solve for it, isolate it.
- Try to [[#How to Use the Unit Circle in Trigonometry|use your unit circle]].
- If we're not using [[#How to Use Inverse Trigonometric Functions|inverse trig functions]], don't restrict our unit circle.

$$2sin\theta+3=2$$
$sin\theta=- \frac{1}{2}$
$\theta=\frac{7\pi}{6}, \frac{11\pi}{6}$ 
Notice how we didn't restrict our domain here, as we would do with inverse trig functions. 
Since trig functions are *cyclical* (they goes on and on forever), we should be more specific by adding:
All solutions on $0\leq\theta<2\pi$.
	Notice how we used $<2\pi$ instead of $\leq2\pi$. This is because 0 and $2\pi$ yield the same value.
or by saying the *general solutions*:
$\theta=\frac{7\pi}{6}+2k\pi, \theta=\frac{11\pi}{6}+2k\pi$

$$4cos^{2}\theta-3=0$$
$cos^{2}\theta=\frac{3}{4}$
$\sqrt{cos^{2}\theta}=\pm\sqrt{\frac{3}{4}}$
$cos\theta=\pm\sqrt{\frac{3}{4}}=\pm \frac{\sqrt{3}}{2}$
For $+ \frac{\sqrt{3}}{2}$, $\theta=\frac{\pi}{6}, \frac{11\pi}{6}$ and for $- \frac{\sqrt{3}}{2}$, $\theta=\frac{5\pi}{6},\frac{7\pi}{6}$.

$$3tan^{2}\theta=1$$
$tan^{2}\theta=\frac{1}{3}$
$\sqrt{tan^{2}\theta}=\pm\sqrt{\frac{1}{3}}$
$tan\theta=\pm\frac{1}{\sqrt{3}}$
Rmb that the [[#Periods|period]] of tangent is $\pi$, so once you've found one solution on the unit circle, adding $\pi$ to it will get the exact same solution.
For $tan\theta=+\frac{1}{\sqrt{3}}$, our solutions should be either in quadrant one or three ($y$ and $x$ either both positive or both negative), so $\theta=\frac{\pi}{6},\frac{7\pi}{6}$.
For $tan\theta=-\frac{1}{\sqrt{3}}$, our solutions should be either in quadrant two or four ($y$ and $x$ has opposite signs), so $\theta=\frac{5\pi}{6},\frac{11\pi}{6}$.

$$sin(3\theta)=-1$$
The approach for this type of problem is to substitute it with something $x, \alpha, etc.$ And solve it as you normally would:
$3\theta=\alpha$
$sin(\alpha)=-1$
$\alpha=\frac{3\pi}{2}$
But because sine is periodic, this angle repeats every $2\pi$ (a full circle). So, the general solution is:
$\alpha=\frac{3\pi}{2}+2k\pi$
Rmb, this is the general solution for $\alpha$ not $\theta$. But since we know that $3\theta=\alpha$, we can get the general solution for $\theta$:
$3\theta=\frac{3\pi}{2}+2k\pi$
$\theta=\frac{\pi}{2}+ \frac{2k\pi}{3}$
	You can think of substituting $3\theta$ with $\alpha$ as **speeding up** the rotation around the unit circle. For every 1 radian of $\theta$, $\alpha$ moves **3 radians**. This means that we'll have *more* solutions in $\theta$ compared to $\alpha$.
With the general solution for $\theta$, we can plug in different values of $k$ to find the solutions within $0\leq\theta<2\pi$:
- $k=0$
$\theta=\frac{\pi}{2}$
- $k=1$
$\theta=\frac{\pi}{2}+ \frac{2\pi}{3}=\frac{7\pi}{6}$
- $k=2$
$\theta=\frac{\pi}{2}+ \frac{4\pi}{3}=\frac{11\pi}{6}$
Adding anymore would exceed $2\pi$ so our solutions are:
$\theta=\frac{\pi}{2}, \frac{7\pi}{6}, \frac{11\pi}{6}$, within $0\leq\theta<2\pi$.



$$tan(2\theta)=-1$$
$2\theta=\alpha$
$tan(\alpha)=-1$
This should be in quadrant two or four where $x$ and $y$ has opposite sign. 
$\alpha=\frac{3\pi}{4},\frac{7\pi}{4}$ or we can write this as $\alpha=\frac{3\pi}{4}+k\pi$ for a general solution.
We can find the general solution for $\theta$:
$2\theta=\frac{3\pi}{4}+k\pi$
$\theta=\frac{3\pi}{8}+ \frac{k\pi}{2}$ or $\theta=\frac{3\pi}{8}+ \frac{4k\pi}{8}= \frac{(3+4k)\pi}{8}$
So, within $0\leq\theta<2\pi$, we got the following solutions:
- $k=0$, $\theta=\frac{3\pi}{8}$
- $k=1$, $\theta= \frac{7\pi}{8}$
- $k=2$, $\theta=\frac{11\pi}{8}$
- $k=3$, $\theta=\frac{15\pi}{8}$

$$cos(2\theta)=- \frac{1}{2}$$
$2\theta=\alpha$
$cos(\alpha)=- \frac{1}{2}$
$\alpha=\frac{2\pi}{3},\frac{4\pi}{3}$
In this case, we can write two general solutions:
- $\alpha=\frac{2\pi}{3}+2k\pi$
- $\alpha=\frac{4\pi}{3}+2k\pi$
So, two general solutions for $\theta$ as well:
- $2\theta=\frac{2\pi}{3}+2k\pi\to\theta=\frac{\pi}{3}+k\pi$
	- Can be simplified as $\frac{(1+3k)\pi}{3}$
- $2\theta=\frac{4\pi}{3}+2k\pi\to\theta=\frac{2\pi}{3}+k\pi$
	- Can be simplified as $\frac{(2+3k)\pi}{3}$
So, within $0\leq\theta<2\pi$, we got the following solutions:
- $k=0$
	- $\theta=\frac{\pi}{3}$
	- $\theta=\frac{2\pi}{3}$
- $k=1$
	- $\theta=\frac{4\pi}{3}$
	- $\theta=\frac{5\pi}{3}$

$$tan(\frac{\theta}{2})=\sqrt{3}$$
$\frac{\theta}{2}=\alpha$
$tan(\alpha)=\sqrt{3}$
One solution in quadrant one and another in quadrant three.
$\alpha=\frac{\pi}{3},\frac{4\pi}{3}$ or we can write this as a general solution: $\alpha=\frac{\pi}{3}+k\pi$.
$\frac{\theta}{2}=\frac{\pi}{3}+k\pi$
	This means that it will take **longer** (slowing down; horizontal stretch; whatever you want to call it) to complete a full cycle around the unit circle for $\theta$. Thus, fewer solutions.
$\theta=\frac{2\pi}{3}+2k\pi$ or simplified as $\theta=\frac{(2+6k)\pi}{3}$
	Notice how this has a period of $2\pi$ instead of the usual $\pi$ for tangent.
So the solutions will be:
- $k=0$, $\theta=\frac{2\pi}{3}$
So $\theta=\frac{2\pi}{3}$ is the only solution within our range.

$$sec(\frac{3\theta}{2})=-2$$
Substitute: $\alpha=\frac{3\theta}{2}$
$sec(\alpha)=-2$
Think $cos(\alpha)=- \frac{1}{2}$
So, $\alpha=\frac{2\pi}{3}, \frac{4\pi}{3}$. As a general solution: $\alpha=\frac{2\pi}{3}+2k\pi$ and $\alpha=\frac{4\pi}{3}+2k\pi$.

So we have: $\frac{3\theta}{2}=\frac{2\pi}{3}+2k\pi$ and $\frac{3\theta}{2}=\frac{4\pi}{3}+2k\pi$.
- $\theta=\frac{4\pi}{9}+ \frac{4k\pi}{3}$
- $\theta=\frac{8\pi}{9}+ \frac{4k\pi}{3}$

Solutions for $\theta=\frac{4\pi}{9}+ \frac{4k\pi}{3}=\frac{(4+12k)\pi}{9}$:
- $k=0$, $\frac{4\pi}{9}$
- $k=1$, $\frac{16\pi}{9}$
Solutions for $\theta=\frac{8\pi}{9}+ \frac{4k\pi}{3}=\frac{(8+12k)\pi}{9}$:
- $k=0, \frac{8\pi}{9}$
- $\cancel{k=1, \frac{20\pi}{9}}$ (over $2\pi$)
So we have three solutions: $\frac{4\pi}{9},\frac{8\pi}{9},\frac{16\pi}{9}$

$$\sqrt{3}cot\theta+1=0$$
$cot\theta=- \frac{1}{\sqrt{3}}$
Think $tan\theta=-\sqrt{3}$. This should be on quadrant two or four.
$\theta=\frac{2\pi}{3},\frac{5\pi}{3}$.

$$4sin\theta+3\sqrt{3}=\sqrt{3}$$
$4sin\theta=\sqrt{3}-3\sqrt{3}$
$4sin\theta=-2\sqrt{3}$
$sin\theta=\frac{-2\sqrt{3}}{4}$
$sin\theta=- \frac{\sqrt{3}}{2}$
$\theta=\frac{4\pi}{3},\frac{5\pi}{3}$

$$sin(3\theta+ \frac{\pi}{18})=1$$
Substitute: $\alpha=3\theta+ \frac{\pi}{18}$.
$sin(\alpha)=1$
$\alpha=\frac{\pi}{2}$. As a general solution: $\alpha=\frac{\pi}{2}+2k\pi$.
$3\theta+ \frac{\pi}{18}=\frac{\pi}{2}+2k\pi$
$3\theta=\frac{\pi+4k\pi}{2}- \frac{\pi}{18}$
$3\theta=\frac{9\pi+36k\pi-\pi}{18}$
$3\theta=\frac{(9+36k-1)\pi}{18}$
$\theta=\frac{(36k+8)\pi}{54}$
$\theta=\frac{2(18k+4)\pi}{54}$
$\theta=\frac{(18k+4)\pi}{27}$
Now we can list out the solutions:
- $k=0, \frac{4\pi}{27}$
- $k=1, \frac{22\pi}{27}$
- $k=2, \frac{40\pi}{27}$

$$cos\theta=0.6$$
How do we solve for cosine when we are not on the unit circle? We use cosine inverse.
$cos^{-1}(cos\theta)=cos^{-1}(0.6)$
$\theta=cos^{-1}0.6$
$\theta\approx0.927$
So, on a unit circle (not cosine graph!):
![[Pasted image 20240913201728.png]]
Rmb that inverse function has to be one-to-one, so they'll give out one solution. BUT! Understand that we can infer from the unit circle that there would be another angle that would make $cos\theta=0.6$. So how do we figure out the angle for the red line? That's $2\pi-\theta$, or in our case:
$2\pi-0.927\approx5.36 \text{ Radians}$

$$sin\theta=0.4$$
$\theta=sin^{-1}(0.4)$
$\theta\approx0.411$
![[Pasted image 20240913202332.png]]
Now what's that angle? That's $\pi-\theta$:
$\pi-0.411\approx2.73 \text{ Radians}$

Let's try out some problems where you cannot isolate the trig function:
$$2cos^{2}\theta+cos\theta=1$$
See how we cannot isolate here... Ask yourself: Is this factorable? 
Substitute: $x=cos\theta$.
$2x^{2}+x=1$
$2x^{2}+x-1=0$
This is a [[Pre-calculus - College Algebra#Introduction to Solving Quadratics|quadratic equation]] and it is certainly factorable.
![[Pasted image 20240913203058.png]]
$(x+1)(2x-1)=0$
By zero product property:
$x=-1, \frac{1}{2}$
Now, get that:
- $cos\theta=-1$
- $cos\theta= \frac{1}{2}$
We can now easily find $\theta$ using the unit circle:
$\theta=\pi$ and $\theta= \frac{\pi}{3}, \frac{5\pi}{3}$

$$(tan\theta-1)(sec\theta-1)=0$$
We can use zero product property to solve this:
- $tan\theta-1=0\to tan\theta=1$
	- Think quadrant one and three: $\theta=\frac{\pi}{4}, \frac{5\pi}{4}$
- $sec\theta-1=0 \to sec\theta=1$
	- $\theta=0$

Real stuff: these will demonstrate the importance of [[#Introduction to Using Trigonometric Identities|identities]].
$$sin^{2}\theta-cos^{2}\theta=1+cos\theta$$
Notice that we have two cosine out of three. Let's try to change sine into cosine. The only identity we know thus far is the [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Identity]] ($x^{2}+y^{2}=r^{2}$):
	$cos^{2}\theta+sin^{2}\theta=1$
	$sin^{2}\theta=1-cos^{2}\theta$
We can substitute this in our equation:
$(1-cos^{2}\theta)-cos^{2}\theta=1+cos\theta$
$1-2cos^{2}\theta=1+cos\theta$
$-2cos^{2}\theta=cos\theta$
	Do not try to divide by things that *could be* equal 0. That will cause a domain issues. 
$0=2cos^{2}\theta+cos\theta$
Now we can try factoring:
$0=cos\theta(2cos\theta+1)$
By zero product property:
- $cos\theta=0$
- $2cos\theta+1=0\to cos\theta=- \frac{1}{2}$
So, our angle is: $\theta=\frac{\pi}{2},\frac{3\pi}{2}, \frac{2\pi}{3}, \frac{4\pi}{3}$.

$$cos\theta=-sin(-\theta)$$
We know that sine is an odd function, so that $sin(-\theta)=-sin(\theta)$. Replacing this in our equation:
$cos \theta=-(-sin(\theta))$
$cos \theta=sin \theta$
We can divide both side by $cos\theta$ to get a $tan\theta$ on one side:
$\frac{cos\theta}{cos\theta}=\frac{sin\theta}{cos\theta}$
$1=tan\theta$
$\theta=\frac{\pi}{4},\frac{5\pi}{4}$

$$tan\theta=2sin\theta$$
We can divide both side by $tan\theta$, and see what'll happen:
$\frac{tan\theta}{tan\theta}=\frac{2sin\theta}{tan\theta}$
$1=2sin\theta\cdot \frac{cos\theta}{sin\theta}$
$1=2cos\theta$
$cos\theta=\frac{1}{2}$
$\theta=\frac{\pi}{3},\frac{5\pi}{3}$

The **rule of thumb**: whenever you're stuck, try to *change everything into sine and cosine*.

## Introduction to Using Trigonometric Identities

Here are the basic identities we've known thus far:
- $tan\theta=\frac{sin\theta}{cos\theta}$
- $cot\theta=\frac{cos\theta}{sin\theta}$
	- $cot\theta=\frac{1}{tan\theta}$
- $csc\theta=\frac{1}{sin\theta}$
- $sec\theta=\frac{1}{cos\theta}$
Notice how these help you change *other trig functions to sine and cosine*.
Here are the [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Identities]] (squared identities), note that there are other ways to write this:
- $sin^{2}\theta+cos^{2}\theta=1$
	- $tan^{2}\theta+1=sec^{2}\theta$
		- This is just the above divided by $cos^{2}\theta$ to all terms.
	- $cot^{2}\theta+1=csc^{2}\theta$
		- This is just the above divided by $sin^{2}\theta$ to all terms.
- Even function identities:
	- $cos(-\theta)=cos\theta$
	- $sec(-\theta)=sec\theta$
- Odd function identities:
	- $sin(-\theta)=-sin(\theta)$
	- $csc(-\theta)=-csc(\theta)$
	- $tan(-\theta)=-tan(\theta)$
	- $cot(-\theta)=-cot(\theta)$

Here's the thought process for solving identities:
1. Start on the *harder* side.
2. If you have more than one fractions, try to combine your fraction (get a common denominator).
3. Use the identities *you know* (don't make up your own!)

For examples:
$$tan\theta\cdot csc\theta$$
$\frac{sin\theta}{cos\theta}\cdot \frac{1}{sin\theta}$
$\frac{1}{cos\theta}=sec\theta$

$$\frac{sin\theta+cos\theta}{cos\theta}+ \frac{cos\theta-sin\theta}{sin\theta}$$
Try to combine your fraction (get a common denominator).
$\frac{sin\theta+cos\theta}{cos\theta}\cdot(\frac{sin\theta}{sin\theta})+ \frac{cos\theta-sin\theta}{sin\theta}\cdot(\frac{cos\theta}{cos\theta})$
$\frac{sin^{2}\theta+sin\theta cos\theta+cos^{2}\theta-sin\theta cos\theta}{cos\theta sin\theta}$
$\frac{sin^{2}\theta+cos^{2}\theta}{cos\theta sin\theta}$
$\frac{1}{cos\theta sin\theta}$
$\frac{1}{cos\theta}\cdot \frac{1}{sin\theta}=csc\theta\cdot sec\theta$
There's really nothing more that we could do here. Rmb, use the identities *you know* (don't make up your own!)

$$\frac{cos^{2}\theta-1}{cos^{2}\theta-cos\theta}$$
I know that $cos^{2}\theta-1=sin^{2}\theta$, but cannot see why we would want to do that (most of the terms are already in cosine). 
Say we substitute $cos\theta=u$.
$\frac{u^{2}-1}{u^{2}-u}$
$\frac{(u-1)(u+1)}{u(u-1)}$
$\frac{u+1}{u}=\frac{cos\theta+1}{cos\theta}$
We can simplify this further:
$\frac{cos\theta}{cos\theta}+ \frac{1}{cos\theta}$
That's: $1+sec\theta$.
Nothing more that we can do here.
## How to Prove Trigonometric Identities

How to prove trig identities:
1. Start with the 'hard side'.
2. Get a single fraction (find a common denominator).
3. Re-write in $\sin$ and $\cos$.
4. Use known identities.
5. Try to work on just 1 side.

- $sin^{2}\theta+cos^{2}\theta=1$
	- $sin^2\theta=1-cos^{2}\theta$
	- $cos^{2}\theta=1-sin^{2}\theta$
- $tan^{2}\theta+1=sec^{2}\theta$
	- This is just $sin^{2}\theta+cos^{2}\theta=1$ divided by $cos^{2}\theta$ to all terms.
	- $tan^{2}\theta=sec^{2}\theta-1$
	- $sec^{2}\theta-tan^{2}\theta=1$
- $cot^{2}+1=csc^{2}\theta$
	- This is just $sin^{2}\theta+cos^{2}\theta=1$ divided by $sin^{2}\theta$ to all terms.
	- $cot^{2}\theta=csc^{2}\theta-1$
	- $csc^{2}\theta-cot^{2}\theta=1$

$$\sec\theta\cdot\sin\theta=\tan\theta$$
Work on the harder side (the left side for me):
$\frac{1}{cos\theta}\cdot sin\theta=tan\theta$
$\frac{sin\theta}{cos\theta}=tan\theta$
$tan\theta=tan\theta$

$$(sec\theta-1)(sec\theta+1)=tan^{2}\theta$$
$(sec^{2}\theta-1)=tan^{2}\theta$
This is a known identity ($tan^{2}\theta+1=sec^{2}\theta$):
$tan^{2}\theta=tan^{2}\theta$

$$cos\theta(tan\theta+cot\theta)=csc\theta$$
We want to turn this into cosine.
$cos\theta(\frac{sin\theta}{cos\theta}+ \frac{cos\theta}{sin\theta})=\frac{1}{sin\theta}$
$\cancel{cos\theta}(\frac{sin^{2}\theta+cos^{2}\theta}{sin\theta\cancel{\cos\theta}})=\frac{1}{sin\theta}$
We know that $sin^{2}\theta+cos^{2}\theta=1$:
$\frac{1}{sin\theta}=\frac{1}{sin\theta}$ or $csc\theta=csc\theta$

$$sin\theta csc\theta-cos^{2}\theta=sin^{2}\theta$$
$sin\theta\cdot \frac{1}{sin\theta}-cos^{2}\theta=sin^{2}\theta$
$1-cos^{2}\theta=sin^{2}\theta$
From $sin^{2}\theta+cos^{2}\theta=1$, that's an identity:
$sin^{2}\theta=sin^{2}\theta$

$$(1-cos^{2}\theta)(1+cot^{2}\theta)=1$$
Working on the hard side:
- We know that $1-cos^{2}\theta=sin^{2}\theta$
- We know that $csc^{2}\theta=1+cot^{2}\theta$
So:
$sin^{2}\theta\cdot\csc^{2}\theta=1$
$sin^{2}\theta\cdot \frac{1}{sin^{2}\theta}=1$
$1=1$

$$sec^{4}\theta-sec^{2}\theta=tan^{4}\theta+tan^{2}\theta$$
$\frac{1}{cos^{4}\theta}- \frac{1}{cos^{2}\theta}=\frac{sin^{4}\theta}{cos^{2}\theta}+ \frac{sin^{2}\theta}{cos^{2}\theta}$
$\frac{1}{cos^{4}\theta}- \frac{1}{cos^{2}\theta}\cdot(\frac{cos^{2}\theta}{cos^{2}\theta})=\frac{sin^{4}\theta}{cos^{4}\theta}+ \frac{sin^{2}\theta}{cos^{2}\theta}\cdot(\frac{cos^{2}\theta}{cos^{2}\theta})$
$\frac{1-cos^{2}\theta}{cos^{4}\theta}=\frac{sin^{4}\theta+sin^{2}\theta\cos^{2}\theta}{cos^{4}\theta}$
$\frac{1-cos^{2}\theta}{cos^{4}\theta}=\frac{sin^{2}\theta(sin^{2}\theta+\cos^{2}\theta)}{cos^{4}\theta}$
We know that:
- $1-cos^{2}\theta=sin^{2}\theta$
- $sin^{2}\theta+cos^{2}\theta=1$
So:
$\frac{sin^{2}\theta}{cos^{4}\theta}=\frac{sin^{2}\theta(1)}{cos^{4}\theta}$
$\frac{sin^{2}\theta}{cos^{4}\theta}=\frac{sin^{2}\theta}{cos^{4}\theta}$
Professor Leonard goes about this more elegantly:
$sec^{2}\theta(sec^{2}\theta-1)=tan^{2}\theta(tan^{2}\theta-1)$
We know that:
- $sec^{2}-1=tan^{2}\theta$
- $tan^{2}\theta-1=sec^{2}\theta$
$sec^{2}\theta\tan^{2}\theta=tan^{2}\theta\sec^{2}\theta$

$$3sin^{2}\theta+4cos^{2}\theta=3+cos^{2}\theta$$
$3sin^{2}\theta+3cos^{2}\theta=3$
$3(sin^{2}\theta+cos^{2}\theta)=3$
We know that $sin^{2}\theta+cos^{2}\theta=1$:
$3=3$
Professor Leonard looked at it as:
$3sin^{2}\theta+3cos^{2}\theta+cos^{2}\theta=3+cos^{2}\theta$
And he just group the first two term to get to $3(1)+cos^{2}\theta=3+cos^{2}\theta$.
That's cool.

$$\frac{sin^{2}(-\theta)-cos^{2}(-\theta)}{sin(-\theta)-cos(-\theta)}=cos\theta-sin\theta$$
Odd and even identities will surely be useful here. However, some points to note:
- $sin^{2}(-\theta)$, we know that sine is an odd function
	- Can we turn this into $-sin^{2}(\theta)$? No! Rmb, the odd identity is $f(-x)=-f(x)$ and this is not squared. 
		I'm saying this because YOU did it!
	- See this as $sin^{2}(-\theta)=[sin(-\theta)]^{2}$. This will affect how your signs will end up.
- You'll see that the same principle applies to even function but will not affect your signs as much.

$\frac{[sin(-\theta)]^{2}-[cos(-\theta)]^{2}}{-sin(\theta)-cos(\theta)}=cos\theta-sin\theta$
$\frac{[-sin(\theta)]^{2}-[cos(\theta)]^{2}}{-sin\theta-cos\theta}=cos\theta-sin\theta$
$\frac{sin^{2}\theta-cos^{2}\theta}{-sin\theta-cos\theta}=cos\theta-sin\theta$
$\frac{-1}{-1}\cdot\frac{sin^{2}\theta-cos^{2}\theta}{-sin\theta-cos\theta}=cos\theta-sin\theta$
$\frac{cos^{2}\theta-sin^{2}\theta}{sin\theta+cos\theta}=cos\theta-sin\theta$
On the left part of the equation, notice that the numerator is a difference of square $(x^{2}-y^{2})=(x-y)(x+y)$:
$\frac{(cos\theta-sin\theta)\cancel{(cos\theta+sin\theta)}}{\cancel{sin\theta+cos\theta}}=cos\theta-sin\theta$
$cos\theta-sin\theta=cos\theta-sin\theta$

$$\frac{1-cot^{2}\theta}{1+cot^{2}\theta}+2cos^{2}\theta=1$$
We know that $1+cot^{2}\theta=csc^{2}\theta=\frac{1}{sin^{2}\theta}$. Think of $1-cot^{2}\theta$ as $\frac{sin^{2}\theta}{sin^{2}\theta}- \frac{cos^{2}\theta}{sin^{2}\theta}= \frac{sin^{2}\theta-cos^{2}\theta}{sin^{2}\theta}$. So:
$\frac{\frac{sin^{2}\theta-cos^{2}\theta}{sin^{2}\theta}}{\frac{1}{sin^{2}\theta}}+2cos\theta=1$
$\frac{sin^{2}\theta-cos^{2}\theta}{\cancel{sin^{2}\theta}}\cdot\cancel{\frac{sin^{2}\theta}{1}}+2cos\theta=1$
$sin^{2}\theta-cos^{2}\theta+2cos\theta=1$
$sin^{2}\theta+cos^{2}\theta=1$
That's an identity:
$1=1$

$$\frac{1+sin\theta}{1-sin\theta}- \frac{1-sin\theta}{1+sin\theta}=4tan\theta sec\theta$$
Working on the left side, firstly, we get the common denominator:
$\frac{(1+sin\theta)^{2}-(1-sin\theta)^{2}}{(1-sin\theta)(1+sin\theta)}=4tan\theta sec\theta$
$\frac{(1+2sin\theta+sin^{2}\theta)-(1-2sin\theta+sin^{2}\theta)}{1-sin^{2}\theta}=4tan\theta sec\theta$
$\frac{1+2sin\theta+sin^{2}\theta-1+2sin\theta-sin^{2}\theta}{1-sin^{2}\theta}=4tan\theta sec\theta$
$\frac{4sin\theta}{1-sin^{2}\theta}=4\tan\theta\sec\theta$
We know that $1-sin^{2}\theta=cos^{2}\theta$:
$\frac{4sin\theta}{cos^{2}\theta}=4tan\theta sec\theta$
$4sin\theta\cdot\frac{1}{cos^{2}\theta}=4tan\theta sec\theta$
$4tan\theta sec\theta=4tan\theta sec\theta$

$$\frac{tan\theta+sec\theta-1}{tan\theta-sec\theta+1}=tan\theta+sec\theta$$
This one is so hard, I got $1=sin\theta$ out of it when I tried it on my own... Professor Leonard advise us that whenever we see like terms but with signs difference like we have in $\frac{tan\theta+sec\theta-1}{tan\theta-sec\theta+1}$, try to factor and get some of the terms to look the same:
$\frac{tan\theta+(sec\theta-1)}{tan\theta-(sec\theta-1)}=tan\theta+sec\theta$
Notice the $sec\theta-1$? This is very close to $sec^{2}-1=tan^{2}\theta$. But we need it to be squared. We can make a difference of square out of this:
$\frac{tan\theta+(sec\theta-1)}{tan\theta-(sec\theta-1)}\cdot\frac{tan\theta+(sec\theta-1)}{tan\theta+(sec\theta-1)}=tan\theta+sec\theta$

$\frac{tan^{2}\theta+2tan\theta(sec\theta-1)+sec^{2}\theta-2sec\theta+1}{tan^{2}\theta-sec^{2}\theta+2sec\theta-1}=tan\theta+sec\theta$

From this we know that:
- $tan^{2}\theta+1=sec^{2}\theta$
- $tan^{2}\theta-sec^{2}\theta=-1$

$\frac{(tan^{2}\theta+1)+2tan\theta(sec\theta-1)+sec^{2}\theta-2sec\theta}{(tan^{2}\theta-sec^{2}\theta)+2sec\theta-1}=tan\theta+sec\theta$

$\frac{(sec^{2}\theta)+2tan\theta(sec\theta-1)+sec^{2}\theta-2sec\theta}{(-1)+2sec\theta-1}=tan\theta+sec\theta$

$\frac{2sec^{2}\theta+2tan\theta(sec\theta-1)-2sec\theta}{2sec\theta-2}=tan\theta+sec\theta$

We can factor out the 2 from both the numerator and denominator:
$\frac{\cancel{2}[sec^{2}\theta+tan\theta(sec\theta-1)-sec\theta]}{\cancel{2}[sec\theta-1]}=tan\theta+sec\theta$

We can group this as:
$\frac{(sec^{2}\theta-sec\theta)+tan\theta(sec\theta-1)}{sec\theta-1}=tan\theta+sec\theta$

We can factor out the $sec\theta$ in the left-most parentheses:
$\frac{sec\theta(sec\theta-1)+tan\theta(sec\theta-1)}{sec\theta-1}=tan\theta+sec\theta$
$\frac{(sec\theta+tan\theta)\cancel{(sec\theta-1)}}{\cancel{sec\theta-1}}=tan\theta+sec\theta$
$tan\theta+sec\theta=tan\theta+sec\theta$
## Introduction to Sum and Difference Formulas in Trigonometry

$$\cos(\alpha+\beta)=\cos\alpha \cos\beta - \sin\alpha \sin\beta$$
$$\cos(\alpha-\beta)=\cos\alpha \cos\beta + \sin\alpha \sin\beta$$
$$\sin(\alpha+\beta)=\sin\alpha \cos\beta + \cos\alpha \sin\beta$$
$$\sin(\alpha-\beta)=\sin\alpha \cos\beta - \cos\alpha \sin\beta$$
$$\tan(\alpha+\beta)=\frac{\tan\alpha+\tan\beta}{1-\tan\alpha\tan\beta}$$
$$\tan(\alpha-\beta)=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}$$
Crazy, I know:
- The sine and cosine formulas come from a *distance formula* on part of the unit circle.
	- A little trick for memorization:
		- Notice that the signs are the same for sine formulas, and the opposite for cosine formulas.
- The tangent formulas come from comparing sine and cosine.

[Sine and Cosine Sum and Difference Proofs](https://www.geogebra.org/m/r4mvnxh2) by [Chip Rollinson](https://www.geogebra.org/u/chiprollinson) is a great way for understanding how this works (credits and deepest gratitude):
![[Pasted image 20240914203131.png]]
![[Pasted image 20240914203146.png]]
	Refer to [[#How to Use the Law of Cosines in Trigonometry|Law of Cosines]].

This is very useful for finding an exact solution for an angle that is not on the unit circle, say $sin(105\degree)$.
	Notice that we can represent $sin(105\degree)$ as $sin(60\degree+45\degree)$.

Let's try it out with an example:
$$sin(105\degree)$$
We can view this as $sin(60\degree+45\degree)$, so we can use the sum formula:
$sin(60\degree+45\degree)=sin(60\degree)cos(45\degree)+cos(60\degree)sin(45\degree)$
Now we can just refer to the unit circle and solve:
$sin(105\degree)=(\frac{\sqrt{3}}{2})(\frac{\sqrt{2}}{2})+(\frac{1}{2})(\frac{\sqrt{2}}{2})$
$sin(105\degree)=\frac{\sqrt{6}}{4}+\frac{\sqrt{2}}{4}$
$sin(105\degree)=\frac{\sqrt{6}+\sqrt{2}}{4}$
And that is an exact solution. 

$$sin(\frac{\pi}{12})$$
We can see this as $sin(\frac{4\pi}{12}- \frac{3\pi}{12})\to sin(\frac{\pi}{3}- \frac{\pi}{4})$, we're using the difference formula here because $\frac{\pi}{12}$ is already small, so it is difficult to think of it as sum of something:
$\sin(\alpha-\beta)=\sin\alpha \cos\beta - \cos\alpha \sin\beta$
$sin(\frac{\pi}{3}- \frac{\pi}{4})=sin(\frac{\pi}{3})cos(\frac{\pi}{4})-cos(\frac{\pi}{3})sin(\frac{\pi}{4})$
$sin(\frac{\pi}{3}- \frac{\pi}{4})=(\frac{\sqrt{3}}{2})(\frac{\sqrt{2}}{2})- (\frac{1}{2})(\frac{\sqrt{2}}{2})$
$sin(\frac{\pi}{3}- \frac{\pi}{4})=\frac{\sqrt{6}-\sqrt{2}}{4}$

$$cos(165\degree)$$
$\cos(\alpha+\beta)=\cos\alpha \cos\beta - \sin\alpha \sin\beta$
$cos(120\degree+45\degree)=cos(120\degree)cos(45\degree)-sin(120\degree)sin(45\degree)$
$cos(120\degree+45\degree)=(- \frac{1}{2})(\frac{\sqrt{2}}{2})- (\frac{\sqrt{3}}{2})(\frac{\sqrt{2}}{2})$
$cos(120\degree+45\degree)=- \frac{\sqrt{2}}{4}- \frac{\sqrt{6}}{4}$
$cos(120\degree+45\degree)=\frac{-\sqrt{2}-\sqrt{6}}{4}$
We can also look at this as $cos(135\degree+30\degree)$.

$$tan(\frac{19\pi}{12})$$
We can look at this as $tan(\frac{4\pi}{12}+ \frac{15\pi}{12})\to tan(\frac{\pi}{3}+ \frac{5\pi}{4})$:
$\tan(\alpha+\beta)=\frac{\tan\alpha+\tan\beta}{1-\tan\alpha\tan\beta}$
$\tan(\frac{\pi}{3}+ \frac{5\pi}{4})=\frac{\tan \frac{\pi}{3} +\tan \frac{5\pi}{4}}{1-\tan \frac{\pi}{3} \tan \frac{5\pi}{4}}$
- $tan\frac{\pi}{3}=\sqrt{3}$
- $tan \frac{5\pi}{4}=1$
$\tan(\frac{\pi}{3}+ \frac{5\pi}{4})=\frac{\sqrt{3} +1}{1-\sqrt{3}\cdot 1}$
Rationalize the denominator:
$\tan(\frac{\pi}{3}+ \frac{5\pi}{4})=\frac{\sqrt{3} +1}{1-\sqrt{3}}\cdot \frac{\sqrt{3}+1}{\sqrt{3}+1}$
$\tan(\frac{\pi}{3}+ \frac{5\pi}{4})=\frac{4+2\sqrt{3}}{-2}=-2-\sqrt{3}$

$$\tan(15\degree)$$
$\tan(\alpha-\beta)=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}$
$tan(60\degree-45\degree)=\frac{tan60\degree-tan45\degree}{1+tan60\degree tan45\degree}$
- $tan60\degree=\sqrt{3}$
- $tan45\degree=1$
$tan(60\degree-45\degree)=\frac{\sqrt{3}-1}{1+\sqrt{3}\cdot 1}$
Rationalize this and we get:
$tan(60\degree-45\degree)=2-\sqrt{3}$

$$sec(-\frac{\pi}{12})$$
Secant is an odd function so $sec(- \frac{\pi}{12})=sec(\frac{\pi}{12})$. We can use the formula for cosine then reciprocate the results to get secant. So, let's view this as $cos(\frac{4\pi}{12}- \frac{3\pi}{12})\to cos(\frac{\pi}{3}- \frac{\pi}{4})$:
$\cos(\alpha-\beta)=\cos\alpha \cos\beta + \sin\alpha \sin\beta$
$cos(\frac{\pi}{3}- \frac{\pi}{4})=(\frac{1}{2})(\frac{\sqrt{2}}{2})+(\frac{\sqrt{3}}{2})(\frac{\sqrt{2}}{2})$
$cos(\frac{\pi}{3}- \frac{\pi}{4})=\frac{\sqrt{6}+\sqrt{2}}{4}$
So:
$sec(-\frac{\pi}{12})=\frac{4}{\sqrt{6}+\sqrt{2}}=\sqrt{6}-\sqrt{2}$

Some examples going in reverse:
$sin(20\degree)cos(80\degree)-cos(20\degree)sin(80\degree)$
That looks very similar to:
$\sin(\alpha-\beta)=\sin\alpha \cos\beta - \cos\alpha \sin\beta$
$sin(20\degree)cos(80\degree)-cos(20\degree)sin(80\degree)=sin(20\degree-80\degree)$
$sin(-60\degree)=-sin(60\degree)=- \frac{\sqrt{3}}{2}$

$$\frac{\tan(40\degree)-\tan(10\degree)}{1+\tan(40\degree)\tan(10\degree)}$$
That's the same as $\tan(\alpha-\beta)=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}$.
$\frac{\tan(40\degree)-\tan(10\degree)}{1+\tan(40\degree)\tan(10\degree)}=tan(40\degree-10\degree)$
$tan(30\degree)=\frac{\sqrt{3}}{3}$

$$sin(\frac{\pi}{12})cos(\frac{7\pi}{12})-cos(\frac{\pi}{12})sin(\frac{7\pi}{12})$$
That's the same format as the difference of sine formula:
$\sin(\alpha-\beta)=\sin\alpha \cos\beta - \cos\alpha \sin\beta$
$sin(\frac{\pi}{12})cos(\frac{7\pi}{12})-cos(\frac{\pi}{12})sin(\frac{7\pi}{12})=sin(\frac{\pi}{12}- \frac{7\pi}{12})$
$sin(\frac{\pi}{12}- \frac{7\pi}{12})=sin(- \frac{6\pi}{12})=-sin(\frac{\pi}{2})=-1$

## Using Sum and Difference Formulas in Trigonometry


$$\cos(\alpha\pm\beta)=\cos\alpha \cos\beta \mp \sin\alpha \sin\beta$$
$$\sin(\alpha\pm\beta)=\sin\alpha \cos\beta \pm \cos\alpha \sin\beta$$
$$\tan(\alpha\pm\beta)=\frac{\tan\alpha\pm\tan\beta}{1\mp\tan\alpha\tan\beta}$$
- Notice the $\pm$ and $\mp$ sign is just to condense the formula. You can read this by following either the top or bottom sign. 
$$sin\alpha=\frac{3}{5}, 0<\alpha<\frac{\pi}{2}$$
$$cos\beta=\frac{2\sqrt{5}}{5}, - \frac{\pi}{2}<\beta< 0$$
$$\text{Find }sin(\alpha+\beta), cos(\alpha+\beta), tan(\alpha-\beta)$$
- From $0<\alpha<\frac{\pi}{2}$, we know that $\alpha$ is in quadrant one.
- We know that with the sine function, $\frac{3}{5}=\frac{y}{r}$.
![[Pasted image 20240914232527.png]]
From here, we can write any trig functions:
$cos\alpha=\frac{4}{5}$
$tan\alpha=\frac{3}{4}$

Let's move on to $\beta$:
- $- \frac{\pi}{2}<\beta< 0$ tells us that $\beta$ is in quadrant four.
![[Pasted image 20240914233342.png]]
So:
$sin\beta=- \frac{\sqrt{5}}{5}$
$tan\beta=- \frac{\sqrt{5}}{2\sqrt{5}}=- \frac{1}{2}$

We can know find $sin(\alpha+\beta), cos(\alpha+\beta), tan(\alpha-\beta)$:
$sin(\alpha+\beta)=sin\alpha cos\beta + cos\alpha sin\beta$
$sin(\alpha+\beta)=(\frac{3}{5})(\frac{2\sqrt{5}}{5})+(\frac{4}{5})(-\frac{\sqrt{5}}{5})$
$sin(\alpha+\beta)=\frac{6\sqrt{5}}{25}- \frac{4\sqrt{5}}{25}$
$sin(\alpha+\beta)=\frac{2\sqrt{5}}{25}$

$cos(\alpha+\beta)=cos\alpha cos\beta- sin\alpha sin\beta$
$cos(\alpha+\beta)=(\frac{4}{5}) (\frac{2\sqrt{5}}{5})- (\frac{3}{5}) (- \frac{\sqrt{5}}{5})$
$cos(\alpha+\beta)=\frac{8\sqrt{5}}{25}+ \frac{3\sqrt{5}}{25}$
$cos(\alpha+\beta)=\frac{11\sqrt{5}}{25}$

$\tan(\alpha-\beta)=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}$
$\tan(\alpha-\beta)=\frac{(\frac{3}{4})-(- \frac{1}{2})}{1+(\frac{3}{4})(- \frac{1}{2})}$
$tan(\alpha-\beta)=\frac{\frac{5}{4}}{\frac{5}{8}}=2$

$$sin\alpha=\frac{5}{13}, - \frac{3\pi}{2}<\alpha<-\pi$$
$$tan\beta=-\sqrt{3}, \frac{\pi}{2}<\beta< \pi$$
$$\text{Find }sin(\alpha+\beta), cos(\alpha+\beta), tan(\alpha-\beta)$$
- From $- \frac{3\pi}{2}<\alpha<-\pi$, we know that $\alpha$ is in quadrant two.
![[Pasted image 20240914234636.png]]
$cos\alpha= - \frac{12}{13}$
$tan\alpha=- \frac{5}{12}$

Let's move on to $\beta$:
- $\frac{\pi}{2}<\beta< \pi$ tells us that $\beta$ is also in quadrant two.
$tan\beta=-\sqrt{3}$ seems like it would be in the unit circle. Say $\beta=\frac{2\pi}{3}$, where $sin\beta= \frac{\sqrt{3}}{2}$ and $cos\beta= - \frac{1}{2}$.

We can know find $sin(\alpha+\beta), cos(\alpha+\beta), tan(\alpha-\beta)$:
$sin(\alpha+\beta)=sin\alpha cos\beta + cos\alpha sin\beta$
$sin(\alpha+\beta)=(\frac{5}{13}) (- \frac{1}{2}) + (- \frac{12}{13}) (\frac{\sqrt{3}}{2})$
$sin(\alpha+\beta)=-\frac{5}{26} - \frac{12\sqrt{3}}{26}$
$sin(\alpha+\beta)=\frac{-5-12\sqrt{3}}{26}$

$cos(\alpha+\beta)=cos\alpha cos\beta- sin\alpha sin\beta$
$cos(\alpha+\beta)=(- \frac{12}{13}) (- \frac{1}{2})- (\frac{5}{13}) (\frac{\sqrt{3}}{2})$
$cos(\alpha+\beta)=\frac{12}{26}- \frac{5\sqrt{3}}{26}$
$cos(\alpha+\beta)=\frac{12-5\sqrt{3}}{26}$

$\tan(\alpha-\beta)=\frac{\tan\alpha-\tan\beta}{1+\tan\alpha\tan\beta}$
$\tan(\alpha-\beta)=\frac{(- \frac{5}{12})-(-\sqrt{3})}{1+(- \frac{5}{12})(- \sqrt{3})}$
$\tan(\alpha-\beta)=\frac{ \frac{-5+12\sqrt{3}}{12}}{\frac{12+5\sqrt{3}}{12}}$
$\tan(\alpha-\beta)=\frac{-5+12\sqrt{3}}{5\sqrt{3}+12}$

$$sin(sin^{-1} \frac{1}{2}+ cos^{-1}0)$$
First of all the $sin$ in front is *not distributable*. Rmb that inverse functions return some *angle*, so this is essentially $sin(\alpha+\beta)$, if $sin^{-1} \frac{1}{2}=\alpha$ and $cos^{-1}0=\beta$.
We know that:
- $sin\alpha= \frac{1}{2}$ and $cos\beta=0$, these are all on the unit circle.
- Since these come from inverse functions, be careful with your [[#Introduction to Inverse Trigonometric Functions|domain and range]].
$\alpha=\frac{\pi}{6}, \cancel{\frac{5\pi}{6}}$ (rmb: the output should be within $- \frac{\pi}{2}\leq\alpha\leq \frac{\pi}{2}$)
$\beta=\frac{\pi}{2}, \cancel{\frac{3\pi}{2}}$ (rmb: the output should be within $0\leq\beta\leq \pi$)
$sin(\frac{\pi}{6}+ \frac{\pi}{2})=sin(\frac{\pi}{6})cos(\frac{\pi}{2})+ cos(\frac{\pi}{6})sin(\frac{\pi}{2})$
$sin(\frac{\pi}{6}+ \frac{\pi}{2})=(\frac{1}{2})(0)+ (\frac{\sqrt{3}}{2})(1)$
$sin(\frac{\pi}{6}+ \frac{\pi}{2})=\frac{\sqrt{3}}{2}$
	Notice that $sin(\frac{2\pi}{3})$ is indeed $\frac{\sqrt{3}}{2}$.

$$cos(tan^{-1} \frac{4}{3}+cos^{-1} \frac{5}{13})$$
Same as before, however the angles inside parentheses are clearly not in the unit circle.
Let's think about $tan^{-1} \frac{4}{3}$ first:
$tan\alpha=\frac{4}{3}=\frac{y}{x}$. 
However, this could be either quadrant one or three.
Rmb that, coming from an inverse function, the output must be in this range: $- \frac{\pi}{2}<\alpha< \frac{\pi}{2}$.
![[Pasted image 20240915001509.png]]
$sin\alpha=\frac{4}{5}$
$cos\alpha=\frac{3}{5}$

Next, $cos^{-1} \frac{5}{13}$:
$cos\beta= \frac{5}{13}, 0\leq\beta\leq\pi$.
![[Pasted image 20240915001814.png]]
$sin\beta= \frac{12}{13}$
$tan\beta= \frac{12}{5}$ (although we won't be needing this.)

$cos(\alpha+\beta)=cos\alpha cos\beta - sin\alpha sin\beta$
$cos(\alpha+\beta)=(\frac{3}{5}) (\frac{5}{13}) - (\frac{4}{5}) (\frac{12}{13})$
$cos(\alpha+\beta)=\frac{15}{65} - \frac{48}{65}$
$cos(\alpha+\beta)=-\frac{33}{65}$
### Cofunction Identities

$$cos(\frac{\pi}{2}-\theta)=sin\theta$$
$$sin(\frac{\pi}{2}-\theta)=cos\theta$$
These are often seen in textbooks and they come from the similarity between [[#Graph of Sine]] and [[#Graph of Cosine]]:
![[Pasted image 20240915002818.png]]
$$cos(\frac{\pi}{2}-\theta)$$
From the difference formula:
$cos(\frac{\pi}{2}-\theta)=cos(\frac{\pi}{2})cos\theta + sin(\frac{\pi}{2})sin\theta$
We know that $cos(\frac{\pi}{2})=0$ and $sin(\frac{\pi}{2})=1$:
$cos(\frac{\pi}{2}-\theta)=\cancel{cos(\frac{\pi}{2})cos\theta} + (1)sin\theta$
$cos(\frac{\pi}{2}-\theta)=sin\theta$


$$sin(\frac{\pi}{2}-\theta)$$
From the difference formula:
$sin(\frac{\pi}{2}-\theta)=sin(\frac{\pi}{2})cos(\theta)-cos(\frac{\pi}{2})sin(\theta)$
We know that $cos(\frac{\pi}{2})=0$ and $sin(\frac{\pi}{2})=1$:
$sin(\frac{\pi}{2}-\theta)=(1)cos(\theta)-\cancel{cos(\frac{\pi}{2})sin(\theta)}$
$sin(\frac{\pi}{2}-\theta)=cos(\theta)$

These one are not so common, but try it out:
$$sin(\theta+ \frac{\pi}{2})$$
$sin(\theta+ \frac{\pi}{2})=sin\theta cos \frac{\pi}{2} + cos\theta sin(\frac{\pi}{2})$
We know that $cos(\frac{\pi}{2})=0$ and $sin(\frac{\pi}{2})=1$:
$sin(\theta+ \frac{\pi}{2})=cos\theta$
This says that: **Cosine is just Sine shifted to the left by $\frac{\pi}{2}$.**

$$cos(\theta- \frac{\pi}{2})$$
$cos(\theta- \frac{\pi}{2})=cos\theta cos \frac{\pi}{2}+sin\theta sin \frac{\pi}{2}$
$cos(\theta- \frac{\pi}{2})=sin\theta$
This says that: **Sine is just Cosine shifted to the right by $\frac{\pi}{2}$.**

Note: Refer to [[#Complementary Angles and Cofunctions]].
## Proving the Double and Half Angle Formulas for Trigonometry
![[Pasted image 20240915143218.png]]
We will be using the identities and formulas we've learned previously to make *more* identities and formulas.
### Double-Angle Formulas
Think the sum formula for sine:
$sin(\alpha+\beta)=sin\alpha cos\beta+cos\alpha sin\beta$
What if $\alpha=\beta=\theta$? We can call this:
$sin(\theta+\theta)=sin\theta cos\theta+cos\theta sin\theta$
And there we have the double angle formula for sine.
$$sin(2\theta)=2sin\theta cos\theta$$

Let's try the same for cosine (notice that there will be three for cosine):
$cos(\alpha+\beta)=cos\alpha cos\beta-sin\alpha sin\beta$
$cos(\theta+\theta)=cos\theta cos\theta- sin\theta sin\theta$
And there we have our first formula for cosine:
$$cos(2\theta)=cos^{2}\theta- sin^{2}\theta$$
Since the terms are squared, unlike in sine, we can use the [[#Pythagorean Identities for Trigonometric Functions|Pythagorean identity]] to manipulate this formula a little.
We know that,  $sin^{2}\theta=1-cos^{2}\theta$:
$cos(2\theta)=cos^{2}\theta-(1-cos^{2}\theta)$
Now we have the second formula for cosine:
$$cos(2\theta)=2cos^{2}\theta-1$$
We can do this the other way and say that $cos^{2}\theta=1-sin^{2}\theta$:
$cos(2\theta)=(1-sin^{2}\theta)- sin^{2}\theta$
That's our final formula for cosine:
$$cos(2\theta)=1-2sin^{2}\theta$$

From these identities, we could manipulate it to get some other identities e.g. formula for $cos^{2}\theta$ from $cos(2\theta)=2cos^{2}\theta-1$:
$$cos^{2}\theta=\frac{cos(2\theta)+1}{2}$$
Or formula for $sin^{2}\theta$ from $cos(2\theta)=1-2sin^{2}\theta$:
$sin^{2}\theta=\frac{cos(2\theta)-1}{-2}$
$$sin^{2}\theta=\frac{1-cos(2\theta)}{2}$$

Let's move on to tangent:
$\tan(\alpha+\beta)=\frac{\tan\alpha+\tan\beta}{1-\tan\alpha\tan\beta}$
Say, $\alpha=\beta=\theta$:
$tan(\theta+\theta)=\frac{tan\theta+tan\theta}{1-tan\theta tan\theta}$
This is the double angle formula for tangent:
$$tan(2\theta)=\frac{2tan\theta}{1-tan^{2}\theta}$$
Interestingly, since we know that $tan^{2}\theta= \frac{sin^{2}\theta}{cos^{2}\theta}$:
$tan^{2}\theta=\frac{\frac{1-cos(2\theta)}{2}}{\frac{cos(2\theta)+1}{2}}$
$$tan^{2}\theta= \frac{1-cos(2\theta)}{1+cos(2\theta)}$$
That's another identity.
### Half-Angle Formulas
$$sin^{2}\theta=\frac{1-cos(2\theta)}{2}$$
$$cos^{2}\theta=\frac{cos(2\theta)+1}{2}$$$$tan^{2}\theta= \frac{1-cos(2\theta)}{1+cos(2\theta)}$$
We'll use these to work on our half-angle formulas. Let $\theta=\frac{\alpha}{2}$:
$sin^{2}(\frac{\alpha}{2})=\frac{1-cos(2\cdot \frac{\alpha}{2})}{2}$
$sin^{2}(\frac{\alpha}{2})=\frac{1-cos(\alpha)}{2}$
To get from $sin^{2}(\frac{\alpha}{2})\to sin(\frac{\alpha}{2})$, just put on a square root:
$\sqrt{sin^{2}(\frac{\alpha}{2})}=\pm\sqrt{\frac{1-cos(\alpha)}{2}}$
$$sin(\frac{\alpha}{2})=\pm\sqrt{\frac{1-cos(\alpha)}{2}}$$
Rmb that:
- Sine is positive in quadrant one and two, and negative in quadrant three and four.
- To know what sign to use, find the quadrant that $\frac{\alpha}{2}$ belongs to.

For cosine:
$cos^{2}\theta=\frac{cos(2\theta)+1}{2}$
$cos^{2}(\frac{\alpha}{2})=\frac{cos(2\cdot\frac{\alpha}{2})+1}{2}$
$cos^{2}(\frac{\alpha}{2})=\frac{cos(\alpha)+1}{2}$
$\sqrt{cos^{2}(\frac{\alpha}{2})}=\pm\sqrt{\frac{cos(\alpha)+1}{2}}$
$$cos(\frac{\alpha}{2})=\pm\sqrt{\frac{cos(\alpha)+1}{2}}$$
Rmb that cosine is positive in quadrant one and four, and negative in quadrant two and three.

For tangent:
$tan^{2}\theta=\frac{1-cos(2\theta)}{1+cos(2\theta)}$
$tan^{2}(\frac{\alpha}{2})=\frac{1-cos(2(\frac{\alpha}{2}))}{1+cos(2(\frac{\alpha}{2}))}$
$tan^{2}(\frac{\alpha}{2})=\frac{1-cos(\alpha)}{1+cos(\alpha)}$
$\sqrt{tan^{2}(\frac{\alpha}{2})}=\pm\sqrt{\frac{1-cos(\alpha)}{1+cos(\alpha)}}$
$$tan(\frac{\alpha}{2})=\pm\sqrt{\frac{1-cos(\alpha)}{1+cos(\alpha)}}$$
Rmb that tangent is positive in quadrant one an three, and negative in quadrant two and four.

## How to Use the Double and Half Angle Formulas for Trigonometry

For example:
$$cos\theta=\frac{3}{5}, 0<\theta<\frac{\pi}{2}$$
Find: $sin(2\theta),cos(2\theta),tan(2\theta),sin(\frac{\theta}{2}),cos(\frac{\theta}{2}),tan(\frac{\theta}{2})$
- $0<\theta,\frac{\pi}{2}$ says that we're in quadrant one.
- From $x^{2}+y^{2}=r^{2}$, we get that:
	- $3^{2}+y^{2}=5^{2}$
	- $y=4,\cancel{-4}$
- So: $sin\theta=\frac{4}{5}$ and $tan\theta=\frac{4}{3}$
$sin(2\theta)=2sin\theta cos\theta$
$sin(2\theta)=2(\frac{4}{5})(\frac{3}{5})=\frac{24}{25}$

$cos(2\theta)=cos^{2}\theta-sin^{2}\theta$
$cos(2\theta)=(\frac{3}{5})^{2}-(\frac{4}{5})^{2}=\frac{9}{25}- \frac{16}{25}=- \frac{7}{25}$
	Note that we can use any of the three double-angle formula for cosine and get the same solution.
Since $sin(2\theta)$ is positve but $cos(2\theta)$ is negative, we get that $2\theta$ is in quadrant two.

$tan(2\theta)=\frac{2tan\theta}{1-tan^{2}\theta}$
$tan(2\theta)=\frac{2\frac{4}{3}}{1-(\frac{4}{3})^{2}}=\frac{\frac{8}{3}}{- \frac{7}{9}}=-3$

$sin(\frac{\theta}{2})=\pm\sqrt{\frac{1-cos\theta}{2}}$
$sin(\frac{\theta}{2})=\pm\sqrt{\frac{1- \frac{3}{5}}{2}}$
$sin(\frac{\theta}{2})=\pm\sqrt{\frac{1}{5}}$
Since we know that $\theta$ is in quadrant one, $\frac{\theta}{2}$ must also be in quadrant one, so $sin(\frac{\theta}{2})$ must be positive:
$sin(\frac{\theta}{2})=\sqrt{\frac{1}{5}}=\frac{\sqrt{5}}{5}$

$cos(\frac{\theta}{2})=\pm\sqrt{\frac{cos\theta+1}{2}}$
$cos(\frac{\theta}{2})=\sqrt{\frac{(\frac{3}{5})+1}{2}}$
$cos(\frac{\theta}{2})=\sqrt{\frac{\frac{8}{5}}{2}}$
$cos(\frac{\theta}{2})=\sqrt{\frac{4}{5}}= \frac{2}{\sqrt{5}}=\frac{2\sqrt{5}}{5}$

$tan(\frac{\theta}{2})=\pm\sqrt{\frac{1-cos\theta}{1+cos\theta}}$
$tan(\frac{\theta}{2})=\sqrt{\frac{1-(\frac{3}{5})}{1+(\frac{3}{5})}}$
$tan(\frac{\theta}{2})=\sqrt{\frac{\frac{2}{5}}{\frac{8}{5}}}$
$tan(\frac{\theta}{2})=\sqrt{\frac{1}{4}}=\frac{1}{2}$
Be a little careful with tangent, but get that tangent in quadrant one are always positive.

$$csc\theta=-\sqrt{5}, cos\theta<0$$
- $cos\theta<0$ tells you that the $x$-coordinate is *negative*, which means that we're in either quadrant two or three.
- $csc\theta$ being negative means that its reciprocal, $sin\theta$, is also negative. This means that we're surely in quadrant three ($\pi<\theta< \frac{3\pi}{2}$).
$sin\theta=- \frac{1}{\sqrt{5}}=- \frac{\sqrt{5}}{5}$
From $y^{2}+x^{2}=r^{2}$, we get that:
$(-\sqrt{5})^{2}+x^{2}=5^{2}$
$x^{2}=20$
$\sqrt{x^{2}}=\pm\sqrt{20}$
$x=\pm2\sqrt{5}$
From the above, we noted that $x$-coordinate is negative. So $x=- 2\sqrt{5}$.
From this, we get that: $cos\theta=-\frac{2\sqrt{5}}{5}$ and $tan\theta= \frac{\sqrt{5}}{2\sqrt{5}}=\frac{1}{2}$ (notice that tangent is positive since we're in quadrant three).
$sin(2\theta)=2sin\theta cos\theta$
$sin(2\theta)=2(- \frac{\sqrt{5}}{5}) (- \frac{2\sqrt{5}}{5})=\frac{20}{25}=\frac{4}{5}$

$cos(2\theta)=2cos^{2}\theta-1$
$cos(2\theta)=2(-\frac{2\sqrt{5}}{5})^{2}-1=\frac{40}{25}- \frac{25}{25}=\frac{3}{5}$
Since both $sin(2\theta)$ and $cos(2\theta)$ is positive, we get that $2\theta$ is in quadrant one.

$tan(2\theta)=\frac{2tan\theta}{1-tan^{2}\theta}$
$tan(2\theta)=\frac{2(\frac{1}{2})}{1-(\frac{1}{2})^{2}}=\frac{1}{\frac{3}{4}}=\frac{4}{3}$

Before we tackle the half-angles, we should think about the quadrant of $\frac{\theta}{2}$ first. We can do this by taking the range for $\theta$ and divide everything by 2:
$\pi<\theta< \frac{3\pi}{2}\to \frac{\pi}{2}<\frac{\theta}{2}< \frac{3\pi}{4}$
And $\frac{\pi}{2}<\frac{\theta}{2}< \frac{3\pi}{4}$ is in quadrant two, so $x$ should be negative and $y$ positive (also making the tangent negative).

$sin(\frac{\theta}{2})=\pm\sqrt{\frac{1-cos\theta}{2}}$
$sin(\frac{\theta}{2})=\sqrt{\frac{1-(- \frac{2\sqrt{5}}{5})}{2}}$
$sin(\frac{\theta}{2})=\sqrt{\frac{\frac{5+2\sqrt{5}}{5}}{2}}$
$sin(\frac{\theta}{2})=\sqrt{\frac{5+2\sqrt{5}}{10}}$

$cos(\frac{\theta}{2})=\pm\sqrt{\frac{cos\theta+1}{2}}$
$cos(\frac{\theta}{2})=-\sqrt{\frac{(- \frac{2\sqrt{5}}{5})+1}{2}}$
$cos(\frac{\theta}{2})=-\sqrt{\frac{\frac{5-2\sqrt{5}}{5}}{2}}$
$cos(\frac{\theta}{2})=-\sqrt{\frac{5-2\sqrt{5}}{10}}$

$tan(\frac{\theta}{2})=\pm\sqrt{\frac{1-cos\theta}{1+cos\theta}}$
$tan(\frac{\theta}{2})=-\sqrt{\frac{1-(- \frac{2\sqrt{5}}{5})}{1+ (-\frac{2\sqrt{5}}{5})}}$
$tan(\frac{\theta}{2})=-\sqrt{\frac{\frac{5+2\sqrt{5}}{5}}{ \frac{5-2\sqrt{5}}{5}}}$
$tan(\frac{\theta}{2})=-\sqrt{\frac{5+2\sqrt{5}}{5-2\sqrt{5}}}$

We're we doing this? We are doing this to find an exact solution for some *very awkward* angles. Let's see some example:
$$cos(22.5\degree)$$
Very awkward indeed. However, note that we can look at this as $\frac{45\degree}{2}$ and use half-angle formulas on it:
$sin(45\degree)=\frac{\sqrt{2}}{2}, cos(45\degree)=\frac{\sqrt{2}}{2}$
$cos(\frac{45\degree}{2})=\pm\sqrt{\frac{cos\theta+1}{2}}$
We know that $22.5\degree$ is in quadrant one.
$cos(\frac{45\degree}{2})=\sqrt{\frac{(\frac{\sqrt{2}}{2})+1}{2}}$
$cos(\frac{45\degree}{2})=\sqrt{\frac{2+\sqrt{2}}{4}}$

$$tan(\frac{9\pi}{8})$$
With the periodicity of tangent, that can be viewed as $tan(\frac{\pi}{8})$. With half-angle formula, we can view this as $tan(\frac{\frac{\pi}{4}}{2})$.
So:
$tan(\frac{\theta}{2})=\pm\sqrt{\frac{1-cos\theta}{1+cos\theta}}$
Understand that $\frac{9\pi}{8}$ is on quadrant three (we can also look at this as $\frac{\pi}{8}$ being on quadrant one), so tangent must be positive. Note that $cos \frac{\pi}{4}=\frac{\sqrt{2}}{2}$.
$tan(\frac{\frac{4\pi}{2}}{2})=\sqrt{\frac{1-(\frac{\sqrt{2}}{2})}{1+(\frac{\sqrt{2}}{2})}}$
$tan(\frac{\frac{4\pi}{2}}{2})=\sqrt{\frac{\frac{2-\sqrt{2}}{2}}{\frac{2+\sqrt{2}}{2}}}$
$tan(\frac{\frac{4\pi}{2}}{2})=\sqrt{\frac{2-\sqrt{2}}{2+\sqrt{2}}}$
### More Identities

$$cos^{4}\theta-sin^{4}\theta=cos(2\theta)$$
	$(cos^{2}\theta-sin^{2}\theta)^{2}=cos(2\theta)$
	This is your first thought. Yeah, yours. And it is incorrect.
Think of this as a difference of squares:
$(cos^{2}\theta)^{2}-(sin^{2}\theta)^{2}=cos(2\theta)$
$(cos^{2}\theta-sin^{2}\theta)(cos^{2}\theta+sin^{2}\theta)=cos(2\theta)$
We know that $cos^{2}\theta+sin^{2}\theta=1$:
$cos^{2}\theta-sin^{2}\theta=cos(2\theta)$
That's one of the [[#Double-Angle Formulas|double-angle identity]] for cosine.

$$cos^{2}(2\theta)-sin^{2}(2\theta)=cos(4\theta)$$
Rmb $cos(2\theta)=cos^{2}\theta-sin^{2}\theta$? It doesn't look the same, yes, but the key point here is the doubling. So we can view $\theta$ as $2\theta$, and $2\theta$ as $4\theta$.
$cos(2\cdot2\theta)=cos^{2}(2\cdot\theta)-sin^{2}(2\cdot\theta)$

Find the $\theta$ for below equation $0\leq\theta<2\pi$:
$$cos(2\theta)+6sin^{2}\theta=4$$
That double angle on the left-most term doesn't fit quite nicely with the rest, so let's change that:
$(1-2sin^{2}\theta)+6sin^{2}\theta=4$
$4sin^{2}\theta=3$
$sin^{2}\theta=\frac{3}{4}$
$\sqrt{sin^{2}\theta}=\pm\sqrt{\frac{3}{4}}$
$sin\theta=\pm\sqrt{\frac{3}{4}}$
$sin\theta=\pm\sqrt{\frac{3}{4}}=\pm\frac{\sqrt{3}}{2}$
If $sin\theta=\frac{\sqrt{3}}{2}$ , then $\theta=\frac{\pi}{3}, \frac{2\pi}{3}$.
If $sin\theta=- \frac{\sqrt{3}}{2}$, then $\theta=\frac{4\pi}{3},\frac{5\pi}{3}$

$$cos(2\theta)=cos\theta$$
We know that $cos(2\theta)=2cos^{2}-1$:
$2cos^{2}\theta-1=cos\theta$
Notice the format here, this can be arranged as a [[Pre-calculus - College Algebra#Introduction to Solving Quadratics|quadratic equation]]:
$2cos^{2}\theta-cos\theta-1=0$
![[Pasted image 20240915184402.png]]
$(cos\theta-1)(2cos\theta+1)=0$
So $cos\theta=- \frac{1}{2}, 1$:
- if $cos\theta=1$, $\theta=0$
- if $cos\theta=- \frac{1}{2}$, $\theta=\frac{2\pi}{3}, \frac{4\pi}{3}$

$$sin(2\theta)=cos\theta$$
We know that $sin(2\theta)=2sin\theta cos\theta$:
$2sin\theta cos\theta=cos\theta$
$2sin\theta=\frac{cos\theta}{cos\theta}$
$sin\theta=\frac{1}{2}$
$\theta=\frac{\pi}{6},\frac{5\pi}{6}$
Rmb how we said we should not divide by anything that might be equal to zero? That's exactly what I did when I put $\frac{cos\theta}{cos\theta}$. We must bear our sins and handle a special case where $cos\theta=0$.
If $cos\theta=0$, then $\theta=\frac{\pi}{2}, \frac{3\pi}{2}$.

Or we could've done this more properly by:
$2sin\theta cos\theta=cos\theta$
$2sin\theta cos\theta-cos\theta=0$
$cos\theta(2sin\theta-1)=0$
Now we have:
- $cos\theta=0$
- $sin\theta= \frac{1}{2}$
And get the same solutions.

## How to Use Product to Sum and Sum to Product Formulas in Trig

### Product to Sum Formulas

Proving product to sum formulas:
$$cos(\alpha-\beta)=cos\alpha cos\beta+sin\alpha sin\beta$$
$$cos(\alpha+\beta)=cos\alpha cos\beta-sin\alpha sin\beta$$
If we add the two above, one of the term will cancel and another will add up:
$cos(\alpha-\beta)+cos(\alpha+\beta)=cos\alpha cos\beta\cancel{+sin\alpha sin\beta}+cos\alpha cos\beta\cancel{-sin\alpha sin\beta}$
$$cos(\alpha-\beta)+cos(\alpha+\beta)=2cos\alpha cos\beta$$
Divide both sides by two:
$$cos\alpha cos\beta = \frac{1}{2}[cos(\alpha-\beta)+cos(\alpha+\beta)]$$
Instead of adding, let's try subtracting:
$cos(\alpha-\beta)-cos(\alpha+\beta)=cos\alpha cos\beta+sin\alpha sin\beta-cos\alpha cos\beta-sin\alpha sin\beta)$
$cos(\alpha-\beta)-cos(\alpha+\beta)=\cancel{cos\alpha cos\beta}+sin\alpha sin\beta\cancel{-cos\alpha cos\beta}+sin\alpha sin\beta$
$$cos(\alpha-\beta)-cos(\alpha+\beta)=2sin\alpha sin\beta$$
$$sin\alpha sin\beta=\frac{1}{2}[cos(\alpha-\beta)-cos(\alpha+\beta)]$$
Let's do the same for sum formulas for sine:
$$sin(\alpha+\beta)=sin\alpha cos\beta+cos\alpha sin\beta$$
$$sin(\alpha-\beta)=sin\alpha cos\beta-cos\alpha sin\beta$$
Adding the above two:
$sin(\alpha+\beta)+sin(\alpha-\beta)=sin\alpha cos\beta\cancel{+cos\alpha sin\beta}+sin\alpha cos\beta\cancel{-cos\alpha sin\beta}$
$$sin(\alpha+\beta)+sin(\alpha-\beta)=2sin\alpha cos\beta$$
$$sin\alpha cos\beta=\frac{1}{2}[sin(\alpha+\beta)+sin(\alpha-\beta)]$$
That's our final formula. Notice that we don't need a formula for $cos\alpha sin\beta$, since multiplication is *commutative* (order doesn't matter) and that $\alpha$ and $\beta$ denotes a different angle anyway. So, if you ever find yourself with $cos\alpha sin\beta$, commute them first and use the appropriate angle ($\alpha$ is just the angle of the first term and $\beta$ the second)

For examples:
$$sin(285\degree)sin(75\degree)$$
$sin\alpha sin\beta=\frac{1}{2}[cos(\alpha-\beta)-cos(\alpha+\beta)]$
$sin(285\degree)sin(75\degree)=\frac{1}{2}[cos(285\degree-75\degree)-cos(285\degree+75\degree)]$
$sin(285\degree)sin(75\degree)=\frac{1}{2}[cos(210\degree)-cos(360\degree)]$
$sin(285\degree)sin(75\degree)=\frac{1}{2}[(- \frac{\sqrt{3}}{2})-(1)]$
Factor from both terms inside the parentheses:
$sin(285\degree)sin(75\degree)=- \frac{1}{2}(\frac{\sqrt{3}}{2}+1)$

$$cos(285\degree)cos(195\degree)$$
$cos\alpha cos\beta=\frac{1}{2}[cos(\alpha-\beta)+cos(\alpha+\beta)]$
$cos(285\degree)cos(195\degree)=\frac{1}{2}[cos(90\degree)+cos(480\degree)]$
From the [[#Periods|periodicity]] of cosine, $cos(480\degree)=cos(120\degree)$:
$cos(285\degree)cos(195\degree)=\frac{1}{2}[(0)+(- \frac{1}{2})]$
$cos(285\degree)cos(195\degree)=- \frac{1}{4}$

$$sin(4\theta)cos(6\theta)$$
$sin\alpha cos\beta= \frac{1}{2}[sin(\alpha+\beta)+sin(\alpha-\beta)]$
$sin(4\theta)cos(6\theta)=\frac{1}{2}[sin(10\theta)+sin(-2\theta)]$
Since sine is an [[#Pythagorean Identities for Trigonometric Functions|odd function]]:
$sin(4\theta)cos(6\theta)=\frac{1}{2}[sin(10\theta)-sin(2\theta)]$
That's as simplified as we can go.

$$cos(3\theta) cos(4\theta)$$
$cos\alpha cos\beta=\frac{1}{2}[cos(\alpha-\beta)+cos(\alpha+\beta)]$
$cos(3\theta) cos(4\theta)=\frac{1}{2}[cos(3\theta-4\theta)+cos(3\theta+4\theta)]$
$cos(3\theta) cos(4\theta)=\frac{1}{2}[cos(-\theta)+cos(7\theta)]$
Since cosine is an [[#Pythagorean Identities for Trigonometric Functions|even function]]:
$cos(3\theta) cos(4\theta)=\frac{1}{2}[cos(\theta)+cos(7\theta)]$
### Sum to Product Formulas

$$sin\alpha+sin\beta=2sin(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})$$
$$sin\alpha-sin\beta=2sin(\frac{\alpha-\beta}{2})cos(\frac{\alpha+\beta}{2})$$
$$cos\alpha+cos\beta=2cos(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})$$
$$cos\alpha-cos\beta=-2sin(\frac{\alpha+\beta}{2})sin(\frac{\alpha-\beta}{2})$$
For example, think:
- From the product to sum formula of sine: $2sinPcosQ=sin(P+Q)+sin(P-Q)$
	- Say, $P=\frac{\alpha+\beta}{2}$ and $Q= \frac{\alpha-\beta}{2}$
	- $2sin(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})=sin[(\frac{\alpha+\beta}{2})+(\frac{\alpha-\beta}{2})]+sin[(\frac{\alpha+\beta}{2})-(\frac{\alpha-\beta}{2})]$
		- $(\frac{\alpha+\beta}{2})+(\frac{\alpha-\beta}{2})=\alpha$
		- $(\frac{\alpha+\beta}{2})-(\frac{\alpha-\beta}{2})=\beta$
	- $2sin(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})=sin(\alpha)+sin(\beta)$
- We can apply the same idea for each of the corresponding product to sum formula to get the four equation above.
- Note that, although we didn't mentioned this above due to commutativity of multiplication: $sin(\alpha+\beta)-sin(\alpha-\beta)=2cos\alpha sin\beta$.

Let's try a few examples:
$$cos(2\theta)+cos(4\theta)$$
$cos\alpha+cos\beta=2cos(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})$
$cos(2\theta)+cos(4\theta)=2cos(\frac{2\theta+4\theta}{2})cos(\frac{2\theta-4\theta}{2})$
$cos(2\theta)+cos(4\theta)=2cos(3\theta)cos(-\theta)$
Since cosine is an even function:
$cos(2\theta)+cos(4\theta)=2cos(3\theta)cos(\theta)$

$$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})$$
$cos\alpha-cos\beta=-2sin(\frac{\alpha+\beta}{2})sin(\frac{\alpha-\beta}{2})$
$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})=-2sin(\frac{\frac{\theta}{2}+\frac{3\theta}{2}}{2})sin(\frac{\frac{\theta}{2}-\frac{3\theta}{2}}{2})$
$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})=-2sin(\frac{2\theta}{2})sin(\frac{-\theta}{2})$
$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})=-2sin(\theta)sin(-\frac{\theta}{2})$
Since sine is an odd function:
$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})=-2sin(\theta)\cdot-sin(\frac{\theta}{2})$
$cos(\frac{\theta}{2})-cos(\frac{3\theta}{2})=2sin(\theta)sin(\frac{\theta}{2})$

$$sin(\frac{\theta}{2})-sin(\frac{3\theta}{2})$$
$sin\alpha-sin\beta=2sin(\frac{\alpha-\beta}{2})cos(\frac{\alpha+\beta}{2})$
$sin(\frac{\theta}{2})-sin(\frac{3\theta}{2})=2sin(\frac{\frac{\theta}{2}-\frac{3\theta}{2}}{2})cos(\frac{\frac{\theta}{2}+\frac{3\theta}{2}}{2})$
$sin(\frac{\theta}{2})-sin(\frac{3\theta}{2})=2sin(\frac{-\theta}{2})cos(\frac{2\theta}{2})$
Since sine is an odd function:
$sin(\frac{\theta}{2})-sin(\frac{3\theta}{2})=-2sin(\frac{\theta}{2})cos(\theta)$

### Why Would We Use Them?

For example, a zero product property:
$$sin(2\theta)+sin(4\theta)=0$$
- Notice how in the sum form, this is hard to solve. But if we convert this into the product form, we can use *zero product property*.
$sin\alpha+sin\beta=2sin(\frac{\alpha+\beta}{2})cos(\frac{\alpha-\beta}{2})$
$2sin(\frac{2\theta+4\theta}{2})cos(\frac{2\theta-4\theta}{2})=0$
$2sin(3\theta)cos(-\theta)=0$
Since cosine is an even function:
$2sin(3\theta)cos(\theta)=0$
So:
- $sin(3\theta)=0$
- $cos(\theta)=0$
	That means $x$-coordinate is 0 on the unit circle. This would happen at $\theta=\frac{\pi}{2}, \frac{3\pi}{2}$.
We can [[#How to Solve Trigonometric Equations|substitute]] $3\theta=\alpha$:
$sin(\alpha)=0$
This only happens at $\alpha=0, \pi$. We can write this as a general solution:
$\alpha=k\pi$
Thus:
$\theta=\frac{k\pi}{3}$
We can now find the solution within $0\leq\theta<2\pi$:
- $k=1, \text{ } \theta=\frac{\pi}{3}$
- $k=2, \text{ } \theta=\frac{2\pi}{3}$
- $k=3, \text{ } \theta=\pi$
- $k=4, \text{ } \theta=\frac{4\pi}{3}$
- $k=5, \text{ } \theta=\frac{5\pi}{3}$
## Introduction to Right Triangle Trigonometry

A more in-depth look into right triangle trigonometry.
Recap:
![[Pasted image 20240916225515.png]]

![[Pasted image 20240916230649.png]]
- **Opposite** refers to the side *opposite* of the angle. ($a$)
- **Hypotenuse** is the longest side. ($c$)
	Drawing any straight line from your *right* angle ($90\degree$ angle) and it will intersect the hypotenuse. That's one way to think about it.
	![[Pasted image 20240916231153.png]] 
- **Adjacent** is just a side guy. ($b$)

$sin\theta=\frac{opp.}{hyp.}$
$cos\theta=\frac{adj.}{hyp.}$
$tan\theta=\frac{opp.}{adj.}$
$csc\theta=\frac{hyp.}{opp.}$
$sec\theta=\frac{hyp.}{adj.}$
$cot\theta=\frac{adj.}{opp.}$

Pythagorean Theorem: 
$(leg)^{2}+(leg)^{2}=(hyp.)^{2}$ 
$(adj.)^{2}+(opp.)^{2}=(hyp.)^{2}$

For example:
![[Pasted image 20240916230730.png]]
Find the hypotenuse first:
$2^{2}+3^{2}=(hyp.)^{2}$
$13=(hyp.)^{2}$
$hyp.=\pm\sqrt{13}$
We want to keep the hypotenuse positive so: $hyp.=\sqrt{13}$
$sin\theta=\frac{opp.}{hyp.}=\frac{2}{\sqrt{13}}=\frac{2\sqrt{13}}{13}$
$cos\theta=\frac{adj.}{hyp.}=\frac{3}{\sqrt{13}}=\frac{3\sqrt{13}}{13}$
$tan\theta=\frac{opp.}{adj.}=\frac{2}{3}$
$csc\theta=\frac{\sqrt{13}}{2}$
$cos\theta=\frac{\sqrt{13}}{2}$
$cot\theta=\frac{3}{2}$

![[Pasted image 20240916231259.png]]
Find the adjacent first:
$3^{2}+(adj.)^{2}=4^{2}$
$(adj.)^{2}=7$
$adj.=\pm\sqrt{7}$
Once again, we want to keep things positive with right triangle because we don't really need to deal with quadrants and signs. 
$sin\theta=\frac{3}{4}$
$cos\theta=\frac{\sqrt{7}}{4}$
$tan\theta=\frac{3}{\sqrt{7}}=\frac{3\sqrt{7}}{7}$
$csc\theta=\frac{4}{3}$
$sec\theta=\frac{4}{\sqrt{7}}=\frac{4\sqrt{7}}{7}$
$cot\theta=\frac{\sqrt{7}}{3}$

![[Pasted image 20240916231829.png]]
Find the opposite:
$2^{2}+(opp.)^{2}=(\sqrt{5})^{2}$
$(opp.)^{2}=1$
$opp.=\pm1$
Keeping things positive:
$sin\theta=\frac{1}{\sqrt{5}}=\frac{\sqrt{5}}{5}$
$cos\theta=\frac{2}{\sqrt{5}}=\frac{2\sqrt{5}}{5}$
$tan\theta=\frac{1}{2}$
$csc\theta=\sqrt{5}$
$sec\theta=\frac{\sqrt{5}}{2}$
$cot\theta=2$

### Complementary Angles and Cofunctions

![[Pasted image 20240916232254.png]]
Rmb that, inside any triangle, all the angles must sums up to $180\degree$. When two angles add up to $90\degree$, that is called *complementary angles*. This is the reason why trig functions are named the way they did:
- Sine and Cosine
- Tangent and Cotangent
- Secant and Cosecant
These pairings are called *Cofunctions*, and **cofunctions of complementary angles are equal**. What does that mean? Let's look at the trig functions with angle $B$ first:
$sinB=\frac{b}{c}$
$cosB=\frac{a}{c}$
$tanB=\frac{b}{a}$
$cotB=\frac{a}{b}$
$cscB=\frac{c}{b}$
$secB=\frac{c}{a}$
Now think about the cofunctions of complementary angles:
Cofunction of sine is co-sine (huh...):
$cosA=\frac{b}{c}$, so $cosA=sinB$
Cofunction of cosine is sine (duh):
$sinA=\frac{a}{c}$, so $sinA=cosB$
Cofuncion of tangent is cotangent:
$cotA=\frac{b}{a}$, so $cotA=tanB$

| **Function** | **Cofunction** | **Relationship for Complementary Angles** |
| ------------ | -------------- | ----------------------------------------- |
| $sin(A)$     | $cos(B)$       | $sin(A) = cos(B)$                         |
| $cos(A)$     | $sin(B)$       | $cos(A) = sin(B)$                         |
| $tan(A)$     | $cot(B)$       | $tan(A) = cot(B)$                         |
| $cot(A)$     | $tan(B)$       | $cot(A) = tan(B)$                         |
| $sec(A)$     | $csc(B)$       | $sec(A) = csc(B)$                         |
| $csc(A)$     | $sec(B)$       | $csc(A) = sec(B)$                         |
Since $A+B=90\degree$, we can write this in terms of $B$ (or $A$): $A=90\degree-B$.
	Rmb $sin\theta=cos(\frac{\pi}{2}-\theta)$ or $cos\theta=sin(\frac{\pi}{2}-\theta)$ from [[#Cofunction Identities]]? 

| **Function** | **Cofunction** | **Relationship for Complementary Angles** |
| ------------ | -------------- | ----------------------------------------- |
| $sin(A)$     | $cos(B)$       | $sin(90\degree - B) = cos(B)$             |
| $cos(A)$     | $sin(B)$       | $cos(90\degree - B) = sin(B)$             |
| $tan(A)$     | $cot(B)$       | $tan(90\degree - B) = cot(B)$             |
| $cot(A)$     | $tan(B)$       | $cot(90\degree - B) = tan(B)$             |
| $sec(A)$     | $csc(B)$       | $sec(90\degree - B) = csc(B)$             |
| $csc(A)$     | $sec(B)$       | $csc(90\degree - B) = sec(B)$             |
Let's practice this idea:
$$sin30\degree$$
$sin(30\degree)=cos(90\degree-30\degree)$
$sin(30\degree)=cos(60\degree)$

$$tan(50\degree)$$
$tan(50\degree)=cot(90\degree-50\degree)$
$tan(50\degree)=cot(40\degree)$

$$sec(5\degree)$$
$sec(5\degree)=csc(90\degree-5\degree)$
$sec(5\degree)=csc(85\degree)$

$$sin(38\degree)-cos(52\degree)$$
Let's change sine into cosine $sin(38\degree)=cos(52\degree)$, and substitute:
$cos(52\degree)-cos(52\degree)=0$

$$tan(20\degree)- \frac{cos(70\degree)}{cos(20\degree)}$$
$\frac{sin(20\degree)}{cos(20\degree)}- \frac{cos(70\degree)}{cos(20\degree)}$
Substitute $sin(20\degree)=cos(70\degree)$:
$\frac{cos(70\degree)}{cos(20\degree)}- \frac{cos(70\degree)}{cos(20\degree)}$
$tan(20\degree)- \frac{cos(70\degree)}{cos(20\degree)}=0$

$$cos(35\degree)sin(55\degree)+sin(35\degree)cos(55\degree)$$
We know that $sin(55\degree)=cos(35\degree)$ and $cos(55\degree)=sin(35\degree)$:
$cos(35\degree)cos(35\degree)+sin(35\degree)sin(35\degree)$
$cos^{2}(35\degree)+sin^{2}(35\degree)=1$

$$1+tan^{2}(5\degree)-csc^{2}(85\degree)$$
We know that $tan^{2}(5\degree)=cot^{2}(85\degree)$:
$1+cot^{2}(85\degree)-csc^{2}(85\degree)$
$1+ \frac{cos^{2}(85\degree)}{sin^{2}(85\degree)}- \frac{1}{sin^{2}(85\degree)}$
$\frac{sin^{2}(85\degree)}{sin^{2}(85\degree)}+ \frac{cos^{2}(85\degree)}{sin^{2}(85\degree)}- \frac{1}{sin^{2}(85\degree)}$
$\frac{[sin^{2}(85\degree)+cos^{2}(85\degree)]-1}{sin^{2}(85\degree)}$
$\frac{1-1}{sin^{2}(85\degree)}=0$

Professor Leonard did this the other way, which I think it more cool:
$[1+tan^{2}(5\degree)]-csc^{2}(85\degree)$
We know that $1+tan^{2}(5\degree)=sec^{2}(5\degree)$:
$sec^{2}(5\degree)-csc^{2}(85\degree)$
We know that $csc^{2}(85\degree)=sec^{2}(5\degree)$
$sec^{2}(5\degree)-sec^{2}(5\degree)=0$
## Finding Sides and Angles with Right Triangle Trigonometry

For example:
![[Pasted image 20240917214213.png]]
Find $b$.

We know that $A+B=90\degree$. So, in this case: $A+10\degree=90\degree\to A=80\degree$. We're not given a hypotenuse so let's not use sine and cosine. Let's use $A$ as our angle (just preference):
$tan(80\degree)=\frac{4}{b}$
Multiply both side by $b$:
$b\cdot tan(80\degree)=4$
To solve for $b$, we divide both side by the tangent:
$b=\frac{4}{tan(80\degree)}$
This is an exact answer. We can plug this in a calculator and get the answer:
$b\approx0.71$

With this information, we can find $c$:
![[Pasted image 20240917215057.png]]
Can we use $b\approx0.71$? Yes, but since it was rounded, using it in further operations would just increase your error. We can use the exact answer to find the solution:
$sin(80\degree)=\frac{4}{c}$
The the same thing with $c$:
$c=\frac{4}{sin(80\degree)}$
$c\approx4.06$
Notice that the Range of Sine function is $[-1,1]$, so it's natural that the magnitude would increase. Additionally, hypotenuse should be longer than opposite (or adjacent).

![[Pasted image 20240917215608.png]]
We're not given any complementary angles here and are asked to find $c$, $A$, and $B$. From the angle $A$, we're given opposite and adjacent. We can easily find $c$ with those.
$3^{2}+5^{2}=c^{2}$
$34=c^{2}$
$c=\sqrt{34}$ (No $\pm$ here since $c$ refers to a magnitude)

Let's start with angle $A$:
$tanA=\frac{5}{3}$
We can now use [[#How to Use Inverse Trigonometric Functions|inverse function]] to find $A$:
$tan^{-1}(tanA)=tan^{-1}(\frac{5}{3})$
$A\approx59.04\degree$

Onto angle $B$:
$tanB=\frac{3}{5}$
$tan^{-1}(tanB)=tan^{-1}(\frac{3}{5})$
$B\approx30.96\degree$

OR we can also find angle $B$ with $A+B=90\degree$:
$B\approx90\degree-59.04\degree$
$B\approx30.96\degree$ 
Subtraction here doesn't increase your error that much. 

The key point here is that we're using right triangle and [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Theorem]] to keep the answer *exact* before using trig functions.  

![[Pasted image 20240917220812.png]]
Given two sides (hypotenuse and a leg), we can easily find the other side.
$4^{2}+b^{2}=6^{2}$
$b^{2}=20$
$b=\sqrt{20}$

We can now find the angles, starting with $A$:
$sinA=\frac{4}{6}$
$sin^{-1}(sinA)=sin^{-1}(\frac{4}{6})$
$A\approx41.81\degree$

Use subtraction:
$B=90\degree-A$
$B=90\degree-41.81\degree$
$B=48.19\degree$

Now for a more practical example:
Suppose that you want to find the height of something really tall (a volcano).
![[Pasted image 20240917221518.png]]
Say we looked up on Google Map and found that the distance between you and the center of the volcano is 80 feet. You also use a tool to measure the angle between the bottom and the top of the volcano, which turned out to be $85.4\degree$.

So, from the angle we're standing from, we want to find the length of *opposite* side. We know the *adjacent* to be 80 feet. We don't know the hypotenuse. From the picture, note that this *is* a right triangle.

Since we want to find opposite and we know adjacent, let's use tangent:
$tan(85.4\degree)=\frac{h}{80ft}$
- $h$ denotes height of the volcano or the opposite side of right triangle.
$h=80ft \cdot tan(85.4\degree)$ 
Note that we already has an exact solution here. We can also approximate. 
$h\approx994.31$

Additionally, we also know the other angle from $A+B=90\degree$. Let's set that $A=85.4\degree$, so that $B= 4.6\degree$.

## How to Use the Law of Sines in Trigonometry



## How to Use the Law of Cosines in Trigonometry

This is when you want to use trigonometry or find missing sides or angles on *oblique* triangles.
![[Pasted image 20240918211416.png]]

With triangles, you need 2 things to find the third. 
	With a right triangle, you will always know at least one angle (the $90\degree$ angle).
There're 4 cases where we can use law of sines and cosines to solve for some oblique triangles (law of sine for the first two, and law of cosine for the final two):

**Law of Sines:**
1. SAA: 2 Angles & 1 Side.
	![[Pasted image 20240918211819.png]]
	We can easily find the final angle, knowing the other two.
2. SSA: 2 Sides & 1 Angle NOT between them.
	![[Pasted image 20240918211902.png]]
	This one is an *ambiguous* case. Since we don't know the length of the final side, we can get 4 results from this: ^8d71d0
	1. No solutions
		![[Pasted image 20240918214531.png]]
		This happens when one of the legs is *too short* to make a whole triangle.
	2. Becomes a right triangle
		![[Pasted image 20240918214606.png]]
		This happens when the length matches up *exactly* to create a right triangle.
	3. Obtuse triangle or Acute triangle (when one of the leg is *too long*)
		![[Pasted image 20240918214625.png]]
		This happens if the opposite (to the angle) leg is too long to make a right triangle, *but shorter than the other known leg*.
	4. Acute triangle (case 2 of when one of the leg is *too long*)
		![[Pasted image 20240918214743.png]]
		This happens if the opposite leg is longer than the other known leg.
	This is for better understanding only as we don't really have to memorize this and the law of sines will take care of this for us.

**Law of Cosines:**
3. SAS: 2 Sides & 1 Angle between them.
	![[Pasted image 20240918211943.png]]
4. SSS: All 3 sides.
	![[Pasted image 20240918212005.png]]
We will come back to this in [[#How to Use the Law of Cosines in Trigonometry]].
### What is Law of Sines?

Given an oblique triangle:
![[Pasted image 20240918215159.png]]
	If we're given two angles, we don't even need law of sines to find the third one due to property of triangle.

Law of Sines creates *proportions* (two fractions set equal to another) for us. In plain English: "Sine of an angle over its opposite side, always equal sine of an another angle over its opposite side."
$$\frac{sinA}{a}=\frac{sinB}{b}=\frac{sinC}{c}$$
Notice that we'll always only need **2 angles and one side (SAA)** or **2 side and 1 angle (SSA)**.

### Examples

![[Pasted image 20240918215725.png]]
Recognize that this is not a right triangle. We can use any [[#Introduction to Right Triangle Trigonometry|right triangle trig]] on this. From this, think law of sines or cosines. We're given two angles and one side, this is a case for law of sines.

With two angles, we don't even need law of sines here:
$95\degree+45\degree+A=180\degree\to A=40\degree$
![[Pasted image 20240918220137.png]]

From here we can easily apply law of sines to find all the sides, starting with $a$ (the opposite side to $45\degree$) and comparing it with the known side:
$\frac{sin(45\degree)}{a}=\frac{sin(95\degree)}{5}$
Cross multiply:
$5sin(45\degree)=asin(95\degree)$
$a=\frac{5sin(45\degree)}{sin(95\degree)}$, This is an exact answer.
We can use a calculator to find an approximation.
$a\approx3.55$

Onto $b$, the remaining side:
$\frac{sin(40\degree)}{b}=\frac{sin(95\degree)}{5}$
$5sin(40\degree)=bsin(95\degree)$
$b=\frac{5sin(40\degree)}{sin(95\degree)}$
$b\approx3.23$

Next example:
![[Pasted image 20240918220934.png]]
We're given two angles and one side, so we can use law of sines here.
Given two angles, we can find the other.
$85\degree+50\degree+A=180\degree \to A=45\degree$
![[Pasted image 20240918221042.png]]
Find $a$:
$\frac{sin(50\degree)}{a}=\frac{sin(45\degree)}{3}$
Notice how this wouldn't be possible if we didn't find the unknown angle first.
$3sin(50\degree)=asin(45\degree)$
$a=\frac{3sin(50\degree)}{sin(45\degree)}$
$a\approx3.25$

Find $b$:
$\frac{sin(85\degree)}{b}=\frac{sin(45\degree)}{3}$
$3sin(85\degree)=bsin(45\degree)$
$b=\frac{3sin(85\degree)}{sin(45\degree)}$
$b\approx4.23$

For example:
![[Pasted image 20240918221531.png]]
We're given two sides and one angle not between them. We can use law of sines.
Let's label this first:
![[Pasted image 20240918221915.png]]
$\frac{sin(50\degree)}{3}=\frac{sinB}{2}$
$2sin(50\degree)=3sinB$
$\frac{2sin(50\degree)}{3}=sinB$
Now, how do we isolate $B$? We use [[#How to Use Inverse Trigonometric Functions|inverse]]:
$sin^{-1}{(\frac{2sin(50\degree)}{3})}=sin^{-1}(sinB)$
$sin^{-1}{(\frac{2sin(50\degree)}{3})}=B$, This is an exact solution.
$B\approx30.7\degree$
Think about what we have for a moment:
![[Pasted image 20240918222626.png]]
Say $B=\theta$, and put it on [[#How to Use the Unit Circle in Trigonometry|the unit circle]]. $sin\theta$ would give some $y$-coordinate on the unit circle. The inverse of sine would only give solution in quadrant one and four, but rmb that there would be another angle that would give the exact same $y$-coordinate:
![[Pasted image 20240918222842.png]]
And that angle is $180-\theta \degree$. Therefore, in this case, $sin(B)=sin(180\degree-B)$.
Let's name this not to get confused:
- $B_{1}\approx30.7\degree$
- $B_{2}\approx180\degree-30.7\degree\approx149.3\degree$
Since we have two solutions, what is the correct one?
We can use the triangle property to find that out, since we already now know two angles:
$50\degree+149.3\degree+A=180\degree\to A=-19.3$
But that doesn't make any sense! This is NOT a valid triangle.
	Note that there are cases when both angles are valid, leaving us with two possible triangles, as we will see soon enough.
So, we are now certain that $B\approx30.7\degree$ alone.

Onto angle $A$ and side $a$, notice that we putting it into proportions doesn't help us now since we have two unknowns. However, we can find $A$ now knowing the other two angles (albeit, with slight error from rounding):
$A+30.7\degree+50\degree=99.3\degree$

Now we can find side $a$:
$\frac{sin(50\degree)}{3}=\frac{sin(99.3\degree)}{a}$
$asin(50\degree)=3sin(99.3\degree)$
$a=\frac{3sin(99.3\degree)}{sin(50\degree)}$
$a\approx3.86$

![[Pasted image 20240919172830.png]]
We know 2 sides and one angle not between them. This is for law of sine. 
![[Pasted image 20240919172923.png]]
Finding $B$ first:
$\frac{sin(40\degree)}{2}=\frac{sinB}{3}$
$3sin(40\degree)=2sinB$
$\frac{3sin(40\degree)}{2}=sinB$
$sin^{-1}{(\frac{3sin(40\degree)}{2})}=sin^{-1}(sinB)$
$B=sin^{-1}{(\frac{3sin(40\degree)}{2})}$
$B\approx74.62\degree$
Same case as before, we know that there would be another angle on quadrant two with the exact same $y$-coordinate on the unit circle, and that angle is: $180\degree-74.62\approx105.38\degree$.
![[Pasted image 20240919173414.png]]

But in this case, both angle should *work*:
- $B\approx74.62\degree \to A+74.62\degree+40\degree=180\degree \to A=65.38\degree$
- $B\approx105.38\degree \to A+105.38\degree+40\degree=180\degree\to A=34.62\degree$
This is the case where there is two solution, we could either get an obtuse or acute triangle. We have to work with both cases:
- $\frac{sin(34.62\degree)}{a}=\frac{sin(40\degree)}{2}\to a\approx2.83$
- $\frac{sin(65.38\degree)}{a}=\frac{sin(40\degree)}{2}\to a\approx1.77$
![[Pasted image 20240919174728.png]]

![[Pasted image 20240919175140.png]]
Two side and an angle not in-between. 
![[Pasted image 20240919175220.png]]
Find $B$ first:
$\frac{sinB}{5}=\frac{sin(60\degree)}{4}$
$4sinB=5sin(60\degree)$
$sinB=\frac{5sin(60\degree)}{4}$
$sin^{-1}(sinB)=sin^{-1}(\frac{5sin(60\degree)}{4})$
$B=\text{MATH ERROR}$
Math error? Stupid calculator! What's going on here?
Think about this:
$\frac{5sin(60\degree)}{4}\approx1.08$ but the Domain for $sin^{-1}$ is $[0,1]$. That's why it doesn't work, $\frac{5sin(60\degree)}{4}$ is not a valid input for an inverse of sine. There is no solution.

Next example, similar as the mountain height example we did in the previous section:
![[Pasted image 20240919180403.png]]
Find $h$.
Filling in what we know, focusing on the left triangle first:
![[Pasted image 20240919182219.png]]
- The $133\degree$ is from $180\degree-47\degree=133\degree$ since it is a straight line. $12\degree$ is from the property of triangle.

$\frac{sin(12\degree)}{900m}=\frac{sin(133\degree)}{a}$
$a\cdot sin(12\degree)=900m\cdot sin(133\degree)$
$a=\frac{900m\cdot sin(133\degree)}{sin(12\degree)}$
$a\approx3165.86m$

$\frac{sin(12\degree)}{900m}=\frac{sin(35\degree)}{c}$
$c\cdot sin(12\degree)=900m\cdot sin(35\degree)$
$c=\frac{900m\cdot sin(35\degree)}{sin(12\degree)}$
$c\approx2485.87m$

![[Pasted image 20240919182554.png]]
- With $a$, we have the hypotenuse for the big right triangle.
Let's use $35\degree$ as our angle:
$sin(35\degree)=\frac{h}{3165.86m}$
	Notice that we're using rounded numbers here. This will add to the errors, although there are not really other way around this.
$h=3165.86m \cdot sin(35\degree)$
$h\approx1815.86m$
Since we're measuring with our eyes $2m$ above the ground, we add that and get the height of the mountain: $1817.86m$.

## How to Use the Law of Cosines in Trigonometry

Following up from the above, there are 2 cases where law of cosines works (and law of sine doesn't):
**Law of Cosines:**
3. SAS: 2 Sides & 1 Angle between them.
	![[Pasted image 20240918211943.png]]
4. SSS: All 3 sides.
	![[Pasted image 20240918212005.png]]

### What is Law of Cosines?

Given an oblique triangle:
![[Pasted image 20240919193512.png]]
Law of Cosines says that:
$$c^{2}=a^{2}+b^{2}-2ab\cos C$$
	A side squared $(c^{2})$ is the sum of other two side squared ($a^{2}+b^{2}$), minus twice the produce of the sides ($2ab$) and *cosine of the angle between them* ($cosC$).
Let's take a look at the 2 possible cases:
1. SAS: 2 Sides & 1 Angle between them.
	![[Pasted image 20240918211943.png]]
	We want to find the third side (which is the opposite side of the given angle or $C$), to use the law of cosines we need the other two sides ($a$ and $b$). This will fit nicely into the equation.
	Notice that, if we use law of sines, say $a=2$ and $b=3$ and $C=45\degree$:
	$\frac{sinA}{a}=\frac{sinB}{b}=\frac{sinC}{c}$
	$\frac{sinA}{2}=\frac{sinB}{1}=\frac{sin(45\degree)}{c}$
	and we can't really solve for anything (since we'll always be left with 2 unknowns). This is why we must use law of cosines for this scenario.
2. SSS: All 3 sides.
	![[Pasted image 20240918212005.png]]
	Say we're given $a=2$, $b=3$, and $c=4$:
	$\frac{sinA}{2}=\frac{sinB}{3}=\frac{sinC}{4}$
	We cannot really solve for anything. However, if we use law of cosines:
	$c^{2}=a^{2}+b^{2}-2ac\cos C$
	$4^{2}=(2)^{2}+(3)^{2}-2(2)(3)\cos C$
	We're ultimately left with one unknown, which we can use cosine inverse to solve for.

Notice that there are no case of ambiguity with the Law of Cosines. Cosine has different signs for acute and obtuse angles, so solving using the law of cosines gives a clear answer *without ambiguity*.
- If $cos(\theta)>0$, $\theta$ is *acute* (in quadrant one)
- If $cos(\theta)<0$, $\theta$ is *obtuse* (in quadrant two)

Notice that given each applicable scenario, we can solve for any side or angle depending on how we name things:
$c^{2}=a^{2}+b^{2}-2ab\cos C$
$a^{2}=b^{2}+c^{2}-2bc\cos A$
$b^{2}=a^{2}+c^{2}-2ac\cos B$
All of these works.

To think about how this works, imagine that the given angle is $\frac{\pi}{2}$ or $90\degree$, which means that we're dealing with a right triangle:
$c^{2}=a^{2}+b^{2}-2ab\cos C$
Say $C=90\degree$:
$c^{2}=a^{2}+b^{2}-2ab\cos (90\degree)$
We know that, with [[#Introduction to Right Triangle Trigonometry|Right Triangle Trigonometry]], $cos(90\degree)=0$:
$c^{2}=a^{2}+b^{2}$
and that's just the [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Theorem]] (we can say that Pythagorean Theorem is a special case of the Law of Cosines, or that the Law of Cosines is a more generalized version of the Pythagorean theorem ).
#### Proof
We can proof this using right triangle trigonometry:
![[Pasted image 20240919193512.png]]
We split these into two right triangles, our goal is to find side $a$:
![[Pasted image 20240919200951.png]]
Starting with the left $\triangle$:
$cos\theta=\frac{d}{b}$
$d=bcosA$
$sin\theta=\frac{m}{b}$
$m=bsinA$
Onto the right $\triangle$:
$e=c-d$
$e=c-(bcosA)$
We now have the necessary components ($m$ and $e$) to in find $a$:
$a^{2}=m^{2}+e^{2}$
Substitute with above values:
$a^{2}=(bsin\theta)^{2}+[c-(bcosA)]^{2}$
$a^{2}=b^{2}sin^{2}A+(c^{2}-2bccosA+b^{2}cos^{2}A)$
Regroup:
$a^{2}=(b^{2}sin^{2}A+b^{2}cos^{2}A)+c^{2}-2bccosA$
$a^{2}=b^{2}(sin^{2}A+cos^{2}A)+c^{2}-2bccosA$
Since we're working with a right triangle, rmb that $sin^{2}A+cos^{2}A=1$ ([[#Pythagorean Identities for Trigonometric Functions|from the Pythagorean Identities]]):
$a^{2}=b^{2}(1)+c^{2}-2bccosA$
$a^{2}=b^{2}+c^{2}-2bccosA$
A side squared is the sum of other two side squared, minus twice the produce of the sides and *cosine of the angle between them*, as desired.
### Examples
![[Pasted image 20240919195428.png]]
Name the sides and angles:
![[Pasted image 20240919195452.png]]
	It doesn't matter how we name things. What matters is how we apply the law of cosines on it.
Given an angle between two sides, we can use law of cosines:
$c^{2}=a^{2}+b^{2}-2ab\cos C$
$c^{2}=(4)^{2}+(3)^{2}-2(4)(3)\cos(30\degree)$
$c^{2}=16+9-24cos(30\degree)$
$\sqrt{c^{2}}=\sqrt{25-24cos(30\degree)}$
	No $\pm$ here (and in other examples) since $c$ refers to magnitude.
$c=\sqrt{25-24cos(30\degree)}$
$c\approx2.05$

With this information, we can use law of cosines to find $B$ and eventually $A$. We can even use law of sines to find $B$, since we now have all three sides and one angle.

Next example:
![[Pasted image 20240919202944.png]]
This looks like a right triangle, but I'm not really sure... When in doubt, we'd rather use law of cosines to be safe.
![[Pasted image 20240919203058.png]]
We can solve for any angle here, let's start with $A$:
$a^{2}=b^{2}+c^{2}-2bc\cos A$
$(5)^{2}=(4)^{2}+(8)^{2}-2(4)(8)\cos A$
$25=16+64-64\cos A$
$\frac{-55}{-64}=cosA$
$cosA=\frac{55}{64}$
$cos^{-1}(cosA)=cos^{-1}(\frac{55}{64})$
$A\approx30.75\degree$

Solve for $B$:
- using law of cosines
	$b^{2}=a^{2}+c^{2}-2ac\cos B$
	$(4)^{2}=(5)^{2}+(8)^{2}-2(5)(8)\cos B$
	$\frac{-73}{-80}=cosB$
	$cosB=\frac{73}{80}$
	$cos^{-1}(cosB)=cos^{-1}(\frac{73}{80})$
	$B=cos^{-1}(\frac{73}{80})$
	$B\approx24.15\degree$
- using law of sines
	$\frac{sin(30.75\degree)}{5}=\frac{sinB}{4}$
	notice how using law of cosines is much more preferable here because $A$ is rounded, so this will *compound* our error.
	$B=sin^{-1}(\frac{4sin(30.75\degree)}{5})$
	$B\approx24.14\degree$
	Notice the $0.01\degree$ difference here due to compounded error and rounding decision.
	Furthermore, rmb that there are some ambiguous case with law of sines where we could get either obtuse or acute angle. To prevent this, **it is best to solve for the angle opposite the smallest side first** when using the law of sines. 
		This is because the smallest angle will always be acute in a triangle, so there is no ambiguity about whether the angle is obtuse or acute. Once you have found the smallest angle, the remaining angles can be found without ambiguity since the angles in any triangle must sum to $180\degree$.

We'll stick with the more accurate approximation of $B\approx24.15\degree$.

Now, to solve for $C$, we simply use the property of triangle:
$C=180\degree-24.15\degree-30.75\degree$
$C=125.1\degree$

Next example:
![[Pasted image 20240919204238.png]]
Two sides and one angle between them. Law of cosines works here.
![[Pasted image 20240919204317.png]]
To solve for $c$:
$c^{2}=a^{2}+b^{2}-2ab\cos C$
$c^{2}=(2)^{2}+(3)^{2}-2(2)(3)\cos (110\degree)$
$c^{2}=4+9-12\cos (110\degree)$
$c=\sqrt{13-12cos(110\degree)}$
$c\approx4.14$

Now we can solve for $A$:
We can use law of sines here and since $A$ is the angle opposite of the smallest side, there'll be no ambiguity. But let's keep it straightforward and use law of cosines again.
$a^{2}=b^{2}+c^{2}-2bc\cos A$
$(2)^{2}=(3)^{2}+(4.14)^{2}-2(3)(4.14)\cos A$
$4=9+17.1396-24.84cos A$
$cosA=\frac{-22.1396}{-24.84}$
$A=cos^{-1}(\frac{22.1396}{24.84})$
$A\approx26.96$

Now $B=180\degree-110\degree-26.96\degree=43.04\degree$.

Practical example:
Say that we're flying from city $A$ to city $B$ at the speed of $220$ MPH. After 15 minutes, the pilot noticed that there is a $10\degree$ error in flight trajectory. Find the angle needed to be adjusted to reach city $B$:
![[Pasted image 20240919211203.png]]
Focusing on the left $\triangle$,:
We can calculate the distance of the plane to city $A$, which will provide us another side to the triangle:
$\frac{220mi.}{hrs.}\cdot \frac{1hr.}{60mins.} \cdot 15mins.=55 mi.$
![[Pasted image 20240919212001.png]]
We can now find $a$:
$a^{2}=b^{2}+c^{2}-2bc\cos A$
$a^{2}=(55)^{2}+(330)^{2}-2(55)(330)\cos (10\degree)$
$a\approx276.0mi.$
	The $.0$ is necessary to signal that we rounded this.

Knowing all three sides, we can find $C$:
$c^{2}=a^{2}+b^{2}-2ab\cos C$
$(330)^{2}=(276)^{2}+(55)^{2}-2(276)(55)\cos C$
$cosC=\frac{29699}{-30360}$
$C=cos^{-1}(- \frac{29699}{30360})$
$C\approx168.02$

With this we can find the the angle we're looking for:
$180\degree-168.02\degree=11.98\degree$

Now, can our yeeyee pilot make it to city $B$ within scheduled time of 90 minutes?
Since the pilot has burned up 15 minutes, they has $75$ minutes left to make it.
$V=\frac{S}{t}$
$V=\frac{276mi.}{75min.}$
$V=3.68 mi./mins.$ or $220.8$ MPH
They need to increase their speed by 0.8 MPH to make it.

## How to Find the Area of a Triangle with Trigonometry

![[Pasted image 20240921113317.png]]
Let's talk about how the area of a triangle first. 
Notice how if you double the left square and right square, you'll get a rectangle with area $b\cdot h$. So, if we divide this area by two:
$$A=\frac{1}{2}\cdot b \cdot h$$
And this is the formula for area of triangles.
### For Side-Angle-Side

But if the height of the triangle is not given:
![[Pasted image 20240921113628.png]]
If you have two sides and an angle in-between them (SAS), you don't need the height. Instead, you can apply trigonometry to find the area:
Say that the area of the whole triangle is $k$ (since we want to use $A$ for angle).
$k=\frac{1}{2}b\cdot h$
Looking from the angle $C$:
$sin C=\frac{h}{a}$
$h=asinC$
We can substitute this:
$$k=\frac{1}{2}absinC$$
Notice that now you don't need $h$ to solve for this area. This is generalized, so:
$$k=\frac{1}{2}bcsinA$$
$$k=\frac{1}{2}acsinB$$
are also true.

### Examples
![[Pasted image 20240921114303.png]]
$k=\frac{1}{2}absinC$
$k=\frac{1}{2}(3)(4)sin(30\degree)$
$k=3$

![[Pasted image 20240921114903.png]]
$k=\frac{1}{2}absin C$
$k=\frac{1}{2}(1)(4)sin(120\degree)$
$k=\sqrt{3}\approx1.73$

### For Side-Side-Side

![[Pasted image 20240921115329.png]]
If you're given three sides of the triangle and not the height, you can still find its area. This is called Heron's formula:
First, we need to find a number $S$, which stands for the *semiperimeter* (simply half the perimeter of the triangle) of the triangle:
$$S=\frac{1}{2}(a+b+c)$$
![[Pasted image 20240921122423.png]]
Check out [this awesome proof](https://www.youtube.com/watch?v=lRDtdIyFhpE)!
Then we use $S$ to calculate the area of the triangle:
$k=\sqrt{S(S-a)(S-b)(S-c)}$
### Proof

To prove this, we need to use 3 facts:
- $k=\frac{1}{2}absinC$; the area of triangle with [[#For Side-Angle-Side|SAS]]
- $c^{2}=a^{2}+b^{2}-2abcosC$; from the [[#What is Law of Cosines?|Law of Cosines]]
- $sin^{2}C+cos^{2}C=1$; from the [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Identity]]

We can now use algebra to prove this:
$k=\frac{1}{2}absinC$
Square the whole thing:
$k^{2}=\frac{1}{4}a^{2}b^{2}sin^{2}C$
We know that $sin^{2}C=1-cos^{2}C$:
$k^{2}=\frac{1}{4}a^{2}b^{2}(1-cos^{2}C)$
We know that $cosC=\frac{a^{2}+b^{2}-c^{2}}{2ab}$:
$k^{2}=\frac{1}{4}a^{2}b^{2}[1-(\frac{a^{2}+b^{2}-c^{2}}{2ab})^{2}]$
We want to get rid of the denominator inside the parentheses, we can do this by:
$\frac{1}{4}a^{2}b^{2}\to \frac{a^{2}b^{2}}{4}\cdot \frac{4}{4} \to \frac{4a^{2}b^{2}}{16}\to \frac{(2ab)^{2}}{16}\to \frac{1}{16}\cdot(2ab)^{2}$ 
$k^{2}=\frac{1}{16}(2ab)^{2}[1-(\frac{a^{2}+b^{2}-c^{2}}{2ab})^{2}]$
Distribute $(2ab)^{2}$ inside the parentheses:
$k^{2}=\frac{1}{16}[(2ab)^{2}-(a^{2}+b^{2}-c^{2})^{2}]$
We have a difference of square inside the parentheses:
$k^{2}=\frac{1}{16}[(2ab+a^{2}+b^{2}-c^{2})(2ab-a^{2}-b^{2}+c^{2})]$
We know that $a^{2}+2ab+b^{2}=(a+b)^{2}$ and $-a^{2}+2ab-b^{2}=-(a-b)^{2}$:
$k^{2}=\frac{1}{16}[[(a+b)^2-c^{2}][-(a-b)^{2}+c^{2}]]$
Once again we have difference of square in both parentheses:
$k^{2}=\frac{1}{16}[[(a+b+c)(a+b-c)][(c+a-b)(c-a+b)]]$
$k^{2}=\frac{1}{16}[(a+b+c)(a+b-c)(c+a-b)(c-a+b)]$
We know that $S=\frac{a+b+c}{2}$:
$k^{2}=\frac{1}{16}[(2S)(2S-2c)(2S-2b)(2S-2a)]$
$k^{2}=\frac{1}{16}[16(S)(S-c)(S-b)(S-a)]$
$k^{2}=(S)(S-c)(S-b)(S-a)$
$k=\sqrt{S(S-c)(S-b)(S-a)}$
As desired.
### Example

![[Pasted image 20240921123733.png]]
$S=\frac{a+b+c}{2}$
![[Pasted image 20240921123812.png]]
$S=\frac{9+6+4}{2}=\frac{19}{2}=9.5$

$k=\sqrt{S(S-a)(S-b)(S-c)}$
$k=\sqrt{9.5(9.5-9)(9.5-6)(9.5-4)}$
$k=\sqrt{9.5\cdot0.5\cdot3.5\cdot5.5}$
$k=\sqrt{91.4375}\approx9.56$

![[Pasted image 20240921124101.png]]
$S=\frac{a+b+c}{2}$
$S=\frac{5+9+8}{2}=\frac{22}{2}=11$

$k=\sqrt{S(S-a)(S-b)(S-c)}$
$k=\sqrt{11(11-5)(11-9)(11-8)}$
$k=\sqrt{11\cdot6\cdot2\cdot3}$
$k=\sqrt{396}\approx19.9$
## Simple Harmonic Motion in Trigonometry

*Simple harmonic motion* refers to vibratory motion that does NOT lessor with time.
	whereas its counterpart that *does* lessor with time is called *damped harmonic motion* (which is a more realistic model).
	 ![[Pasted image 20240921124639.png]]
Simple harmonic motion can be modelled with *sinusoidal functions* (a function that is based on the sine and cosine function). 
$$d=acos(\omega t)$$
- This is used when starting *away* from resting position ($d\neq0$ at $t=0$).
	Rmb, how cosine starts at $y=1$ when $x=0$?
![[Pasted image 20240921145421.png]]
$$d=asin(\omega t)$$
- This is used when starting at resting position ($d=0$ at $t=0$).
![[Pasted image 20240921145358.png]]
whereas:
- $d=$ Displacement from rest
- $|a|$ = Amplitude
- $T=\frac{2\pi}{\omega}$ = Period (shrinking or growing the period)
- $f=\frac{\omega}{2\pi}$ = frequency (number of oscillation per time unit e.g. $t$)

For example,
Say a sign hangs from a spring. You pull it down 7 inches and let it go. It takes 4 seconds to come back to where you released it.

"You pull it down 7 inches and let it go." This means that the motion starts away from the resting position. We'll use cosine to model this. Since we pulled it *down*, $a=-7$.

"It takes 4 seconds to come back to where you released it." This means that the period is every 4 seconds, so $T=4$. 
This also allows us to solve for $\omega$:
$T=\frac{2\pi}{\omega}$
$4=\frac{2\pi}{\omega}$
$\omega=\frac{\pi}{2}$

Frequency is how many oscillation per time unit (in this case seconds.) Since it takes full 4 seconds to go from where you released it, back to where you released it, this has $\frac{1}{4}$ oscillations per second. Notice that your frequency is always the reciprocal of your period, so $f=\frac{1}{4}$.
	The entire motion — from where you start, down and back to the same point — takes $2\pi$ radians, not $\pi$. $π$ refers to the midpoint of the oscillation (the zero-crossing).

We can can now derive a formula for $d$:
$d=-7cos(\frac{\pi}{2} t)$
We can use this to model the simple harmonic motion:
![[Pasted image 20240921150956.png]]
Since the spring is pulled down, the initial motion will be climbing up.
### More examples

$$|a|=4, T=\frac{\pi}{2}$$
Pushed up 4 feet and let go:

Pushed up means that $a$ is positive and that the motion does not start at resting position. We're given a period which can be used to solve for $\omega$:
$\frac{\pi}{2}=\frac{2\pi}{\omega}$
$\omega=4$

Frequency is the reciprocal of our period, so: $f=\frac{1}{\frac{\pi}{2}}=\frac{2}{\pi}$.

$d=4cos(4t)$
![[Pasted image 20240921151618.png]]
To think about the initial motion: the object is pushed up 4 feet before letting it go, causing it to climb down.

$$|a|=4, T=\frac{\pi}{2}$$
At rest and moving up.

At rest means we'll be using sine to model this, and moving up means that $a$ is positive.
The other variables are the same as before. So:
$d=4sin(4t)$
![[Pasted image 20240921151944.png]]
To think about the initial motion: our object starts at rest, we hit it, causing an upward motion.

Let's try to think about it with a model instead:
$$d=5sin(3t)$$

We know what type of motion this function is by just looking at it: a damp harmonic motion would have a decaying exponential or $e$ to a negative exponent. Since we don't have that here, we have a simple harmonic motion.

Having sine means that the object starts at rest ($d$ at $t=0$ is $0$). With $a=5$, this means that the initial motion is upward up to 5, which is the max displacement.

Time for 1 oscilation or period is $T=\frac{2\pi}{3}$ seconds, whereas that frequency is reciprocal of that: $f=\frac{3}{2\pi}$ oscillation per second.


$$d=-3sin(\frac{1}{2}t)$$
Once again, here we have a simple harmonic motion. With sine, the motion starts at rest and would initially go down due to $a=-3$. This means that $3$ is our maximum displacement.

$T=\frac{2\pi}{\frac{1}{2}}=4\pi$ seconds, and $f=\frac{1}{4\pi}$ oscillation per second.

$$d=-2cos(2t)$$
Cosine tells us that the motion starts away from the resting point. In this case, it starts at $a=-2$, suggesting that the initial motion is upward. Of course, with the max displacement of $2$.

$T=\frac{2\pi}{2}=\pi$ seconds ,and $f=\frac{1}{\pi}$ oscillation per second.

$$d=6+2cos(\frac{\pi}{2}t)$$
Is this still a simple harmonic motion? Yes, although the graph is shifted up by 6, or that the resting position, instead of 0, is raised up to 6. Cosine means that the motion starts at $8$ (6+2).

So is the max displacement $8$? No, displacement refers to the distance from resting position, so max displacement would still be $2$. So it would oscillate between $8$ and $4$.

$T=\frac{2\pi}{\frac{\pi}{2}}=4$ seconds and $f=\frac{1}{4}$ oscillation per second.

$d$ at $t=0$ would be 8. and the initial motion would be downwards.
![[Pasted image 20240921154025.png]]

## Introduction to Polar Coordinates

![[Pasted image 20240921171526.png]]
Why Polar Coordinates?
	Graphing Polar Coordinates is easier compared to using $xy-$coordinates. Things that are not function (fail vertical line test) become functions under polar coordinate, and we don't have to use [[Pre-calculus - College Algebra#How to Graph Piecewise Functions|piecewise functions]] to separate the parts.
	It also makes a lot of calculus easier for certain coordinates e.g. spherical coordinates or cylindrical coordinates.

What are Polar Coordinates?
A way to graph points without $x$, $y$ (rectangular coordinate). Instead, we use an angle and a distance. Here, we have *a pole*, which acts like an origin, and *a polar axis*, which acts like $x$-axis.
For $(r,\theta)$:
- $\theta \text{ } (+)$: Counter-clockwise.
- $\theta \text{ } (-)$: Clockwise.
- $r \text{ } (+)$: Distance from pole along $\theta$.
- $r \text{ } (-)$: Distance from pole in the opposite direction from $r \text{ } (+)$.
![[Pasted image 20240921172457.png]]

For example,
$$(2,\frac{\pi}{4})$$
This says that the distance is 2 and the angle is $\frac{\pi}{4}$.
![[Pasted image 20240921172726.png]]
	2 units away from the pole, and $\frac{\pi}{4}$ counter-clockwise from the polar axis.

$$(-2,\frac{\pi}{4})$$
![[Pasted image 20240921172916.png]]
Notice how we "lift" the ray up $\frac{\pi}{4}$, go along the ray to the distance of 2, then reflect it.
Also notice how we can get the exact same coordinate with: $(2,\frac{5\pi}{4})$ and $(2,- \frac{3\pi}{4})$. This means that there are ways to manipulate this:
- $(r,\theta)=(-r,\theta\pm\pi)$
- $(r,\theta)=(r,\theta\pm2\pi)$
### More examples
$$(3,- \frac{\pi}{3})$$
![[Pasted image 20240921173654.png]]
$$(3, \frac{5\pi}{3})$$
![[Pasted image 20240921173756.png]]

$$(-3, \frac{2\pi}{3})$$
![[Pasted image 20240921173858.png]]

Notice how each of these points to the exact same coordinate. Manipulated in such ways that:
- $(r,\theta)=(-r,\theta\pm\pi)$
- $(r,\theta)=(r,\theta\pm2\pi)$

![[Pasted image 20240921174252.png]]
On a polar coordinate.

More examples
$$(-2,0)$$
This would be in quadrant 2 where $x$ is negative. We can view this as $(2,\pi)$.
![[Pasted image 20240921175058.png]]

$$(-3,\pi)$$
The angle is $\pi$ then reflected back. This would be in quadrant one. We can view this as $(3,0)$
![[Pasted image 20240921175123.png]]

$$(2,- \frac{5\pi}{4})$$
We can look at this as $(-2,- \frac{\pi}{4})$. $- \frac{\pi}{4}$ is in quadrant four, reflected we would be in quadrant two.
![[Pasted image 20240921175225.png]]

$$(-3,120\degree)$$
$120\degree$ is in quadrant two. Reflected, it would lie in quadrant four.
![[Pasted image 20240921175323.png]]

Next problem:
$$(4, \frac{3\pi}{4})$$
![[Pasted image 20240921175626.png]]
$$r>0, -2\pi\leq\theta<0$$
$(4,\frac{3\pi}{4})=(4,\frac{3\pi}{4}-2\pi)=(4,-\frac{5\pi}{4})$
![[Pasted image 20240921175805.png]]

$$r<0, 0\leq\theta<2\pi$$
$(4, \frac{3\pi}{4})=(-4,\frac{3\pi}{4}+\pi)=(-4,\frac{7\pi}{4})$
![[Pasted image 20240921180132.png]]

$$r>0, 2\pi\leq\theta<4\pi$$
$(4, \frac{3\pi}{4})=(4,\frac{3\pi}{4}+2\pi)=(4,\frac{11\pi}{4})$
![[Pasted image 20240921180400.png]]
## How to Convert From Polar Coordinates to Rectangular Coordinates

![[Pasted image 20240921180602.png]]
Understand that we can convert polar coordinate $(r,\theta)$ into rectangular coordinate $(x,y)$ by understanding that $r$ is the hypotenuse to imaginary right triangle:
![[Pasted image 20240921180839.png]]
We can then use trig functions to solve for any $x$ and $y$:
- $sin\theta=\frac{y}{r}\to y=rsin\theta$
- $cos\theta=\frac{x}{r} \to x=rsin\theta$

So, as the above is the way to convert polar to rectangular, below is the way to convert rectangular to polar:
Tangent, however, is a way to convert rectangular back to polar coordinates:
- $tan\theta=\frac{y}{x}\to \theta=tan^{-1}(\frac{y}{x})$
You can also use [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Theorem]] to find $r$:
- $x^{2}+y^{2}=r^{2}\to r=\sqrt{x^{2}+y^{2}}$

For example:
$$(4,\frac{3\pi}{2})$$
We're given a polar coordinate. With $r=4$ and $\theta=\frac{3\pi}{2}$. Think about the quadrant first. $\frac{3\pi}{2}$ would be in-between quadrant three and four. 
To convert this to rectangular:
$sin\theta=\frac{y}{r}$
$4sin(\frac{3\pi}{2})=y$
$y=-4$
$cos\theta=\frac{x}{r}$
$4cos(\frac{3\pi}{2})=x$
$x=0$
So in rectangular system $(4,\frac{3\pi}{2})$ is $(0,-4)$

### More examples
$$(-2,0)$$
$r=-2$ and $\theta=0$. This would be in-between quadrant two and three.
$sin\theta=\frac{y}{r}$
$sin(0)=\frac{y}{-2}$
$-2sin(0)=y$
$y=0$
$cos\theta=\frac{x}{r}$
$-2cos(0)=x$
$x=-2$
So, $(-2,0)\to (-2,0)$.
	Although this is the same number, they mean something completely different.

$$(6,150\degree)$$
$r=6$ and $\theta=150\degree$. This would be in quadrant two.
$y=rsin\theta$
$y=6sin(150\degree)$
$y=3$
$x=rcos\theta$
$x=6cos(150\degree)$
$x=-3\sqrt{3}$
So, $(6,150\degree)\to (-3\sqrt{3},3)$.

$$(-2, \frac{3\pi}{4})$$
$r=-2$ and $\theta=\frac{3\pi}{4}$. $\frac{3\pi}{4}$ is in quadrant two, reflected to quadrant four.
$y=rsin\theta$
$y=-2sin \frac{3\pi}{4}$
$y=-\sqrt{2}$
$x=rcos\theta$
$x=-2cos \frac{3\pi}{4}$
$x=\sqrt{2}$
So, $(-2, \frac{3\pi}{4})\to (\sqrt{2},-2\sqrt{2})$

$$(-3,- \frac{\pi}{3})$$
$- \frac{\pi}{3}$ is in quadrant four, reflected to quadrant two.
$y=rsin\theta$
$y=-3sin(- \frac{\pi}{3})$
$y=\frac{3\sqrt{3}}{2}$
$x=rsin\theta$
$x=-3cos(- \frac{\pi}{3})$
Rmb that $cos(-\theta)=cos(\theta)$.
$x=- \frac{3}{2}$
So, $(-3,- \frac{\pi}{3})\to (- \frac{3}{2}, \frac{3\sqrt{3}}{2})$

For the next example, it would no longer be on the unit circle:
$$(-3.1,182\degree)$$
$182\degree$ is in quadrant three, reflected, that's quadrant one. We can also think of this from $(r,\theta)=(-r,\theta\pm\pi)$, so $(3.1,2\degree)$ and that's clearly quadrant one.
$y=-3.1sin(182\degree)$
$y\approx0.11$
$x=-3.1sin(182\degree)$
$x\approx 3.10$
So, $(-3.1,182\degree)\to(3.10,0.11)$.

$$(6,3.8RAD)$$
Rmb that, a **radian** is the central angle needed on any circle to make the *arc* subtended (cut) equal to the radius (see [[#Introduction to Radians]]). Since the radius is 6, a radian is an angle that make the arc equal to 6.

Rmb that, $1RAD=\frac{180\degree}{\pi}$ (from [[#Converting Radians and Degrees]]):
$3.8\cdot1RAD=3.8\cdot\frac{180\degree}{\pi}$
$3.8$ RAD$=\frac{684\degree}{\pi}$

We can also just do this in radians. $3.8$ Radian is slightly above $\pi$ but not over $\frac{3\pi}{2}$, meaning that this angle is on the quadrant three.
$y=rsin\theta$
$y=6sin(3.8RAD)$
Make sure your calculator is in radian:
$y\approx-3.67$
$x=rcos\theta$
$x=6cos(3.8RAD)$
$x\approx-4.75$
So, $(6,3.8RAD)\to(-4.74,-3.67)$

## How to Convert From Rectangular Coordinates to Polar Coordinates

Continuing from the [[#How to Convert From Polar Coordinates to Rectangular Coordinates|above]], the way to convert rectangular to polar:
Tangent, however, is a way to convert rectangular back to polar coordinates:
- $tan\theta=\frac{y}{x}\to \theta=tan^{-1}(\frac{y}{x})$
You can also use [[#Pythagorean Identities for Trigonometric Functions|Pythagorean Theorem]] to find $r$:
- $x^{2}+y^{2}=r^{2}\to r=\sqrt{x^{2}+y^{2}}$
- Keeping $r$ positive here is more convenient for us, and let the $\theta$ (whether positive or negative) determine the quadrant.

Thinking about quadrant here will be very important, since $tan^{-1}(\theta)$ only gives $\theta$ in quadrant one or four $(- \frac{\pi}{2}\leq 0 \leq \frac{\pi}{2})$.
	If the point should be in quadrant two or four, add $\pi$ to $\theta$.

For example:
$$(3,0)$$
Think about the quadrant FIRST. This is very important here. $(3,0)$ would be in-between quadrant one and four. 
To solve for $r$:
$x^{2}+y^{2}=r^{2}$
$9=r^{2}$
$r=3$
	We don't need ambiguity by putting $\pm$ with $r$, since we know that $(-r, \theta\pm\pi)=(r,\theta)$, unless there are some restriction on what $\theta$ should be e.g. $-\pi\leq\theta<0$. We can just write it as a given formula to avoid putting in the $\pm$ ourselves: $r=\sqrt{x^{2}+y^{2}}$.

$tan\theta=\frac{y}{x}$
$tan\theta=\frac{0}{3}$
$tan\theta=0$
$\theta=tan^{-1}(0)$
$\theta=0$
So, in polar system, $(3,0)$.

$$(0,2)$$
This would be in-between quadrant one and two.
$r=\sqrt{x^{2}+y^{2}}$
$r=\sqrt{0+4}$
$r=2$

$tan\theta=\frac{y}{x}$
$tan\theta=\frac{2}{0}$
That's undefined. Think about what angle would cause tangent to output undefined: $\frac{\pi}{2}, \frac{3\pi}{2}$.
From identifying the quadrant we know for sure that this is $\frac{\pi}{2}$ (in-between Q1 and Q2).
In polar form: $(2,\frac{\pi}{2})$.

$$(1,-1)$$
Positive $x$ and negative $y$. This is surely in quadrant four.
$r=\sqrt{(1)^{2}+(-1)^{2}}$
$r=\sqrt{2}$

$tan\theta=\frac{y}{x}$
$tan\theta=\frac{-1}{1}$
$tan\theta=-1$
$\theta=tan^{-1}(-1)$
What angle(s) give tangent of -1? That's $- \frac{\pi}{4}$ or $\frac{7\pi}{4}$ and $\frac{3\pi}{4}$. We use the angle which is in quadrant four:
$\theta=- \frac{\pi}{4}$

And this is quadrant four. So, in polar form, $(\sqrt{2},- \frac{\pi}{4})$ or $(\sqrt{2}, \frac{7\pi}{4})$, if we need a positive angle.

### More examples

$$(-3,3)$$
Negative $x$ and positive $y$, that's surely quadrant two.
$r=\sqrt{x^{2}+y^{2}}$
$r=\sqrt{(-3)^{2}+(3)^{2}}$
$r=\sqrt{18}$
$r=3\sqrt{2}$

$tan\theta=\frac{3}{-3}$
$tan\theta=-1$
$\theta=tan^{-1}(-1)$
Once again, what angle(s) give tangent of -1? That's $- \frac{\pi}{4}$ or $\frac{7\pi}{4}$ and $\frac{3\pi}{4}$. We use the angle which is in quadrant two:
$\theta=\frac{3\pi}{4}$
	We can get the same thing if we stuck with $- \frac{\pi}{4}$, which is in quadrant four. Simple add $\pi$ to it and we'll get $\frac{3\pi}{4}$.

In polar form: $(3\sqrt{2},\frac{3\pi}{4})$.

$$(-2,-2\sqrt{3})$$
Both $x$ and $y$ are negative, this is in quadrant three.
$r=\sqrt{(-2)^{2}+(-2\sqrt{3})^{2}}$
$r=\sqrt{4+12}$
$r=4$

$tan\theta=\frac{-2\sqrt{3}}{-2}$
$tan\theta=\sqrt{3}$
There should be two positive angle that make this: $\frac{4\pi}{3}$ and $\frac{\pi}{3}$. We pick one that's in quadrant three:
$\theta=\frac{4\pi}{3}$

In polar form: $(4,\frac{4\pi}{3})$.

Below examples are not on the unit circle:
$$(1.3,-2.1)$$
$x$ is positive and $y$ is negative, this is in quadrant four.

$r=\sqrt{(1.3)^{2}+(-2.1)^{2}}$
$r\approx2.47$

$tan\theta=\frac{-2.1}{1.3}$
$\theta=tan^{-1}(- \frac{2.1}{1.3})$
$\theta=-1.02$ Radian (which is in quadrant four)

In polar form: $(2.47,-1.02)$

$$(-0.8,-2.1)$$
Both $x$ and $y$ are negative, this is in quadrant three.
$r=\sqrt{(-0.8)^{2}+(-2.1)^{2}}$
$r\approx2.45$

$tan\theta= \frac{-2.1}{-0.8}$
$\theta=tan^{-1}(\frac{2.1}{0.8})$
$\theta\approx1.21$ Radian
This is in quadrant one, but we should have a quadrant three angle. This is since $tan^{-1}$ has the range of $[- \frac{\pi}{2}, \frac{\pi}{2}]$. We can add $\pi$ to this and get the same coordinate: $1.21+\pi$ Radian $\approx 4.35$ Radian.
So, in polar form, $(2.45,4.35)$

## How to Convert From Rectangular Equations to Polar Equations

$$x^{2}+y^{2}=r^2$$
- Always look for these *first*.
$$x=rcos\theta$$
$$y=rsin\theta$$

For example,
$$2x^{2}+2y^{2}=3$$
$2(x^{2}+y^{2})=3$
$2(r^{2})=3$
$r^{2}=\frac{3}{2}$
$r=\sqrt{\frac{3}{2}}$
Keeping $r$ positive here, since in the polar system, we can let $\theta$ determine the quadrant for us.
$r=\frac{\sqrt{6}}{2}$
This is simpler to graph than $2x^{2}+2y^{2}=3$, since $r$ simply represent the distance from the origin. We can imagine this in a circle with radius $\frac{\sqrt{6}}{2}$.

$$x^{2}+y^{2}=x$$
$r^{2}=x$
Rmb, that $x=rcos\theta$:
$r^{2}=rcos\theta$
By this step, we've already *converted* this into a polar equations. All that's left is how far we want to go for simplification.
$r=cos\theta$
Note that we can only divide by $r$ if $r\neq0$.
We can also do:
$r^{2}-rcos\theta=0$
$r(r-cos\theta)=0$
We can then use zero product property:
- $r=0$
- $r=cos\theta$

$$x^{2}=4y$$
$(rcos\theta)^{2}=4(rsin\theta)$
$r^{2}cos^{2}\theta=4(rsin\theta)$
If allowed, we can divide both side by $r$:
$rcos^{2}\theta=4sin\theta$
$r=\frac{4sin\theta}{cos^{2}\theta}$
$r=\frac{4sin\theta}{cos\theta}\cdot \frac{1}{cos\theta}$ 
$r=4\tan\theta\sec\theta$
If not allowed:
$r^{2}cos^{2}\theta=4(rsin\theta)$
$r^{2}cos^{2}\theta-4rsin\theta=0$
$r(rcos^{2}\theta-4sin\theta)=0$
By zero product property:
- $r=0$
- $r=4\tan\theta\sec\theta$

$$2xy=1$$
$2(rcos\theta)(rsin\theta)=1$
$2r^{2}cos\theta sin\theta=1$
Rmb [[#Double-Angle Formulas]]: $sin(2\theta)=2sin\theta cos\theta$:
$r^{2}sin(2\theta)=1$
$r^{2}=csc(2\theta)$
$r=\sqrt{csc(2\theta)}$

$$(x-3)^{2}+y^{2}=9$$
$(x^{2}-6x+9)+y^{2}=9$
$(x^{2}+y^{2})-6x+9=9$
$r^{2}-6x=0$
$r^{2}-6(rcos\theta)=0$
$r(r-6cos\theta)=0$
By zero product property:
- $r=0$
- $r=6cos\theta$

While converting from rectangular to polar equation can be nice, there are rectangular-driven equations e.g. vertical line ($x=3$), horizontal line $(y=7)$, or diagonal line $y=2x$, rectangular can be easier to do with (depending on what you want to do.) For example:
$$x=3$$
$rcos\theta=3$
$r=\frac{3}{cos\theta}$
$r=3sec\theta$
Notice how, if you want to graph this, $x=3$ is easier.

$$y=7$$
$rsin\theta=7$
$r=\frac{7}{sin\theta}$
$r=7sec\theta$

$$y=\sqrt{3}x$$
$\frac{y}{x}=\sqrt{3}$
We know that $\frac{y}{x}=tan\theta$:
$tan\theta=\sqrt{3}$
This is on the unit circle.
$\theta=\frac{\pi}{3},\frac{4\pi}{3}$
What does this says? $y=\sqrt{3}x$ is a diagonal line. With $\theta$, we know the angle of this diagonal line going through the origin.
	This tells us that the line $y = \sqrt{3}x$ forms a $\frac{\pi}{3}$ with the positive $x$-axis when moving counterclockwise, and an angle of $\frac{4\pi}{3}$​ when extended through the third quadrant.
	Note that this has a positive slope ($m=\sqrt{3}$), which already indicates that the line rises steeply (faster than the $\frac{\pi}{4}$ diagonal of $y=x$).

## How to Convert From Polar Equations to Rectangular Equations

$$x^{2}+y^{2}=r^2$$
$$x=rcos\theta$$
$$y=rsin\theta$$
- Similar as [[#How to Convert From Rectangular Equations to Polar Equations]], but in this case, we'll be going in reverse order. We'll look to substitute $x=rcos\theta$ and $y=rsin\theta$ first.

$$r=cos\theta$$
Multiply both sides by $r$:
$r^{2}=rcos\theta$
$r^{2}=x$
$x^{2}+y^{2}=x$
$x^{2}-x+y^{2}=0$

$$r=sin\theta+1$$
$r^{2}=rsin\theta+r$
$x^{2}+y^{2}=y+r$
Rmb that $r^{2}=x^{2}+y^{2}\to r=\sqrt{x^{2}+y^{2}}$ (keeping $r$ positive):
$x^{2}+y^{2}=y+\sqrt{x^{2}+y^{2}}$

$$r^{2}=cos\theta$$
$x^{2}+y^{2}=cos\theta$
Multiply both sides by $r$:
$r(x^{2}+y^{2})=rcos\theta$
$(\sqrt{x^{2}+y^{2}})(x^{2}+y^{2})=x$
$(x^{2}+y^{2})^{\frac{1}{2}}(x^{2}+y^{2})^{1}=x$
$(x^{2}+y^{2})^{\frac{3}{2}}=x$

We can also look at this as:
$x^{2}+y^{2}=cos\theta$
$x^{2}+y^{2}=\frac{x}{r}$
$x^{2}+y^{2}=\frac{x}{\sqrt{x^{2}+y^{2}}}$

In the cases we've seen so far, notice that the polar form of both look much nicer.

$$r=\frac{sin\theta}{cos^{2}\theta}$$
$r=\frac{sin\theta}{cos\theta}\cdot \frac{1}{cos\theta}$
$rcos\theta=tan\theta$
$x=\frac{y}{x}$
$x^{2}=y$
Notice how this is just a basic parabola.

$$r=3csc\theta$$
$r=3\cdot \frac{1}{sin\theta}$
$rsin\theta=3$
$y=3$

$$r=sin\theta cos^{2}\theta$$
$rsin\theta=sin^{2}\theta cos^2\theta$
$y=sin^{2}\theta cos^{2}\theta$
$r^{4}y=r^{4}sin^{2}\theta cos^{2}\theta$
$(x^{2}+y^{2})^{2}y=(r^{2}sin^{2}\theta)(r^{2}cos^{2}\theta)$
$(x^{2}+y^{2})^{2}y=(rsin\theta)^{2}(rcos\theta)^{2}$
$(x^{2}+y^{2})^{2}y=(y)^{2}(x)^{2}$
$(x^{2}+y^{2})^{2}=y(x)^{2}$
$\sqrt{(x^{2}+y^{2})^{2}}=\sqrt{y(x)^{2}}$
$x^{2}+y^{2}=x\sqrt{y}$

$$r=2$$
Note: this would create a circle with radius of 2.
$r^{2}=4$
$x^{2}+y^{2}=4$

$$r=\frac{4}{1-cos\theta}$$
$r-rcos\theta=4$
$r-x=4$
$\sqrt{x^{2}+y^{2}}-x=4$
Isolate the square root:
$\sqrt{x^{2}+y^{2}}=x+4$
Square both side:
$x^{2}+y^{2}=(x+4)^{2}$
$x^{2}+y^{2}=x^{2}+8x+16$
$y^{2}=8x+16$
$y=\sqrt{8x+16}$
$y=\sqrt{4(2x+4)}$
$y=2\sqrt{2x+4}$

## How to Graph Basic Polar Equations 


$$x^{2}+y^{2}=r^2$$
$$x=rcos\theta$$
$$y=rsin\theta$$
$$tan\theta=\frac{y}{x}$$

For example:
$$r=3$$
We can translate this into a rectangular equation to see this more clearly:
$r^{2}=9$
$x^{2}+y^{2}=9$
	$x^{2}+y^{2}$ is a circle, not shifted, with a radius of $3$ ($r^{2}=9$).
![[Pasted image 20240922171412.png]]

$$\theta=\frac{\pi}{4}$$
We can put tangent on both sides to convert to rectangular form:
$tan\theta=tan(\frac{\pi}{4})$
$tan\theta=\frac{1}{1}$
![[Pasted image 20240922171704.png]]

$$rsin\theta=2$$
$y=2$
That's a horizontal line.
![[Pasted image 20240922171827.png]]

$$rcos\theta=-3$$
$x=-3$
That's a vertical line.
![[Pasted image 20240922171904.png]]
Notice that in polar form $rcos\theta=-3$ means that $r$ and $\theta$ has to be constantly changing to match the vertical line.
![[Pasted image 20240922172051.png]]
In this such cases, rectangular form are much more simpler to think about.

$$r=4sin\theta$$
$sin\theta$ relates to $y$. Let's further translate this:
$r^{2}=4rsin\theta$
$x^{2}+y^{2}=4y$
Get this on one side:
$x^{2}-4y+y^{2}=0$
We can factor this as:
$x^{2}+(y^{2}-4y)=0$
Complete the square on $y^{2}-4y$:
![[Pasted image 20240922172704.png]]
	**Factoring** wouldn't have provided the same geometric insight. Factoring $y$ out of the equation $y^2 - 4y$ would not lead to the recognizable form of a circle i.e. $(x−h)^2+(y−k)^2=r^{2}$.
To complete the square we have to add 4 (and subtract by 4 outside):
$x^{2}+[(y-2)^{2}-4]=0$
$x^{2}+(y-2)^{2}=4$
This is in a format very similar to a circle or $x^{2}+y^{2}=r^{2}$. Rmb how inside the parentheses, things are the opposite of what you think it would be. In this case, the $-2$ next to $y$ means *shift up* by 2, instead of down.
![[Pasted image 20240922173006.png]]
Imagine the origin of the circle shifted up by 2. Since $r^{2}=4$, $r=2$, this circle has a radius of 2.
![[Pasted image 20240922173114.png]]
	That's a very bad circle, I know.

$$r=-2cos\theta$$
Very similar to above:
$r^{2}=-2rcos\theta$
$x^{2}+y^{2}=-2x$
$x^{2}+2x+y^{2}=0$
Complete the square.
![[Pasted image 20240922173539.png]]
$[(x+1)^{2}-1]+y^{2}=0$
$(x+1)^{2}+y^{2}=1$
The $+1$ inside the parentheses affect the $x$, this is a shift left by 1. The circle has a radius of 1.
![[Pasted image 20240922173739.png]]
## How to Graph Advanced Polar Equations with Symmetry

If the equations are too hard to convert to rectangular, we can use the idea of symmetry for graphing:
- If $r(\theta)=r(-\theta)$, symmetry about polar axis ($x$-axis)
- If $r(\theta)=r(\pi-\theta)$, symmetry about $\frac{\pi}{2}$ ($y$-axis)
	This is similar to the SSA solution [[#^8d71d0]], where we can have two solutions (obtuse and acute).
- If $r(\theta)=-r(\theta)$, symmetry about pole (origin)

$$r=1-sin\theta$$
We can turn this into: $x^{2}+y^{2}=\sqrt{x^{2}+y^{2}}-y$. But that's not very nice to deal with.
We can start looking for symmetry:
- $(-\theta)$: $r=1-sin(-\theta)$
Can we turn this into our original equation? If it does, we have identified a symmetry:
Rmb that sine is an odd function.
$r=1-(-sin(\theta))$
$r=1+sin\theta$
That's not the same. No symmetry about the polar axis.

- $(\pi-\theta):$ $r=1-sin(\pi-\theta)$
Rmb, [[#Using Sum and Difference Formulas in Trigonometry|sum and difference formula for sine]]? $sin(\pi-\theta)=sin(\pi)cos(\theta)-cos(\pi)sin(\theta)$. 
$r=1-[sin(\pi)cos(\theta)-cos(\pi)sin(\theta)]$
We know that $sin(\pi)=0$ and $cos(\pi)=-1$:
$r=1-[(0)cos(\theta)-(-1)sin(\theta)]$
$r=1-sin(\theta)$
Hey! That's the exact same as our original equation. We have a symmetry about $\frac{\pi}{2}$-axis.

- $-r:$ $-r=1-sin\theta$
Mult. both sides by $-1$:
$r=sin\theta-1$
That's not the same. No symmetry about the pole.

Now, we can plot some points to get our graph. With symmetry about $\frac{\pi}{2}$-axis, we only need to plot one side of the graph and reflect the symmetry.

We list out some common $\theta$ into the function and get out the outputs:
![[Pasted image 20240922205134.png]]

Starting with $- \frac{\pi}{2}$:
$r=1-sin(-\frac{\pi}{2})$
$r=1-(-1)$
$r=2$

$- \frac{\pi}{3}$:
$r=1-sin(- \frac{\pi}{3})$
$r=1- (-\frac{\sqrt{3}}{2})$
$r\approx1.87$

$- \frac{\pi}{4}$:
$r=1-sin(- \frac{\pi}{4})$
$r=1-(-\frac{\sqrt{2}}{2})$
$r\approx1.7$

$- \frac{\pi}{6}$:
$r=1-sin(- \frac{\pi}{6})$
$r=1-(- \frac{1}{2})$
$r=1.5$

$0$:
$r=1-sin(0)$
$r=1-0$
$r=1$

$\frac{\pi}{6}$:
$r=1-sin(\frac{\pi}{6})$
$r=1- \frac{1}{2}$
$r=0.5$

$\frac{\pi}{4}$:
$r=1-sin(\frac{\pi}{4})$
$r=1-(\frac{\sqrt{2}}{2})$
$r\approx0.29$

$\frac{\pi}{3}$:
$r=1-sin(\frac{\pi}{3})$
$r=1-(\frac{\sqrt{3}}{2})$
$r\approx0.13$

$\frac{\pi}{2}$:
$r=1-sin(\frac{\pi}{2})$
$r=1-1$
$r=0$

That's a pretty long list, but that would've doubled if you haven't identified your symmetry yet. Now we can plot those point:
![[Pasted image 20240922210122.png]]
![[Pasted image 20240922210152.png]]

Now sketch the symmetry about the $\frac{\pi}{2}$-axis. 
![[Pasted image 20240922210241.png]]
Hey! That's super cool. Looks like a heart.
![[Pasted image 20240922211212.png]]
*Cardioid curve* plotted in Cartesian $xy$-coordinates
```python
theta = np.arange(0, 2*np.pi,0.01)
def r(theta):
    return 1-np.sin(theta)
x=r(theta)*np.cos(theta)
y=r(theta)*np.sin(theta)

plt.axhline(0,color='black')
plt.axvline(0,color='black')
plt.plot(x,y)
plt.show()
```

Apparently, `numpy` has a very handy function for creating polar plots:
![[Pasted image 20240922211637.png]]
```python
theta = np.arange(0, 2*np.pi, 0.01)
def r(theta):
    return 1 - np.sin(theta)
plt.polar(theta, r(theta))
plt.show()
```
Very cool.
$$r=1+2cos\theta$$
This is hard to convert to rectangular nicely. Let's check the symmetry:
- $(-\theta)$: $r=1+2cos(-\theta)$
Rmb that cosine is an even function:
$r=1+2cos(\theta)$
We got it. There's a symmetry about the polar axis ($x$-axis).

- $(\pi-\theta)$: $r=1+2cos(\pi-\theta)$
$r=1+2cos(\pi-\theta)$
$r=1+2[cos\pi cos\theta + sin\pi sin\theta]$
$r=1+2(-cos\theta)$
$r=1-2cos\theta$
Nope. No symmetry here.

- $(-r)$: $-r=1+2cos(\theta)$
$r=-1-2cos(\theta)$
Nope.

Since we have a symmetry about the $x$-axis, we only want to plot the common angles on the first and second quadrant and reflect that symmetry (we can do it the other way but that's just weird). 
![[Pasted image 20240922212357.png]]
if $\theta=0$, $r=3.00$ 
if $\theta=\frac{\pi}{6}$, $r=2.73$ 
if $\theta=\frac{\pi}{4}$, $r=2.41$ 
if $\theta=\frac{\pi}{3}$, $r=2.00$ 
if $\theta=\frac{\pi}{2}$, $r=1.00$ 
if $\theta=\frac{2\pi}{3}$, $r=0.00$ 
if $\theta=\frac{3\pi}{4}$, $r=-0.41$ 
if $\theta=\frac{5\pi}{6}$, $r=-0.73$ 
if $\theta=\pi$, $r=-1.00$
Notice that some $r$ is negative, these must be reflected.
![[Pasted image 20240922213544.png]]
![[Pasted image 20240922213608.png]]
Reflect this about the polar axis:
![[Pasted image 20240922213644.png]]
![[Pasted image 20240922213817.png]]
![[Pasted image 20240922213850.png]]

$$r=2cos(2\theta)$$
Rmb that $cos(2\theta)=cos^{2}\theta-sin^{2}\theta$:
$r=2(cos^{2}\theta-sin^{2}\theta)$
That does really help our case. Let's think about the symmetry instead:
- $(-\theta):$ $r=2cos(-2\theta)$
Since cosine is an even function:
$r=2cos(2\theta)$
We have symmetry about the polar axis.

- $(\pi-\theta)$: $r=2cos(2(\pi-\theta))$
$r=2cos(2\pi-2\theta)$
$r=2[cos(2\pi)cos(2\theta)+sin(2\pi)sin(2\theta)]$
	Future me: we don't even really have to think about the $2\pi$ here since this is the [[#Periods|period]] of cosine. So $2cos(2\pi-2\theta)=2cos(-2\theta)=2cos(2\theta)$.
Since $cos(2\pi)=1$ and $sin(2\pi)=0$:
$r=2cos(2\theta)$
That's the same. We have symmetry about the $\frac{\pi}{2}$-axis.

Notice that we have two symmetry here. Think about this. Your graph are reflected about the $x$-axis and then $y-axis$. That's equivalent to symmetry about the origin. We don't need to check for $-r$. We surely have the symmetry about the pole.

I still checked for it anyways:
- $(-r):$ $-r=2cos(2\theta)$
$r=-2cos(2\theta)$
Nope. Isn't this contradictory? 
	Checking for $r=-r$ is only one way to confirm rotational symmetry about the origin. Even though the test $r = -2\cos(2\theta)$ did not give the same equation, **the combined symmetries of the x- and y-axes confirm that the curve is rotationally symmetric about the origin**. 

Rotational symmetry about the origin (Both $x$- and $y$-axis symmetry)
![[Pasted image 20240922215907.png]]
if $\theta=0$, $r=2.00$
if $\theta=\frac{\pi}{6}$, $r=1.00$
if $\theta=\frac{\pi}{4}$, $r=0.00$
if $\theta=\frac{\pi}{3}$, $r=-1.00$
if $\theta=\frac{\pi}{2}$, $r=-2.00$
![[Pasted image 20240922220317.png]]
Reflection about the polar axis:
![[Pasted image 20240922220401.png]]
Reflection about the $\frac{\pi}{2}$-axis:
![[Pasted image 20240922220502.png]]
Isn't that cool?
![[Pasted image 20240922220633.png]]
![[Pasted image 20240922220847.png]]
Why are there more petals in rectangular coordinate system?
```python
theta = np.arange(0, 2*np.pi, 0.01)
def r(theta):
    return 2*np.cos(2*theta)
x = r(theta)*np.cos(theta)
y = r(theta)*np.sin(theta)
plt.axhline(0,color='black')
plt.axvline(0,color='black')
plt.plot(x,y)
plt.axis('equal')
plt.show()
```
- In our variable declaration of $x$ and $y$, we're effectively doing:
	- $x=r(θ)cos(θ)=2cos(2θ)cos(θ)$
	- $y=r(θ)sin(θ)=2cos(2θ)sin(θ)$
- This process creates an additional complexity because we're now involving both the cosine of $2\theta$ and the regular cosine/sine of $\theta$.
- When we convert the polar equation into rectangular form, it produces **four petals** instead of two because conversion to rectangular multiplies the frequency of the shape, resulting in more petals.

$$r^{2}=4sin(2\theta)$$
- $(-\theta):$ $r^{2}=4sin(-2\theta)$
Sine is an odd function, so:
$r^{2}=-4sin(2\theta)$
Nope.

- $(\pi-\theta):$ $r^{2}=4sin(2(\pi-\theta))$
$r^{2}=4sin(2\pi-2\theta)$
We can ignore the $2\pi$ since that is the period of sine:
$r^{2}=4sin(-2\theta)$
Nope.

- $(-r):$ $(-r)^{2}=4sin(2\theta)$
Understand that $(-r)^{2}=r^{2}$:
$r^{2}=4sin(2\theta)$
We have a rotational symmetry about the origin. Notice how we don't need both $x$- and $y$-axis symmetry to get to this like in our previous example. 

![[Pasted image 20240922222041.png]]
Now we replace these $\theta$ in $r=\pm\sqrt{4sin(2\theta)}$.
	Notice the $\pm$ as this is exactly *why* we have symmetry about the origin.
if $\theta=0$, $r=0.00$
if $\theta=\frac{\pi}{6}$, $r=\pm1.86$
if $\theta=\frac{\pi}{4}$, $r=\pm2.00$
if $\theta=\frac{\pi}{3}$, $r=\pm1.86$
if $\theta=\frac{\pi}{2}$, $r=0.00$
Be sure to plot both plus and minus for each point.
![[Pasted image 20240922222438.png]]
Let's think about some other angle for a moment:
if $\theta=\frac{2\pi}{3}$, $r=nan$
if $\theta=\frac{3\pi}{4}$, $r=nan$
if $\theta=\frac{5\pi}{6}$, $r=nan$
if $\theta=\pi$, $r=0$
Why $nan$? For example, $r^{2}=4sin(2(\frac{2\pi}{3}))$:
$r=\pm\sqrt{4sin(\frac{4\pi}{3})}$
$r-\pm\sqrt{4(-\frac{\sqrt{3}}{2})}$
Notice that we have an imaginary number here. This means that our graph will only exist in quadrant one and three. 
![[Pasted image 20240922222946.png]]
![[Pasted image 20240922223116.png]]
![[Pasted image 20240922223140.png]]