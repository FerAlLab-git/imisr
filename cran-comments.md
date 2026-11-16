## Resubmission

This is a resubmission. In response to the review:

* References in the Description are now written as authors (year)
  <doi:...>, with years in parentheses and no commas.
* The only term in single quotes is now the package name 'future', which
  the Description calls the 'future' package (it said 'future' framework);
  the quotes around IMIS-opt were removed.

Since the first submission I also added two arguments to `imis()`
(`initial_draws` and `initial_log_lik`), fixed importance weights for initial
draws with zero prior density, and added references for the example models
in the documentation.

## Submission

This is a new submission. 'imisr' re-implements the incremental mixture
importance sampling algorithm of the archived 'IMIS' package (Raftery and
Bao), whose authors are credited as contributors. The package is licensed
GPL (>= 3), compatible with the GPL (>= 2) license of 'IMIS'.

## R CMD check results

0 errors | 0 warnings | 1 note

* New submission.

The words flagged as possibly misspelled in DESCRIPTION are names: Raftery,
Bao and Emond are authors of the cited references, and IMIS is the name of
the algorithm and of the archived package.

## Test environments

* local macOS, R 4.5.2
* GitHub Actions: macOS, Windows and Ubuntu (R release, devel and oldrel-1)
* win-builder: Windows, R-devel
