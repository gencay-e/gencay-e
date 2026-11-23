# Gencay

Open-source projects across security, developer tooling, and local-first software.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[scanfuse](https://github.com/gencay-e/scanfuse)** | Merges and deduplicates findings across 11 scanner formats (Nmap, Nuclei, OWASP ZAP, Burp Suite, Nessus, Trivy, SARIF, Semgrep, Grype, Nikto, and testssl.sh) into Markdown, standalone HTML, JSON, CSV, SARIF, or PDF reports, with `--baseline` retest diffs. Runs offline without network calls. Install with `pipx install scanfuse` ([PyPI](https://pypi.org/project/scanfuse/)). | Python 3.12+, Typer, Pydantic, defusedxml, Jinja2, nh3 |
| **[mcp&#8209;moat](https://github.com/gencay-e/mcp-moat)** | A stdio policy proxy (`moat`) between an MCP client and a local MCP server. Checks path and command arguments against a policy, scrubs sensitive environment variables from the child process, enforces tool allowlists, prompts on the terminal before risky calls, masks known secret formats in server output, and writes a hash-chained JSONL audit log. Install with `cargo install --locked mcp-moat` ([crates.io](https://crates.io/crates/mcp-moat)) or from the [releases page](https://github.com/gencay-e/mcp-moat/releases). | Rust, Tokio, Clap, Aho-Corasick, SHA-256 / HMAC |
