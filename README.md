# NetProbe

> Read-only network diagnostics for local connectivity troubleshooting.

[![Python](https://img.shields.io/badge/python-3.10%2B-3776AB?style=flat-square)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-111111?style=flat-square)](LICENSE)

NetProbe is a small diagnostic toolkit for inspecting local network connectivity without performing exploitation or modifying remote systems.

## Scope

- Local hostname and address resolution
- Reachability checks for systems you own or administer
- Human-readable diagnostic output
- Read-only operation
- No credential handling
- No exploitation functionality

## Workflow

```text
host / address
      ↓
resolution
      ↓
connectivity check
      ↓
human-readable result
```

## Use Cases

Useful for quick troubleshooting, lab environments, defensive diagnostics and network-learning workflows.

## Development

```bash
python -m unittest discover -s tests -v
```

## Responsible use

Only run network checks against systems and infrastructure you are authorized to inspect.

## License

MIT. See [`LICENSE`](LICENSE).

Built by **Meduuv**.

[More projects](https://github.com/meduuv?tab=repositories) · [guns.lol/meduu](https://guns.lol/meduu)
