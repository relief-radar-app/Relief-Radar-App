# ReliefRadar Site

Static site for ReliefRadar's public-facing pages (privacy policy, support contact), hosted via GitHub Pages.

## Structure

- `index.html` — landing page
- `privacy-policy.html` — privacy policy (linked from App Store Connect)
- `.nojekyll` — tells GitHub Pages to serve files as-is, skipping Jekyll processing

## Deploying

1. Push this repo to GitHub.
2. In the repo's Settings → Pages, set the source to the `main` branch, root folder.
3. GitHub will publish it at `https://<username>.github.io/<repo-name>/`.

## Updating the privacy policy

Edit `privacy-policy.html` directly, update the "Effective" date in the masthead, commit, and push — GitHub Pages redeploys automatically within a minute or two.
