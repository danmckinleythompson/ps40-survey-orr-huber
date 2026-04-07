# PS40 Class Survey: Orr & Huber (2020) Replication

A minimal in-class replication of [Orr & Huber (2020)](https://doi.org/10.1017/S0003055420000441), "The Policy Basis of Measured Partisan Animosity in the United States," *APSR*.

## What it does

Students answer three background questions (party ID, immigration position, Iran policy position), then evaluate three randomized profiles on a 0–10 feeling thermometer. Each profile shows a person's state, occupation, and party. Half the profiles also include a randomly assigned policy position (the treatment condition).

The key test: is the gap in warmth between co-partisans and out-partisans smaller when policy information is present? Orr & Huber find yes — much of what looks like partisan animosity is actually policy disagreement.

## Design

- **Control arm:** Profile shows state, job, party only
- **Policy treatment:** Profile adds a randomly selected immigration or Iran policy position
- **Randomization:** Treatment assignment, profile party, and policy position are all independently randomized per profile
- **Outcome:** 0–10 feeling thermometer
- **Observations per student:** 3 profile evaluations

## Results dashboard

Click "📊 Results" in the nav bar to see live results, including mean warmth by treatment arm, the 2×2 (party × policy congruence), and an affective polarization comparison.

## Data

Responses are stored in a Google Sheet via an Apps Script webhook. Click "⬇ CSV" in the results dashboard to download the raw data.

## Deployment

Hosted on GitHub Pages. Built as a single `index.html` file with no dependencies beyond Google Fonts.
