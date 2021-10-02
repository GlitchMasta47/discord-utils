# Discord Utils

A small little site with a few useful utility tools for Discord and Discord-related services. It's most useful for specific types of bot developers, and those involved/interested in [Discord-Datamining](https://github.com/DJScias/Discord-Datamining).

The website is created with [Preact](https://preactjs.com/), built with [Parcel](https://parceljs.org/), and deployed with [Vercel](https://vercel.io/) at [discord-utils.gm47.cf](https://discord-utils.gm47.cf/).

## Getting Started

First, ensure you have Node.js and npm installed on your system. Download this repo however you want to, and run `npm i` to install dependencies.

To run the development server:

```bash
npm start
# or
yarn start
```

The development server will host a webserver running on [localhost:1234](http://localhost:1234). You can start editing the different utilities in the `./src/utils/` directory, and the page will auto-update when you save a file.
To build the production site, including minification and other optimizations:

```bash
npm run build
# or
yarn build
```

You can then serve the files from `./dist/`.

## Planned Utils

- [ ] App Constants - shows the constants in each app, including strings
- [ ] Experiments - shows the list of open user and guild experiments, and which targets are enrolled in the experiment
- [ ] Mobile Assets - shows the manifest for the mobile apps, and allows you to browse the assets for a specific version or commit
- [ ] User ID <-> User Tag - converts an user id to a user tag (Username#1234) and vice versa
- [ ] Membership Screening Editor - editor for Membership Screening that allows more customizability than Discord's UI allows
- [ ] Enhanced Discovery Requirements - shows more verbose data about a server's eligibility for server discovery