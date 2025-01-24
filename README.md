# template-nttnp

Template built on `NextJS` `TRPC` `TailwindCSS` `NextAuth` `Prisma` bootstrapped with `create-t3-app`

> Works as of Jan 23, 2025

### Installation

1. Clone locally

```sh
git clone https://github.com/sqwyer/template-nttnp.git \<dir_name\>
```

2. Install and setup database

```sh
npm install
sh ./start-database.sh
npm db:push
npm run dev
```

### Info

- Uses Google oAuth by default. Can be changed by adjusting providers in `src/server/auth/config.ts`
-
