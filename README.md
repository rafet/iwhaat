# iwha.at

**I would have asked AI too.**

A single page you can send to someone who asked you a question you'd have to
look up yourself. It explains — without being rude about it — that asking the
AI directly is faster than routing the question through you, and what to do
with the answer once they have it.

Live at **[iwha.at](https://iwha.at)**.

## Contents

One file: `index.html`. No build step, no dependencies, no tracking, no
JavaScript beyond a copy-to-clipboard button. Open it in a browser and it
works.

## Hosting

GitHub Pages serves `main` from the repository root. Pushing to `main`
publishes; there is nothing else to run.

DNS lives in Amazon Route 53. The apex points at the GitHub Pages addresses
and `www` is a CNAME to `rafet.github.io`.

## Changing it

Edit `index.html` and push. That's the whole workflow.

## Licence

Do what you like with it.
