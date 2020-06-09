# Nextjs Boilerplate

## Setting up Next.js
Follow official [doc](https://nextjs.org/docs/getting-started)
```
$ npx create-next-app
```

## Setting up TypeScript, ESLint and Prettier
### TypeScript
Follow official [doc](https://nextjs.org/docs/basic-features/typescript)
```
$ touch tsconfig.json
$ yarn dev
$ yarn add --dev typescript @types/react @types/node
```

### ESLint
```
$ yarn add --dev eslint
$ npx install-peerdeps --dev eslint-config-airbnb
$ yarn add --dev @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

### Prettier
```
$ yarn add --dev prettier eslint-plugin-prettier eslint-config-prettier
```
