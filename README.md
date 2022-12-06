# hugo-bearblog-starter

This is a pretty "bear" bones [Hugo](https://gohugo.io/) site that's ready for use with [Forestry.io](https://forestry.io/). It uses the [Bear Blog](https://github.com/janraasch/hugo-bearblog/) theme and contains very little content that you'll need to change or remove.

## How it works

It comes paired with a Forestry.io config that will allow you to use their editor to create and modify your site's content. Just clone or copy this repo, import your repo as a Forestry site, and you're all set. Any changes you make in Forestry will be pushed into your repo and will kick off a gh-pages buidl and deploy.

## Setup

- Copy of clone this repo into a repo you own
- Change the site settings in `config.toml` to whatever you want
- Add a site in your Forestry.io dashboard, pick Hugo, and point at your repo
- Add and edit content in Forestry.io
- Changes will be saved to this repo and kick off the build and deploy Github Action
- Now you will have a `gh-pages` banch, [configure your repo to use it](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) by publishing pages from that branch
- When the action triggers, you should be able to load your site at `https://<username>.github.io/<reponame>`
