# Some Visual Proofs by Desmos

Here are a number of visual proofs of classic mathematical results I (re)created in Desmos. Most of these illustrations are interactive, so feel free to tinker with the sliders, toggle the folders (by clicking the circle to their left) to enable/disable features, zoom in/out on the right panel, and such.

The demonstrations are loosely grouped in the following categories:

- [Sum of Finitely Many Quantities](#sum-of-finitely-many-quantities)
- [Sum of Infinitely Many Quantities](#sum-of-infinitely-many-quantities)
- [Geometry and Trigonometry](#geometry-and-trigonometry)
- [Others](#others)

Links to these demonstrations are also provided below -- please feel free to adapt them for your own use. If you have any questions/comments/bug reports about these demonstrations, or would simply like to let me know that you find them useful, please feel free to e-mail me at `Pau@mathQ.usask.caR` (with P,Q, and R removed).

[Back to Dr. Au's Homepage](http://math.usask.ca/~au/)

___

## Sum of Finitely Many Quantities

- The $n$-th triangular number (i.e., $1+2+\cdots+n$) is equal to $\frac{n(n+1)}{2}$.
<iframe src="
https://www.desmos.com/calculator/cz8bnz6nsl
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](https://www.desmos.com/calculator/cz8bnz6nsl))
- A positive integer is an odd square if and only if it is eight times a triangular number plus one.
<iframe src="
https://www.desmos.com/calculator/plgyl002jw
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](https://www.desmos.com/calculator/plgyl002jw))

- For every integer $n \geq 1$, $1^2+2^2+ \cdots + n^2 = \frac{1}{3} \cdot (2n+1) \cdot \frac{n(n+1)}{2}$.

<iframe src="
https://www.desmos.com/calculator/spojco39nz
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/spojco39nz))

- For every integer $n \geq 1$, $1^3+2^3+ \cdots + n^3 = (1+2+ \cdots +n)^2$.

<iframe src="
https://www.desmos.com/calculator/uduuifbp9u
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/uduuifbp9u))

- An alternative proof to the previous result. This one does so by showing that   $4(1^3+2^3+ \cdots + n^3) = (n(n+1))^2$.

<iframe src="
https://www.desmos.com/calculator/2hbuitxf6u
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/2hbuitxf6u))

- Let $F_n$ be the $n$-th Fibonacci number for every $n \geq 0$. (So $F_0=1, F_1=1$, and $F_n = F_{n-1}+F_{n-2}$ for every $n \geq 2$.) Then $F_0^2+F_1^2+ \cdots + F_n^2 = F_n \cdot F_{n+1}$ for every $n \geq 0$.

<iframe src="
https://www.desmos.com/calculator/hv0sfm020w
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/hv0sfm020w))

___

## Sum of Infinitely Many Quantities

- The series $\displaystyle\sum_{i \geq 1} \frac{1}{i}$ diverges.

<iframe src="
https://www.desmos.com/calculator/my155ztet4
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](
https://www.desmos.com/calculator/my155ztet4
))

(One can also see from the above demonstration that $\displaystyle\lim_{n\to\infty} \sum_{i=2^n}^{2^{n+1}-1} \frac{1}{i} = \ln(2)$.)

- The series $\displaystyle\sum_{i \geq 1} \frac{1}{i^2}$ converges to less than $2$.

<iframe src="
https://www.desmos.com/calculator/4haplx2amm
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](
https://www.desmos.com/calculator/4haplx2amm
))

(More generally, it shows that $\displaystyle\sum_{i \geq 2^n} \frac{1}{i^2} < 2^{1-n}$ for every integer $n\geq0$.)

- For every real number $p$ where $-1 < p < 1$, the series $\displaystyle\sum_{i \geq 0} p^i$ converges to $\frac{1}{1-p}$.

<iframe src="
https://www.desmos.com/calculator/rqkady4pap
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/rqkady4pap))


___

## Geometry and Trigonometry

