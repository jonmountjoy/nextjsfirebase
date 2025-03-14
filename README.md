This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

It has a single addition, `npm install firebase-admin` and the use of that import.

This fails:
```bash
npm run dev
```

   TypeError: Cannot read properties of undefined (reading 'INTERNAL')

This succeeds:

```bash
node_modules/next/dist/bin/next dev
```
