# Timeout guidance

Network diagnostics should use bounded timeouts so an unreachable endpoint cannot stall an entire run.

Choose timeout values according to the protocol and network environment, and report timeout outcomes separately from confirmed connection failures.
