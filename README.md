# hermes-oauth-site

Static legal pages for a personal Google OAuth application, published as a GitHub Pages project site
at https://robbonner2-cell.github.io/hermes-oauth-site/. The landing page describes the tool as
"Hermes Workspace": a private, single-operator automation tool running on its owner's own server,
which uses Google APIs with the owner's explicit consent to read and write that owner's own mail,
calendar, drive files and spreadsheets. It states the tool is not a public service, has no sign-up,
and is not offered to any third party. The bundle is a copy of the account's root Pages legal pages,
with the application named "Hermes Workspace" rather than "Hermes Fleet" as at the root.

## How to run

There is no build step and no script. The pages are plain HTML with inline CSS, served by GitHub
Pages; `index.html` can also be opened directly in a browser. Publishing is a push to `main`.

## Layout

- `index.html` — landing page: what the app is, with links to the two policies
- `privacy.html` — privacy policy: Google scopes accessed, how data is used and stored, retention and
  deletion, Limited Use
- `terms.html` — terms of service: private personal use, no warranty, revoking access

## Not included

- No application source code — legal pages only.
- No OAuth client secrets, tokens or user data; the policies point only at Google's own
  permission-revocation page.
- No analytics, trackers or third-party scripts.
