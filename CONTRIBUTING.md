# Contributing to Lost Minions Games Projects

Thank you for helping build **Lost Minions Games**!

This file is shared across multiple repositories under the `LostMinionsGames`
umbrella: game projects, engine tools, modding helpers, and support libraries.
Each repo may have its own README or docs with project-specific details — always
read those first.

---

## 🧭 Where to Start

- **New feature or gameplay idea?**
  Open an issue in the target repo and describe:
  - What you want to add or change
  - Why it’s fun, useful, or improves the experience
  - Any references, prototypes, or design notes

- **Bug fix or technical improvement?**
  Check existing issues first. If nothing matches, open a new issue with:
  - Steps to reproduce
  - Expected vs actual behavior
  - Logs, stack traces, screenshots, or editor output

- **Docs or workflow updates?**
  You can usually open a PR directly. If your change affects builds,
  CI, or shipping behavior, please link or create an issue.

---

## 🧱 Types of Repositories

Lost Minions Games includes several kinds of repos, such as:

- **Game projects** – Unreal/Unity projects, prototypes, and shared game code
- **Engine tools & utilities** – editor extensions, commandlets, pipeline helpers
- **Shared libraries** – C#/C++/Python utilities used across multiple games
- **Build & automation** – scripts, GitHub Actions, and packaging workflows

For each repo:

- Check the **README** for engine version, build steps, and prerequisites.
- Look for a **`/docs`** folder or wiki for deeper technical notes.
- Follow any repo-specific contribution guidelines there.

---

## 📝 How to Contribute

1. **Fork or branch from `main`**
   - External contributors: fork the repo on GitHub.
   - Collaborators: create a feature branch from `main`.

2. **Create or link an issue**
   - Reference an existing issue if one already tracks your change.
   - Otherwise, open a new issue and outline:
     - What you’re changing
     - Why it’s needed
     - Any potential impact (builds, CI, tools, or other repos)

3. **Set up your environment**
   - Match the **engine version** and **tooling** listed in the README.
   - For Unreal/Unity projects, confirm you can build and run a clean clone
     before making large changes.

4. **Make focused, readable commits**
   - Group related changes together.
   - Use clear messages that explain *why* as well as *what*.
   - If the repo uses commit tags (e.g. `[skip ci]`, `[publish]`, `[publish-zip]`),
     follow any conventions noted in the README.

5. **Add tests or validation where appropriate**
   - For code libraries: add or update unit/integration tests if present.
   - For game logic: consider adding automated tests, debug commands, or
     editor-only helpers when possible.
   - For build/packaging scripts: add sanity checks or dry-run options when reasonable.

6. **Open a Pull Request**
   - Clearly describe the change and link the related issue.
   - Mention if your change affects:
     - CI / GitHub Actions
     - Build pipelines (editor builds, cook, packaging)
     - Shared libraries or engine plugins
     - Multiple repos or game projects

7. **Respond to review**
   - Keep feedback constructive and focused on the work.
   - It’s fine to push follow-up commits — just keep them tidy and readable.

---

## ⚖️ Code of Conduct

All contributions must follow the
[Lost Minions Code of Conduct](./CODE_OF_CONDUCT.md).

We expect respect, patience, and collaboration — whether you’re editing a tiny
utility function or changing core gameplay systems.

---

## 🔒 Security & Vulnerabilities

If you discover a security issue in a Lost Minions Games project:

- **Do not** open a public issue.
- Report privately via [GitHub Security Advisories](../../security/advisories) or email:
  **security@lostminions.org**

Please include:

- A clear description of the problem
- Steps or scripts to reproduce
- Any potential impact (players, services, builds, or tools)

We’ll coordinate fixes here and in any related repositories.

---

## 💡 Need Help?

If you’re unsure about:

- Which repo is the right place for your change
- How a build script, workflow, or tool is supposed to behave
- What impact your update might have on other games or libraries

Open a **“Question”** issue in the relevant repo with as much context as you can.

Lost Minions Games is meant to be a collaborative lab for experiments and games,
not a puzzle box — it’s always okay to ask before you dive in.
