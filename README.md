# Tailwind CSS + TypeScript + Next.js Starter

This is a lightweight starterkit / boilerplate to get up and running with Tailwind CSS, TypeScript and Next.js.

## Why make this boilerplate?

Tailwind, Next.js, and TypeScript is an excellent stack for building web apps. The most annoying part of using the stack
is setting it up every time, so I made an easy to use template that I and many others can use.

## Usage

### 1. Clone Repo

Github released [Github Templates](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) which allows users to generate a new repo from a template repo that will have the exact same files and structure. You can generate your own repo from this template by using [this link](https://github.com/kyrelldixon/next-tailwind-typescript-starter/generate).

From there, you can clone your own repo and modify it however you like.

If you would rather clone this repo, go to the command line and run:

```bash
git clone https://github.com/kyrelldixon/next-tailwind-typescript-starter <your-project-name>
cd <your-project-name>
```

### 2. Install Dependencies

```bash
pnpm install # npm i
```

### 3. Run Development Environment

```bash
pnpm dev # npm run dev
```

### Test Production Environment

I also included a `stage` script that will build and start a production server. You can run it with:

```bash
pnpm stage # npm run stage
```

Alternatively you can run:

```bash
pnpm build # npm run build
pnpm start # npm start
```
