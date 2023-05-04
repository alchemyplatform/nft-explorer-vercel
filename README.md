# CW3D Dapp Boilerplate For Vercel

This boilerplate is set up to be deployed on Vercel and you can directly deploy this project by clicking the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/alchemyplatform/nft-explorer-vercel)

## Resources

Please refer to CW3D's documentation and the following useful links for an in depth explanation of how to work with projects bootstrapped with CW3D:

- [Docs](https://docs.alchemy.com/docs/create-web3-dapp) - Everything you need to know when using CW3D
- [GitHub](https://github.com/alchemyplatform/create-web3-dapp) - look at the extensive code example or start contributing
- [Website](https://createweb3dapp.alchemy.com) - Learn more about CW3D and add components to your project
- [Templates](https://createweb3dapp.alchemy.com/#templates) - Check out the pre-built project templates
- [Components Library](https://createweb3dapp.alchemy.com/#components) - Add features directly to your project through components
- [Examples](https://github.com/alchemyplatform/create-web3-dapp-examples) - See the components implemented in a real world dapp
- [Community](https://t.me/createweb3dapp) - Meet other builders, get support, and give feedback!

## Overview

This project spins up a fully-fledge NFT Explorer, created using [Create Web3 Dapp](https://github.com/alchemyplatform/create-web3-dapp). It is preconfigured to be deployed on [Vercel](https://vercel.com/), providing you with a seamless way to get your dApp up and running in no time.

This boilerplate is built using [CW3D (Create Web3 Dapp)](https://github.com/alchemyplatform/create-web3-dapp), a powerful tool developed by [Alchemy](https://www.alchemy.com/) that allows developers to rapidly create and deploy dApps.

## What's Included?

This boilerplate has everything you need to start building a dapp:

- Next.js
- Wagmi Hooks
- Ethers.js
- Rainbowkit
- Alchemy SDK

## Supported Chains

The project supports all the major EVM chains:

- Ethereum
- Polygon
- Polygon zkEVM
- Arbitrum
- Optimism

## Getting Started

### Prerequisites

To get started with this boilerplate, you'll need to have the following software installed on your local machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/alchemyplatform/nft-explorer-vercel
   ```
2. Navigate to the `frontend` directory in the project:
   ```
   cd nft-explorer-vercel
   ```
3. Install the required dependencies:
   ```
   yarn install
   ```

### Running the Project

1. Start the local development server:
   ```
   yarn run dev
   ```
2. Open your browser and navigate to [`http://localhost:3000/`](http://localhost:3000/) to view the dApp in action.

### Deploying to Vercel

This boilerplate is set up to be deployed on Vercel and you can directly deploy this project by clicking the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Falchemyplatform%2Fvercel-alchemy-dapp-boilerplates-w-hardhat%2Ftree%2Fmain%2Ffrontend)

If you prefer to deploy it manually, follow these steps:

1. Sign up for a Vercel account at [vercel.com](https://vercel.com/) if you don't already have one.
2. Install the Vercel CLI:
   ```
   npm install -g vercel
   ```
3. Run the following command to deploy your dApp to Vercel:
   ```
   vercel deploy
   ```
4. Follow the prompts and provide the required information. Your dApp will be deployed and accessible via a unique URL.

## Project Structure

The boilerplate consists of one directory:

- `frontend`: Contains the Next.js frontend application and related components.

```
📦root
 ┣ 📂components
 ┃ ┣ 📂navigation
 ┃ ┃ ┗ 📜navbar.jsx
 ┃ ┗ 📜nftGallery.jsx
 ┣ 📂layout
 ┃ ┗ 📜mainLayout.jsx
 ┣ 📂pages
 ┃ ┣ 📂api
 ┃ ┃ ┣ 📜getNftsForCollection.js
 ┃ ┃ ┗ 📜getNftsForOwner.js
 ┃ ┣ 📜_app.js
 ┃ ┗ 📜index.jsx
 ┣ 📂public
 ┃ ┗ 📜alchemy_logo.svg
 ┣ 📂styles
 ┃ ┣ 📜Home.module.css
 ┃ ┣ 📜Navbar.module.css
 ┃ ┣ 📜NftGallery.module.css
 ┃ ┗ 📜globals.css
 ┣ 📜.env.local
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜package-lock.json
 ┗ 📜package.json
```

Start editing the `pages/index.jsx` file in the `frontend` directory to customize the project according to your own needs!
