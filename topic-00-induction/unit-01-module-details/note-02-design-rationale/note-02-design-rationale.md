---
order: 3
icon:
  type: hugeicons:ai-innovation-01
  color: "#2D7FF9"
---

# Why the Module Looks Like This

Rationale behind the structure

A conventional version of this module would follow the field's textbook chronology and spend three
weeks on classical material before reaching anything current. This one treats history as a **fast
orientation — one week, not three** — and spends the freed time on where the field is actually moving.

Three commitments follow from that.

## 1. Science-inspired AI

Two directions at once. **AI for science**: AlphaFold 3, GNoME materials discovery, weather and
climate models. **Science-grounded architectures**: physics-informed neural networks, neural
operators, neural ODEs, diffusion understood as thermodynamics.

The unifying idea, and the one to carry from Week 4 into Week 5: *embedding scientific structure as
inductive bias makes models more data-efficient and more trustworthy*. An architecture is an
assumption about the world. When the assumption matches reality, the model needs less data and
generalises better.

## 2. Scale-free, lean LLMs

The move beyond brute-force scaling: state-space models such as Mamba, linear and attention-free
architectures, mixture-of-experts, distillation, low-bit quantization, parameter-efficient
fine-tuning, on-device and neuromorphic deployment, and test-time-compute reasoning.

Scaling worked. The module's thesis is that the frontier has moved past it — and that the interesting
engineering question is now *how small and how cheap can this get while still working*.

## 3. Responsible AI from day one

Bias, fairness and explainability sit in **Week 2**, framed as a design constraint that shapes every
model built afterwards, rather than as a closing topic bolted on in Week 11. Moving it early also
means LO6 is taught and consolidated well before the Week 6 quiz.

## Frontier strands beyond the current descriptor

These four strands are additions. If the programme is validated against the existing descriptor, the
descriptor's indicative content — and ideally LOs 2, 3 and 7 — should be refreshed to name them.

| Strand | Week | Examples taught |
|---|---|---|
| Science-grounded architectures | 5 | PINNs, neural operators (FNO, DeepONet), neural ODEs, diffusion as thermodynamics, equivariant/geometric nets, thermodynamics-informed GNNs |
| Scale-free architectures | 8 | State-space models (S4, Mamba, Mamba-2), RetNet, RWKV, linear/attention-free models, mixture-of-experts, test-time-compute reasoning |
| Lean / efficient models | 9 | Distillation (transformer→recurrent), low-bit quantization including 1-bit, pruning, LoRA/QLoRA, small language models, edge/TinyML, neuromorphic/spiking |
| AI for scientific discovery | 11 | AlphaFold 2→3, GNoME materials discovery, protein binder design, weather and climate models, foundation models for science |
