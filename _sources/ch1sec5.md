## Formulaire et Tables des principales transformées de Fourier

````{tabs}

```{tab} Propriétés générales

$$\begin{aligned} 
  ax(t)+by(t) &   \rightleftharpoons  aX(f)+bY(f) \\
  x(t-t_{0}) &   \rightleftharpoons X(f)e^{-i 2 \pi f t_{0}} \\
  x(t)e^{+i 2 \pi f_{0} t} &   \rightleftharpoons X(f-f_{0}) \\
  x^{\ast }(t)&  \rightleftharpoons  X^{\ast}(-f) \\
  x(t) y(t)&   \rightleftharpoons   X(f)\ast Y(f) \\
  x(t)\ast y(t) &   \rightleftharpoons  X(f) Y(f) \\
  x(at+b) &   \rightleftharpoons  \frac{1}{\left|a\right|}X\left(\frac{f}{a}\right) e^{i2\pi \frac{b}{a}f} \\
  \frac{dx^{(n)}(t)}{dt^{n}} &   \rightleftharpoons  \left( i2\pi f\right) ^{n}X(f)  \\
  \left( -i2\pi t\right)^{n}x(t) &   \rightleftharpoons  \frac{dX^{(n)}(f)}{df^{n}}  
\end{aligned}$$ 
```

```{tab} Formules Parseval

$$\int_{\mathbb{R}}x(t)y^{\ast }(t)dt=\int_{\mathbb{R}}X(f)Y^{\ast }(f)df$$ 
   
$$\int_{\mathbb{R}}\left| x(t)\right| ^{2}dt=\int_{\mathbb{R}}\left| X(f)\right| ^{2}df$$

```
```{tab} Série de Fourier  

   $$\underset{n\in \mathbb{Z}}{\sum }c_{n}e^{+i2\pi nf_{0}t}\rightleftharpoons \underset{n\in \mathbb{Z}}{\sum }c_{n}\delta \left( f- nf_{0}\right)$$

```

```{tab} Transformées


$$\begin{aligned}
    \hline\\
      1 &   \rightleftharpoons  \delta \left( f \right)\\ 
      \delta \left( t\right) &   \rightleftharpoons  1 \\ 
      e^{+i2\pi f_{0}t}&   \rightleftharpoons \delta \left( f-f_{0}\right)\\ 
     \delta \left( t-t_{0}\right) &   \rightleftharpoons e^{-i2\pi ft_{0}} \\
      \amalg \hspace{-0.3cm}\amalg _{T}\left( t\right)  &  \rightleftharpoons \frac{1}{T}\amalg \hspace{-0.3cm}\amalg _{1/T}\left(f\right) \\
      \cos \left( 2 \pi f_{0}t \right) &   \rightleftharpoons \frac{1}{2}\left(\delta \left( f-f_{0}\right) +\delta \left( f+f_{0}\right) \right) \\ 
      \sin \left( 2\pi f_{0}t\right) &   \rightleftharpoons \frac{1}{2i}\left( \delta \left( f-f_{0}\right)-\delta \left( f+f_{0}\right) \right)\\ 
      e^{-a\left| t\right| } &   \rightleftharpoons \frac{2a}{a^{2}+4\pi ^{2}f^{2}} \\ 
      e^{-\pi t^{2}} &   \rightleftharpoons e^{-\pi f^{2}} \\ 
      \Pi _{T} \left( t\right) &   \rightleftharpoons T \mathrm{sinc}\left( \pi Tf\right) \\ 
      \Lambda _{T}\left( t\right) &   \rightleftharpoons T \mathrm{sinc}^{2}\left( \pi Tf\right) \\ 
      B \mathrm{ sinc}\left( \pi Bt\right) &   \rightleftharpoons \Pi _{B}\left( f\right) \\ 
      B \mathrm{ sinc}^{2}\left( \pi Bt\right)  &   \rightleftharpoons \Lambda _{B}\left( f\right) \\ 
      \hline
\end{aligned}$$


$$\amalg \hspace{-0.3cm}\amalg _{T}\left( t\right) = \underset{k\in \mathbb{Z}}{\sum } \delta \left( t-kT\right)$$

$$\mathrm{sinc}\left( \pi Tf\right)=\frac{\sin \left( \pi Tf\right) }{\pi T f}$$
    
```
````


```{warning} 

$\Pi _{T}\left( t\right)$ note une fenêtre rectangulaire de support égal à $T$.

$\Lambda _{T}\left( t\right)$ note une fenêtre triangulaire de support égal à $2T$ (de demi-base égale à $T$).

$$\Pi _{T}\left( t\right) \ast \Pi _{T}\left( t\right) =T~\Lambda _{T}\left(
t\right)$$

```