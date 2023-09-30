Let $w = G(x,y,z)$ be defined in a region of [[3-Space]] containing a surface S

S is a graph of $z = f(x,y)$
- Projection $R$ of $S$ onto [[x-y plane]] is either a Type I or Type II Region

If $G$, $f$, $\partial_x f$, $\partial_y f$ are all continuous in region containing S:
$$ \iint_R G(x,y,z)dS = \iint_R G(x,y,f(x,y))\cdot \sqrt{1 + (\partial_xf)^2 + (\partial_y f)^2}\; dA $$
For projections onto other planes (ex. xz plane) $y = g(x,z)$ -> 
$$\iint_R G(x,y,z)dS = \iint_R G(x,g(x,z),z)\cdot \sqrt{1 + (\partial_xf)^2 + (\partial_zf)^2}\; dA $$
