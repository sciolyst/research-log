# Week 01 — Numerical Solution of ODEs

Euler, RK4, stability, convergence order. Foundation for every time-stepping scheme used later in the roadmap (heat equation, Burgers, Euler equations, detonation model).

## Goals

- [ ] Derive forward Euler from a Taylor expansion; identify the truncation error term
- [ ] Understand RK4 conceptually (weighted average of slope estimates across the step)
- [ ] Read about stability regions — why Euler blows up on stiff problems, why implicit methods don't
- [ ] Implement forward Euler and RK4 **from scratch, no libraries**, on a problem with a known exact solution (simple harmonic oscillator: y'' = -y)
- [ ] Run both at several step sizes; plot error vs. step size on log-log axes
- [ ] Confirm the slope matches theoretical order (~1 for Euler, ~4 for RK4)
- [ ] Write up what matched theory and what didn't

## Files

- `src/` — solver implementations
- `report.md` — write-up

## Notes / open questions

(fill in as you go)
