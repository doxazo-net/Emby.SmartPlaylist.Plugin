# Security Policy

## Supported Versions

| Version | Supported |
| ------- | --------- |
| latest  | Yes       |

This repository is a **fork**. Security issues in the plugin itself should be reported to the upstream project at [ShanePe/Emby.SmartPlaylist.Plugin](https://github.com/ShanePe/Emby.SmartPlaylist.Plugin).

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Use [GitHub Security Advisories](https://github.com/sydlexius/Emby.SmartPlaylist.Plugin/security/advisories/new)
to report vulnerabilities privately. This ensures the issue can be triaged and a
fix prepared before public disclosure.

When reporting, please include:

- A description of the vulnerability and its potential impact
- Steps to reproduce or a proof-of-concept
- The affected version(s) or commit(s)
- A suggested fix, if you have one

You should receive an initial acknowledgment within 72 hours. Critical issues
will be addressed as quickly as practical.

## Scope

In scope:

- Changes made in this fork that do not exist upstream
- The workflows in `.github/workflows/`

Out of scope:

- Vulnerabilities present in upstream (report those to the upstream project)
- Vulnerabilities in Emby itself (report those to Emby)

## Security Measures

- **Pinned actions:** all GitHub Actions are pinned to a commit SHA
- **Secret scanning** with push protection is enabled
- **Dependabot:** NuGet and GitHub Actions dependencies are tracked
