
# Changelog

## v2026.01 (unreleased)

* Rename repo from *cip_extremes* to *igcc_t_extremes* to align with the official abbreviation and better reflect that only temperature extremes are considered.

## v2025.01 (02.03.2026)

Release of the version for the analysis for the paper looking at 2024 (Forster et al., [2025](https://essd.copernicus.org/articles/17/2641/2025/)).

- Adapt code to filefisher v1.1.0, formerly filefinder ([#16](https://github.com/ClimateIndicator/igcc_t_extremes/pull/16)).
- Update BerkeleyEarth scripts ([#17](https://github.com/ClimateIndicator/igcc_t_extremes/pull/17)):
  - comment tnn code
  - show last timestep before loading full data
  - update to newly downloaded data
  - re-process new data
- Update ALL_txx_tnn_ts notebook ([#18](https://github.com/ClimateIndicator/igcc_t_extremes/pull/18)).
- Update data for 2024: time series and decadal means ([#19](https://github.com/ClimateIndicator/igcc_t_extremes/pull/19)).
- Add Berkeley Earth to data table ([#23](https://github.com/ClimateIndicator/igcc_t_extremes/pull/23)).
- Only show 1850-1900 in table and remove 1961-1990 to simplify it ([#24](https://github.com/ClimateIndicator/igcc_t_extremes/pull/24)).

## v2024.01 (12.03.2025)

Release of the version for the analysis for the paper looking at 2023 (Forster et al., [2024](https://doi.org/10.5194/essd-16-2625-2024)). (As always it's confusing: the paper looking at 2023 came out in 2024 and I push the tag in 2025, just before working on the new paper.)

- Process data and re-do figures.
- BerkeleyEarth
  - version data to enable comparing across years
  - add notebook to compare across years

## v2023.02 (04.03.2024)

- Save decadal means as csv, for comparability.
- No longer load TNn in main notebook.

## v2023.01 (22.02.2024)

Create a release of the version for the analysis for the paper looking at 2022 (Forster et al., [2023](https://essd.copernicus.org/articles/15/2295/2023/)). (Allthough the date is 2024, the code reflects the status of the analysis in 2023 of 2022.)

* Code for the analysis of 2022.
