## Getting Started

Project boiler plate built using NextJS typescript framework, scss styling.

First, For Project setup execute the below command

```
npm run project:setup

```

To run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## CodeCommit (git) steps

> Note: Below steps are mandatory before checkin your code to CodeCommit.

1.  Check your code, if it is not throwing any error in the console by executing the below commands

        npm run dev
        npm run build

2.  `npm run format` (Which internally runs the pre-commit hooks which checks eslint, ts type check, and build check).

3.  Add all the required files to the stage.

4.  Commit staged changes.

5.  Take a pull from the default branch(currently **develop** is the default branch)

6.  If you get any conflicts, fix those. If conflict is from other developers' components or files, check with a respected developer and fix them.

7.  If code is merged with no conflicts, push committed code to your branch.

8.  Create PR if your component or task is completed from your branch(source) to default branch(destination).
