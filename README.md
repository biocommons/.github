# biocommons .github repo

This repo contains biocommons-wide configuration and templates.

The contents of this repo are used in various ways by GitHub. Here's a summary:

- `.github/ISSUE_TEMPLATE` are used by all organization repos directly.  Changes to these templates will be available to other organizations repos. NOTE: If repos have their own `.github/ISSUE_TEMPLATE` directory, these templates will not be available (so don't do that).

- `.github/workflows/` contains GitHub Actions with configuration that is used by biocommons repos.

- `docs/` contains templates for `CODE_OF_CONDUCT.md`, etc.

- `etc/` contains global configuration, such as labels. (This is a Reece-ism.)

- `profile/README.md` is our organizational README at https://github.com/biocommons/

- workflow-templates are *templates* available for manual selective incorporation into other repos.

---

    snafu$ tree */ .github/
    actions/
    └── stale.yml
    docs/
    ├── CODE_OF_CONDUCT.md
    ├── CONTRIBUTING.md
    ├── GOVERNANCE.md
    └── SUPPORT.md
    etc/
    └── labels.yml
    profile/
    └── README.md
    .github/
    ├── CODEOWNERS
    ├── ISSUE_TEMPLATE
    │   ├── bug-report.md
    │   ├── feature-request.md
    │   └── project-proposal.md
    ├── labels.yml
    └── workflows
        ├── labels.yml
        ├── python-package.yml
        └── stale.yml
