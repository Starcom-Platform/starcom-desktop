# Starcom Desktop

A native host for the [Starcom](https://github.com/Starcom-Platform/starcom) web app, built with Electron. It renders
no interface of its own. It exists to grant capabilities a browser withholds:
- cross-origin requests, with the observation fixed as evidence when asked;
- direct TCP probes and reading a site's TLS certificate;
- an instrumented browsing view for pages assumed hostile;
- local model inference over loopback;
- a signer kept in its own process, away from the app's window.

## Status

- **Early macOS builds** are downloadable from
  [`Jthora/starcom-desktop-releases`](https://github.com/Jthora/starcom-desktop-releases/releases), which is moving
  to this organization.
- **The code is not public yet.** It is licensed AGPL-3.0, like the web app, and is planned to be published here;
  until then this repository holds only its licence.
- **Planned:** a personal relay on the person's own computer, the first network node anyone can run (decision D-DR).
  It is recorded in Starcom's [`docs/missions/01-architecture-decisions/desktop-relay.md`](https://github.com/Starcom-Platform/starcom/blob/main/docs/missions/01-architecture-decisions/desktop-relay.md).
