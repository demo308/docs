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

Configuration docs are [here](/projects/incognito/#config)

## Docker with NodeJS

You will need: [Docker](https://docker.com).

You should use our official Docker image.

To start, pull the image.
```bash
docker pull ghcr.io/amethystnetwork-dev/incognito:latest
```

And then you can start a docker container:
```bash
docker run -p 8080:8080 ghcr.io/amethystnetwork-dev/incognito
```

## Terminal with Deno

You will need: [Deno](https://deno.land).

(coming soon)