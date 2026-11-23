# SOCIETY-X — Discovery Portal

The public research portal for SOCIETY-X. This repository contains the static website, published research outputs, and public methodology. The research engine is maintained separately.

## Website
The current GitHub Pages address is:
https://society-x-d.github.io/

A custom domain (for example, `society-x.io`) can be connected after it has been registered and its DNS records have been configured.

## Published material
- Latest exploratory research record: `results/latest.json`
- Research run history: `results/history.jsonl`
- Research methodology and source notes: `docs/RESEARCH_METHOD.md`

## Interpretation
Current records are exploratory and unverified. Correlation is not causation. These results do not establish novelty, causality, or predictive usefulness. Stronger claims require robustness checks and independent replication.

## Deployment
The GitHub Actions workflow in `.github/workflows/pages.yml` deploys this static site. In Settings → Pages, set **Build and deployment → Source** to **GitHub Actions**. Future pushes to `main` will deploy automatically.

## Separation and privacy
This repository is intended to remain public. Do not place private agent code, internal prompts, credentials, tokens, private data, or internal operational logs here. The core research repository is maintained separately. Moving files does not erase public Git history.
