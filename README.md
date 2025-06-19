<img alt="icon" src=".diploi/icon.svg" width="32">

# Hono Component for Diploi

Run [Hono](https://hono.dev/) on Diploi. Uses [Bun](https://bun.sh/) to handle dependencies and to run the application.

Uses the official [oven/bun](https://hub.docker.com/r/oven/bun) Docker image.

## Operation

### Development

Will run `bun install` when component is first initialized, and `bun dev` when deployment is started.

### Production

Will build a production ready image. Image runs `bun install` & `bun run build` when being created. Once the image runs, `bun start` is called.

## Links

- [Hono documentation](https://hono.dev/docs/)
- [Bun documentation](https://bun.sh/docs)
