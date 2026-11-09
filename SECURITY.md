# Security Policy

This policy applies to every repository under `SukritJaAIproject` that does not ship its own `SECURITY.md`.

## Reporting a vulnerability

Please do not report security problems in a public issue.

Use GitHub's private vulnerability reporting instead: open the **Security** tab of the affected repository and choose **Report a vulnerability** (the URL has the form `https://github.com/SukritJaAIproject/<repository>/security/advisories/new`). Reports in Thai or English are both fine.

Include:

- what you found and which repository, file or endpoint is affected,
- steps to reproduce or a proof of concept,
- the version, release tag or commit you tested.

You should receive a first reply within one week. Once a fix is ready it is published in the next release of the affected project and the advisory is credited to you unless you prefer otherwise.

## Scope

Projects that handle live infrastructure deserve particular care: the OCPP central system (`bpc-csms-cloud`), the EV-charger fault-detection tooling, and the local LLM workbench with its MCP tool gateway. Issues such as authentication bypass, command injection through OCPP or MCP messages, credential leakage, or unsafe default configuration are all in scope.

## Supported versions

Fixes go into the latest release of each project. Older installers and tagged snapshots are not patched.
