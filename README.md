> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/startup-idea-validator)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/startup-idea-validator/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🦈 startup-idea-validator

**Stress-test a startup idea with a VC, customer and competitor panel, cheap experiments and a verdict. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/startup-idea-validator)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/startup-idea-validator?style=social)](https://github.com/milad-ahmd/startup-idea-validator)
![Category](https://img.shields.io/badge/category-Founders-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/startup-idea-validator/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- startup-idea-validator
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/startup-idea-validator /tmp/startup-idea-validator
mkdir -p ~/.claude/skills && cp -r /tmp/startup-idea-validator/skills/startup-idea-validator ~/.claude/skills/
```

**Per project:** copy `skills/startup-idea-validator` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/startup-idea-validator/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Validate my startup idea: ...
What could kill this idea?
```

The full workflow, rules and output format are in [`SKILL.md`](skills/startup-idea-validator/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
