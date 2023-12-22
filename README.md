## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# Copy from .env.local on the Vercel dashboard
# https://nextjs.org/learn/dashboard-app/setting-up-your-database#create-a-postgres-database

POSTGRES_URL="postgres://default:KoSBl0T1AYUu@ep-still-field-51970156-pooler.us-east-1.postgres.vercel-storage.com:5432/verceldb"
POSTGRES_PRISMA_URL="postgres://default:KoSBl0T1AYUu@ep-still-field-51970156-pooler.us-east-1.postgres.vercel-storage.com:5432/verceldb?pgbouncer=true&connect_timeout=15"
POSTGRES_URL_NON_POOLING="postgres://default:KoSBl0T1AYUu@ep-still-field-51970156.us-east-1.postgres.vercel-storage.com:5432/verceldb"
POSTGRES_USER="default"
POSTGRES_HOST="ep-still-field-51970156-pooler.us-east-1.postgres.vercel-storage.com"
POSTGRES_PASSWORD="KoSBl0T1AYUu"
POSTGRES_DATABASE="verceldb"

# `openssl rand -base64 32`
AUTH_SECRET=
AUTH_URL=http://localhost:3000/api/auth
