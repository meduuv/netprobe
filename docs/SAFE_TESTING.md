# Safe Testing

NetProbe is intended for defensive diagnostics on systems and networks you are authorized to inspect.

## Test boundaries

- Prefer loopback, lab, staging, or owned infrastructure.
- Keep probes read-only.
- Use the smallest scope that answers the diagnostic question.
- Avoid automated probing of third-party infrastructure.

## Reproducibility

Record the target, command, timestamp, network context, and observed result when reporting a diagnostic issue.

## Sensitive output

Do not publish credentials, tokens, private addresses, or unrelated host information in bug reports.
