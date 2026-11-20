# Regularization of plurisubharmonic exhaustions on complex surfaces

**Zhijian Chen and Bo Xiao** · Version 2 · 20 November 2026 · 13 pages

[Read the paper](papers/paper_v2.pdf) · [LaTeX source](papers/src/main.tex) · [Personal website](https://chen-zhijian.github.io/#surface-regularization)

Theorem 1.2 gives a proposed affirmative answer to Nakano’s question for every connected normal complex surface. A continuous plurisubharmonic exhaustion on one proper resolution suffices to construct a smooth plurisubharmonic exhaustion on the surface itself. Near each singular point the exhaustion is the real part of a holomorphic function, so its smoothness holds in a local ambient embedding.

Remark 6.2 explains the boundary of this result. On a reduced irreducible quasi-projective surface built from a cuspidal cubic, a continuous plurisubharmonic exhaustion exists and every ambient $C^1$ plurisubharmonic function is constant. The example is Proposition 5.7 of the companion paper.

The proof starts from level currents and combines a local Hermitian heat operator with a Dirichlet problem on exhaustion sublevels. Their regular boundaries provide the pluriharmonic collars used to construct the global exhaustion. The introduction describes the contribution of OpenAI Codex to the proposed proof and its internal review. Independent mathematical review is pending.

The companion manuscript *Regularity of plurisubharmonic exhaustions and related problems* supplies the compactifiable surface case, the smooth threefold counterexample, and the nonnormal surface counterexample. References to its theorem numbers follow the 20 November 2026 manuscript. [Companion project](https://github.com/chen-zhijian/psh-exhaustion)

Version 1 included the smooth-surface proof and a normal-surface corollary. [Version 1 PDF](papers/paper_v1.pdf) · [Version 1 source](https://github.com/chen-zhijian/surface-regularization/blob/a29276cf6aecbfd73cb30e59a364f316f2ff411c/papers/src/main.tex)

## Build

The bibliography is embedded in the source. From `papers/src`, run `xelatex main.tex` three times to produce `main.pdf` with the contents, citations, and bibliography back-links resolved.

The [release manifest](verification/build_manifest.json) records the published source and PDF checksums. See the [licensing notice](LICENSE-NOTICE.md) for reuse information.
