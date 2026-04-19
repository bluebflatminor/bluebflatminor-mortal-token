# The Mortal Token
### A Coherence-Gated Persistence Filter for Photonic AI Acceleration

**Solbakken Research Initiative**  
April 2026

---

## What This Is

The mortal token proposes temporal self-limitation as a fifth required property of the modal token — a hybrid computational primitive introduced in the parent paper *The Conversion Floor*. Instead of engineering around analog weight decay, the mortal token designs it in: a binary-flag leaky integrator instantiated in grain boundary trap states of ferroelectric-graphene photonic MVM devices, with programmable decay lifetime τ and coherence-gated renewal.

**The inversion**: decay is not the enemy. Unverified persistence is.

The mortal token is a coherence-gated persistence filter with no absolute reference frame. It bounds persistence against step-change coherence violations. Whether it bounds persistence against slow coherent drift depends on Unknown Eleven and is not assumed.

This is a preprint research direction. The mortal token is not demonstrated, not implemented, and not claimed to be compatible with the Goldilocks window without measurement. The speculation is labeled. The questions are answerable. The measurement exists — with one instrumentation prerequisite named.

---

## Document

**[mortal_token_v7.pdf](./mortal_token_v7.pdf)** — current version, supersedes all prior versions.

Prior versions (v1–v6) are superseded and not included. The version history in the v7 footer records what each version corrected and why.

---

## Parent Paper

This document is a standalone addendum to:

**The Conversion Floor: Tokens, Modal Tokens, and the Two-Source Noise Condition for Photonic AI Acceleration**  
Nils Haaland, Solbakken Research Initiative, April 2026  
→ [bluebflatminor/graphene-photonic-memory-routes](https://github.com/bluebflatminor/graphene-photonic-memory-routes)

The parent paper introduces the modal token, the two-dimensional conversion floor (weight memory stability δ_m and modulation noise σ_mod), the Goldilocks window, and eight named unknowns. This document introduces Unknown Nine through Unknown Eleven and proposes a fifth required property of the modal token.

---

## The Core Claim

The mortal token extends the parent paper's conversion floor to three axes:

```
b ≥ max( f(δ_m), g(σ_mod), h(m, τ) )
```

where h(m, τ) is the governance tax — the ADC precision cost of operating near the mortality boundary — formalized as an SNR-constrained scaling ansatz anchored to published HfO₂ noise data.

The scalar Goldilocks margin G = min(distance to nearest Goldilocks boundary) in (δ_m, σ_mod) space defines the Pareto frontier between filter utility and operating window position.

---

## Named Unknowns

| Unknown | Question | Resolution |
|---|---|---|
| Five-A | Is the Raman perturbation a reliable proxy for γ? | Prerequisite measurement |
| Nine | Does the G-versus-τ Pareto frontier contain workable operating points? | Route I device ensembles |
| Nine-A | What is the latency-noise Pareto for σ_read(t_int) below 100 ns? | Probe power separation |
| Ten | Is S(ψ, s) the appropriate coherence test? Cost-additive or class-changing? | Primary protocol + deferred pulse-shaping phase |
| Ten-A | What is the functional form of γ(m)? | γ(t) trajectory measurement |
| Eleven | Does Route I exhibit Regime A (quantization brake) or Regime B (distributed trap, no brake)? | Step 5 drift resolution |

**Protocol gap**: Full Unknown Ten resolution (class-change detection) requires pulse-shaping hardware with sub-nanosecond timing resolution and phase control. That phase is deferred and named. The primary protocol resolves all other unknowns.

---

## The Filter's Hard Boundary

The mortal token governs persistence against step-change coherence violations.  
It does not govern persistence against slow coherent drift.  
Unknown Eleven determines whether grain boundary physics closes that gap (Regime A) or leaves it open (Regime B).  
A well-characterized filter with a known hard boundary is more useful than an overclaimed primitive.

---

## Review Provenance

This document was developed through seven versions and six AI review rounds:

- **Perplexity** — saturation cutoff derivation, negative control requirements, scalar Goldilocks margin, claim layer separation
- **DeepSeek** — Bayesian formalism mismatch, h(m,τ) tightening, confirmed v6 direction, synthesized ChatGPT review
- **GPT-4** — distributed trap regime fork for Unknown Eleven, S(ψ,s) class-change risk, γ(m) separability assumption
- **Gemini** — pulse-shaping hardware gap via Step 4 temporal asymmetry detection question
- **Deep Think** — latency-noise Pareto constraint for Unknown Nine-A, minimum resolvable drift framing for Unknown Eleven
- **ChatGPT** — γ(m) three-assumption falsifiable structure, Unknown Ten functional equivalence risk, logarithmic δs spacing

Each round's specific contributions are recorded in the version history in the document footer.

---

## Status

| Property | Status |
|---|---|
| Demonstrated | No |
| Implemented | No |
| Compatible with Goldilocks window | Unknown — measurement required |
| Goldilocks margin G defined | Yes — first-order projection, not sufficient statistic |
| σ_read anchored | Order-of-magnitude — Route I device characterization required |
| Unknown Ten fully resolved | No — deferred pulse-shaping phase required |
| Unknown Eleven | Open — Regime A or B determination required |

---

## Epistemic Standard

This document applies the Yamamoto standard from the parent paper: exact about the boundary between what the architecture provides, what it requires, and what remains unknown. Claims are labeled as established device analogs, proposed formalism, or experimental conjecture. The filter boundary — step-change violations bounded, coherent drift not bounded — is held throughout without softening.

Epistemic drift across review rounds was actively monitored and corrected. The version history records where drift occurred and what was fixed.

---

## Citation

If you use or build on this work, attribution to the Solbakken Research Initiative is expected:

```
Haaland, N. The Mortal Token: A Coherence-Gated Persistence Filter 
for Photonic AI Acceleration. Solbakken Research Initiative, April 2026.
github.com/bluebflatminor/mortal-token
```

---

## License

MIT License — see [LICENSE](./LICENSE).  
This repository uses the MIT license for GitHub compatibility. For a research document of this nature, attribution to the Solbakken Research Initiative is expected in any derivative work or citation, consistent with standard academic norms.

---

## Contact

**Nils Haaland**  
Solbakken Research Initiative  
nhaaland@yahoo.com  
GitHub: [bluebflatminor](https://github.com/bluebflatminor)
