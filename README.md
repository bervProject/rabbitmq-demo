# RabbitMQ Demo

Simple Publish/Subscribe App.

## Tools

* [Nodejs](https://nodejs.org/en/).
* [Yarn v1](https://classic.yarnpkg.com/en/docs/install#windows-stable).

## Preparation

* (For Linux/MacOS user) Copy `.env.sh.example` to `.env.sh`.
* (For Windows user - CMD) Copy `,env.cmd.example` to `.env.cmd`.
* (For Powershell) Copy `.env.ps1.example` to `.env.ps1`.

1. Update the `.env` file to point your RabbitMQ host.
2. Run `yarn --frozen-lockfile` to download the dependencies.

## Consumer

* Run `node consumer.js`.

## Publisher/Sender

* Run `node sender.js`.

### LICENSE

MIT