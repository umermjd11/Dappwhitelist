# About

This code represents a decentralized application (DApp) designed to manage a whitelist of addresses. The DApp facilitates the inclusion of addresses into a designated whitelist, with a cap defined by `maxWhitelistedAddresses`—indicating the maximum number of addresses eligible for whitelisting. Notably, addresses on this whitelist are granted priority in receiving NFTs within a corresponding NFT contract, exempt from any associated fees.

## Key Features:

1. **Whitelist Management:**
   - The DApp enables the addition of addresses to a whitelist.
   - The maximum number of whitelistable addresses is governed by `maxWhitelistedAddresses`.

2. **NFT Contract Integration:**
   - White-listed addresses gain preferential access to mint NFTs from the Crypto Devs collection.
   - The mint function within the NFT contract verifies the user's whitelist status and the availability of reserved tokens.

## User Benefits:

The Whitelist DApp serves as a mechanism for early supporters to secure a spot on the whitelist, guaranteeing them exclusive rights to mint NFTs from the Crypto Devs collection.

## Minting Process:

The mint function in the NFT contract performs the following checks:
   - Validates the user's whitelist status.
   - Verifies the availability of reserved tokens.

Upon meeting these requirements, a new NFT is minted for the user, ensuring a seamless and exclusive experience.




# DApp is made using Next.js
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
