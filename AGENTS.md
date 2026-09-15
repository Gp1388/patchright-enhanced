# Codex Integration

## Purpose
Use this repository as an optional browser-automation component when ordinary HTTP tooling or the project's existing browser stack cannot satisfy an authorized task.

## Codex rules
- Audit the fork's actual implementation and README before adopting it; do not assume behavior from the project name.
- Prefer the project's existing stable Playwright/browser implementation unless this fork provides a tested, necessary advantage.
- Use browser automation only for authorized workflows and respect authentication/access-control boundaries.
- Do not use the tool to bypass access controls, CAPTCHAs, paywalls, or other security protections.
- Never expose secrets, tokens, credentials, cookies, private keys, or personal data.
- Make integrations modular and reversible. Do not replace a stable browser path without tests and a rollback option.
- Do not deploy to production/VPS without explicit permission.
- Keep code, commands, paths, identifiers, and filenames in English.
- All progress updates, reports, explanations, and final results to the user must be in Persian (Farsi).

## Context efficiency
Inspect only relevant modules and load this component on demand. Avoid adding it to tasks that do not require browser automation.
