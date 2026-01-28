# BuildNinja Quickstart

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Ready-to-use BuildNinja YAML configurations for real, public open-source projects.

Clone this repo, point BuildNinja's Config File runner at any project, and run a build in minutes.

## Quick Start

1. Clone this repository
2. In BuildNinja, create a new Build Configuration
3. Add VCS Settings → Point to this repository
4. Add Execution Step → Select **Config File** runner
5. Enter path to any project's `buildninja.yaml` (e.g., `nodejs-sample/buildninja.yaml`)
6. Authorize your agent if not already done
7. Click **Run Build**

> **Note:** When using the Config File runner, VCS settings must be configured manually in BuildNinja's UI. The `vcs-steps` section in YAML files is for documentation purposes only and will be ignored during build execution.

## Projects

| Folder | Stack | Source Repository | Stars | Description |
|--------|-------|-------------------|-------|-------------|
| [apache-ant](./apache-ant) | Java/Ant | [piona/ant-sample](https://github.com/piona/ant-sample) | - | Sample Ant-based Java project (155 forks) |
| [aspnet-core](./aspnet-core) | .NET | [abheekm/ASP_NET_Core_App](https://github.com/abheekm/ASP_NET_Core_App) | - | ASP.NET Core web application |
| [monorepo-pnpm](./monorepo-pnpm) | pnpm | [AmruthPillai/Reactive-Resume](https://github.com/AmruthPillai/Reactive-Resume) | 25K+ | Privacy-focused resume builder (970K users) |
| [mstest-runner](./mstest-runner) | .NET/MSBuild | [abheekm/MSTest_Runner_App](https://github.com/abheekm/MSTest_Runner_App) | - | MSBuild runner example |
| [nodejs-sample](./nodejs-sample) | Node.js | [abheekm/node-js-sample](https://github.com/abheekm/node-js-sample) | - | Basic Node.js npm build |
| [python-vite](./python-vite) | Python/Vite | [open-webui/open-webui](https://github.com/open-webui/open-webui) | 75K+ | Self-hosted AI interface (Ollama/OpenAI) |
| [ruby-rspec](./ruby-rspec) | Ruby | [abheekm/Ruby_App](https://github.com/abheekm/Ruby_App) | - | Ruby app with RSpec tests |
| [rust-cargo](./rust-cargo) | Rust | [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | 59K+ | Blazingly fast grep replacement |
| [vite-lexical](./vite-lexical) | TypeScript | [facebook/lexical](https://github.com/facebook/lexical) | 22K+ | Meta's extensible text editor framework |
| [vstest-runner](./vstest-runner) | .NET/VSTest | [abheekm/VSTest_Runner_App](https://github.com/abheekm/VSTest_Runner_App) | - | VSTest runner example |

## Agent Requirements by Project

| Project | Requirements |
|---------|--------------|
| apache-ant | Java JDK 8+, Apache Ant |
| aspnet-core | .NET SDK 6.0+ |
| monorepo-pnpm | Node.js 18+, pnpm |
| mstest-runner | .NET SDK 8.0, MSBuild (Windows) |
| nodejs-sample | Node.js 18+ |
| python-vite | Node.js 18+ |
| ruby-rspec | Ruby 3.0+, Bundler |
| rust-cargo | Rust 1.85+ |
| vite-lexical | Node.js 18+ |
| vstest-runner | .NET SDK 8.0 (Windows) |

## BuildNinja Runners Demonstrated

This quickstart demonstrates all BuildNinja runners:

| Runner | Key | Examples |
|--------|-----|----------|
| Command Line | `runner_cmd` | All projects |
| MSBuild | `runner_msbuild` | mstest-runner |
| VSTest | `runner_vstest` | vstest-runner |

## Recommended Starting Points

| If you want to... | Start with |
|-------------------|------------|
| Test basic setup | `nodejs-sample` |
| Test .NET builds | `aspnet-core` |
| Test MSBuild runner | `mstest-runner` |
| Test VSTest runner | `vstest-runner` |
| Build a popular project | `rust-cargo` or `vite-lexical` |
| Build a complex monorepo | `monorepo-pnpm` |

## Links

- [BuildNinja Website](https://buildninja.grapehub.io)
- [BuildNinja Documentation](https://buildninja.grapehub.io/docs)
- [YAML Configuration Reference](https://buildninja.grapehub.io/docs)
- [Docker Hub - Server](https://hub.docker.com/r/grapehub/buildninja-server)
- [Docker Hub - Agent](https://hub.docker.com/r/grapehub/buildninja-agent)

## License

MIT - Configurations in this repository are MIT licensed. Source projects have their own licenses.

## Support

- Website: [buildninja.grapehub.io](https://buildninja.grapehub.io)
- Documentation: [buildninja.grapehub.io/docs](https://buildninja.grapehub.io/docs)
- Issues: [GitHub Issues](https://github.com/BuildNinja-CICD/buildninja-quickstart/issues)
- Contact: hello@grapehub.io
