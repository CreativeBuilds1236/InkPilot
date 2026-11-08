# InkPilot Roadmap

This is a living plan. Items may move between phases as the project grows.

## Phase 0 — Foundations
- [ ] Choose the tech stack and set up the project structure
- [ ] Set up builds and automated checks (GitHub Actions)
- [ ] Document how Epson printers report status and accept maintenance commands
- [ ] Collect test data from the first printer (Epson EcoTank L3252)

## Phase 1 — Find and read the printer
- [ ] Detect printers connected by USB
- [ ] Detect printers on the local network (Wi-Fi / Ethernet)
- [ ] Show model name, serial number and firmware version
- [ ] Show live status (ready, busy, error, out of paper, paper jam)
- [ ] Show ink levels (cartridge models)

## Phase 2 — Maintenance
- [ ] Nozzle check print
- [ ] Print head cleaning
- [ ] Power cleaning / ink charge (with clear warnings about ink use)
- [ ] Print head alignment
- [ ] Read the maintenance (waste ink pad) counter — read-only

## Phase 3 — EcoTank support
- [ ] Ink tracking per tank
- [ ] Reset ink level after refill
- [ ] Refill reminders

## Phase 4 — Print jobs
- [ ] View the print queue
- [ ] Pause, resume and cancel jobs
- [ ] Saved print presets

## Phase 5 — Polish and reach
- [ ] Guided first-time setup (including Wi-Fi setup)
- [ ] Linux version
- [ ] Command-line tool
- [ ] Translations (starting with Arabic)

## Later / ideas
- [ ] Scanning for all-in-one models
- [ ] Plugin system for model-specific features
- [ ] Usage history (pages printed, ink used)
