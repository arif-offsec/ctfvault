# Contributing to CTFVault

Thanks for helping keep this list accurate. CTF sites appear and die constantly — this only stays useful if people fix it.

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before participating.

## Ways to Contribute

- **Add a missing resource** — a free CTF platform, wargame, or vulnerable lab not already listed
- **Fix a dead link**
- **Flag a pricing change** — a platform listed as free that's gone freemium or paid (or vice versa)
- **Fix a mis-tagged difficulty** — if you've actually used a resource and think it's tagged wrong
- **Improve a description** — tighten wording, fix a typo, clarify scope

You don't need to ask permission for small fixes — just open a PR.

## Adding a New Resource

1. **Confirm it's genuinely free.** No subscription, no paid tier blocking the core challenges. A free sample of a paid platform doesn't qualify — see the [Freemium](README-freemium.md) section for where those go instead.
2. **Pick the right category** from the [Table of Contents](README-free.md#table-of-contents). If it doesn't fit cleanly, say so in your PR and we'll figure it out together.
3. **Pick a difficulty tier:**
   - 🟢 **Beginner** — no prior experience needed, or teaches the fundamentals as you go
   - 🟡 **Intermediate** — assumes basic familiarity with the category (e.g. you've used a debugger before, you know basic SQL)
   - 🔴 **Advanced** — assumes solid fundamentals; the challenge itself is the hard part, not learning the basics
4. **Format the entry** to match the file you're adding it to:
   - In `README-free.md` (100% free resources):
     ```markdown
     - **[Resource Name](https://example.com)** — One or two sentences: what it covers, what makes it worth listing.
     ```
   - In `README-freemium.md` (freemium / free-tier-only resources):
     ```markdown
     - **[Resource Name](https://example.com)** - One short clause on exactly what's free vs. paid.
     ```
5. **Keep descriptions factual and concise.** No marketing language — say what it actually covers.

## Fixing a Dead Link

> ⚠️ If a link isn't just dead but has been **hijacked or now serves something malicious** (malware, phishing, a credential-harvesting clone), don't open a public PR or issue — see [SECURITY.md](SECURITY.md) and report it privately instead, so it can be pulled before anyone else clicks it.

Open a PR removing or updating the link.

## Reporting a Pricing Change

If a platform listed as free now has a paywall (or a Freemium-listed platform expanded its free tier), open a PR moving it to the correct file — reformatting the entry to match that file's style (see "Format the entry" above) — or open an issue if you're not sure how to phrase the change.

## Commit Messages

Keep them short and specific:

```
Add pwnable.xyz to Binary Exploitation (Beginner)
Fix dead link: RingZer0 CTF now at ringzer0ctf.com
Move Root-Me to Freemium — confirmed paid Pro tier
```

Avoid vague messages like `update` or `fix stuff`.

## Submitting a Pull Request

1. Fork the repo and create a branch
2. Make your change in `README-free.md` (100% free resources) or `README-freemium.md` (freemium / free-tier-only resources)
3. Open a PR describing what changed and why — for a new resource, confirm you've verified it's actually free
4. One logical change per PR is easier to review than a bundle of unrelated edits

## Scope Reminder

This list only includes resources meant for **legal, authorized** security practice. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for what's out of scope.

---

Thanks again for contributing. 🚩
