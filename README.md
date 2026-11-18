# Embodied-RSI

## Recursive Policy Improvement through Autonomous Experience Feedback

This repository publishes the supplied **anonymous manuscript draft** on recursive task-policy improvement for simulated robotic manipulation. It is a manuscript release; the PDF does not claim conference acceptance.

## Read

- [Original manuscript (PDF)](PAPER.pdf) — the canonical nine-page paper.
- [Illustrated reading guide](REPORT.md) — a web-readable account of the method, reported observations, and evaluation limits.

## At a glance

Embodied-RSI connects physical task execution, outcome checking, filtered experience replay, failure-informed exploration, candidate evaluation, and policy activation. In the reported simulated object-transfer task, approximate stage success rises from **30%** to **70%** to **90%**. These are preliminary stage summaries. The manuscript does not provide complete episode counts, repeated runs, or matched-budget controls sufficient to estimate uncertainty or isolate the effect of recursion.

The separate xArm7 small-step control case study is **not part of the RSI learning curve**. Proposed matched-budget comparisons and active-acquisition extensions are evaluation designs, not reported experimental results. See the [PDF](PAPER.pdf) for exact wording and details.
