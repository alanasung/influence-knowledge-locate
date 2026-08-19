<p align="center">
  <h1 align="center">Locating Factual Knowledge With Influence Functions</h1>
  <p align="center"><strong>Use influence functions on tiny models to find which training points most affect factual behaviors.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Locating Factual Knowledge With Influence Functions**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Use influence functions on tiny models to find which training points most affect factual behaviors.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
