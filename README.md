# summit-leo-dashboard-api

Cloudflare Worker that reads the Leo CRM API and serves the KPI dashboard's
`/api/pipelines`, `/api/opportunities`, `/api/pipeline-stats`, `/api/lead-sources`
and `/api/leo/summary` endpoints.

Deploy: Cloudflare -> Workers & Pages -> Create -> Import a repository -> this repo,
root directory `leo-worker`, build command blank, deploy command `npx wrangler deploy`.
Then add the `LEO_API_KEY` secret under Settings -> Variables and Secrets.
