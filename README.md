# .github

Default community health files for [Hakula Lab](https://github.com/hakulab) repositories. GitHub falls back to each file here in any repository that lacks its own copy:

- [Pull request template](.github/pull_request_template.md)
- [Bug report and feature request forms](.github/ISSUE_TEMPLATE), with blank issues offered to maintainers only
- [Security policy](SECURITY.md)

A repository overrides a file by adding its own. A valid issue template or template `config.yml` in its own `.github/ISSUE_TEMPLATE/` replaces the whole default folder, including the chooser configuration. The forms apply the `bug` and `enhancement` labels, which must exist in the repository.
