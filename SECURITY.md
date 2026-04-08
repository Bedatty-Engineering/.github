<table><tr>
<td><img src="https://github.com/Bedatty-Engineering.png" alt="Bedatty Engineering" width="80" /></td>
<td><h1>Security policy</h1></td>
</tr></table>

This GitHub organization hosts **personal projects** I maintain and share publicly. Security still matters: if you find a vulnerability, please report it privately so it can be fixed without putting users at risk.

## Support expectations

These repositories are maintained **in my spare time**. I cannot guarantee corporate-style SLAs, but I will treat credible security reports seriously and respond when I can.

## Supported versions

Patches are provided **on a best-effort basis**, usually for the **default branch** and the **latest release** (if the repo uses releases). Older tags or forks may not be updated.

| Area              | Typical support   |
| ----------------- | ----------------- |
| Default branch    | Yes, best effort  |
| Latest release    | Yes, when applicable |
| Older versions    | No guarantee      |

## Reporting a vulnerability

**Do not** open a public issue, discussion, or pull request to report a security vulnerability.

Report suspected issues privately by email: **security@bedatty.com**

### What to include

When possible:

- a clear description of the issue and its impact;
- affected repository, component, or version;
- steps to reproduce or a proof of concept;
- any mitigation ideas you have.

### Safe harbor

I support **good-faith** research that:

- avoids privacy violations, data destruction, or unnecessary service disruption;
- stays within reasonable expectations for testing this code (no scraping unrelated systems, etc.);
- does not go further than needed to show impact.

I will not pursue legal action against researchers who follow this policy and coordinate with me. This does not apply to conduct that breaks the law.

## After you report

- **Acknowledgment:** I will try to confirm receipt within a **few days**; sometimes it may take longer.
- **Updates:** I will share meaningful progress when practical.
- **Disclosure:** I prefer **coordinated disclosure**. Please allow reasonable time for a fix before going public; we can align on timing.

## Scope

**Generally in scope:** security issues in code or documented configuration in repositories under this organization, when exploitation is realistic.

**Generally out of scope (examples):** social engineering, physical attacks, large-scale DoS, issues only in third-party services (unless caused by how my code uses them), or already known/public findings.

## For contributors

- Do not commit secrets, API keys, or private keys; use environment variables and local ignores as appropriate.
- Use least privilege for tokens and CI secrets.
- Keep dependencies reasonably up to date where the project allows it.

This policy applies to all repositories in this organization.

---

## Related

| Topic | Document |
|-------|----------|
| Help, issues, expectations | [`SUPPORT.md`](SUPPORT.md) |
| Security reports | [`SECURITY.md`](SECURITY.md) |
| This org’s default community files | [`README.md`](README.md) |

---

<p align="center">
  <a href="https://github.com/Bedatty-Engineering"><strong>Bedatty Engineering</strong></a> — personal projects and experiments<br />
  <sub>Thank you for stopping by.</sub>
</p>
