<p align="center">
  <img src="assets/inkpilot.svg" alt="InkPilot logo" width="96">
</p>

<h1 align="center">InkPilot</h1>

<p align="center"><b>An open-source printer manager for Epson printers.</b></p>

Setup, ink levels, maintenance, print settings and print jobs, all in one simple app. No bloat, no ads, no account sign-ups.

<p align="center">
  <img src="docs/screenshots/overview.png" alt="InkPilot overview screen showing printer status, ink levels and today's cleaning count" width="860">
</p>

> ⚠️ **Status: early development.** The screenshots below come from the v0.2 UI design. There's no public release yet. Star or watch the repo to follow progress.

---

## Why InkPilot?

Epson's own software works, but it's spread across several separate tools, it's heavy, it nags you, and it looks different for every model. InkPilot aims to be one clean, fast utility that works the same way across Epson printers.

## Features

### Live status and ink levels
See at a glance whether the printer is ready, busy or stuck, with live ink levels for every colour. Low ink is flagged before it ruins a print. For EcoTank models, tap **I just refilled** after topping up the tanks.

### Clear help when something goes wrong
When the printer stops, InkPilot tells you what happened in plain words and walks you through the fix step by step. Your print job waits safely in the queue until you're done.

<p align="center">
  <img src="docs/screenshots/error-help.png" alt="Paper jam screen with four numbered steps to clear it" width="860">
</p>

### Guided maintenance
No more guessing from a nozzle check printout. InkPilot shows a good and a bad example side by side, then cleans only if it's needed. It tracks how many cleanings you've done today, so you don't waste ink or wear out the waste ink pad.

<p align="center">
  <img src="docs/screenshots/maintenance.png" alt="Maintenance screen comparing a good and a bad nozzle check pattern" width="49%">
  <img src="docs/screenshots/cleaning.png" alt="Print head cleaning in progress with a countdown timer" width="49%">
</p>

### Print settings and presets
Everything from Epson's driver tabs in one page: paper, quality, colour, layout, two-sided printing and more. Save your own presets like *Everyday*, *Fast draft* or *Ink saver*, and they apply to prints from every app.

<p align="center">
  <img src="docs/screenshots/print-settings.png" alt="Print settings page with presets, paper, quality, layout and preview" width="760">
</p>

### Light and dark mode
Follows your Windows theme by default, or pick Light or Dark yourself.

<p align="center">
  <img src="docs/screenshots/overview-dark.png" alt="InkPilot overview screen in dark mode" width="860">
</p>

### App settings
Choose a theme and accent colour, decide which alerts you want, start with Windows, and set maintenance reminders.

<p align="center">
  <img src="docs/screenshots/app-settings.png" alt="App settings page with appearance, notifications, startup and maintenance options" width="760">
</p>

### Coming later

| Tray icon and notifications | Scanning |
|---|---|
| <img src="docs/screenshots/tray.png" alt="Tray popup with ink levels and a low-ink notification" width="300"> | <img src="docs/screenshots/scan.png" alt="Scan tab with page preview and scan options" width="520"> |
| Lives in the Windows tray. Ink at a glance, plus a notification when ink runs low, paper runs out, a job finishes or an error appears. | Scan documents and photos on all-in-one models, save as PDF, JPEG, PNG or TIFF. *(Proposal)* |

See the full plan in [docs/ROADMAP.md](docs/ROADMAP.md).

## Supported printers

The first test printer is the **Epson EcoTank L3252**. The goal is to support as many Epson models as possible over time.

See [docs/SUPPORTED_PRINTERS.md](docs/SUPPORTED_PRINTERS.md) for the current list. If you own an Epson printer and want to help test, please [open a printer support request](https://github.com/CreativeBuilds1236/InkPilot/issues/new?template=printer_support.md).

## Platforms

- Windows (first target)
- Linux (planned)

## Contributing

Contributions are welcome, especially testing on printer models we don't have. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

InkPilot is open source under the [MIT License](LICENSE).

## Disclaimer

InkPilot is an independent project. It is **not affiliated with, endorsed by, or supported by Seiko Epson Corporation**. "Epson" and "EcoTank" are trademarks of Seiko Epson Corporation, used here only to describe which printers the software works with.

Maintenance features send commands directly to your printer. Use them at your own risk. Features that could damage a printer or void its warranty will always be clearly marked and will ask for confirmation first.

---

Made by [Rajesh Divakaran](https://github.com/CreativeBuilds1236)
