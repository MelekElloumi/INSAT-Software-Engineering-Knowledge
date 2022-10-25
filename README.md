# Website

Going to put everything I know about INSAT & its software engineering degree here

- CheatSheets
- Tips
- Guides
- PFE things

Contributions through PRs are always welcome

### Installation

```console
yarn
```

### Local Development

```console
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```console
USE_SSH=true yarn deploy
```

Not using SSH:

```console
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
