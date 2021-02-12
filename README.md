# Probot & Begin example

This repository is an example of how to deploy the "Hello, World" of probot apps to [Begin](https://begin.com/).

[![Begin build status](https://buildstatus.begin.app/dream-zdj/status.svg)](https://begin.com)

## Deploy your own

[![Deploy to Begin](https://static.begin.com/deploy-to-begin.svg)](https://begin.com/apps/create?template=https://github.com/probot/example-begin)

Deploy your own clone of this app to Begin!

Once deployed, make sure to configure the environment variables for your production environment once you [registered a GitHub App](https://github.com/settings/apps/new)

1. `APP_ID`
2. `PRIVATE_KEY` (base64 encoded, you can do that [here](https://www.base64encode.org/))
3. `WEBHOOK_SECRET`

## Local setup

- Start the local dev server: `npm start`
- Run your tests: `npm test`

## Reference

- [Probot](https://probot.github.io/docs/) - The Probot documentation
- [Begin Quickstart](https://docs.begin.com/en/guides/quickstart/) - basics on working locally, project structure, deploying, and accessing your Begin app
- [Creating new routes](https://docs.begin.com/en/functions/creating-new-functions) - basics on expanding the capabilities of your app

Head to [docs.begin.com](https://docs.begin.com/) to learn more about Begin!
