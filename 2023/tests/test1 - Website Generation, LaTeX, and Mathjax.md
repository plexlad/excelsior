Pythagorean Theorum
$$a^{2} + b^{2} = c^2$$
Matice Example
$$\begin{bmatrix}
1 & 2 & 3 \\
a & b & c
\end{bmatrix}$$
Fractions?:
$$\frac{A_{1} + A_{2}}{B_{1} + B_{2}} = M$$
Linear Function:
$$f(x) = x$$
Drawing Functions:
```tikz
\begin{document}
  \begin{tikzpicture}[domain=0:4]
    \draw[very thin,color=gray] (-0.1,-1.1) grid (3.9,3.9);
    \draw[->] (-0.2,0) -- (4.2,0) node[right] {$x$};
    \draw[->] (0,-1.2) -- (0,4.2) node[above] {$f(x)$};
    \draw[color=red]    plot (\x,\x)             node[right] {$f(x) =x$};
    \draw[color=blue]   plot (\x,{sin(\x r)})    node[right] {$f(x) = \sin x$};
    \draw[color=orange] plot (\x,{0.05*exp(\x)}) node[right] {$f(x) = \frac{1}{20} \mathrm e^x$};
  \end{tikzpicture}
\end{document}
```
Personal function:
```tikz
\begin{document}
	\begin{tikzpicture}[domain=0:5]
		\draw[help lines] (-0.4, -0.4) grid (4.9, 4.9);
		\draw[thick,<->] (-0.4, 0) -- (4.9, 0) node[above] {$x$};
		\draw[thick,<->] (0, -0.4) -- (0, 4.9) node[right] {$f(x)$};
		\draw[variable=\x,red,thick,domain=-0.4:2.2] plot ({\x}, {\x*\x}) node[right] {$f(x)=x^2$};
		\draw[variable=\x,color=yellow,thick,domain=-0.4:3.5] plot({\x},{sin(\x r)/pi}) node[right] {$f(x)=\frac{\sin(x)}{\pi}$};
	\end{tikzpicture}
\end{document}
```
Quadratic formula:
$$x=\frac{{-b\pm\sqrt{b^2-4ac}}}{2a}$$
Sin Function:
$$f(x)=\frac{\sin(x)}{\pi}$$
Sigma:
$$\Sigma$$
