# biocommons .github repo

This repo contains biocommons-wide configuration and templates.

The contents of this repo are used in various ways by GitHub. Here's a summary:

- actions/ contains GitHub Actions with configuration that is used by biocommons repos.

- .github/ISSUE_TEMPLATE are used by all organization repos directly.  Changes to these templates will be available to other organizations repos. NOTE: If repos have their own .github/ISSUE_TEMPLATE directory, these templates will not be available (so don't do that).

- .github/workflows are *templates* available for manual selective incorporation into other repos.

- docs contains templates for CODE_OF_CONDUCT.md, etc. (N.B. GitHub says that docs/ is a viable option, but it appears that this is a secondary and less-effective optiion. These files should probably move to the root.)

- etc/ is a Reece-ism.  It is intended for global configuration, such as labels.

- profile/README.md is our organizational README at https://github.com/biocommons/

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
