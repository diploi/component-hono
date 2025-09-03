<img alt="icon" src=".diploi/icon.svg" width="32">

# Hono Component for Diploi

[![launch with diploi badge](https://diploi.com/launch.svg)](https://diploi.com/component/hono)
[![component on diploi badge](https://diploi.com/component.svg)](https://diploi.com/component/hono)
[![latest tag badge](https://badgen.net/github/tag/diploi/component-hono)](https://diploi.com/component/hono)

Start a free demo without registering an account
https://diploi.com/component/hono

Run [Hono](https://hono.dev/) on Diploi. Uses [Bun](https://bun.sh/) to handle dependencies and to run the application.

Uses the official [oven/bun](https://hub.docker.com/r/oven/bun) Docker image.

## Operation

### Getting started

1. **Sign up** for a free Diploi account at [https://console.diploi.com/](https://console.diploi.com/)
2. In the Dashboard, click **Create Project +**
3. Under **Pick Components**, choose **Hono**
 You can add other frameworks from this page.
4. In **Pick Add-ons**, select any databases or extra tools you need.
5. Choose **Create Repository** so Diploi generates a new GitHub repo for your project.
6. Click **Launch Stack**

Link to guide 
https://diploi.com/blog/hosting_hono_apps

### Development

Will run `bun install` when component is first initialized, and `bun dev` when deployment is started.

### Production

Will build a production ready image. Image runs `bun install` & `bun run build` when being created. Once the image runs, `bun start` is called.

## Links

- [Hono documentation](https://hono.dev/docs/)
- [Bun documentation](https://bun.sh/docs)
