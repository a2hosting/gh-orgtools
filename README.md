# gh-orgtools

gh-extension for working with your GitHub org.

## Installation

First, install `gh` from <https://github.com/cli/cli/releases/latest> (`brew
install gh` on a Mac using Homebrew).

Install gh-orgtools via `gh extension install`:

```sh
gh extension install a2hosting/gh-orgtools
```

## Usage

- `gh orgtools help`             - prints documentation gh-orgtools and its commands
- `gh orgtools repo-list`        - list an organizations repositories
- `gh orgtools team-add-to-repo` - grant an organization team access to the given repository
- `gh orgtools team-get-id`      - get GitHub ID for the given team
- `gh orgtools team-list`        - list the organization's teams
- `gh orgtools user-get`         - get information about the given user
- `gh orgtools user-invite`      - invite users to join the organization
- `gh orgtools user-list`        - list users in the organization
- `gh orgtools user-remove`      - remove users from the organization

See `gh orgtools help` for full documentation.

## Bug Reports

Issues can be reported on GitHub:

<https://github.com/a2hosting/gh-orgtools/issues>

## License

MIT License - see [`LICENSE`](./LICENSE) in this repo.
