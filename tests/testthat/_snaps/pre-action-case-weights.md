# `remove` is validated

    Code
      add_case_weights(workflow(), foo, remove = 1)
    Condition
      Error in `add_case_weights()`:
      ! `remove` must be a single `TRUE` or `FALSE`.

# case weights `col` can't select >1 columns in `data`

    Code
      fit(wf, mtcars)
    Condition
      Error in `fit()`:
      ! `col` must specify exactly one column from `data` to extract case weights from.

# case weights must be integer or double

    Code
      fit(wf, df)
    Condition
      Error in `new_stage_pre()`:
      ! `case_weights` must be an integer or double vector.
