<p align="center">
  <img src="https://raw.githubusercontent.com/Mimi-agent-os/.github/main/profile/mimi-logo.png" alt="mimi-os" width="112">
</p>

<h1 align="center">mimi-os</h1>

<p align="center">Your own AI agents, on your own machines.</p>

<p align="center">
  <a href="https://mimi-agent-os.github.io/">Site</a> ·
  <a href="https://mimi-agent-os.github.io/wiki/">Wiki</a> ·
  <a href="https://mimi-agent-os.github.io/wiki/#/launch">Get started</a>
</p>

A gateway on a machine you own holds the models and runs the chats. Each agent is a folder of TypeScript you write
with the SDK. The app, on a macOS desktop, a Windows desktop or an Android phone, talks to them over an end-to-end
encrypted channel, and any tool an agent marks as a write waits for your Allow.

## Repos

| Repo | What |
| --- | --- |
| [launch](https://github.com/Mimi-agent-os/launch) | `mimi-launch`, which sets up a workspace for a server or an agent developer |
| [protocol](https://github.com/Mimi-agent-os/protocol) | the wire vocabulary and the secure channel core |
| [sdk](https://github.com/Mimi-agent-os/sdk) | `@mimi-os/sdk`, the agent runtime |
| [plugins](https://github.com/Mimi-agent-os/plugins) | `@mimi-os/plugins`, memory, wiki and cron packs for agents |
| [gateway](https://github.com/Mimi-agent-os/gateway) | the always-on daemon and the `mimi` CLI |
| [devkit](https://github.com/Mimi-agent-os/devkit) | `mimi-dev`, which tests an agent against a real gateway while you write it |
| [app](https://github.com/Mimi-agent-os/app) | the client: desktop on macOS and Windows, and Android |
| [Mimi-agent-os.github.io](https://github.com/Mimi-agent-os/Mimi-agent-os.github.io) | the site and the wiki |

## Built with

| | |
| --- | --- |
| Gateway and agents | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js 24](https://img.shields.io/badge/Node.js_24-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-30363D?style=flat-square) |
| App | ![Tauri 2](https://img.shields.io/badge/Tauri_2-24C8D8?style=flat-square&logo=tauri&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Android](https://img.shields.io/badge/Android-34A853?style=flat-square&logo=android&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| Channel | ![Noise IK](https://img.shields.io/badge/Noise_IK-30363D?style=flat-square) ![ML-KEM-768](https://img.shields.io/badge/ML--KEM--768-30363D?style=flat-square) ![noble](https://img.shields.io/badge/@noble_cryptography-30363D?style=flat-square) |
| Models | ![vLLM](https://img.shields.io/badge/vLLM-30363D?style=flat-square) ![llama.cpp](https://img.shields.io/badge/llama.cpp-30363D?style=flat-square) ![OpenRouter](https://img.shields.io/badge/OpenRouter-30363D?style=flat-square) |
| Push | ![Firebase Cloud Messaging](https://img.shields.io/badge/FCM-DD2C00?style=flat-square&logo=firebase&logoColor=white) |

## Start

One command sets up the gateway's machine, and one link pairs the app with it. Requires git, Node.js 24 or
newer and pnpm. The wiki's [launch](https://mimi-agent-os.github.io/wiki/#/launch) page has the steps for a
server and for an agent developer, and the [SDK](https://mimi-agent-os.github.io/wiki/#/sdk) page shows how to
write an agent.

## Contributing

Bugs and ideas go in the affected repo's issues, through its forms. A pull request comes after the change
is agreed in an issue: see [CONTRIBUTING.md](https://github.com/Mimi-agent-os/.github/blob/main/CONTRIBUTING.md).

## License and security

The repos above are licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0).
To report a vulnerability privately, follow [SECURITY.md](https://github.com/Mimi-agent-os/.github/blob/main/SECURITY.md).
