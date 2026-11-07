# Gencay

I build security and developer tools: local-first command-line utilities, runtime guardrails for AI agents, and report automation.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[scanfuse](https://github.com/gencay-e/scanfuse)** | Merges findings from Nmap, Nuclei, OWASP ZAP, Burp Suite, Nessus and Trivy into one report as Markdown, standalone HTML, JSON or CSV. Runs offline without network calls. Install with `pipx install scanfuse` ([PyPI](https://pypi.org/project/scanfuse/)). | Python 3.12+, Typer, Pydantic, Jinja2, nh3 |
| **[mcp-moat](https://github.com/gencay-e/mcp-moat)** | A stdio firewall (`moat`) between an AI agent and its MCP servers: directory jails, tool allowlists, approval prompts in the terminal, secret masking in tool output and a hash-chained JSONL audit log. Binaries for Linux, macOS and Windows are on the [releases page](https://github.com/gencay-e/mcp-moat/releases). | Rust, Tokio, Clap, Aho-Corasick |
