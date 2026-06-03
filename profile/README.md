<div align="center">
  <img src="./mira_logo2.png" alt="MIRA" width="600">
  <br>
</div>

**MIRA** is an open-source AI agent tooling for long-running research work.

MIRA helps you go from **idea -> experiments -> report** in one workflow. It is built for project-based research, not one-off chat, so every run leaves behind traceable artifacts such as workspace files, experiment outputs, and `task_plan.json`.

## Start Here

If you are new to MIRA, start with the **desktop bundle**.

1. Download the latest **MIRA Desktop Bundle** from [`mira-ui` releases](https://github.com/MIRA-Intelligence/mira-ui/releases/latest).
2. Open the app and keep **Local** mode selected.
3. In **Settings -> Local Engine**, fill in your provider, model, and API key.
4. Create your first project and let MIRA plan work, run experiments, and export results.

For most users, this is the fastest way to get started.

## Download

- **Recommended for most users:** [MIRA Desktop downloads](https://github.com/MIRA-Intelligence/mira-ui/releases/latest)
- **Docs and product overview:** [mira-intelligence.github.io](https://mira-intelligence.github.io/)
- **CLI / engine binaries and Python package:** [`mira` releases](https://github.com/MIRA-Intelligence/mira/releases/latest)

### Which package should I choose?

- Choose **`MIRA-bundle-*`** if you want the easiest local setup. It includes the desktop app plus a bundled local engine.
- Choose **`MIRA-standalone-*`** if you already run `mira` separately or want the UI to connect to a remote deployment.
- Choose **`mira-engine-*`** or the Python package from [`mira` releases](https://github.com/MIRA-Intelligence/mira/releases/latest) if you only need the engine / CLI side.

## Why MIRA

- **Built for long-running research tasks**: organize work around workspace, project, experiment, and task plan instead of a single chat thread.
- **20+ built-in model providers**: works with OpenAI, Anthropic, OpenRouter, DeepSeek, Ollama, Azure, vLLM, and more.
- **CLI / Web / Desktop**: use the same system in the terminal, browser, or packaged desktop app.
- **13 channel integrations**: connect MIRA to tools like Feishu, Slack, Telegram, email, Matrix, and others.
- **Guardrail auto-repair**: MIRA can repair incomplete experiment outputs before handing work back to you.
- **Local-first and self-hostable**: data stays under your control and can run on one machine or in your own deployment.

## Typical Ways To Use It

### 1. Personal desktop workflow

Use the **desktop bundle** on macOS or Windows, configure your model provider, and start projects locally.

### 2. Team or server workflow

Install `mira` on a remote machine, then connect to it from **MiraUI standalone** or the web UI.

## Learn More

- [Concepts](https://mira-intelligence.github.io/docs/concepts)
- [Provider and runtime configuration](https://mira-intelligence.github.io/docs/usage/agent-config/providers-and-runtime)
- [Channel integrations](https://mira-intelligence.github.io/docs/usage/agent-config/channels)
- [Desktop UI guide](https://mira-intelligence.github.io/docs/usage/ui)
- [Deployment options](https://mira-intelligence.github.io/docs/deployment)

## Quick Note For New Users

If you only want to try MIRA as quickly as possible, **download the latest `MIRA-bundle-*` package and start there**.

If you need remote deployment, team setup, or server-side control, install `mira` separately and connect the UI to that deployment.
