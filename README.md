# Discord Utils

A small little site with a few useful utility tools for Discord and Discord-related services. It's most useful for specific types of bot developers, and those involved/interested in [Discord-Datamining](https://github.com/DJScias/Discord-Datamining).

The website is created with [Next.js](https://nextjs.org/) and deployed to [Vercel](https://vercel.io/) at [discord-utils.gm47.cf](https://discord-utils.gm47.cf/).

## Getting Started

First, ensure you have Node.js and npm installed on your system. Download this repo however you want to, and run `npm i` to install dependencies.

To run the development server:

```bash
npm run dev
# or
yarn dev
```

To build the production site:

```bash
npm run build
# or
yarn build
```

You can then start the production server:

```bash
npm start
# or
yarn start
```

Both the development and production servers will host a webserver running on [localhost:3000](http://localhost:3000). You can start editing pages in the `pages/` directory, and your changes will live-update when you save a file.

## Planned Utils

- [ ] App Constants - shows the constants in each app, including strings
- [ ] Experiments - shows the list of open user and guild experiments, and which targets are enrolled in the experiment
- [ ] Mobile Assets - shows the manifest for the mobile apps, and allows you to browse the assets for a specific version or commit
- [ ] User ID <-> User Tag - converts an user id to a user tag (Username#1234) and vice versa