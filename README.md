This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app)
and testing out the Static Web APP Data API. [Next.js](https://nextjs.org/)

[Public link](https://purple-sea-07cdac80f.2.azurestaticapps.net)

Site uses a system managed identity.

## Getting Started

To run locally, run:

```
swa start --data-api-location swa-db-connections

```

Note that you will need to create a local .env file that contains a database connection string to an Azure SQL instance. You will also need to change the schema in swa-db-connections if you need any other apis.

Limited to 100MB right now.
