# Haunted Manor Bot — Public Policy Website

This is the **public GitHub Pages documentation repository** for a *private, non-commercial* Discord murder mystery bot used by roughly 20 friends. The operator is **RNYR** and questions or deletion requests go to **`v4rdr` on Discord**.

## Files

- `index.md` — short public homepage
- `terms.md` — rules for the private bot
- `privacy.md` — plain-language data-handling information
- `_config.yml` — GitHub Pages/Jekyll theme configuration

No bot code, player assignments, trait database, or Discord tokens belong in this repo.

## Publish

1. Create a **public** GitHub repository named `haunted-manor-website` under the `RNYR` account.
2. Upload the **contents of this folder directly to the repository root** (not the parent folder).
3. In GitHub, open **Settings → Pages**; set **Build and deployment → Deploy from a branch**, choose `main`, `/ (root)`, and save.
4. Wait for publication and verify:
   - Homepage: https://rnyr.github.io/haunted-manor-website/
   - Terms: https://rnyr.github.io/haunted-manor-website/terms.html
   - Privacy: https://rnyr.github.io/haunted-manor-website/privacy.html
5. Place the Terms and Privacy URLs into the corresponding fields in the Discord Developer Portal.

These URLs are expected paths after successful publication, not confirmation that Pages is live.

## Operator checklist

- **Keep the bot repository private** and the live assignments off public GitHub. If player assignments were ever committed to a public repository, removing the file is not enough to remove it from git history.
- Ensure the bot uses **persistent, private storage** on Railway. The website itself stores no player assignments.
- **Delete the live player assignments manually within 30 days of the event ending**, as stated in `privacy.md`; the bot does not currently enforce this automatically. If you cannot commit to that, update the policy *before* publishing it.
- Revisit policies if the Bot becomes public, runs in other servers, or handles additional data.
- Ensure `v4rdr` can receive contact messages on Discord from the intended participants.

The private household exception to GDPR may be relevant to this use, but its applicability depends on the facts. These documents are informational templates, not legal advice.
