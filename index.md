# Web3 Research Archive

Security research documenting smart contract vulnerabilities and protocol economic risk analysis.

---


## Research Archive
{% if site.posts.size > 0 %}
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt | strip_html | truncate: 200 }}

---
{% endfor %}
{% else %}

### Active Research
Current investigations include:
- Smart contract vulnerability analysis
- Protocol economic security and credit risk
- Cross-chain bridge security
- DeFi lending covenant enforcement

Detailed research findings are documented in the folders below.
{% endif %}

---

## Research Resources

**[Code Experiments](./code-experiments)** — Proof-of-concept implementations for vulnerabilities and defenses

**[Quantitative Models](./quantitative)** — Financial models, credit analysis, and risk simulations

**[Protocols](./protocols)** — Supporting data and analysis files for protocol research

**[Research Notes](./research-notes)** — Ongoing investigations and experimental findings

**[Exploits](./exploits)** — Additional vulnerability documentation and case studies

---
## About This Research
For detailed methodology and research standards, see the [README](./README.md).
