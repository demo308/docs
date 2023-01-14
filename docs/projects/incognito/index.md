---
sidebar_position: 2
---

# Welcome

Welcome to the [amethystnetwork-dev/Incognito](https://github.com/amethystnetwork-dev/Incognito) docs!

## Intro

This is a unofficial Incognito easy deployment version with [TompHTTP bare server](https://github.com/tomphttp/bare-server-node) included.

Incognito is a Titanium Network official proxy site

[![Titanium Network Discord](https://invidget.switchblade.xyz/unblock?theme=light)](https://discord.gg/unblock)

## Backend

The Bare Server backend used is from [tomphttp/bare-server-node/examples/static.js](https://github.com/tomphttp/bare-server-node/blob/master/examples/static.js)


## Config
To change the HTTP server port set the environment variable variable `PORT`.

### SSL Config
To enable SSL place your certificates in the SSL folder.

The certificate should be named `cert.pem` and the private key named `key.pem`.

When SSL is enabled port 443 will be used instead of 8080.