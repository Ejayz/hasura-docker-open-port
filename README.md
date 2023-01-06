# hasura-docker-open-port
Hasura config file with postgres 15 and open 5432 port docker file

Change this to your pannel setting

```HASURA_GRAPHQL_ADMIN_SECRET: [PanelPassword]```

Change this to your desired postgress password

```POSTGRES_PASSWORD: admin```

Update this base on your postgres db password

```HASURA_GRAPHQL_METADATA_DATABASE_URL: postgres://postgres:admin@postgres:5432/postgres```
