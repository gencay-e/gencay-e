# Gencay

I work in IT security and build small, local-first CLI tools in Rust and Python for penetration testing workflows and runtime guardrails around AI coding agents.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[scanfuse](https://github.com/gencay-e/scanfuse)**<br>[![PyPI](https://img.shields.io/pypi/v/scanfuse?color=blue)](https://pypi.org/project/scanfuse/) | Merges and deduplicates findings across 11 scanner formats (Nmap, Nuclei, OWASP ZAP, Burp Suite, Nessus, Trivy, SARIF, Semgrep, Grype, Nikto, and testssl.sh) into Markdown, standalone HTML, JSON, CSV, SARIF, or PDF reports, with `--baseline` retest diffs. Runs offline without network calls. | Python&#160;3.12+, Typer, Pydantic, defusedxml, Jinja2, nh3 |
| **[mcp&#8209;moat](https://github.com/gencay-e/mcp-moat)**<br>[![crates.io](https://img.shields.io/crates/v/mcp-moat?color=orange)](https://crates.io/crates/mcp-moat) | Stdio policy proxy (`moat`) between an MCP client and a local MCP server. Checks path and command arguments against a policy, scrubs sensitive environment variables from the child process, enforces tool allowlists, prompts on the terminal before risky calls, masks known secret formats in server output, and writes a hash-chained JSONL audit log ([releases](https://github.com/gencay-e/mcp-moat/releases)). | Rust, Tokio, Clap, Aho&#8209;Corasick, SHA&#8209;256, HMAC |

### Quick install

```bash
pipx install scanfuse
cargo install --locked mcp-moat
```
