# Theory Audit

fasttfp v0.4.0 separates theory estimators from software compatibility modes.

Key principles:
- OP, LP, ACF and GNR are implemented according to original estimating equations.
- Existing Stata/R packages are treated as compatibility references.
- Theory mode avoids hidden regularization.
- ACF multiple roots are diagnosed rather than hidden.
