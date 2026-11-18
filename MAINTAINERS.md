# Maintaining a package

## Package basics

Every package needs:

- Contributor instructions, test commands, maintainer contacts, and release steps.
- Documentation with installation steps, a worked example, and an API reference.
- Issues enabled and appropriate issue templates set up.
- CI tests that must pass before merge.
- Clear licenses for code and prose.

Maintainers choose tools and workflows within these requirements, including shared or local issue templates.
Only exceptions to the shared requirements need agreement from the Steering Committee.
Say whether the package is experimental, maintained, seeking help, or archived.
For forks, explain the upstream relationship and any separate releases.

## Licenses

Use MIT or Apache-2.0 for new code and CC-BY-SA-4.0 for documentation prose.
Code examples use the code license. Make this distinction clear in license notices.
Keep required notices and check compatibility when using others' work.
Existing licenses survive a transfer. License changes need the relevant rights holders' agreement.
Agree exceptions with the Steering Committee.

## New maintainers and packages

For a new maintainer:

- Agree responsibilities with the existing maintainers for that package and update maintainer contacts.
- Meet the [account requirements](ACCOUNTS_AND_ACCESS.md#keeping-your-account-safe). The package team asks an Owner for your access.
- Walk through tests, reviews, documentation, and a release with an existing maintainer.

For an incoming package:

- Follow the [package transfer process](README.md#your-package-stays-yours).
- Confirm the package's license before the move. Agree on support expectations with the Steering Committee.
- Agree on a plan with the Steering Committee for any package requirements to complete after the move.
- Check URLs, registry entries, CI, documentation, access, and release automation after the move.

One maintainer is enough. Where possible, name a backup who can restore access or find help.  
If you need a break, share what handover you can and update contacts.  
You don't have to wait for a replacement.
