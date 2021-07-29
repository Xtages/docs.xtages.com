---
title: "Database"
weight: 400
---

Every organization is provisioned with a PostgreSQL 13 database server on signup. To access the database you will need to use the standard PostgreSQL connection [environment variables](https://www.postgresql.org/docs/current/libpq-envars.html). More specifically:

* `PGHOST`
* `PGUSER`
* `PGDATABASE`
* `PGPASSWORD`
* `PGPORT`

{{% alert title="Tip!" color="info" %}}
We recommend using an automated DB migration framework (like [db-migrate](https://db-migrate.readthedocs.io/en/latest/), [Knex.js](https://knexjs.org/) or [Sequelize](https://sequelize.org/master/manual/migrations.html)) to evolve your DB schemas.
{{% /alert %}}
