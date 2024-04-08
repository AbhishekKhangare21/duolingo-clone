# Build a Duolingo Clone With Nextjs, React, Drizzle, Stripe (2024)

![Duolingo thumb (1)](https://github.com/AntonioErdeljac/next14-duolingo-clone/assets/23248726/d58e4b55-bb09-456f-978e-f5f31e81b870)

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
DATABASE_URL="postgresql://..."
STRIPE_API_KEY=""
NEXT_PUBLIC_APP_URL="http://localhost:3000"
STRIPE_WEBHOOK_SECRET=""
```

### Setup Drizzle ORM

```shell
npm run db:push

```

### Seed the app

```shell
npm run db:seed

```

or

```shell
npm run db:prod

```

### Start the app

```shell
npm run dev
```
