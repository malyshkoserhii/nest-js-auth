docker-compose up -d
npx prisma migrate dev --create-only
npx prisma db push
npx prisma studio
