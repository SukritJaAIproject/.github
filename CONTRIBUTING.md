# Contributing

Thank you for helping with these projects. This guide applies to every repository under `SukritJaAIproject` that does not have its own `CONTRIBUTING.md`. Issues and pull requests are welcome in English or Thai (ยินดีรับทั้งภาษาไทยและภาษาอังกฤษ).

## What the repositories are

Most of them are applied AI for the electricity sector in Thailand: EV-charger fault detection and OCPP tooling, solar and hydro forecasting, predictive maintenance, IoT energy management, and a fully local LLM workbench. Older numbered repositories (`1_…` to `16_…`) are research notebooks from 2018–2021 kept for reference; fixes to them are welcome but they are not under active development.

## Ways to help

- **Report a bug** with the bug-report form: what you ran, what happened, what you expected, your OS and Python version.
- **Ask for a feature** with the feature-request form and explain the use case.
- **Pick an issue** labelled `good first issue` (small and self-contained) or `help wanted` (larger, guidance available).
- **Improve documentation**: README clarifications, Thai or English translations, and reproducible examples count as contributions.
- **Comment first** on an issue before starting substantial work so efforts are not duplicated.

## Pull requests

1. Fork the repository and create a branch from `main` (or `master` in the older repositories).
2. Keep each pull request to one logical change.
3. Describe what changed, why, and how you tested it. If a change moves a benchmark or model result, name the script and the result file.
4. Make sure existing tests or notebooks still run. Repositories with a `tests/` folder or a GitHub Actions workflow must stay green.
5. Do not commit datasets, packet captures, credentials, API keys, connection strings or anything that identifies a real station, vehicle, patient or person.

## Data and privacy

Several projects were built on operational or clinical data that cannot be redistributed. Share synthetic or anonymised samples only, and describe the real data instead of attaching it.

## Licensing

Unless a repository states otherwise, code is released under the MIT License (`bpc-csms-cloud` uses Apache-2.0). By submitting a contribution you agree that it is licensed under the same license as the repository it goes into.

## Questions

Open a GitHub Discussion where enabled, or an issue with the `question` label. See `SUPPORT.md` for details.
