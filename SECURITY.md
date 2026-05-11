# Security Policy

## Audit Status

This project has not been externally audited. There are currently no plans for
an external audit.

The keeper and executor contracts can interact with live blockchain networks and
move real assets. Tests, simulations, fork tests, and code review reduce risk,
but they do not guarantee correctness, profitability, or safety. Operators
should treat this software as unaudited and use dedicated hot wallets funded
only with assets they are willing to lose.

## Reporting Security Issues

This project does not currently have a private vulnerability disclosure channel,
a security contact, a service-level agreement, or a bug bounty program.

To report a security issue, open a GitHub issue or pull request in this
repository. Public GitHub reports are visible to everyone, so do not include:

- private keys, API keys, seed phrases, keystore passwords, or other secrets
- wallet addresses or operational details that you need to keep private
- exploit transactions against live systems
- instructions that would put third-party funds at immediate risk

When possible, include a minimal reproduction, failing test, affected file or
contract, expected behavior, actual behavior, and any relevant dry-run or fork
test output.

## Operator Responsibility

Running this keeper is solely the operator's responsibility. Repository
maintainers, protocol contributors, tokenholders, and any related foundation do
not operate an operator's keeper, custody funds, provide financial advice, or
guarantee outcomes unless a separate written agreement says otherwise.

## Supported Versions

This repository does not currently maintain separate supported release lines.
Security fixes, if any, are expected to land on the default branch unless a
specific release process is later documented.
