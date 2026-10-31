# Contributing to RW Digital Solutions repositories

Thanks for building with us. These rules apply to every repository in the organization unless a repo has its own CONTRIBUTING.md.

## 1. Getting access
- Enable two-factor authentication (2FA) on your GitHub account.
- An org admin adds you to the right team (e.g. `developers`). Teams — not individuals — get repository access.

## 2. Creating or uploading a repository
- Create new repos **inside the organization** (New → Owner: `rw-digital-solutions`), not under your personal account.
- To move an existing personal repo in: Repo → Settings → General → Danger Zone → **Transfer ownership** → `rw-digital-solutions` (ask an admin if you lack permission).
- Naming: lowercase, hyphen-separated, descriptive — e.g. `rw-digital-os`, `client-acme-website`.
- Every repo needs: a `README.md` (what it is, how to run it), a `.gitignore`, and a description.
- Default to **Private**. Make a repo public only with admin approval.

## 3. Branches
- `main` is always deployable. Never push directly to `main`.
- Branch names: `feature/short-description`, `fix/short-description`, `chore/short-description`.

## 4. Commits
- Small, focused commits with clear messages in the imperative: `Add login page`, `Fix invoice total rounding`.

## 5. Pull requests
- Open a PR into `main` and fill in the PR template.
- At least **one approving review** from another developer before merging.
- Keep PRs small; link the related issue (`Closes #12`).
- Prefer **Squash and merge**; delete the branch afterwards.

## 6. Secrets
- Never commit passwords, API keys, `.env` files or credentials. Use GitHub Actions secrets or a secrets manager.
- If a secret is committed by mistake, tell an admin immediately and rotate it.

## 7. Issues
- Use the issue templates (Bug report / Feature request). Label and assign issues so work is visible.
