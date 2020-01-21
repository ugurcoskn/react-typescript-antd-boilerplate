# React-Typescript-Antd Boilerplate

A boilerplate for setting up your react-typescript project in seconds with antd, react, typescript, eslint, prettier support.

Antd implementation always take a lot of time for my typescript projects. This boilerplate has some configuration for that.

## Getting Started

```bash
git clone https://github.com/ugurcoskn/react-typescript-antd-boilerplate.git my-app
cd my-app
yarn install  # install dependencies
yarn dev    # start dev server
```

#### yarn dev

Start the app in dev mode

#### yarn build

Build the app in production mode

#### yarn lint

Check all `ts,tsx` files whether they match given coding style

## Commit Message Standard

Commit messages must comply with [conventional-changelog](https://conventionalcommits.org). Otherwise [husky](https://github.com/typicode/husky) will complain. In order to create a conventional commit, `yarn commit` command can be used.

## Releasing

Running `yarn release` command;

-   Creates a new version tag based on the commit history.
-   Updates version number in `package.json`.
-   Generates `CHANGELOG.md`.
-   Commits these changes with a message like `chore(release): publish %s`.

After that, `git push --follow-tags origin master && npm publish` command can be used to push these changes to upstream.

Have fun!
