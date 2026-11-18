# Accounts and access

Maintainers request access for their teams. Any Owner can grant it under these rules.
Disputes and exceptions go to the council.

| Role                  | GitHub access                          |
|-----------------------|----------------------------------------|
| Council               | Organisation Owner                     |
| Maintainer            | Maintain permissions on their packages |
| Member                | Access granted by an Owner as needed   |
| External Collaborator | Access granted by an Owner as needed   |

Owner access doesn't confer ownership of packages or copyright.
An Owner can grant repository Admin access when a task needs it.
Anyone can contribute without joining the organisation.

Maintainers can vouch for Members or external collaborators. An Owner grants the agreed access to the relevant repositories.

## Keeping your account safe

Everyone with access **must**:

- Be the sole user of their GitHub account, enable 2FA, and follow the code of conduct.
- Store recovery codes safely and have a second way to sign in.
- Relinquish access they no longer need.
- Tell an Owner about lost keys or suspected account misuse, and take appropriate steps to actively mitigate.

Everyone **should** use passkeys or security keys, sign commits with GPG or SSH, and share a reachable contact.
A personal email address needn't be public.

Owners and repository Maintainers **must** sign commits and release tags.  
Owners and repository Maintainers **must** be contactable on the Julia Language Slack.  
Owners **must** use passkeys on their GitHub account. Using a physical security key is **strongly encouraged**. A software passkey is acceptable if a physical key is unavailable.

## Organisation settings

- Keep at least two Owners able to recover the organisation and release services independently.
- Enforce 2FA, including for outside collaborators. Give notice and setup help.
- Limit bot permissions and review credentials, apps, and access when responsibilities change.
- Assess trust through relevant conduct, not reputation or affiliation.

## Signing

We **strongly encourage** verified signatures on protected branches, including bot commits, and on release tags.  
Unsigned PRs are welcome: merge with a signed commit that preserves credit and the PR link.  
GitHub's verified signatures are accepted.  
Check release workflows before enforcing these rules, and record any bypass.  
Signatures establish provenance, not correctness. Review and tests are still required.
