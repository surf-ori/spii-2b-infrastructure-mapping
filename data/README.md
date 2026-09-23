# Data

## `open-science-nl-components.csv` / `OpenScienceNL_components.xlsx`

An inventory of 112 infrastructure components and agreements (standards, guidelines,
registries, repositories, and similar) in the Dutch Open Science digital research ecosystem,
each with its type, category, maintenance status, level (institutional/national/international/
European), maintainer, country, and (where known) a link and description.

Source: Bey, T. (2026). *Open Science components in the Netherlands digital research
ecosystem* (Version 0.1) [Dataset]. Zenodo.
[https://doi.org/10.5281/zenodo.20509748](https://doi.org/10.5281/zenodo.20509748).

`OpenScienceNL_components.xlsx` is the original file as received. `open-science-nl-components.csv`
is a straight conversion of its one sheet (`Sheet 1`) to CSV: the header row plus 112 data rows,
dropping only a handful of fully blank trailing rows and a stray "Table 1" label above the
header in the original sheet. Typos in the source (e.g. "in developement", "planned?") are kept
as-is for faithful extraction rather than corrected. This is version 0.1 of an evolving
inventory — consult the Zenodo record for later versions before citing any of its content as
final.

Columns: `Type` (Infrastructure or Agreement), `Category`, `Component` (name), `Status`
(maintained / in development / planned), `Level` (institutional / national / international /
European), `Maintainer`, `Country`, `Adopters`, `Integration`, `Integration points`, `Link`,
`Description`, `Comments`.
