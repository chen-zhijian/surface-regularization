# Regularization of plurisubharmonic exhaustions on complex surfaces

**Zhijian Chen and Bo Xiao** · Version 1 · 20 November 2026 · 11 pages

[Read the paper](papers/paper_v1.pdf) · [LaTeX source](papers/src/main.tex) · [Personal website](https://chen-zhijian.github.io/#surface-regularization)

This preprint proposes an affirmative answer to Nakano’s question in complex dimension two. Given a continuous plurisubharmonic exhaustion on a smooth complex surface, it constructs a smooth plurisubharmonic exhaustion. The argument also treats normal complex surfaces, with smoothness understood in local ambient embeddings.

The proof starts from level currents and combines a local Hermitian heat operator with a Dirichlet problem on exhaustion sublevels. Their regular boundaries provide the pluriharmonic collars used to construct the global exhaustion. The introduction describes the contribution of OpenAI Codex to the proposed proof and its internal review. Independent mathematical review is pending.

The companion manuscript *Regularity of plurisubharmonic exhaustions and related problems* supplies the compactifiable surface case, the smooth threefold counterexample, and the nonnormal surface counterexample. References to its theorem numbers follow the 20 November 2026 manuscript. [Companion project](https://github.com/chen-zhijian/psh-exhaustion)

## Build

The bibliography is embedded in the source. From `papers/src`, run `xelatex main.tex` three times to produce `main.pdf` with the contents, citations, and bibliography back-links resolved.

The [release manifest](verification/build_manifest.json) records the published source and PDF checksums. See the [licensing notice](LICENSE-NOTICE.md) for reuse information.
