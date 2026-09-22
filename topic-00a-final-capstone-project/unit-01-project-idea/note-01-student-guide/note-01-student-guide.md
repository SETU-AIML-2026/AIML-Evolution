---
order: 1
icon:
  type: fluent:lightbulb-24-filled
  color: "#C68A1B"
---

# Student Guide: Your Capstone Idea in Five Steps

The form takes 15 minutes.

## The five steps

1. **Pick something that changes.** A cup of coffee cooling. A swing slowing down. Flu spreading through a town.
2. **Find the law of science it follows.** Use the table below. If you are not sure, tick "not sure" on the form and we will help.
3. **Say who would use your answer.** A café owner. A doctor. A school principal.
4. **Say how you would check the answer.** The table tells you for each idea.
5. **Fill in the form.** Use the **Capstone Idea Form** card next to this guide.

## How it works, in one paragraph

In Week 3 the machine learned by **guess, check, blame, nudge**, and the *check* used a dataset. In your project the *check* uses a **law of science** instead: if the model's guess breaks the law, the loss is high, and the model is nudged until it obeys. No dataset needed. You will learn how in Week 5.

## Twelve ideas to choose from

The first six are the easiest. Pick one, or change one to suit you.

| The idea | In plain words | The law of science | How to check it |
|---|---|---|---|
| **1. Coffee cooling** | Hotter than the room means it cools faster | Newton's law of cooling: dT/dt = −k(T − T_room) | Exact formula |
| **2. Painkiller leaving the blood** | The same fraction goes every hour | First-order elimination: dC/dt = −kC | Exact formula |
| **3. Camera flash charging** | Fast at first, then slower and slower | RC circuit: RC dV/dt + V = V_s | Exact formula |
| **4. A swing slowing down** | Pulled back to the middle, slowed by friction | Damped oscillator: m d²x/dt² + c dx/dt + kx = 0 | Exact formula |
| **5. A pendulum at big angles** | The further it swings, the harder the pull back | Pendulum equation: d²θ/dt² + (g/L) sin θ = 0 | Solver; energy stays the same |
| **6. A ball slowed by air** | Gravity pulls down, air pushes back | Newton's second law with drag: m dv/dt = mg − cv | Exact formula |
| **7. Foxes and rabbits** | More rabbits feed more foxes; more foxes eat more rabbits | Lotka-Volterra: dR/dt = aR − bRF, dF/dt = cRF − dF | Solver |
| **8. A flu outbreak** | Spread depends on who is ill and who can still catch it | SIR model: dS/dt = −βSI/N, dI/dt = βSI/N − γI, dR/dt = γI | Solver; the total stays the same |
| **9. Heat in a metal spoon** | Heat flows from warm bits to cool neighbours | Heat equation: ∂u/∂t = α ∂²u/∂x² | Exact formula (simple cases) |
| **10. A guitar string** | Each bit is pulled by its neighbours | Wave equation: ∂²y/∂t² = c² ∂²y/∂x² | Exact formula |
| **11. A sagging shelf** | Weight bends it, stiffness resists | Euler-Bernoulli beam: EI d⁴w/dx⁴ = q | Exact formula |
| **12. A spill in a river** | Carried along and spreading out | Advection-diffusion: ∂c/∂t + u ∂c/∂x = D ∂²c/∂x² | Exact formula |

**You do not need to solve these equations.** You only need to know which one is yours. *dT/dt* just means "how fast T is changing", the same idea as the slope in Week 3.

## What happens next

| When | What |
|---|---|
| **Now** | Fill in the form. We reply within a week. |
| **Week 5** | You learn how to build the model. |
| **Week 12** | Show your project live. |

At the end you hand in four things: **your working model**, **a comparison** with a model that learns from examples instead of the law, **a short report** on who it helps and how, and **a live showcase**. Together they are 40% of the module.

## Stuck?

Pick idea 1 (coffee). It is a complete project on its own. Or post in the channel; that is what it is for.
