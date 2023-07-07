# NextJS app dir, Drizzle ORM, PlanetScale, NextAuth starter

An example setup project for NextJS, shadcn-ui, Drizzle ORM, PlanetScale and NextAuth.

## Usage

Clone this repo

```bash
git clone https://github.com/blusrc/nextauth-drizzle-planetscale-starter.git
```

Install necessary dependencies

```bash
pnpm install
```

Fill up .env

If you use planetscale, delete the options after the db name and change it to `?ssl={}`
Very obscure problem

```env
DATABASE_URL='mysql://username:passowrd@0.0.0.0/db' #PlanetScale

NEXTAUTH_URL='http://localhost:3000'
NEXTAUTH_SECRET=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

Run db migrations

```bash
pnpm run db:push
```

Run db migrations

```bash
pnpm run db:studio
```

Run the development server

```bash
npm run dev
```

## Credits

Drizzle Adapter by [@mattddean](https://github.com/mattddean)
Original Template by [@miljan-code](https://github.com/miljan-code/drizzle-next-auth)
