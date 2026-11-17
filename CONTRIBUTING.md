# Contributing to Vertex

Thank you for your interest in contributing to the **Vertex Application**! I welcome bug reports, feature suggestions, and modular addon development from the open-source community.

## Module & Plugin Development

- **Personal Use**: Users and developers are completely free to build and run their own custom plugins and modules for personal or internal use without needing prior permission or contact.
- **Publishing to Vertex Cloud Store Catalog**: If you intend to submit a module to be featured in the official Vertex Cloud Store catalog or distributed officially, you **must strictly adhere to the non-negotiable rules below and contact me first before submitting code or pull requests**.

To propose a module for the catalog or collaborate on core features, get in touch with me directly:
- **Contact Author**: [https://vishwasupponi.blogspot.com/links](https://vishwasupponi.blogspot.com/links)

Let me know what you have in mind so we can discuss the approach and ensure it aligns with Vertex's architecture and security standards.

## Non-Negotiable Invariants

Any contribution or module submitted for the official catalog must strictly adhere to the core principles of Vertex:
1. **Zero Telemetry**: No tracking, analytics, diagnostic telemetry, or remote call-homes under any circumstances.
2. **100% Offline-First**: All data processing must execute locally on the user's computer without mandatory cloud or external server dependencies.
3. **Decoupled Addon Architecture**: New tools must be structured as independent, modular plugins.
4. **No Personal Data or Paths**: No machine paths, personal accounts, credentials, or private keys may ever be introduced.

## Reporting Bugs & Suggesting Features

If you encounter an issue or have an idea for an improvement:
- **Bug Reports**: Open an issue using the Bug Report template with details on your Windows environment, steps to reproduce, and any relevant log excerpts from `UserData/app_debug.log`.
- **Feature Requests**: Open an issue using the Feature Request template describing the workflow improvement you would like to see.

## License

By contributing to Vertex, you agree that your contributions will be licensed under the project's **GNU Affero General Public License v3 (AGPL-3.0)**.
