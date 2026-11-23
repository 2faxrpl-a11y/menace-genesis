# Production and deployment checklist

All items unchecked. Do not mint, publish, list or upload publicly without the owner's explicit confirmation. This checklist is a plan, not an assertion that a platform supports the steps.

## Decisions and compatibility

- [x] User confirmed Puffles Studio means puffles.io. [Its guide](https://puffles.io/guide) states it creates images and OpenSea-style EVM metadata, does not mint or host, and does not write formats for other kinds of chains. Use it to assemble the finished artwork and generate metadata. XRP Cafe is the intended destination; verify its current import requirements before preparing the final files. Do not build a custom minter.
- [ ] Approve collection name, nine types, four 1/1 characters, supply, allocations, trait compatibility, backgrounds, rights and lore.
- [ ] Identify and independently verify the **NFT issuer** and network with the owner. The supplied fungible-token issuer `rDR84iroyGoS7a4BjfPZnfoERjpEUvhk1n` is not evidence of the NFT issuer. Never request or store seed phrases or private keys.
- [ ] Select and verify the XRPL service's import format, collection identification, NFT taxon, mint authority, transfer flags, transfer fee, costs and marketplace display. Taxon and issuer should be recorded as approved values, not guessed. Confirm testnet support.
- [ ] Agree storage, durability, licensing, supply, reserve, price, royalty behavior, and wallet operational safeguards. Fees and royalties are platform and ledger dependent; do not promise enforcement without verification.

## Art and metadata preparation

- [ ] Produce and approve style frame, trait assets and four unique masters. Verify one background influence and registered lore against final pixels.
- [ ] Import artwork to the confirmed Puffles service; configure layer order, compatibility, counts and rarity only after approval. Preview edge cases and keep the exact seed, configuration and project backup. If using puffles.io, export images and source metadata for conversion/validation against the chosen XRPL service; do not assume its EVM export is XRPL-ready.
- [ ] Select a stable image/metadata host and confirm URI retrieval. Prepare metadata to [XLS-0024](https://xls.xrpl.org/xls/XLS-0024-nft-metadata.html) and the chosen platform's documented requirements. `metadata/example.json` is a non-mintable illustration; replace every placeholder and validate against the actual schema and importer.
- [ ] Audit one-to-one mapping of image, metadata, edition, visible traits and any named rare; check duplicates and counts. Check lore sourcing and that hidden placement isn't accidentally exposed.
- [ ] Check NFT URI length and permanence against current [XRPL NFT standard](https://xls.xrpl.org/xls/XLS-0020-non-fungible-tokens.html) and selected service. Do not assume storage or future editability.
- [ ] If supported, perform a testnet-only trial after the owner approves the test action; inspect issuer, taxon, metadata, image, fee, flags and marketplace display. A testnet trial is not mainnet release approval.

## Release gate

- [ ] Present final issuer, network, asset list, content addresses, collection parameters, costs and exact mint/publish actions for explicit owner confirmation.
- [ ] Only after confirmation, follow the verified service's instructions; independently verify issued objects and display. Record resulting transaction IDs, NFToken IDs, issuer, taxon, storage identifiers and release configuration. No transaction has occurred yet.
