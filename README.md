# Koji Miyazawa

Data scientist and product manager based in London. I work on Bayesian statistics for healthcare data and marketing science, and publish the tools I build along the way.

## Open source

| Project | What it does |
|---|---|
| [jpomop](https://github.com/kojikojikojikoji/jpomop) | Converts Japanese DPC inpatient data to the OMOP Common Data Model v5.4. Built from the public specification and synthetic data only. |
| [partworth](https://github.com/kojikojikojikoji/partworth) | Hierarchical Bayes choice-based conjoint analysis in Python (PyMC), with Sawtooth-style outputs and a market simulator. |
| [natural-japanese-writing](https://github.com/kojikojikojikoji/natural-japanese-writing) | An agent skill for Claude Code, Codex and Cursor that rewrites AI-sounding Japanese into natural Japanese without changing the facts. |

## Contributions to other projects

- [ArviZ (arviz-stats) #489](https://github.com/arviz-devs/arviz-stats/pull/489), merged: `hdi` now returns NaN for both bounds when the input contains NaN and `skipna` is False.
- [OHDSI CommonDataModel #819](https://github.com/OHDSI/CommonDataModel/pull/819), open: typo fixes in the OMOP CDM documentation.

## Worked examples in Bayesian statistics

Executed Jupyter notebooks, each on one method and one public dataset.

- [bayesian-pairwise-ranking](https://github.com/kojikojikojikoji/bayesian-pairwise-ranking): Bradley-Terry, Davidson and Plackett-Luce in PyMC, applied to LLM arena votes, food preferences and tennis
- [bayesian-ab-decision-kit](https://github.com/kojikojikojikoji/bayesian-ab-decision-kit): sequential A/B testing with expected-loss stopping rules
- [bayesian-psychometrics](https://github.com/kojikojikojikoji/bayesian-psychometrics): Rasch, 2PL and graded response models
- [dp-customer-segmentation](https://github.com/kojikojikojikoji/dp-customer-segmentation): Dirichlet process mixtures on retail RFM features
- [uplift-modeling-benchmark](https://github.com/kojikojikojikoji/uplift-modeling-benchmark): S/T/X meta-learners on the Criteo uplift dataset
- [bayesian-volatility-regimes](https://github.com/kojikojikojikoji/bayesian-volatility-regimes): stochastic volatility and regime-switching HMMs
- [backtest-overfitting-check](https://github.com/kojikojikojikoji/backtest-overfitting-check): CSCV/PBO, Deflated Sharpe Ratio and MinBTL

## kintone plugins

Thirteen open-source plugins for [kintone](https://www.kintone.com/), written in TypeScript. A few to start with:
[command palette](https://github.com/kojikojikojikoji/kintone-command-palette),
[record diff viewer](https://github.com/kojikojikojikoji/kintone-record-diff-viewer),
[status time tracker](https://github.com/kojikojikojikoji/kintone-status-time-tracker),
[draft autosave](https://github.com/kojikojikojikoji/kintone-draft-autosave).
The rest are listed under [repositories](https://github.com/kojikojikojikoji?tab=repositories&q=kintone).

## Writing

- partworth: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/partworth-hierarchical-bayes-for-choice-based-conjoint-in-python-3d9k) / [Medium](https://medium.com/@miyako0434/partworth-hierarchical-bayes-for-choice-based-conjoint-in-python-563964bf0eae) / [Zenn (日本語)](https://zenn.dev/koji4/articles/441c78ed1db94b)
- jpomop: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/jpomop-open-code-to-convert-japanese-dpc-inpatient-data-to-omop-1m23) / [Medium](https://medium.com/@miyako0434/jpomop-open-code-to-convert-japanese-dpc-inpatient-data-to-omop-f25930ffa852) / [Zenn (日本語)](https://zenn.dev/koji4/articles/289c359381b03d)
