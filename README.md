# Koji Miyazawa

Data scientist in Japan.

At a medical data company, I analyse electronic health records and cancer genomic panel test results from hospitals, for pharmaceutical companies. For example, how often lung side effects appear with anticancer drugs, how often gene variants appear, and finding side effects in free-text clinical notes.

I also build products: an on-premise AI server, an ERP built from scratch, and software for accounting and education. I recently released [GogaQ](https://apps.apple.com/app/id6762157603), an iPhone and iPad app for learning languages from real sentences.

Other areas I work in: claims data, doctor surveys (conjoint analysis), Bayesian statistics and causal inference. I publish the tools I make here.

## Open source

| Project | What it does |
|---|---|
| [jpomop](https://github.com/kojikojikojikoji/jpomop) | Converts Japanese DPC inpatient data to the OMOP Common Data Model v5.4. Built from the public specification and synthetic data only. On PyPI: [`pip install jpomop`](https://pypi.org/project/jpomop/). |
| [partworth](https://github.com/kojikojikojikoji/partworth) | Hierarchical Bayes choice-based conjoint analysis in Python (PyMC), with Sawtooth-style outputs and a market simulator. On PyPI: [`pip install partworth`](https://pypi.org/project/partworth/). |
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

Ten open-source plugins for [kintone](https://www.kintone.com/), written in TypeScript. Each README is available in English and Japanese.

| | Plugin | What it does |
|---|---|---|
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-command-palette/HEAD/plugin/icon.png" width="28" alt=""> | [command-palette](https://github.com/kojikojikojikoji/kintone-command-palette) | Ctrl+K command palette: jump to apps, views and records from the keyboard |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-record-diff-viewer/HEAD/plugin/icon.png" width="28" alt=""> | [record-diff-viewer](https://github.com/kojikojikojikoji/kintone-record-diff-viewer) | Compare two records side by side with field-level and inline text diff |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-status-time-tracker/HEAD/plugin/icon.png" width="28" alt=""> | [status-time-tracker](https://github.com/kojikojikojikoji/kintone-status-time-tracker) | Track how long records spend in each process status and locate bottlenecks |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-round-robin-assigner/HEAD/plugin/icon.png" width="28" alt=""> | [round-robin-assigner](https://github.com/kojikojikojikoji/kintone-round-robin-assigner) | Assign new records to team members in rotation or by current workload |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-draft-autosave/HEAD/plugin/icon.png" width="28" alt=""> | [draft-autosave](https://github.com/kojikojikojikoji/kintone-draft-autosave) | Auto-save form input and restore it after a lost tab or session timeout |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-markdown-copy/HEAD/plugin/icon.png" width="28" alt=""> | [markdown-copy](https://github.com/kojikojikojikoji/kintone-markdown-copy) | Copy records and list views to the clipboard as Markdown tables, lists or TSV |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-image-annotator/HEAD/plugin/icon.png" width="28" alt=""> | [image-annotator](https://github.com/kojikojikojikoji/kintone-image-annotator) | Draw arrows, shapes and text on attached images, keeping the original file |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-image-compressor/HEAD/plugin/icon.png" width="28" alt=""> | [image-compressor](https://github.com/kojikojikojikoji/kintone-image-compressor) | Compress and resize images in the browser before attaching, stripping EXIF location data |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-dummy-data-generator/HEAD/plugin/icon.png" width="28" alt=""> | [dummy-data-generator](https://github.com/kojikojikojikoji/kintone-dummy-data-generator) | Generate realistic Japanese test data, reproducible with a fixed seed |
| <img src="https://raw.githubusercontent.com/kojikojikojikoji/kintone-theme-switcher/HEAD/plugin/icon.png" width="28" alt=""> | [theme-switcher](https://github.com/kojikojikojikoji/kintone-theme-switcher) | Dark and dim themes with per-user switching and OS auto mode |

## Writing

- partworth: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/partworth-hierarchical-bayes-for-choice-based-conjoint-in-python-3d9k) / [Medium](https://medium.com/@miyako0434/partworth-hierarchical-bayes-for-choice-based-conjoint-in-python-563964bf0eae) / [Zenn (日本語)](https://zenn.dev/koji4/articles/441c78ed1db94b)
- jpomop: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/jpomop-open-code-to-convert-japanese-dpc-inpatient-data-to-omop-1m23) / [Medium](https://medium.com/@miyako0434/jpomop-open-code-to-convert-japanese-dpc-inpatient-data-to-omop-f25930ffa852) / [Zenn (日本語)](https://zenn.dev/koji4/articles/289c359381b03d)
- natural-japanese-writing: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/japanese-has-its-own-ai-tells-i-built-an-agent-skill-that-fixes-them-385d) / [Zenn (日本語)](https://zenn.dev/koji4/articles/42b8c6d5901323)
- GogaQ, a language-learning app: [DEV](https://dev.to/koji_m_f02cae8a899bf33627/a-language-app-that-corrects-the-sentence-you-actually-wrote-3cb7) / [Medium](https://medium.com/@miyako0434/a-language-app-that-corrects-the-sentence-you-actually-wrote-62548c46ed2e)
