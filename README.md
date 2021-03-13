# Alfred.app No Sleep Workflow

<img src="assets/no-sleep.png" width="64" height="64" alt="No Sleep" />

Workflow to prevent macOS from sleeping.

Allows you to close the lid of your MacBook without entering sleep mode if sleep is disabled.

* `on` - Turn on No Sleep (disables sleep)
* `on for` - Turn on No Sleep for N minutes (disables sleep for N minutes)
* `off` - Turn off No Sleep (enables sleep)

## State agnostic

The workflow is state agnostic and shows the `on`/`off` options according to the current state.

## Sleep for N minutes

Turn on No Sleep only for N minutes.
> Note: Shows a password prompt after N minutes to turn off No Sleep. Does currently not prevent the battery from being drained if you forget to turn off No Sleep.

## Requires administrator privileges

The command (`pmset -a disablesleep [0,1]`) run by the workflow requires administrator privileges and therefore a password prompt is shown when the workflow is executed.
