# songbirdz-collection-media

This repo contains all the CC0 media (images, metadata) for the Songbirdz project.

1. Install dependencies:
```bash
npm install
```

2. Run the verify script:
```bash
node verifyMedia.js
```

This will check that all media files match the merkle tree in the solidity contract on Base and report any discrepancies.

## ./airdrops

This folder contains a CSV file that can be used when targeting our most active users for airdrops/allowlists for upcoming NFT mints.

- `top-10.csv`: The first 10 users to include, i.e. our most active Songbirdz holders.

## ./hof-data

This folder contains a JSON file with the data used to generate the fully onchain svg trophies in the Songbirdz Hall of Fame.

- `2025-09-18.json`

Link to collection: [https://opensea.io/collection/songbirdz-hall-of-fame](https://opensea.io/collection/songbirdz-hall-of-fame)

Link to contract: [SongBirdzHOF.sol](https://github.com/dry-tortuga/songbirdz-collection-backend/blob/main/contracts/SongBirdzHOF.sol)

## ./points

This folder stores the points history for each of the past seasons of the Songbirdz onchain bird watching seasons.

- `Season 1`: "Big Onchain Summer": 04-04-2024 to 08-31-2024.
- `Season 2`: "Big Onchain Fall": 09-01-2024 to 11-30-2024.
- `Season 3`: "Big Onchain Winter": 12-01-2024 to 02-28-2025.
- `Season 4`: "Big Onchain Spring": 03-01-2025 to 05-31-2025.
- `Season 5`: "Big Onchain Summer 2.0": 06-01-2025 to 08-31-2025.
- `Daily Streak Tracker`: A backup of the daily streak tracker data at a point-in-time.
- `Memory Match Log`: A backup of the memory match game data at a point-in-time.
