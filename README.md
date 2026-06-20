# semver
Learning semantic versioning for releases.


## Comit Messages

Commit messages need to adhere to following structure,

`<change type>`: `<commit message>`
Example: "fix: revamp authentication flow"

Following commit types are available

`feat`: A new feature → minor version bump

`fix`: A bug fix → patch version bump

`perf`: A performance improvement → patch version bump

`refactor`: Code change that is neither a bug fix nor a feature → no version bump ( never refactor old releases, always do it on main and ship it on the next release )

`docs`: Documentation changes only → no version bump

`Style`: Code style changes (e.g., formatting, missing semicolons) → no version bump

`test`: Adding or updating tests → no version bumps

`build`: Changes to the build system or dependencies → no version bump

`chore`: Routine tasks not modifiying source or test files → no version bump

`revert`: Reverting a previous commit → patch version bump
