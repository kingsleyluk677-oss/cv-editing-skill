# Public Release Safety

## Scope

This repository contains only the `cv-editing` skill: Markdown guidance, one YAML interface file, and an anonymous layout-preview image. It contains no executable code, credentials, telemetry, network client, or candidate CV.

## Before publishing a release

- Review every tracked file; keep only documentation, skill resources, and the anonymous preview.
- Do not add real CVs, JDs, interview notes, screenshots, PDFs, DOCX files, candidate data, or contact details.
- Confirm that `.gitignore` is present and that no `.env`, key, certificate, or credential file is staged.
- Scan staged text for API keys, tokens, passwords, private keys, real email addresses, phone numbers, and personal identifiers.
- Inspect images and archive contents for embedded personal data before publishing.

## Reporting a concern

Do not post credentials or personal data in a public issue. Use GitHub’s private vulnerability-reporting channel when available, or contact the repository owner privately through a verified channel.
