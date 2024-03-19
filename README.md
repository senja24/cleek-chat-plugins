<div align="center"><a name="readme-top"></a>

<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-emoji/1.3.0/files/assets/puzzle-piece.webp">
<img height="120" src="https://gw.alipayobjects.com/zos/kitchen/qJ3l3EPsdW/split.svg">
<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-emoji/1.3.0/files/assets/convenience-store.webp">

<h1>Cleek Plugins Index</h1>

[**Submit Your Plugin >>**][submit]

[Cleek](https://github.com/senja24/cleek) accesses [`index.json`][website-url] from this repo to show user the list of available plugins for Function Calling.

<!-- SHIELD GROUP -->

[![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/senja24/cleek-plugins)
[![website][website-shield]][website-url]
[![][github-action-test-shield]][github-action-test-link]
[![][github-action-release-shield]][github-action-release-link]<br/>
[![][github-contributors-shield]][github-contributors-link]
[![][github-forks-shield]][github-forks-link]
[![][github-stars-shield]][github-stars-link]
[![][github-issues-shield]][github-issues-link]

[![](https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/268670883-33c43a5c-a512-467e-855c-fa299548cce5.png)](https://github.com/senja24/cleek)

</div>

## 🚀 How to Submit your Plugin

If you wish to add a plugin onto the index, make an entry in `plugins` directory using `plugin-template.json`, write a short description and tag it appropriately then open as a pull request ty!

### Step-by-step Instructions

1. <kbd>Fork</kbd> of this repository.
2. Make a copy of `plugin-template.json`
3. Fill in the copy and rename it appropriately
4. Move it into `src` directory
5. Submit a pull request and wait for review.

> \[!IMPORTANT]\
> The `createAt` date will be automatically populated after merge.

> \[!NOTE]
>
> - An plugin will need to be functioning for it to be included.
> - If plugin is no longer functional and or not maintained, we might redirect it to a fork or remove it form the index.
> - Not all plugins will be accepted, we will review the plugin and make an assessment.
> - You can submit plugins even if you are not the author, but it is preferred that the author do it themselves.
> - If you wish to have your plugin removed, or believes the description does not properly describe your plugin, please open the issue or pull request.

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🛳 Self Hosting

If you want to deploy this service by yourself, you can follow the steps below.

### Deploy to Vercel

Click button below to deploy your private plugins index.

[![Deploy with Vercel][deploy-shield]][deploy-url]

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## ⌨️ Local Development

You can use Github Codespaces for online development:

[![][github-codespace-shield]][github-codespace-link]

Or clone it for local development:

[![][bun-shield]][bun-link]

```bash
$ git clone https://github.com/senja24/cleek-plugins.git
$ cd cleek-plugins
$ bun install
```

If you need to run the `format` script locally, you need to configure the corresponding environment variables:

| Environment Variable | Type     | Example              |
| -------------------- | -------- | -------------------- |
| `OPENAI_API_KEY`     | Required | `sk-xxxxxx...xxxxxx` |
| `OPENAI_PROXY_URL`   | Optional | `-`                  |

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🔗 Links

- **[🤖 Cleek](https://github.com/senja24/cleek)** - An open-source, extensible (Function Calling), high-performance chatbot framework. It supports one-click free deployment of your private ChatGPT/LLM web application.
- **[🤖 / 🏪 Agent Index](https://github.com/senja24/cleek-agents)** - Cleek accesses index.json from this repo to show user the list of available agents for LobeChat.

<div align="right">

[![][back-to-top]](#readme-top)

</div>

---

#### 📝 License

Copyright © 2023 [Cleek][profile-url]. <br />
This project is [MIT](./LICENSE) licensed.

<!-- LINK GROUP -->

[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-151515?style=flat-square
[bun-link]: https://bun.sh
[bun-shield]: https://img.shields.io/badge/-speedup%20with%20bun-black?logo=bun&style=for-the-badge
[deploy-shield]: https://vercel.com/button
[deploy-url]: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flobehub%2Flobe-chat-plugins&project-name=lobe-chat-plugins&repository-name=lobe-chat-plugins
[github-action-release-link]: https://github.com/senja24/cleek-plugins/actions/workflows/release.yml
[github-action-release-shield]: https://img.shields.io/github/actions/workflow/status/senja24/cleek-plugins/release.yml?label=release&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-action-test-link]: https://github.com/senja24/cleek-plugins/actions/workflows/test.yml
[github-action-test-shield]: https://img.shields.io/github/actions/workflow/status/senja24/cleek-plugins/test.yml?label=test&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-codespace-link]: https://codespaces.new/senja24/cleek-plugins
[github-codespace-shield]: https://github.com/codespaces/badge.svg
[github-contrib-link]: https://github.com/senja24/cleek-plugins/graphs/contributors
[github-contrib-shield]: https://contrib.rocks/image?repo=lobehub%2Flobe-chat-plugins
[github-contributors-link]: https://github.com/senja24/cleek-plugins/graphs/contributors
[github-contributors-shield]: https://img.shields.io/github/contributors/senja24/cleek-plugins?color=c4f042&labelColor=black&style=flat-square
[github-forks-link]: https://github.com/senja24/cleek-plugins/network/members
[github-forks-shield]: https://img.shields.io/github/forks/senja24/cleek-plugins?color=8ae8ff&labelColor=black&style=flat-square
[github-issues-link]: https://github.com/senja24/cleek-plugins/issues
[github-issues-shield]: https://img.shields.io/github/issues/senja24/cleek-plugins?color=ff80eb&labelColor=black&style=flat-square
[github-stars-link]: https://github.com/senja24/cleek-plugins/network/stargazers
[github-stars-shield]: https://img.shields.io/github/stars/senja24/cleek-plugins?color=ffcb47&labelColor=black&style=flat-square
[pr-welcome-shield]: https://img.shields.io/badge/🧩/🏪_submit_plugin-%E2%86%92-95f3d9?labelColor=black&style=for-the-badge
[profile-url]: https://github.com/senja24
[submit]: https://github.com/senja24/cleek-plugins/pulls
[website-shield]: https://img.shields.io/website?down_message=offline&label=chat-plugins.cleek.id&up_message=online&url=https%3A%2F%2Fchat-plugins.cleek.id&labelColor=black&logo=vercel&style=flat-square
[website-url]: https://chat-plugins.cleek.id
