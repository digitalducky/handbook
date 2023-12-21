# Handbook

<p align="center">
    <img width="200" src="static/img/ducky-yellow.png">
</p>

<div align="center">
  The Digital Ducky Handbook
</div>

## Motivations

This handbook is inspired largely by [the handbook](https://about.gitlab.com/handbook/) and the transparent, public-by-default culture at [GitLab](https://gitlab.com).[^1]

Our wish is for Digital Ducky to be a largely open company, and this handbook is the start of that open culture.
While just publishing some random company documents alone might not get much done, there is a potential for incredible value when a company is truly open.
Openness builds trust from staff, customers, and the greater community.
A culture of openness can lead to a culture of greatness.
It inspires others.

### Why a handbook?

Written documentation is essential to building a modern company.
But writing is hard.
It requires a ton of practice, thought, and patience.
Written communication is essential for maintaining a sense of calm in a sea of chaos.

Anything worth remembering should be written down.
In a business, anything worth sharing should be written down.
And in an open business, everything should be written down and shared widely.

This handbook will allow us to start building and documenting Digital Ducky in public.

## Development

This website is built using [Docusaurus 3](https://docusaurus.io/).

### Easy Local Dev

Install node, then run
```sh
npm run start
```

- The site launches at `https://localhost:3000` in your browser.
- Live reloads changes.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

- [Vercel](https://vercel.com/digitalducky/handbook)
- Deployed via the Vercel git Integration
- Deploys to production automatically with new merges to `main`.
- Deploys to preview automatically when a pull request is opened.

[^1]: I would highly recommend reading more about the handbook philosophy at GitLab. See also:
    - https://about.gitlab.com/handbook/
    - https://about.gitlab.com/handbook/handbook-usage/#why-handbook-first
    - https://about.gitlab.com/company/culture/all-remote/handbook-first-documentation/
