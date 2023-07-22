# TO RUN LOCALLY

1. Clone this repo

2. Install [Bun](https://bun.sh)

3. Run `bun install` to install dependencies

4. Create a database with [Turso](https://turso.tech) and add the connection url and token to a `.env` file in the root of this project

5. Run `bun run db:push` to push the database schema to your database

6. Run `bun run dev` to start the dev server
