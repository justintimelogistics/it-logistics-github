# Deploy Checklist

Upload the contents of this folder to your Cloudflare Pages project.

After upload:

1. Create a D1 database named `jit-logistics-db`.
2. Run the SQL in `schema.sql`.
3. In Pages project settings, add a D1 binding named `DB`.
4. Add environment variables:
   - `APP_PASSWORD`
   - `AUTH_SECRET`
5. Redeploy the project.

Live app target:

- `https://app.jitlogisticsllc.com`
