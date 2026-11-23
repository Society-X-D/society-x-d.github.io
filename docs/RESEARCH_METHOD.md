# Current research methodology

## Why this first experiment?
An initial autonomous research system needs a transparent, reproducible task that can run without a paid model API or private credentials. The prototype scans a finite set of open indicators for persistent relationships that may merit deeper investigation. It is intentionally modest: a first instrument for discovery, not a claim to general intelligence or scientific validation.

## Current data coverage
The prototype currently uses **only the World Bank's World Development Indicators (WDI)**, accessed through its documented public API. It does not yet combine World Bank data with OECD, Eurostat, UN, national statistical agencies, academic literature, or other independent sources. The WDI-only scope is a practical first experiment, not a restriction on the project's longer-term research scope.

The selected indicators, codes, years, and retrieval URLs are captured in each run record. Review the World Bank's terms and attribution guidance before reusing data outside this prototype:
- https://datahelpdesk.worldbank.org/knowledgebase/articles/898581-api-basic-call-structures
- https://www.worldbank.org/en/about/legal/terms-of-use-for-datasets

## Analysis
For each pair of indicators, Pearson's r is calculated separately for each year using only countries with both values. A year requires at least 40 countries, and a pair requires at least 8 usable years. Pairs are ranked by mean absolute yearly correlation and direction consistency. No causal inference, p-value fishing, or novelty claim is made.

## Next research loop
A candidate association should lead to competing explanations, possible confounders, falsification tests, and a more focused follow-up question. The next stage should add independent datasets and time-aware robustness checks before any claim is promoted.

## Important limitations
The current prototype performs a bounded statistical scan of a small, predefined indicator set. It does not yet autonomously survey all scientific literature or the wider internet, and its output is not peer-reviewed research. Treat every candidate as a lead for further investigation, not as an established discovery.