- (Pythagorean Theorem) Given a right triangle with legs of lengths $a,b$ and hypotenuse of length $c$, the side lengths must satisfy the equation $a^2+b^2=c^2$.

<iframe src="
https://www.desmos.com/calculator/bgdyab1z1i
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](https://www.desmos.com/calculator/bgdyab1z1i))

- Another (in my opinion, very neat) proof of the Pythagorean Theorem. 

<iframe src="
https://www.desmos.com/calculator/mei6dlighx
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>
([Link to Demonstration](https://www.desmos.com/calculator/mei6dlighx))

- The circular disk of radius $r$ has area $\pi r^2$. 

<iframe src="
https://www.desmos.com/calculator/3vk3ovwpss
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/3vk3ovwpss))

(Note that the proof only makes use of the definition of $\pi$ being the ratio between a circle's circumference to its diameter, and not our knowledge of the numerical value of $\pi$.)

- The sum-of-angles identities for cosine and sine.

  <iframe src="
  https://www.desmos.com/calculator/us7fhkqd3d
  " width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

  ([Link to Demonstration](
  https://www.desmos.com/calculator/us7fhkqd3d
  ))

- $\arctan(1/3) + \arctan(1/2) = \arctan(1)$. 

<iframe src="
https://www.desmos.com/calculator/dur9crmrgs
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/dur9crmrgs))

(In fact, one can tinker with the value of $c$ and the location of the point $P$ in the demonstration to generate other similar $\arctan$ identities.)

- (Viviani's Theorem) Let $P$ be any point inside an equilateral triangle. Then the sum of the lengths of the three perpendiculars from $P$ is equal to the height of the equilateral triangle.

<iframe src="
https://www.desmos.com/calculator/5pu0djb28q
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/5pu0djb28q))

___

## Others

- There is a bijection between the open interval $(0,1)$ and the set of real numbers $\mathbb{R}$.

<iframe src="
https://www.desmos.com/calculator/dvoezl9tey
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/dvoezl9tey)

(In fact, the function shown above is $f :(0,1) \to \mathbb{R}$ where $f(x) = \tan( \pi x - \frac{\pi}{2})$.)

- If a natural number $p$ is not a perfect square, then $\sqrt{p}$ is irrational. 

<iframe src="
https://www.desmos.com/calculator/onbvgkquf5
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/onbvgkquf5))

(This one requires some additional explanation. The illustration above shows that if there was a positive integer $k$ where $\sqrt{p} \cdot k$ is an integer, then there would be a smaller positive integer $\ell$ where $\sqrt{p} \cdot \ell$ is also an integer, contradicting the existence of $k$.)

- One can rotate $p$ disks inside a larger circle, and place $q$ points on each disk, such that the $pq$ points collectively trace out a $(p+q)$-point star.

<iframe src="
https://www.desmos.com/calculator/iwvtgdi8bn
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/iwvtgdi8bn))

(Note: The statement above is pretty imprecise! For some values of $p$ and $q$ the points in fact lie outside the rotating disks, and the "star" may or may not look like a star. This is created in response to [this video](https://www.youtube.com/watch?v=oEN0o9ZGmOM) by Mathologer.)

- Finally, as a cautionary tale for relying on visual proofs without thinking critically, here is a very standard proof showing that $25=24$.

<iframe src="
https://www.desmos.com/calculator/ts4qhpxhqd
" width="800" height="400" style="border: 1px solid #ccc" frameborder=0></iframe>

([Link to Demonstration](https://www.desmos.com/calculator/ts4qhpxhqd))

Like what you saw? You can find more visual proofs by doing an internet search for "Proofs without words". In particular, check out the excellent [Mathologer Youtube channel](https://www.youtube.com/channel/UC1_uAIS3r8Vu6JjXWvastJg), as well as [this post on Mathoverflow](https://mathoverflow.net/questions/8846/proofs-without-words), which are the sources of inspiration for some of the visual proofs above.

___

[Back to Dr. Au's Homepage](http://math.usask.ca/~au/)