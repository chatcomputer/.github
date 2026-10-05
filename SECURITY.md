# Security policy

Chat Computer runs an AI agent inside a macOS virtual machine on your Mac and stores API keys and the virtual
Mac's password on your Mac. We take problems in that boundary seriously.

## Reporting

Please report security problems privately through
[GitHub's private vulnerability reporting](https://github.com/chatcomputer/chatcomputer/security/advisories/new),
not in a public issue. Include the version (Chat Computer › About), what an attacker could do, and how to
reproduce it. We aim to acknowledge reports within a few days.

Examples of what we want to hear about:

- the agent or the virtual Mac reaching files, apps or secrets on the host beyond what was shared;
- API keys or the virtual Mac's password leaving the Mac, or appearing in logs or diagnostics;
- the agent acting without the input control the host grants, or completing an irreversible action without
  asking;
- text on screen or in files steering the agent in ways the safety rules should prevent.

## Supported versions

Only the latest release receives fixes.
