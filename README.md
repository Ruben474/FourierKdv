# Physics-Informed Neural Networks and Fourier Methods for the Generalized Korteweg--de Vries Equation

**Autores**: Rubén Darío Ortiz Ortiz, Ana Magnolia Marín Ramírez, Miguel Angel Ortiz Marín

## Abstract

We conduct a comprehensive comparative study of numerical solvers for the generalized Korteweg--de Vries (gKdV) equation, focusing on classical Fourier-based Crank--Nicolson methods and Physics-Informed Neural Networks (PINNs). Our work benchmarks these approaches across nonlinear regimes—including the cubic case \( \nu = 3 \)—and diverse initial conditions such as solitons, smooth pulses, discontinuities, and noisy profiles. In addition to pure PINN and spectral models, we propose a novel hybrid PINN–spectral method incorporating a regularization term based on Fourier reference solutions, leading to improved accuracy and stability. Numerical experiments show that while spectral methods achieve superior efficiency on structured domains, PINNs provide flexible, mesh-free alternatives for data-driven and irregular setups. The hybrid model achieves lower relative \( L^2 \) error and better captures soliton interactions. Our results demonstrate the complementary strengths of spectral and machine learning methods for nonlinear dispersive PDEs.
