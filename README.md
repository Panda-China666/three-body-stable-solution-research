# Three-Body Stable Solution Research

Using a new advanced algorithm, we publish 139 numerically verified periodic solutions of the Newtonian three-body problem that are linearly stable under spatial perturbations.

![Stable orbits](figures/stable_orbits_gallery.png)

## Completed numerical validation

All 139 published solutions passed the following numerical checks. Error bounds below cover the entire catalog, with $G=1$ and energy normalized to $E=-1$.

| Check | Passed | Result across all 139 solutions |
| --- | --- | --- |
| Relative periodic closure | 139 / 139 | State-return residual below $5.41\times10^{-11}$ after removing the accumulated rotation. |
| Spatial Floquet stability | 139 / 139 | Six nontrivial multipliers per solution; maximum deviation from the unit circle below $6.64\times10^{-9}$. |
| Reduced symplectic structure | 139 / 139 | Relative symplectic defect below $4.07\times10^{-9}$. |
| Initial energy normalization | 139 / 139 | Absolute deviation from $E=-1$ below $3.99\times10^{-13}$. |
| Rational rotation and period reconstruction | 139 / 139 | $\theta=2\pi p/q$ with coprime $p,q$ and inertial period $T=q\tau$. |

Per-solution initial conditions, closure residuals, spatial Floquet multipliers and symplectic defects are available in [the JSON catalog](data/stable_orbits.json). Initial conditions and summary metrics are also available in [CSV format](data/stable_orbits.csv).
