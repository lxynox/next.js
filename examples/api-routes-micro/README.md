# API routes with Micro example

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/zeit/next.js/tree/canary/packages/create-next-app) with [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) or [npx](https://github.com/zkat/npx#readme) to bootstrap the example:

```bash
npx create-next-app --example api-routes-micro api-routes-micro-app
# or
yarn create next-app --example api-routes-micro api-routes-micro-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/api-routes-micro
cd api-routes-micro
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

Next.js ships with [API routes](https://github.com/zeit/next.js#api-routes), which provide an easy solution to build your own `API`. This example shows their usage alongside [Micro](https://github.com/zeit/micro), an `http` server for microservices
