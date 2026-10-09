# ETH AI Safety Courses

A community-ranked list of ETH Zurich courses relevant to AI safety, served from GitHub Pages.

There's no backend. Each course is a GitHub issue with the `course` label, and an upvote is a 👍 reaction on that issue.

- **Suggest a course:** open an issue using the "Suggest a course" form. It gets the `suggestion` label.
- **Approve a suggestion:** a maintainer adds the `course` label. Only issues with `course` appear on the site.
- **Remove a course:** close the issue or remove the label.
- **Vote counts:** the page fetches them live from the GitHub API. If the API fails (unauthenticated calls are limited to 60/hour per IP), it falls back to `courses.json`, a snapshot the workflow rebuilds hourly and on every issue change.

## Setup

1. Push this repo to GitHub and make it public.
2. Settings → Pages → Source: **GitHub Actions**.
3. Create the labels `course` and `suggestion`.
4. If you fork or rename the repo, update `REPO` in `index.html`.
