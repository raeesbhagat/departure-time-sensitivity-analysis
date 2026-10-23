# Island Hopper Departure-Time Sensitivity Analysis

What does a departure-time coefficient mean in practical terms?

This is a public documentation repository for a connected research workstream in Raee Bhagat’s portfolio. It describes methods and decisions from reviewed project materials. It does not contain the original analysis implementation, participant data, or internal research files.

[Portfolio](https://raeeb.dev/) · [Workstream in the project library](https://raeeb.dev/project-library#P16)

## Research context

Examined how departure timing relates to cognitive performance, fatigue, and sleepiness in Island Hopper operations. The notebook fits separate outbound and inbound regressions and translates hourly coefficients into an estimated change for a 30-minute schedule shift. Related calculations explore how adjusting for departure timing affects outcome variability and planned sample sizes. This is a useful example of translating a regression coefficient into an operationally understandable scenario.

## What the workflow produces

Outbound/inbound regressions and illustrative 30-minute schedule-shift summaries.

## Methods and decisions

- Linear regression.
- schedule sensitivity.
- effect-size interpretation.
- covariate-adjusted variance.
- sample-size planning.

## Libraries and tools

`R`, `dplyr`, `tidyr`, `TrialSize`, `ggplot2`, `openxlsx`, `knitr`, `R Markdown`.

These tools are associated with the reviewed workstream. This repository is documentation, so it does not install or execute those libraries.

## How to read this workstream

1. Start with the research question: What does a departure-time coefficient mean in practical terms?
2. Read the documented approach above, paying attention to cohort definitions, temporal alignment, repeated observations, and the stated methods where applicable.
3. Evaluate the output in context: Outbound/inbound regressions and illustrative 30-minute schedule-shift summaries.
4. Separate exploratory or planning work from final conclusions. The repository contains no executable replication or new validation run.

## Where the methods transfer

Translating regression coefficients into understandable scenarios without overstating causality.

## Evidence and boundaries

The schedule-shift summaries describe associations, not causal effects of changing a schedule.

The portfolio contains twenty connected workstreams. Several share datasets, preparation logic, research programs, or legacy code. Separate documentation repositories do not imply twenty independent completed studies or exclusive authorship of all underlying research.

## Privacy and reproducibility

- Original datasets, participant identifiers, internal file paths, workbooks, and unpublished source code are not included.
- Public interactive examples on the portfolio use synthetic teaching data and are labeled accordingly.
- There is no install command, runnable research pipeline, or reproducibility claim for this documentation repository.
- No institutional endorsement or ownership of shared research materials is implied.

## Author and contact

Raee Bhagat · [Portfolio](https://raeeb.dev/) · [LinkedIn](https://www.linkedin.com/in/raee-suresh-bhagat-53168890/) · [Email](mailto:raeesbhagat@gmail.com)
