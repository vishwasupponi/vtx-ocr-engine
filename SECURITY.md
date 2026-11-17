# Security Policy

## Privacy & Offline Execution Policy

Vertex is engineered with a strict **Privacy-First, Zero-Telemetry Architecture**:
- **100% Offline Execution**: All file processing, parsing, OCR, and spreadsheet operations take place entirely in memory or on the local filesystem of your machine.
- **Zero Remote Telemetry**: Vertex does not harvest analytics, telemetry, user data, file contents, or device identifiers. No remote servers are contacted during normal offline operation.
- **Credential Safety**: User-provided credentials (such as portal logins or PDF passwords) are retained only in volatile session memory during execution and are never written to disk or transmitted to third parties.

## Supported Versions

Only the latest official release receives active security and bug fix updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability or privacy concern within Vertex or any of its official addon modules:

1. **Do not create a public issue.**
2. Reach out to me directly via the contact options on my website:
   - **Contact**: https://vishwasupponi.blogspot.com/links
3. Include details of the issue:
   - A clear description of the vulnerability.
   - Steps to reproduce or proof-of-concept.
   - Potential impact on local file confidentiality or execution integrity.

I will review and acknowledge valid reports promptly. Patches will be released with credit attributed in the release notes (unless anonymity is requested).
