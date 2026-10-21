---
order: 3
---

# Lecture Outline

Phase II - LO1, LO3

Topic Highlights

## Roadmap

1. **What "learning" means**: a model is a formula with dials
2. **Guess, with one neuron**: weigh the clues, add them up, decide
3. **Guess, with a network**: how it is wired, and why a hidden layer moves the dots
4. **Check**: one number for how wrong
5. **Nudge**: walking downhill, and the step size
6. **Blame**: backpropagation, worked by hand with one dial
7. **The loop, running**: watching a network learn, and reading its curves

The through-line is one small network, 2 → 16 → 16 → 1, learning to separate two interlocking crescents of dots. Every key formula is shown three ways: in symbols, in words, and with that example's numbers.

## What you should be able to do afterwards

- Say what "learning" means in one sentence, and name the four steps of the training loop in order: guess, check, blame, nudge.
- Compute a neuron by hand, and explain why one neuron can only draw one straight line.
- Explain ReLU, why every neuron needs a bend, and how a hidden layer moves the XOR dots so that a straight line works.
- Read the squared-miss and cross-entropy losses aloud in plain words, and say when each is used.
- State gradient descent as "new dial = old dial − step size × slope", and predict what too small or too big a step does.
- Find a dial's blame by nudging, state the chain rule as gears, and describe backpropagation's three rules.
- Read a pair of training curves and say whether a run is healthy, too slow, too jumpy or memorising.

## Where this goes

Week 2's logistic regression turns out to be one neuron; Week 2's overfitting and ridge penalty come back as memorising and weight decay; Week 5's learned representation becomes the hidden layer. Week 8 explains *why* the maths works: why cross-entropy is the natural loss, and the linear algebra under every layer. Every deep model in Weeks 9 to 11 runs this same loop with a different machine in the first box.

## In the lab

**How a Machine Learns, and How It Is Wired**: the lecture's examples on your own machine, in the same order. The house dials, the umbrella and loan neurons, XOR wired by hand, the forward pass of a 2 → 16 → 16 → 1 network, gradient descent on one dial, backpropagation written from scratch and proved right with a gradient check, then training on the two moons (97%) and on the Week 1 credit data, compared honestly with Week 2's logistic regression.
