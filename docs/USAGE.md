# Usage Notes

NetProbe is intended for defensive network diagnostics on systems and networks you are authorized to test.

## Before running checks

- Confirm you have permission to probe the target.
- Start with the narrowest host and port scope necessary.
- Avoid aggressive concurrency against production services.
- Record the command and environment when results need to be reproduced.

## Interpreting results

Treat network observations as diagnostic evidence rather than proof of a vulnerability. Validate important findings independently and preserve timestamps when troubleshooting changing services.