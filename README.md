## Experimental Source Code

(adapted from
[go/source-code-guidelines#definitions](https://goto.corp.google.com/source-code-guidelines#definition)

Experimental source code is source code (and all its dependencies, including
binary dependencies) that is not currently used to build X applications,
systems, or services, and will never conceivably be used by them in the future.
This includes:

- Code used for educational or training purposes.
- Demo or prototype code that will never become part of an X application,
system, or service.
- Proof of concept code that will never become part of an X application,
system, or service.
- Code run only once by the code author themselves, that is not re-used or
used by another person.

## Getting Started

Since you created this repository using the
[experimental](https://github.com/theteamatx/experimental) template, these
have been set up for you as a starting point:

- this README.md
- SECURITY.md to keep [go/allstar](https://goto.corp.google.com/allstar) happy

Code scanning will occur automatically once code in a [supported language](https://docs.github.com/en/enterprise-cloud@latest/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql#about-codeql) is added to the repository.

Since we are relying on a third-party to keep your code safe, it's recommended
that you mirror this repository to [go/gob](https://goto.corp.google.com/gob) so
you have a backup in case of a GitHub disaster or security incident. See instructions for doing so [here](https://www.dev.x.company/github#setting-up-gob-mirror).

If you want to collaborate with other Xers on your experiments, consider setting
up a
[CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
file.

Happy experimenting!
