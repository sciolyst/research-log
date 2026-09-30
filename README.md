# Research Log

Weekly deep-dives building toward computational research in thermal/fluids, combustion, and propulsion. Mechanical Engineering, IUT. Started pre-semester, Year 1.

Each week gets its own folder under `weeks/`: theory notes, from-scratch code (no black-box libraries unless stated), and a short write-up of what got verified and what didn't.

## Roadmap (Year 1, ~8–10 hrs/week, elastic around exam weeks)

- [ ] **Months 1–3 — Numerics & math**: linear algebra/ODE review, Barba's *CFD Python: 12 Steps to Navier–Stokes*, finite volume methods (heat equation, advection, Burgers)
- [ ] **Months 4–6 — Compressible flow, thermo, combustion**: 1D Euler solver (Sod shock tube), quasi-1D nozzle, reactive source term, CJ/ZND detonation
- [ ] **Months 7–9 — Deeper thread**: nonlinear dynamics or rarefied gas (choose at month 6)
- [ ] **Months 10–12 — Research skills**: reproduce one published result end-to-end, differentiable simulation/SciML intro, faculty contact

## Weeks

| Week | Topic | Status |
|---|---|---|
| [01](weeks/week-01-ode-numerics) | Numerical ODEs — Euler, RK4, stability, convergence order | in progress |

## Setup

```bash
pip install -r requirements.txt
```
