# Exit codes

Automation should be able to distinguish outcomes consistently.

- `0`: completed successfully.
- Non-zero: an error or unsuccessful diagnostic outcome occurred.

Scripts should treat output text as informational and use the process exit status for automation decisions.
