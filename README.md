# Approximating $\pi$ graphically using various formulae

The following formulae were compared:
- [x] Double Factorial Formula

$$
\sum_{k=0}^{\infty}\frac{k!}{(2k+1)!!}=\sum_{k=0}^{\infty}\frac{2^k{k!}^2}{(2k+1)!}=\frac{\pi}{2}
$$

- [x] [Bailey-Borwein-Plouffe Formula](https://en.wikipedia.org/wiki/Bailey–Borwein–Plouffe_formula)

$$
\sum_{k=0}^{\infty}\frac{1}{16^k}(\frac{4}{8k+1}-\frac{2}{8k+4}-\frac{1}{8k+5}-\frac{1}{8k+6})=\pi
$$

- [x] [Basel Problem](https://en.wikipedia.org/wiki/Basel_problem)

$$
\zeta(2)=\sum_{k=1}^{\infty}\frac{1}{k^2}=\frac{\pi^2}{6}
$$

- [x] [Leibniz Formula](https://en.wikipedia.org/wiki/Leibniz_formula_for_pi)

$$
\sum_{k=0}^{\infty}\frac{(-1)^k}{2k+1}=1-\frac{1}{3}+\frac{1}{5}-\frac{1}{7}+\frac{1}{9}-\ldots=\arctan{1}=\frac{\pi}{4}
$$

- [x] [Wallis Product](https://en.wikipedia.org/wiki/Wallis_product)

$$
\prod_{k=1}^{\infty}\frac{(2k)(2k)}{(2k-1)(2k+1)}=\frac{\pi}{2}
$$

- [x] [Viète's Formula](https://en.wikipedia.org/wiki/Viète%27s_formula)

$$
\frac{\sqrt{2}}{2}\cdot\frac{\sqrt{2+\sqrt{2}}}{2}\cdot\frac{\sqrt{2+\sqrt{2+\sqrt{2}}}}{2}\cdot\ldots=\frac{2}{\pi}
$$

Formulae to add:
- [ ] [Chudnovsky Algorithm](https://en.wikipedia.org/wiki/Chudnovsky_algorithm)

$$
\sum_{k=0}^{\infty}\frac{(-1)^k(6k)!(13591409+545140134k)}{(3k)!(k!)^3{640320}^{3k}}=\frac{4270934400}{\sqrt{10005}\pi}
$$

- [ ] [Ramanujan-Sato Series](https://en.wikipedia.org/wiki/Ramanujan–Sato_series)

$$
\sum_{k=0}^{\infty}\frac{(4k)!(1103+26390k)}{(k!)^4{396}^{4k}}=\frac{9801}{2\sqrt{2}\pi}
$$

- [ ] Plouffe's series

$$
\sum_{k=1}^{\infty}k\frac{2^k{k!}^2}{(2k)!}=\pi+3
$$

- [ ] [Riemann zeta function](https://en.wikipedia.org/wiki/Riemann_zeta_function)

$$
\zeta(4)=\sum_{k=1}^{\infty}\frac{1}{k^4}=\frac{\pi^4}{90}
$$

- [ ] Newton, Second Letter to Oldenburg

$$
\sum_{k=0}^{\infty}\frac{(-1)^\frac{k^2-k}{2}}{2k+1}=1+\frac{1}{3}-\frac{1}{5}-\frac{1}{7}+\frac{1}{9}+\frac{1}{11}-\ldots=\frac{\pi}{2\sqrt{2}}
$$

- [ ] [Madhava series](https://en.wikipedia.org/wiki/Madhava_series)

$$
\sum_{k=0}^{\infty}\frac{(-1)^{k}}{3^k(2k+1)}=1-\frac{1}{3^1\cdot3}+\frac{1}{3^2\cdot5}-\frac{1}{3^3\cdot7}+\frac{1}{3^4\cdot9}-\ldots=\sqrt{3}\arctan\frac{1}{\sqrt{3}}=\frac{\pi}{2\sqrt{3}}
$$

- [ ] Nilakantha series

$$
\sum_{k=0}^{\infty}\frac{(-1)^{k+1}}{k(k+1)(2k+1)}=\pi-3
$$

- [ ] $n$-th Fibonacci number

$$
\sum_{n=1}^{\infty}\frac{F_{2n}}{n^2\left({{2n}\atop{}n}\right)}=\frac{4\pi^2}{25\sqrt{5}}
$$

- [ ] Euler's infinite product

$$
\left(\prod_{p\equiv1\text{ (mod }4)}\frac{p}{p-1}\right)\cdot\left(\prod_{p\equiv3\text{ (mod }4)}\frac{p}{p+1}\right)=\frac{3}{4}\cdot\frac{5}{4}\cdot\frac{7}{8}\cdot\frac{11}{12}\cdot\frac{13}{12}\cdot\ldots=\frac{\pi}{4}
$$

- [ ] [Euler's continued fraction](https://en.wikipedia.org/wiki/Euler%27s_continued_fraction_formula#A_continued_fraction_for_π)

$$
\frac{4}{1+\cfrac{1^2}{2+\cfrac{3^2}{2+\cfrac{5^2}{2+\cfrac{7^2}{2+\ddots}}}}}=\pi
$$

- [ ] Archimedes' algorithm

$$
a_0=2\sqrt3,b_0=3,a_{n+1}=\text{hm}(a_n,b_n),b_{n+1}=\text{gm}(a_{n+1},b_n),\pi=\lim_{n\rightarrow\infty}a_n=\lim_{n\rightarrow\infty}b_n
$$

- [ ] Riemann sum to evaluate the area of a unit circle

$$
\lim_{n\rightarrow\infty}\frac{4}{n^2}\sum_{k=1}^{n}\sqrt{n^2-k^2}=\pi
$$

- [ ] Remainder formula

$$
\lim_{n\rightarrow\infty}\frac{1}{n^2}\sum_{k=1}^{n}({n}\text{ mod }{k})=1-\frac{\pi^2}{12}
$$

- [ ] Summing a circle's area

$$
\lim_{r\rightarrow\infty}\frac{1}{r^2}\sum_{x=-r}^{r}\sum_{y=-r}^{r}\left\{\begin{array}{rcl}1&\mbox{if}&\sqrt{x^2+y^2}\le{r}\\0&\mbox{if}&\sqrt{x^2+y^2}\gt{r}\\\end{array}\right.=\pi
$$

- [ ] Combination of Stirling's approximation and Wallis product

$$
\lim_{n\rightarrow\infty}\frac{2^{4n}n!^4}{n(2n)!^2}=\lim_{n\rightarrow\infty}\frac{2^{4n}}{n\left({{2n}\atop{n}}\right)^2}=\lim_{n\rightarrow\infty}\frac{1}{n}\left({\frac{(2n)!!}{(2n-1)!!}}\right)^2=\pi
$$

The comparison was against `math.pi` from Python's `math` package, and `matplotlib` was used to plot the graph.
