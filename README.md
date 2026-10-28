# AB InBev Brand Guidance Skill

A Codex skill for applying AB InBev's corporate visual identity to presentations and interfaces. It includes brand guidance, the reference PDF, and selected official assets.

## Quick start

### Install from Codex

1. Open Codex and start a chat.
2. Enter:

   ```text
   $skill-installer Install the abi-brand-guidance skill from calice-joao/abi-brand-guidance.
   ```

3. If prompted, authorize access to the GitHub repository. If it is private, the environment running Codex needs GitHub credentials with read access.
4. Start a new chat. If the skill is not listed, restart Codex.

### Install from a terminal

Install Node.js 22.20 or later, then run:

```bash
npx skills add calice-joao/abi-brand-guidance --skill abi-brand-guidance --agent codex --global
```

This installs the skill for your Codex user account. The `skills` command is provided by the Skills CLI and runs through `npx`; you do not need to install it separately.

If the repository is private, your GitHub account must have read access. Configure Git credentials, GitHub CLI authentication, or SSH before running the command.

## Use the skill

In Codex, ask naturally or invoke it directly with `$abi-brand-guidance`:

- `$abi-brand-guidance Create a corporate presentation about ...`
- `$abi-brand-guidance Design an interface for ...`
- `$abi-brand-guidance Review this presentation for AB InBev brand consistency.`

Creation is the default. Ask explicitly when you want an existing presentation or interface reviewed. The skill covers AB InBev's corporate identity, not product-brand guidance.

## Update or remove

If you installed with the Skills CLI, update with:

```bash
npx skills update abi-brand-guidance
```

To remove a CLI installation:

```bash
npx skills remove abi-brand-guidance --global
```

To update a Codex `$skill-installer` installation, remove or move the existing folder at `$CODEX_HOME/skills/abi-brand-guidance`, then run the installation prompt again.

## Brand source

The included guideline is version 1.1, last updated January 2022. Check the [ABI Creative Hub](https://brandworld.ab-inbev.com/) and the current internal resource kit for newer guidance before using the skill for new work.
