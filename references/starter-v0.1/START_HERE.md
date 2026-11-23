# MENACE — Genesis collection starter pack (v0.1)

**Status: design draft only. No NFTs have been minted or registered on XRPL.**

## Addresses and on-chain identity

- **MENACE fungible token issuer (user supplied, unverified):** `rDR84iroyGoS7a4BjfPZnfoERjpEUvhk1n`
- **NFT collection issuer:** NOT YET SELECTED. Recommended: a dedicated issuer address separate from the fungible token issuer.
- **NFT collection grouping:** Give all Genesis NFTs the same `NFTokenTaxon` when minting. Taxon is not yet chosen.
- **NFT supply:** NOT YET SELECTED.
- **MENACE fungible token code:** NOT YET VERIFIED. An XRPL trust-line token is identified by *both* currency code and issuer.

## Included files

1. `collection_config.json`: collection configuration and unresolved launch decisions.
2. `traits_catalog.json`: nine character families, official proposed trait categories, and four reserved 1-of-1 special slots.
3. `sample_nft_metadata.json`: example JSON for one NFT. Its IPFS and website URLs are placeholders; do not mint it as-is.

## Creative rules

- Character-first, premium CGI detail, readable at avatar size.
- A single unobtrusive background influence for each character (collaborate with XRPL artists or use original interpretations of broad street-art traditions).
- Hidden, genuinely accurate XRPL lore built into stitches, engravings, eye reflections and scenery at zoom level, not an overcrowded collage.
- Master images should be high resolution, but the final release image and metadata must be checked for actual readability of microdetails.
- Maintain a **private clue manifest** that records the exact source, clue location, and verification status for every Easter egg. Don't publish spoiler details in public metadata.

## On-chain prerequisites before launch

1. Confirm the NFT issuer and who controls signing keys. **Do not send private keys or recovery phrases to a website or chat.**
2. Choose the final total supply and confirm if four special characters will each be 1-of-1.
3. Choose an unused Genesis taxon for that NFT issuer.
4. Decide transferability, issuer burn rights, secondary-sale transfer fee, and whether a fixed-supply guarantee is needed.
5. Finish and review all artwork, uniqueness constraints and rarity distribution.
6. Pin finalized images and metadata to persistent storage; test retrieval and CID integrity.
7. Validate mint transactions and marketplace compatibility on testnet; mint mainnet only after explicit owner approval.
8. Publish official mint links and verify a small sample in an independent ledger explorer.

## Official XRPL documentation

- https://xrpl.org/docs/concepts/tokens/nfts/collections
- https://xrpl.org/docs/references/protocol/transactions/types/nftokenmint
- https://xrpl.org/docs/concepts/tokens/nfts/payload-storage
- https://xrpl.org/docs/concepts/tokens/nfts/guaranteeing-a-fixed-supply
