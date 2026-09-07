# Security policy

Agent Etna runs other people's agents in isolated sandboxes and opens pull
requests on their repositories. A security report is the most useful message
we can receive, and it is read by the people who build the product.

## Reporting a vulnerability

Email **contact@agentetna.com** with "security" in the subject line. Include
what you found, where it is (the hosted platform at agentetna.com and its
API, the GitHub Action, the GitHub App, the CLI), and the steps to reproduce
it. We aim to reply within two business days and to keep you informed until
the issue is resolved.

Please do not open a public issue for a security report, and do not test
against accounts, agents or repositories that are not your own.

## Scope

- agentetna.com and its API
- The Agent Etna GitHub App and the sign-in flow
- The GitHub Action, `AgentEtna/action`
- The Agent Etna CLI and MCP server

## What happens next

We acknowledge the report, reproduce it, fix it, and tell you when the fix is
live. Fixes are recorded in the changelog at agentetna.com/changelog.html,
with credit to the reporter if they want it.
