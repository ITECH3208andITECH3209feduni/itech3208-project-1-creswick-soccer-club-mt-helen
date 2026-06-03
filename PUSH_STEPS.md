# GitHub Push Steps - Sprint 2 Final V3

Use this if Version 1 is already on GitHub and you want to upload the organised Sprint 2 final website.

## Recommended team workflow: branch + pull request

```bash
git clone https://github.com/ITECH3208andITECH3209feduni/itech3208-project-1-creswick-soccer-club-mt-helen.git
cd itech3208-project-1-creswick-soccer-club-mt-helen

git checkout main
git pull origin main
git checkout -b sprint2-final-v3-website
```

Now copy these organised files into the repository folder:

- `index.html`
- `styles/`
- `scripts/`
- `assets/`
- `README.md`

Then run:

```bash
git status
git add index.html styles scripts assets README.md
git commit -m "Add Sprint 2 final V3 website"
git push -u origin sprint2-final-v3-website
```

After pushing:
1. Open the GitHub repository in the browser.
2. Click **Compare & pull request**.
3. Add a short PR description.
4. Ask one team member to review.
5. Merge into `main` after review.

## Optional: create a release tag after merge

```bash
git checkout main
git pull origin main
git tag v3.0-sprint2-final
git push origin v3.0-sprint2-final
```

## Do not do this unless your team agrees

Avoid pushing directly to `main` because your Sprint 2 report says the team uses reviewed pull requests.
