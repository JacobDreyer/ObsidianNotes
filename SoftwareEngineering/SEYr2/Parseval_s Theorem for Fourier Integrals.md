let:
$$ g(\alpha) = \int_{-\infty}^\infty \frac1{2\pi}f(x)e^{i\alpha x}dx $$
$$ f(x) = \int_{-\infty}^\infty g(\alpha)e^{-i\alpha x}d\alpha $$
- ^ f.t. pair

- Parseval's Theorem says that:
$$ \int_{-\infty}^\infty |g(\alpha)|^2d\alpha = \frac1{2\pi}\int_{-\infty}^\infty |f(x)|^2 dx $$
- This means that the total energy or power (depending on what f(x) physically represents) in f(x) and the f.t. of f(x) must be the same.
- If f(x) represents some spacial quantity, the energy associated with f(x) is the same regarless of whether you represent f(x) in space, or the frequency domain
- The transformation of a function from the space or time domain, into the spatial frequency or frequency domain, must conserve energy. They are different representations of the same physical thing