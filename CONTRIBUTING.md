# Contributing to InkPilot

Thanks for wanting to help! Here's how to get involved.

## Ways to help

- **Test on your printer.** The most useful thing you can do. Open a [printer support request](https://github.com/CreativeBuilds1236/InkPilot/issues/new?template=printer_support.md) with your model.
- **Report bugs.** Use the [bug report](https://github.com/CreativeBuilds1236/InkPilot/issues/new?template=bug_report.md) template.
- **Suggest features.** Open an issue and describe what you'd like and why.
- **Write code or docs.** Pick an open issue, comment that you're working on it, then open a pull request.

## Pull requests

1. Fork the repo and create a branch from `main` (for example `feature/ink-levels` or `fix/usb-detect`).
2. Keep each pull request focused on one change.
3. Describe what you changed and how you tested it, including which printer model you used.
4. Make sure the build and checks pass.

## Safety rule for maintenance features

Some printer commands can waste ink, wear the printer, or void its warranty. Any feature like this must:

- be clearly labelled in the app,
- ask the user to confirm before running, and
- never run automatically in the background.

Writing to printer memory (for example resetting the waste ink counter) is **out of scope** for now.

## Be respectful

Be kind and patient with other contributors. Harassment or personal attacks are not tolerated.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
