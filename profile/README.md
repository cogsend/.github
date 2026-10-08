<p align="center">
  <img width="96" alt="CogSend" src="https://github.com/user-attachments/assets/42c2579f-b1f2-4345-980a-01e24c9e027c" />
</p>

<h1 align="center">CogSend</h1>

<p align="center">
  Self-hosted social scheduler for Mastodon, Bluesky, LinkedIn, Threads and X.<br />
  Write a draft, customize it per platform, then publish it now or schedule it.
</p>

<p align="center">
  <a href="https://cogsend.com">Website</a>
  ·
  <a href="https://cogsend.com/docs/">Docs</a>
  ·
  <a href="https://cogsend.com/docs/deploy/">Install</a>
  ·
  <a href="https://github.com/cogsend/cogsend/releases">Releases</a>
</p>

<p align="center">
  <img alt="The CogSend composer" src="https://cogsend.com/shots/composer.png" />
</p>

CogSend runs on your own Cloudflare account. Your posts stay in your own D1 database, your media in your own R2 bucket, and everything goes out through your own API credentials. There is no subscription and no hosted service in between.

## Repositories

| Repository | What it is |
| --- | --- |
| [cogsend](https://github.com/cogsend/cogsend) | The app: SvelteKit on Cloudflare Workers, D1 and R2. Issues, discussions and the docs live here. |
| [website](https://github.com/cogsend/website) | [cogsend.com](https://cogsend.com), which also renders the docs from the app repository. |
| [deploy](https://github.com/cogsend/deploy) | A prebuilt copy of the app for the Deploy to Cloudflare button, regenerated on each release. |

## Getting help

- Questions and ideas: [Discussions](https://github.com/cogsend/cogsend/discussions)
- Bugs: [Issues](https://github.com/cogsend/cogsend/issues)
- Security: report privately through [a security advisory](https://github.com/cogsend/cogsend/security/advisories/new)

CogSend is [MIT licensed](https://github.com/cogsend/cogsend/blob/main/LICENSE).
