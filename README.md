# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment
### DEV

For deployment on DEV environment use the following commands:

```
# 1 - Build the dev image defined on Dokerfile.dev
npm run docker:build-dev

# 2 - Push the build dev image
npm run docker:push-dev

# 3 - Access to the server via SSH and pull the docker image
docker pull ghcr.io/fpalero/poleprojectstrapi-dev:latest
```

### PROD
For deployment on PROD environment use the following commands:

```
# 1 - Build the prod image defined on Dokerfile.prod
npm run docker:build-prod

# 2 - Push the build prod image
npm run docker:push-prod

# 3 - Access to the server via SSH and pull the docker image
docker pull ghcr.io/fpalero/poleprojectstrapi:latest
```

## Run Docker
For trying that the docker image is create correctly run:
```
# Run the DEV image using the local.env variable. 
# The local configuration uses the SQLITE Database
npm run docker:run-local

# Run the DEV image using the remote.env variable
# The remote configuration uses the Mysql Database
npm run docker:run-dev

# Run the PROD image using the remote.env variable
# The remote configuration uses the Mysql Database
npm run docker:run-dev
```

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
