# submission name

OPAL temporal-projector compression v4

# archive

- Size: **182,040 bytes**
- SHA-256: `bd9a47149b52a8f4986758e9274e509836bfa9c89f9b5cb069e90837eeb18400`
- Single stored ZIP member `p`: **181,940 bytes**
- Token stream: **110,022 bytes**

# score

- PoseNet distortion: `0.0000068843892` (unchanged from F26)
- SegNet distortion: `0.0002963935258` (unchanged from F26)
- Exact score: **0.1591495384**

# GPU requirement

Yes. OPAL deliberately inherits F26's CUDA renderer. Its entropy backend is CPU-oriented C.

# technical claim

OPAL changes only the lossless probability law used to arithmetic-code F26's frozen tokens. It decomposes the inherited five-class law into the rank-one maximal projector and its complement, learns only probability transport between those sectors, and preserves F26's relative conditional law inside the complement. A finite commutative algebra of 55 causal projector families includes uncertainty, maximal-projector identity, HPAC incidence, temporal word orbits, causal defect words, and spacetime holonomy sectors. All 49.4 MB of adaptive sector state is regenerated from the decoded prefix; transmitted OPAL parameters are zero bytes.

The full-sequence causal gain is 37,472.661262 ideal bits, 908.321262 bits beyond the historical OPAL brief. The production archive independently decodes all 600 frames with zero token mismatches and the frozen token SHA-256 `c5c7671d037b6912980c57929a5b6d789d250ee6a93e3b0a6018cf9f63e32ece`.

# novelty boundary

Arithmetic coding, logistic Newton updates, context models, and finite operator algebras are established. The nontrivial composition is the constrained maximal/complement transfer, decoder-synchronous central-sector dynamics, projector-identity refinement, temporal word quotient, causal holonomy, zero transmitted adaptive state, and real bit-exact transcode of a leading neural representation.
