# Security

## What counts

A vulnerability in any public mimi-os repo, in particular in:

- the gateway: pairing, admitting agents and devices, tool approvals, provider keys and its files
- the secure channel: the Noise IK handshake, the ML-KEM-768 key exchange and the frames in `protocol`
- the app: its device key and pairing, and how it isolates agent mini-apps
- the SDK: what an agent exposes, including the `gatewayOnly()` and `fromGateway()` guards
- `mimi-launch`: what it clones, runs and writes on a machine

By design, an agent on the gateway's machine runs as your OS user and can read the gateway's files.
Run agents you did not write on another machine or as another user, as the
[launch README](https://github.com/Mimi-agent-os/launch#readme) describes.

Report against the current `main` of the repo.

## How to report

Use GitHub's private vulnerability reporting: open the affected repo, go to its **Security** tab and
choose **Report a vulnerability**. When unsure which repo it is, pick the closest one.

Keep vulnerability reports in this private channel, out of public issues, discussions and pull requests.

## What to include

- the repo and the commit or version
- your platform: OS, Node.js version, and the app's platform if it is involved
- the steps to reproduce it, or a proof of concept
- what an attacker gains, and from where: the network, a paired device, an agent, a mini-app
- a fix, if you have one in mind

## How reports are handled

Reports are handled privately.
