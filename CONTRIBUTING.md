# Contributing to hoardDB

Pull requests are welcome in every hoardDB repository. The server repository's
`CONTRIBUTING.md` has the full rules (error messages that name the fix, a failing test
first for every bug fix, no swallowed errors, allowed dependency licences); the same rules
apply to the client libraries and the codec.

- For anything larger than a fix, open an issue or a Discussion first.
- Run the repository's checks before you push (`make lint`, or the repository's own test
  command if it has no Makefile).
- **Sign off every commit** with `git commit -s`. That certifies you wrote the change or
  have the right to submit it under the repository's licence (the Developer Certificate of
  Origin 1.1, at developercertificate.org). There is no other agreement to sign.
- A bug fix names the test that fails without it.
- Security problems never go in an issue or a pull request: see `SECURITY.md`.
