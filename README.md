# Alfred.app Workflows

## No Sleep

<img src="assets/no-sleep.png" width="64" height="64" alt="No Sleep" />

Workflow to prevent macOS from sleeping.

Allows you to close the lid of your MacBook without entering sleep mode if sleep is disabled.

### State agnostic

The workflow is state agnostic and shows the `on`/`off` options according to the current state.

### Requires administrator privileges

The command (`pmset -a disablesleep [0,1]`) run by the workflow requires administrator privileges and therefore a password prompt is shown when the workflow is executed.
