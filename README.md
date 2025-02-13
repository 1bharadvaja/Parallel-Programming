# Two Electron Integral API

This repo will be dedicated to trying to write a CUDA library/API for calculating double electron integrals using various recurrence relations and things of that sort

I will be implementing the Boys Function $$\(F(n,z)=\int _{0}^{1}e^{-zt}t^{2}ndt\)$$ soon, and then I will implement Hermite coefficients. 

Finally, I will implement calculation via recurrence for arbitrary angular momentum, in order to produce the repulsion integral $$(ab \mid cd) = \int \int \frac{\phi_a(r_1) \phi_b(r_1) \phi_c{r_2}\phi_d(r_2)}{|r_1 - r_2|} d\tau_{1} d\tau_2$$. 

After all this, I'll probably try to handle contracted basis functions which are sums over primitives, which will be an interesting problem to handle
