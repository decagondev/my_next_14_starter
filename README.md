## Getting Started
- Sign up to a free account at [Clerk Auth](https://www.clerk.com/)
- Set up a new app giving it a name that makes sense for you.
- copy the public and private keys to enter in to the `.env` file later
- setup a `.env` file and add the following to it
```JavaScript
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<YOUR_PUBLIC_KEY>
CLERK_SECRET_KEY=<YOUR_SECRET_KEY>
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
```
**Remember to add your actual public and private keys**

- run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
