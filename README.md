# Germany Imaging Atlas — inpatient CT and MRI

**Open the atlas: https://w3id.org/germany-imaging-atlas/**

Inpatient CT and MRI utilisation across 624 ICD-10-GM diagnoses in Germany,
2005–2024, from the German DRG statistics, a mandatory annual census of every
inpatient hospital case. For each diagnosis and each ICD-10 chapter the atlas
shows how often CT and MRI were coded, how that changed over twenty years, the
none / single / multiple procedure-code breakdown, rates for men and women, and
the age and comorbidity of each imaging group.

Companion to the Article *"Inpatient CT and MRI utilisation across 624 diagnoses
in Germany, 2005–24: a national atlas"* (in submission).

## Data

All figures are disclosure-controlled aggregates. The analysis was executed by
staff of the Research Data Centre (RDC) of the Federal Statistical Office and the
statistical offices of the Länder under project 4509-2021, who applied statutory
anonymisation and returned only aggregated tables. A year × code × sex cell is
shown only where at least 100 cases in it received the modality; suppressed cells
are absent, never counted as zero. No author had access to individual-level
records, and the microdata cannot be redistributed. Qualified researchers may
apply to the RDC under its standard terms.

**Required source line for any reuse:**

> RDC of the Federal Statistical Office and Statistical Offices of the Länder,
> Fallpauschalenbezogene Krankenhausstatistik (DRG-Statistik), 2005–2024,
> own calculations (project 4509-2021).

## Cite

> Mirbagheri H, Scheurig-Münkler C, Hellbrück S, Kröncke T, Decker JA.
> Germany Imaging Atlas: inpatient CT and MRI, version 1.0 (extraction v2.8)
> [dashboard]. 2026. https://w3id.org/germany-imaging-atlas/

Please cite the Article for any use of these estimates.

## About this repository

This repository holds the built site only. It is served by GitHub Pages at
https://hamed-kalak.github.io/germany-imaging-atlas/; cite the permanent w3id
address above, which will follow the atlas if it moves. The site makes
no requests to third parties: fonts and data are bundled. `build.json` records
the data file's SHA-256 and the validation checks it passed before release.
