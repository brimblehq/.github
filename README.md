# Brimble `.github`

Special organization repository for [@brimblehq](https://github.com/brimblehq).

This repo does two things:

1. **Organization profile** — [`profile/README.md`](profile/README.md) is rendered at
   [github.com/brimblehq](https://github.com/brimblehq).
2. **Organization-wide defaults** — files in this repo act as defaults for every
   repository in the org that doesn't define its own:
   - `CODE_OF_CONDUCT.md`
   - `CONTRIBUTING.md`
   - `SECURITY.md`
   - `SUPPORT.md`
   - `.github/ISSUE_TEMPLATE/*`
   - `.github/pull_request_template.md`

Per [GitHub docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file),
these defaults apply automatically. If a repository defines its own file, that
file wins.

## Structure

```text
.
├── profile/README.md                  # org profile page
├── CODE_OF_CONDUCT.md                 # default code of conduct
├── CONTRIBUTING.md                    # default contributing guide
├── SECURITY.md                        # default security policy
├── SUPPORT.md                         # where to get help
├── LICENSE                            # Apache-2.0
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.yml
    │   ├── feature_request.yml
    │   └── config.yml
    └── pull_request_template.md
```

## Contributing

This repo is for org-level defaults and the public profile only. Found a broken
link or outdated info? Open a PR. For product help, see [SUPPORT.md](SUPPORT.md).
