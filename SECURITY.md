# Security Policy

## Supported Versions

Security fixes are provided for the latest public release of MacDriveSnap.

## Reporting a Vulnerability

Please report security issues privately by emailing the maintainer or by using GitHub private vulnerability reporting if it is enabled for the repository.

Do not open a public issue for suspected vulnerabilities. Include:

- Affected MacDriveSnap version
- macOS version
- Steps to reproduce
- Any sample report files needed to reproduce the issue, with private paths or filenames removed

## Security Model

MacDriveSnap is designed to run locally. It does not upload scanned file data.

The app is sandboxed and only requests user-selected file access. Reports may include local file paths, file metadata, optional direct file links, and optional SHA-256 checksums, so treat generated reports as potentially sensitive.
