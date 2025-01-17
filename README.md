# Qwik-X ⚡️

Social media web app like Twitter build with Qwikcity

## Tech Stack

- Qwikcity
- Typescript
- Drizzle ORM
- Neon
- Postgresql
- Node/Express server
- Tailwindcss
- daisyui

> Note: copy .env.example inside .env

## Development

Development mode uses [Vite's development server](https://vitejs.dev/). The `dev` command will server-side render (SSR) the output during development.

```shell
pnpm run dev
```

> Note: If you want to generate random 100 users then open this url inside your browser
> http://localhost:5173/api/seeding/?entities=users

## Preview

The preview command will create a production build of the client modules, a production build of `src/entry.preview.tsx`, and run a local server. The preview server is only for convenience to preview a production build locally and should not be used as a production server.

```shell
pnpm run preview
```

## Production

The production build will generate client and server modules by running both client and server build commands. The build command will use Typescript to run a type check on the source code.

```shell
pnpm run build
```

## Express Server

This app has a minimal [Express server](https://expressjs.com/) implementation. After running a full build, you can preview the build using the command:

```shell
pnpm run serve
```

Then visit [http://localhost:8080/](http://localhost:8080/)
