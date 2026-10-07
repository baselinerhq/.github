<p align="center">
  <a href="https://github.com/baselinerhq/baseliner">
    <img src="https://baselinerhq.github.io/social-preview.png" width="640"
      alt="baseliner — assessment-as-code for repository fleets: your policy, and what it can’t see">
  </a>
</p>

## Assessment-as-code for repository fleets

We build **[baseliner](https://github.com/baselinerhq/baseliner)**, a single
dependency-free binary that checks every repo in a fleet against a policy you
write. It scores what it can observe and reports what it can't. No server, no
GitHub App, no org admin: point it at a GitHub org (or local checkouts) and get a
0–1 score and a coverage figure per repo. Findings come as a console table,
JSON, SARIF or a findings issue in each repo.

Today it checks repository hygiene and governance. Next it reads what is
actually enforced: branch protection and rulesets together, and bypass actors.
Why: [Your branch protection is not where you think it is](https://cameronbrooks11.github.io/devops/2026/09/12/branch-protection-is-not-where-you-think/).

### Projects

- 📦 **[baseliner](https://github.com/baselinerhq/baseliner)** — the scanner (Go, single static binary)
- ⚙️ **[baseliner-action](https://github.com/baselinerhq/baseliner-action)** — drop it into a GitHub Actions workflow
- 📖 **[Documentation](https://baselinerhq.github.io)** — getting started, configuration, writing a custom policy

New here? Start with **[baseliner](https://github.com/baselinerhq/baseliner)** or the **[docs](https://baselinerhq.github.io)**.
