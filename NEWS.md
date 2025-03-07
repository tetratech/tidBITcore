NEWS
================
<Erik.Leppo@tetratech.com> and <jon.harcum@tetratech.com>

<!-- NEWS.md is generated from NEWS.Rmd. Please edit that file -->

    #> Last Update: 2025-03-01 10:45:42.533007

# tidBITcore 0.2.0.9001 (2025-03-01)

- renamed tidBIT to tidBITcore

# tidBIT 0.1.0.9037 (2025-02-03)

- refactor: hod_edge_match_C to new int_grid format; transform_inverse\>
  FisherZ bug corrected

# tidBIT 0.1.0.9036 (2024-12-02)

- refactor: Add new function hod_edge_match_C

# tidBIT 0.1.0.90305_dev (2024-11-13)

- docs: refactored beta_logit_tran_inverse to algorithm updated for
  execution time

# tidBIT 0.1.0.9031_dev (2024-11-13)

- docs: Update documentation details for `report_diagnostics`
- docs: Begin set up of GitHub Action for pkgdown
- fix: Update `report_objects` palette for maps
  - volume 1 map 1
  - volume 2 map 2
- refactor: Change color of points in volume 2 report;
  `report_diagnostics`
  - Change salmon to red

# tidBIT 0.1.0.9030_dev (2024-11-08)

- style: Move commas to end of line in `report_diagnostics`
- refactor: Move support files for `report_diagnostics`
  - RMD and R files
- refactor: Update `report_diagnostics` help
- docs: Update packages in DESCRIPTION for use with diagnostics report
- refactor: Add new functions for use with diagnostics report
- refactor: Update `report_objects` function
  - Add package prefix to functions
  - Add objects to global environment where needed for rendering of RMD

# tidBIT 0.1.0.9029_dev (2024-11-01)

- refactor: Intermediate (unfinished) updates prior to merging updates
  from main branch

# tidBIT 0.1.0.9034

- wrapper for matrix multiplication added

# tidBIT 0.1.0.9033

- refactor help file for replicate_rows_by_seq

# tidBIT 0.1.0.9032

- added matrix multiplication function

# tidBIT 0.1.0.9031

- added Cholesky decomposition function

# tidBIT 0.1.0.9030

- added Cholesky decomposition function

# tidBIT 0.1.0.9029

- refactor: Add default xlab and ylab to plot_bivariate_date, Issue \#13

# tidBIT 0.1.0.9028

- refactor: transformations: Fisher Z transformation option added.

# tidBIT 0.1.0.9027

- update help files

# tidBIT 0.1.0.9026

- refactor function files

# tidBIT 0.1.0.9025

- refactor transformations

# tidBIT 0.1.0.9024

- refactor: Added package name for functions
  - stats::fivenum
- docs: Remove unused packages from DESCRIPTION
  - MASS
- docs: Modify list of package imported, Issue \#9
  - Change importfrom %\>% from magrittr to dplyr
  - Remove magrittr from Imports

# tidBIT 0.1.0.9023

- docs: Update Vignette name and added to docs folder, Issue \#8

# tidBIT 0.1.0.9022

- refactor correlation and covariance functions

# tidBIT 0.1.0.9021

- added fivenum_char, fivenum_charp, …

# tidBIT 0.1.0.9020

- added plot_mat_cov (Matrix-Based Covariance Plot)

# tidBIT 0.1.0.9019

- added plot_matr_corr (Matrix-Based Correlation Plot)

# tidBIT 0.1.0.9018

- ar1 modeling refactored, migrate from as.Date to lubridate::date

# tidBIT 0.1.0.9017

- leap_yday added to package help page; supporting leap_yday functions
  refactored

# tidBIT 0.1.0.9016

- refactored to add helper functions decimal_date and decimal_hours

# tidBIT 0.1.0.9015

- refactored leap_yday to allow for arbritrary start day

# tidBIT 0.1.0.9014

- refactored leap_yday to allow for ‘water’- or ‘climate’- based year

# tidBIT 0.1.0.9013

- ar(1) function documentation improved

# tidBIT 0.1.0.9012

- functions arima_def, arima_alt, arima_mm, estimate_ar1, plot_acf_pacf
  refactored to improve documentation and remove options for user to try
  and use order != c(1,0,0)

# tidBIT 0.1.0.9011

- functions arima_def, arima_alt, arima_mm, estimate_ar1, plot_acf_pacf
  added

# tidBIT 0.1.0.9010

- functions plot_obs_pred_res, plot_bivariate_data, and
  plot_4_panel_distr added

# tidBIT 0.1.0.9008

- refactor: reduced exported functions

# tidBIT 0.1.0.9007

- refactor: Corrected beta logit documentation, Issue \#3
  - fun_beta_logit.R

# tidBIT 0.1.0.9006

- refactor: Corrected beta logit transformation, Issue \#2
  - fun_beta_logit.R

# tidBIT 0.1.0.9005

- feature: Add new functions and checked with Check Package
  - fun_cb4d_buildout_01.R

# tidBIT 0.1.0.9004

- refactor: Update NEWS install section and format, Issue \#1

# tidBIT 0.1.0.9003

- docs: Update package documentation
  - DESCRIPTION
  - NEWS
  - README
  - License (MIT)
- functions: Add new function files
  - fun_beta_logit.R
  - fun_cb4d_buildout_00.R
  - fun_mapping.R
  - tidBIT.R
- style: Add style to functions
  - Wrap text at 80 lines
  - Denote ending braces for functions
- documentation: Run CMD check and fix issues
  - Add packages to DESCRIPTION
  - Add bindings for global variables for functions
  - Add missing ImportFrom functions

# tidBIT 0.1.0.9002

- docs: Add issue templates to repository

# tidBIT 0.1.0.9001

- Create Repository on GitHub
