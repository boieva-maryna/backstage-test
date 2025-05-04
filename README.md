# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn start
```

## Setting up a Local Database

To set up a local database for your Backstage app, you can use Docker Compose. Follow the instructions provided in the [Backstage documentation](https://backstage.io/docs/getting-started/config/database/#docker-compose) to configure and run the database.

### Environment Variables

Ensure the following environment variables are set in your `.env` file:

```properties
POSTGRES_HOST=localhost
POSTGRES_PORT=5432
POSTGRES_USER=
POSTGRES_PASSWORD=
```
