<p align="center">
  <img src="assets/logo.svg" alt="CommandLyne" width="120" />
</p>

<h1 align="center">CommandLyne</h1>
<h3 align="center">Every model. Every agent. One governed command layer.</h3>

<p align="center">
  <a href="https://app.commandlyne.ai">Sign in</a> &bull;
  <a href="https://github.com/commandlyne/terraform-selfhost">Self-host on GCP</a>
</p>

---

CommandLyne is an AI assistant platform for teams on Google Workspace. Every person in your organization gets their own AI agent, and admins manage all of them from one control panel: which models they can use, which tools they can reach, and what they can spend.

## What your agents can do

- **Work across Google Workspace.** Read and draft email in Gmail, schedule in Calendar, set up Meet calls and use their transcripts, find people in Contacts, and reply in Google Chat.
- **Use your other tools.** Connect services from a catalog of connectors, or add your own MCP servers with OAuth sign-in.
- **Run work on their own.** Scheduled tasks, webhook triggers, and multi-step workflows that run without a person in the chat.
- **Share work in projects.** Shared projects with their own context, files, and daily notes.
- **Browse and operate.** Automate web pages, and run Google Cloud and Workspace admin tasks with credentials your organization controls.

## Built for organizations

- **One model catalog for the whole org.** Admins choose the allowed models and providers. Agents route each request to a suitable model, and fall back to another provider when one fails.
- **Cost under control.** Weekly spend limits for the org and for each team, and cost reporting you can export.
- **Org-managed configuration.** Provider credentials, skills, and connectors are set once in the control panel and pushed to every agent.
- **Isolation by default.** Each agent runs on its own virtual machine, and its secrets are stored in an encrypted vault on that machine.
- **Your cloud, if you prefer.** Run the agent machines in your own Google Cloud project with our [Terraform module](https://github.com/commandlyne/terraform-selfhost). The platform reaches them over Private Service Connect through one service-account grant that you can revoke at any time.

## Get started

Sign in at **[app.commandlyne.ai](https://app.commandlyne.ai)** with your organization's Google Workspace account.

---

<p align="center">
  Built by <a href="https://codimite.com">Codimite</a> &bull; &copy; 2026 CommandLyne
</p>
