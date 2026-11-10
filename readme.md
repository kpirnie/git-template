# {{PROJECT_NAME}}

A starting point for new repositories: issue and pull request templates, funding links, contributing and security policies, a container build workflow, and a disabled tag / release / Packagist job.

## Badges

<!-- Build -->
[![Build Main](https://img.shields.io/github/actions/workflow/status/{{OWNER}}/{{REPO}}/build.yml?branch=main&label=Main&logoColor=white&logo=github&labelColor=000&style=for-the-badge)](https://github.com/{{OWNER}}/{{REPO}}/actions/workflows/build.yml?query=branch%3Amain)
[![Build Develop](https://img.shields.io/github/actions/workflow/status/{{OWNER}}/{{REPO}}/build.yml?branch=develop&logoColor=white&label=Develop&logo=github&labelColor=000&style=for-the-badge)](https://github.com/{{OWNER}}/{{REPO}}/actions/workflows/build.yml?query=branch%3Adevelop)
<!-- Issues -->
[![GitHub Issues](https://img.shields.io/github/issues/{{OWNER}}/{{REPO}}?style=for-the-badge&logo=github&color=006400&logoColor=white&labelColor=000)](https://github.com/{{OWNER}}/{{REPO}}/issues)
<!-- Security -->
[![GitHub Security](https://img.shields.io/badge/Security-View-6495ED?link=https://github.com/{{OWNER}}/{{REPO}}/security&logoColor=white&style=for-the-badge&labelColor=000&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiPjxwYXRoIGQ9Ik0xMiAyTDQgNXY2LjA5YzAgNS4wNSAzLjQxIDkuNzYgOCAxMC45MSA0LjU5LTEuMTUgOC01Ljg2IDgtMTAuOTFWNWwtOC0zeiIvPjwvc3ZnPg==)](https://github.com/{{OWNER}}/{{REPO}}/security)
<!-- Last Commit -->
[![Last Commit](https://img.shields.io/github/last-commit/{{OWNER}}/{{REPO}}?style=for-the-badge&labelColor=000&logoColor=white&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIxLjgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PHJlY3QgeD0iMyIgeT0iNC41IiB3aWR0aD0iMTgiIGhlaWdodD0iMTYuNSIgcng9IjIiLz48bGluZSB4MT0iMyIgeTE9IjkuNSIgeDI9IjIxIiB5Mj0iOS41Ii8+PGxpbmUgeDE9IjgiIHkxPSIyLjUiIHgyPSI4IiB5Mj0iNi41Ii8+PGxpbmUgeDE9IjE2IiB5MT0iMi41IiB4Mj0iMTYiIHkyPSI2LjUiLz48L3N2Zz4=)](https://github.com/{{OWNER}}/{{REPO}}/commits/main)
<!-- License -->
[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=000)](LICENSE)
<!-- Links/Social -->
[![Discord](https://img.shields.io/badge/Discord-Join-blue?logo=discord&logoColor=white&style=for-the-badge&labelColor=000)](https://discord.gg/bd4Qan3PaN)
[![Kevin Pirnie](https://img.shields.io/badge/-KevinPirnie.com-000d2d?style=for-the-badge&labelColor=000&logoColor=white&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIxLjgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+CiAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz4KICA8ZWxsaXBzZSBjeD0iMTIiIGN5PSIxMiIgcng9IjQuNSIgcnk9IjEwIi8+CiAgPGxpbmUgeDE9IjIiIHkxPSIxMiIgeDI9IjIyIiB5Mj0iMTIiLz4KICA8bGluZSB4MT0iNC41IiB5MT0iNi41IiB4Mj0iMTkuNSIgeTI9IjYuNSIvPgogIDxsaW5lIHgxPSI0LjUiIHkxPSIxNy41IiB4Mj0iMTkuNSIgeTI9IjE3LjUiLz4KPC9zdmc+Cg==)](https://kevinpirnie.com/)

<!-- OPTIONAL BADGES: move the ones that apply above this comment, set the versions, and delete the rest
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-orange.svg?style=for-the-badge&logo=gnu&logoColor=white&labelColor=000)](LICENSE)
[![Alpine](https://img.shields.io/badge/Base-Alpine%20Linux-0D597F?logo=alpinelinux&logoColor=white&style=for-the-badge&labelColor=000)](https://www.alpinelinux.org/)
[![Debian](https://img.shields.io/badge/Base-Debian%20Trixie-A81D33?logo=debian&logoColor=white&style=for-the-badge&labelColor=000)](https://www.debian.org/)
[![Ubuntu](https://img.shields.io/badge/Base-Ubuntu%20Noble-E95420?logo=ubuntu&logoColor=white&style=for-the-badge&labelColor=000)](https://ubuntu.com/)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white&style=for-the-badge&labelColor=000)](https://python.org)
[![Go](https://img.shields.io/badge/Go-1.26.1-00ADD8?logo=go&logoColor=white&style=for-the-badge&labelColor=000)](https://go.dev/)
[![PHP](https://img.shields.io/badge/Min.-php8.4-777BB4?logo=php&logoColor=white&style=for-the-badge&labelColor=000)](https://php.net)
[![WordPress](https://img.shields.io/badge/Min.%20WP-6.0-3858e9?logo=wordpress&logoColor=white&style=for-the-badge&labelColor=000)](https://wordpress.org)
[![MySQL](https://img.shields.io/badge/Min.%20MySQL-8.0-4479a1?logo=mysql&logoColor=white&style=for-the-badge&labelColor=000)](https://www.mysql.com/)
[![MariaDB](https://img.shields.io/badge/Min.%20MariaDB-10.4-003545?logo=mariadb&logoColor=white&style=for-the-badge&labelColor=000)](https://mariadb.org/)
[![SQLite](https://img.shields.io/badge/Min.%20SQLite-3.8-003b57?logo=sqlite&logoColor=white&style=for-the-badge&labelColor=000)](https://www.sqlite.org/)
[![PostgreSQL](https://img.shields.io/badge/Min.%20Postgres-12-4169e1?logo=postgresql&logoColor=white&style=for-the-badge&labelColor=000)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Min.%20Redis-6.0-dc382d?logo=redis&logoColor=white&style=for-the-badge&labelColor=000)](https://redis.io/)
[![JSON](https://img.shields.io/badge/Min.%20JSON-1.0-000000?logo=json&logoColor=white&style=for-the-badge&labelColor=000)](https://www.json.org/)
[![Packagist](https://img.shields.io/packagist/v/{{PACKAGIST_PACKAGE}}?style=for-the-badge&logo=packagist&logoColor=white&color=F28D1A&labelColor=000&label=Packagist)](https://packagist.org/packages/{{PACKAGIST_PACKAGE}})
-->

## Using the template

1. Create the new repository from this one (**Use this template**), or copy the files across.
2. Search the repository for `{{` and replace every placeholder (see below).
3. Search for `TEMPLATE:` comments, act on them, and delete them.
4. Search `.github/workflows/build.yml` for `BUILD ACTION` and `RELEASE ACTION` and adjust to the project.
5. Replace this readme with the project's own.

## Placeholders

| Placeholder | Used in | Meaning |
| ----------- | ------- | ------- |
| `{{PROJECT_NAME}}` | `CONTRIBUTING.md`, `SECURITY.md`, issue templates | Human readable project name |
| `{{OWNER}}` / `{{REPO}}` | `CONTRIBUTING.md`, readme badges | GitHub owner and repository name |
| `{{BUILD_COMMAND}}` | `CONTRIBUTING.md`, PR template | Command that builds the project |
| `{{LINT_COMMAND}}` | `CONTRIBUTING.md`, PR template | Command that lints / statically checks the project |
| `{{REQUIREMENT_n}}` / `{{SETUP_AND_BUILD_COMMANDS}}` | `CONTRIBUTING.md` | Tooling and setup steps for contributors |
| `{{PATH_n}}` / `{{PURPOSE_n}}` | `CONTRIBUTING.md` | Project layout table rows |
| `{{IN_SCOPE}}` | `SECURITY.md` | What a vulnerability report may cover |
| `{{BINARY_NAME}}` / `{{GENERATED_ASSET}}` | `.gitignore` | Project specific ignores |
| `{{PACKAGIST_PACKAGE}}` | readme badges | Packagist package name, example `vendor/package` |
| `{{PHP_EXTENSIONS}}` | `build.yml` (release job) | PHP extensions to install before releasing |

## Workflow

- `develop` is the working branch, `main` is the stable branch.
- Pushes to `main` publish the `latest` image, pushes to `develop` publish `dev` (both to `ghcr.io`).
- Tagging, GitHub releases, and the Packagist update are in `build.yml`, commented out. It runs on a pushed `v*` tag and needs the `PACKAGIST_USERNAME` and `PACKAGIST_API_TOKEN` repository secrets. The setup steps are in the comment block above the `release` job.

## Files

| Path | Purpose |
| ---- | ------- |
| `.github/workflows/ci.yml` | CI checks on push and pull request, with commented PHP, Go, Node and Python blocks |
| `.github/workflows/build.yml` | Container build and push, plus the commented release job |
| `.github/ISSUE_TEMPLATE/` | Bug report and feature request forms |
| `.github/PULL_REQUEST_TEMPLATE.md` | Pull request checklist |
| `.github/FUNDING.yml` | Sponsor links |
| `.dockerignore` | Paths excluded from the image build context |
| `.gitignore` | Ignored files, with commented per-language blocks |
| `CONTRIBUTING.md` | Contributor guide |
| `SECURITY.md` | Vulnerability reporting policy |
| `LICENSE` | MIT |

## Stats

<p align="center">
  <a href="https://github-stats-extended.vercel.app/api?username=kpirnie&amp;hide_title=true&amp;show_icons=true&amp;include_all_commits=true&amp;card_width=400&amp;line_height=40">
    <picture>
      <source srcset="https://github-stats-extended.vercel.app/api?username=kpirnie&amp;hide_title=true&amp;show_icons=true&amp;include_all_commits=true&amp;card_width=400&amp;line_height=40&amp;theme=algolia" media="(prefers-color-scheme: dark)" />
      <img src="https://github-stats-extended.vercel.app/api?username=kpirnie&amp;hide_title=true&amp;show_icons=true&amp;include_all_commits=true&amp;card_width=400&amp;line_height=40&amp;theme=default" width="49%" alt="GitHub Stats" />
    </picture>
  </a>
  <a href="https://github-stats-extended.vercel.app/api/top-langs?username=kpirnie&amp;hide_title=true&amp;langs_count=5&amp;card_width=400">
    <picture>
      <source srcset="https://github-stats-extended.vercel.app/api/top-langs?username=kpirnie&amp;hide_title=true&amp;langs_count=5&amp;card_width=400&amp;theme=algolia" media="(prefers-color-scheme: dark)" />
      <img src="https://github-stats-extended.vercel.app/api/top-langs?username=kpirnie&amp;hide_title=true&amp;langs_count=5&amp;card_width=400&amp;theme=default" width="49%" alt="Top Languages" />
    </picture>
  </a>
</p>
