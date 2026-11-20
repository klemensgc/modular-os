# Security policy

## Reporting a vulnerability

Please report security issues privately through GitHub: open the **Security** tab of this repository and choose
**Report a vulnerability** (a private security advisory). Don't open a public issue for a security problem.

Describe the problem, how to reproduce it, and which version you used (the **Version** line in the menu bar
icon menu, or the top of **Settings…**). We will reply in the advisory.

## Scope

Things we especially want to hear about:

- the agents service accepting requests from anything other than the local app and your own terminal sessions
  (it listens on `127.0.0.1` only),
- the hooks or the installer running commands you did not approve,
- a request from another person or another Mac acting without your approval,
- secrets, tokens or file contents ending up in logs or reports.

## Supported versions

Only the latest beta gets fixes.

Never attach session files, prompts or keys to a report.
