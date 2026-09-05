# Troubleshooting

Use this checklist when a diagnostic does not produce the expected result.

1. Confirm the target is correct and authorized.
2. Verify local DNS and routing configuration.
3. Check whether the target is reachable over the intended address family.
4. Compare the observed error with the documented exit status.
5. Repeat with a bounded timeout.
6. Record the environment and exact observation before reporting the issue.

Avoid treating a timeout as proof that a service is offline. Firewalls, routing, and filtering can produce similar symptoms.