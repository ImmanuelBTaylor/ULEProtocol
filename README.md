# ULEProtocol

The ULEProtocol is a decentralized protocol for social networking platforms, inspired by Bluesky's AT Protocol. It powers the Kodo ecosystem, including platforms like ibty, with support for `unytoken` (utility token) and `unycoin` (transaction currency).

## Goals
- **Decentralized Data**: Users control their data (posts, blogs, goals, etc.) via a standardized record system.
- **Token Economy**: `unytoken` for platform interactions (likes, votes), `unycoin` for transactions (donations, purchases).
- **Interoperability**: All Kodo platforms (e.g., Kodoninja) can interact via KDNProtocol.

## Structure
- **Backend**: Motoko canister on the Internet Computer (IC) for data and token management.
- **Records**: Store user data (posts, blogs, etc.) as JSON records.
- **Tokens**: `kodotoken` and `kodocoin` for ecosystem interactions.

## Getting Started
1. Clone the repo: `git clone https://github.com/ImmanuelBTaylor/unyProtocol.git`
2. Navigate to the project: `cd unyProtocol/unyprotocol`
3. Start the DFX replica: `dfx start --background`
4. Deploy the canister: `dfx deploy`

## Next Steps
- Define a full schema for KDNRecords.
- Implement token transfer logic with balance checks.
- Create a frontend SDK for Kodo platforms to interact with KDNProtocol.
