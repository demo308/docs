# Manual Deployment

How to use Incognito on your own server.

You will need [Git](https://git-scm.com) installed.

## Terminal with NodeJS

You will need: [NodeJS](https://nodejs.org).

First, clone the repo:
```sh
git clone https://github.com/amethystnetwork-dev/Incognito.git
```

To install the required packages, you will need to cd into the repository you just cloned and then run `npm install`. The commands can be seen below:
```sh
cd Incognito
npm install
```

To start Incognito, run the command below:
```sh
npm start
```

This starts the bare server and serves the static files on port 8080 by default.

## Docker with NodeJS

You will need: [NodeJS](https://nodejs.org) and [Docker](https://docker.com).

```bash
git clone https://github.com/amethystnetwork-dev/Incognito
```

Then CD into the repo:
```bash
cd Incognito
```

To create the dockerfile, run:

```bash
npm run create-dockerfile
```

And then you can start the docker container.

## Terminal with Deno

You will need: [Deno](https://deno.land).

(coming soon)