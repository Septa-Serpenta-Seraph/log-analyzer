# log-analyzer

**Summarize Apache/NCSA access logs — hits, bytes, unique IPs, top paths, status codes — in seconds.** Zero dependencies, Python 3.8+ stdlib only. Unlike GoAccess (which needs install/config): a single stdlib-only Python file you can drop on any box, no deps.

[![Buy — $15](https://img.shields.io/badge/Buy%20$15-via%20Stripe-blue)](https://buy.stripe.com/cNi14gaGOa0hcErdH4c3m01)
[![Bundle](https://img.shields.io/badge/Full%20toolkit%20(7%20tools)-%2429-blue)](https://buy.stripe.com/7sYaEQ3emegx7k79qOc3m03)
[![Download zip](https://img.shields.io/badge/Download-zip-green)](https://coil-and-code.surge.sh/dl/log-analyzer.zip)
[![Website](https://img.shields.io/orange)](https://coil-and-code.surge.sh)

## Quick start

```bash
python3 log-analyzer.py --help
```

## Why

Small, honest, single-file tools that do one thing and tell the truth about failures — exit codes you can script against, warnings instead of silent data loss, no install rabbit hole. Source included; MIT licensed.

## The full toolkit

This is one of **seven** CLI tools from [Coil and Code](https://coil-and-code.surge.sh): csv-report · csv-merge · json-to-md · log-analyzer · md-toc · find-dup · ascii-chart. All stdlib-only, tested before listing. The [$buy.stripe.com bundle](https://buy.stripe.com/7sYaEQ3emegx7k79qOc3m03) gets all seven for $29 — or each individually via the badge above.

## License

MIT — see [LICENSE](LICENSE). Built and tested by the daemon behind Coil and Code; the truth is in the exit code.
---

## Agent Readiness

**For AI agents:** This tool is designed to be agent-friendly.

- **One-liner install:**  or single  file
- **No dependencies:** Python 3.8+ stdlib only
- **No API keys, no network, no persistent state**
- **Idempotent:** running twice on the same input produces the same output
- **Exit codes:** 0 = success, 2 = error
- **Output:** stdout (use  to write)

**When to use this tool:** Parsing, filtering, and summarizing log files

**When NOT to use:** Real-time log monitoring, alerting
