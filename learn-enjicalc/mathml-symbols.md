# MathML Symbols

We are using MathML to define a variable name for several reasons. First, defining subscripts and superscripts is extremely easy with MathML. To define a subscript or superscript, write underscore ` _ ` for subscript or caret ` ^ ` for superscript anywhere after the symbol baseline. You can find examples below. 

A_s,xx -> $A_{s,xx}$ 

L_span,i^0.5 -> $L_{span,i}^{0.5}$ 

- L - baseline
- span,i - subscript
- 0.5 - superscript

Another reason is that Greek letters in MathML can be defined using Latin letters. You can find the complete list of Greek letters and how they are defined below. 

| Small Letter | Definition | Capital Letter | Definition |  Alternative  | Definition  |
| :----------: | :--------: | :------------: | :--------: | :-----------: | :---------: |
|   $\alpha$   |   \alpha   |      $A$       |     A      |               |             |
|   $\beta$    |   \beta    |      $B$       |     B      |               |             |
|   $\gamma$   |   \gamma   |    $\Gamma$    |   \Gamma   |               |             |
|   $\delta$   |   \delta   |    $\Delta$    |   \Delta   |               |             |
|  $\epsilon$  |  \epsilon  |      $E$       |     E      | $\varepsilon$ | \varepsilon |
|   $\zeta$    |   \zeta    |      $Z$       |     Z      |               |             |
|    $\eta$    |    \eta    |      $H$       |     H      |               |             |
|   $\theta$   |   \theta   |    $\Theta$    |   \Theta   |  $\vartheta$  |****  \vartheta  |
|   $\zeta$    |   \zeta    |      $I$       |     I      |               |             |
|   $\kappa$   |   \kappa   |      $K$       |     K      |  $\varkappa$  |  \varkappa  |
|  $\lambda$   |  \lambda   |   $\Lambda$    |  \Lambda   |               |             |
|    $\mu$     |    \mu     |      $M$       |     M      |               |             |
|    $\nu$     |    \nu     |      $N$       |     N      |               |             |
|    $\xi$     |    \xi     |     $\Xi$      |    \Xi     |               |             |
|  $\omicron$  |  \omicron  |      $O$       |     O      |               |             |
|    $\pi$     |    \pi     |     $\Pi$      |    \Pi     |   $\varpi$    |   \varpi    |
|    $\rho$    |    \rho    |      $P$       |     P      |   $\varrho$   |   \varrho   |
|   $\sigma$   |   \sigma   |    $\Sigma$    |   \Sigma   |  $\varsigma$  |  \varsigma  |
|    $\tau$    |    \tau    |      $T$       |     T      |               |             |
|  $\upsilon$  |  \upsilon  |   $\Upsilon$   |  \Upsilon  |               |             |
|    $\phi$    |    \phi    |     $\Phi$     |    \Phi    |   $\varphi$   |   \varphi   |
|    $\chi$    |    \chi    |      $X$       |     X      |               |             |
|    $\psi$    |    \psi    |     $\Psi$     |    \Psi    |               |             |
|   $\omega$   |   \omega   |    $\Omega$    |   \Omega   |               |             |

Finally, if your goal is to create a perfect equation for the web that is very easy to read, MathML is your choice.

$$
\begin{align*}
    \int_0^2
        \left(
            -\frac{1}{4}\left(e^{-4t_1}+e^{4t_1-8}\right)
        \right)
    \,dt_1
\end{align*}
$$
