# model is validated

    Code
      add_model(workflow(), 1)
    Condition
      Error in `new_action_model()`:
      ! `spec` must be a `model_spec`.

# cannot add two models

    Code
      add_model(workflow, mod)
    Condition
      Error in `add_action()`:
      ! A `model` action has already been added to this workflow.
