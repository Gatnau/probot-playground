# add-teams

> A GitHub App built with [Probot](https://github.com/probot/probot) that A Probot to add default teams

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t add-teams .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> add-teams
```

## Contributing

If you have suggestions for how add-teams could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Ivan Gatnau Lopez <ivan.lopez@gcp.deuba.com>
