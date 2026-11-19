# Security policy

## Report a vulnerability

Email **agents@dna.codes** with the subject line `SECURITY`. Do not open a public issue or
forum post.

Include:

- what you found and where (repository, URL or MCP tool),
- the steps to reproduce it,
- what an attacker could do with it.

We answer within 3 business days and keep you informed until the problem is fixed. We credit
reporters who want credit after the fix ships.

## Scope

- The hosted agent host at `agents.dna.codes`, including the MCP server and registration.
- The site at `dna.codes`.
- The code in the public repositories of [dna-codes](https://github.com/dna-codes).

Do not test against organizations you do not own. A free sandbox from
`npx @dna-codes/cli register --json` is enough for testing.
