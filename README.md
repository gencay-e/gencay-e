# Gencay

Open-source projects across security, developer tooling, and local-first software.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[scanfuse](https://github.com/gencay-e/scanfuse)** | Parses and deduplicates scan output from Nmap, Nuclei, OWASP ZAP, Burp Suite, Nessus and Trivy into one report as Markdown, standalone HTML, JSON, CSV, SARIF or PDF. Runs offline without network calls. Install with `pipx install scanfuse` ([PyPI](https://pypi.org/project/scanfuse/)). | Python 3.12+, Typer, Pydantic, Jinja2, nh3 |
| **[mcp-moat](https://github.com/gencay-e/mcp-moat)** | A stdio policy proxy (`moat`) between an MCP client and its MCP servers. Enforces directory jails and tool allowlists, prompts on the terminal before sensitive actions, masks secrets in server output and writes a hash-chained JSONL audit log. Install with `cargo install mcp-moat` ([crates.io](https://crates.io/crates/mcp-moat)) or from the [releases page](https://github.com/gencay-e/mcp-moat/releases). | Rust, Tokio, Clap, Aho-Corasick |
