# ipmisc 2.0.0

  - New function: `stats_type_switch`.
  
  - `signif_column` now explicitly returns a dataframe.
  
  - The following function are no longer re-exported from `broomExtra` to remove
    it from imports: `tidy`, `glance`, `augment`, and `easystats_to_tidy_names`.
    This gets rid of dependence on `broomExtra`.
    
  - `bartlett_message` and `normality_message` function lose `output` argument.
    They now always return a message.
    
  - Minimum R version needed is bumped to `R 3.6.0`.

# ipmisc 1.2.0

  - Re-exports `easystats_to_tidy_names` from `broomExtra`.
  
  - Fixes tests for the new release of `tibble`.

# ipmisc 1.1.0

  - Re-export `tibble::as_tibble` and color functions from `crayon`.
  
  - New function: `easystats_to_tidy_names`, `sort_xy`.

# ipmisc 1.0.0

  - Initial release of the package.
