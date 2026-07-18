<!-- TEMPLATE:START -->
> ### 📄 This is a repository template
>
> It ships GitHub community health files, CI, and release automation so a new
> public project starts with good defaults. To adapt it to your project, run the
> initializer once — it replaces the `{{PLACEHOLDER}}` tokens throughout the repo
> and removes this banner:
>
> ```powershell
> pwsh ./scripts/init-template.ps1
> ```
>
> See [CHECKLIST.md](CHECKLIST.md) for the full adoption steps (including the
> one-time GitHub settings a maintainer must apply). Delete this block manually
> if you prefer not to run the script.
<!-- TEMPLATE:END -->

<a id="readme-top"></a>

<div align="center">

English | [日本語](./README_ja.md)

<!-- TODO: add your logo and uncomment
<img src="assets/logo.png" alt="{{PROJECT_NAME}} logo" width="120" height="120">
-->

<h1>{{PROJECT_NAME}}</h1>

<p><em>{{DESCRIPTION}}</em></p>

[![CI](https://github.com/{{OWNER}}/{{REPO_NAME}}/actions/workflows/ci.yml/badge.svg)](https://github.com/{{OWNER}}/{{REPO_NAME}}/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/{{OWNER}}/{{REPO_NAME}}?include_prereleases&sort=semver)](https://github.com/{{OWNER}}/{{REPO_NAME}}/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/{{OWNER}}/{{REPO_NAME}}/badge)](https://securityscorecards.dev/viewer/?uri=github.com/{{OWNER}}/{{REPO_NAME}})

<p>
  <a href="docs/development.md"><strong>Explore the docs »</strong></a>
  <br /><br />
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/issues/new?template=bug_report.yml">Report Bug</a>
  ·
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/issues/new?template=feature_request.yml">Request Feature</a>
  ·
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/discussions">Discussions</a>
</p>

</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About The Project</a></li>
    <li><a href="#features">Features</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#development">Development</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#project-docs">Project Docs</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<a id="about"></a>

## About The Project

<!-- TODO: add a screenshot and uncomment
<img src="assets/screenshot.png" alt="{{PROJECT_NAME}} screenshot">
-->

{{DESCRIPTION}}

<!-- TODO: A short paragraph on what the project does, who it's for, and why it exists. -->

### Built With

<!-- TODO: List the major frameworks / languages / tools this project is built with. -->

- Tool one
- Tool two

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="features"></a>

## Features

<!-- TODO: Describe what your project does. -->

- Feature one
- Feature two
- Feature three

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="getting-started"></a>

## Getting Started

<!-- TODO: How to get a local copy up and running. -->

<a id="prerequisites"></a>

### Prerequisites

<!-- TODO: List anything users need installed first. -->

<a id="installation"></a>

### Installation

```sh
git clone https://github.com/{{OWNER}}/{{REPO_NAME}}.git
cd {{REPO_NAME}}
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="usage"></a>

## Usage

<!-- TODO: Examples of how to use the project. Screenshots and code blocks help. -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="development"></a>

## Development

```sh
{{BUILD_COMMAND}}
{{TEST_COMMAND}}
```

Full development and build instructions: **[docs/development.md](docs/development.md)**
How to contribute: **[CONTRIBUTING.md](CONTRIBUTING.md)**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="roadmap"></a>

## Roadmap

See the [open issues](https://github.com/{{OWNER}}/{{REPO_NAME}}/issues) and
[ROADMAP.md](ROADMAP.md) for planned features and known issues.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="contributing"></a>

## Contributing

Contributions are welcome. Please read **[CONTRIBUTING.md](CONTRIBUTING.md)** for the
workflow (Conventional Commits, DCO sign-off, PR process) and our
[Code of Conduct](CODE_OF_CONDUCT.md).

Thanks to everyone who has contributed to {{PROJECT_NAME}}. This list is updated automatically from git history.

<!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/dreamingdog0529">
                    <img src="https://avatars.githubusercontent.com/u/301185108?v=4" width="100;" alt="dreamingdog0529"/>
                    <br />
                    <sub><b>dreamingdog0529</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="project-docs"></a>

## Project Docs

Repository automation and community files are adapted from
[container-registry/oss-project-template](https://github.com/container-registry/oss-project-template).

| Document | Purpose |
|----------|---------|
| [CONTRIBUTING.md](CONTRIBUTING.md) | Develop, test, PRs, DCO, CI/CD, releases |
| [SUPPORT.md](SUPPORT.md) | How to get help |
| [ROADMAP.md](ROADMAP.md) | Direction and how to propose work |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Community standards |
| [SECURITY.md](SECURITY.md) | Private vulnerability reporting |
| [CODEOWNERS](CODEOWNERS) | Default code review owners |
| [CHANGELOG.md](CHANGELOG.md) | Release history |
| [LICENSE](LICENSE) | MIT license text |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="license"></a>

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

MIT © {{YEAR}} {{AUTHOR}}

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="acknowledgments"></a>

## Acknowledgments

- [container-registry/oss-project-template](https://github.com/container-registry/oss-project-template) — automation and community files
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template) — README structure
- [awesome-readme](https://github.com/matiassingers/awesome-readme) — README inspiration
- [Shields.io](https://shields.io/) — badges

<p align="right">(<a href="#readme-top">back to top</a>)</p>
