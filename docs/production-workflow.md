# MENACE Genesis: artwork to XRPL

Owner's intended sequence: finish and approve the whole collection's artwork and traits; use Puffles Studio to assemble the images and generate metadata; prepare the result for XRP Cafe; only mint or publish after explicit confirmation. The immediate production phase is artwork and trait creation. This is not yet a finished collection.

## 1. Complete the artwork first

- Approve the visual identity, nine base characters, four unique rare artworks, trait catalog and exact collection supply. The current names and designs are proposals. Finish a representative visual master first, then build all compatible trait artwork using a consistent camera, scale, canvas and lighting.
- Create six backgrounds, each portraying exactly one influence; create transparent, fitted foreground layers; create four finished 1/1 images. Detailed XRPL references must be checked against `lore.md` and actually visible when zoomed in.
- Create a production inventory listing each actual asset, its trait value, character compatibility, version, approval and rights. Set rarity counts/weights and constraints based on the chosen supply; test whether the possible unique combinations satisfy it.
- High-end 3D compositing is the main technical risk: pieces made for one head may not fit another, and shadows or materials may conflict. Use character-specific fitted assets and never-together rules, or render finished composites when necessary. Make a small internal test to prove quality before producing the entire set. A test is not a public release.

## 2. Assemble in Puffles once assets are ready

Puffles' [guide](https://puffles.io/guide) documents aligned same-sized images, transparent foregrounds, trait folders, never-together rules, rarity weights/counts and separate complete 1/1 images. Its project planner checks constraints and uniqueness. Its export includes images, individual JSON, combined metadata, rarity report and settings. Puffles generates the metadata from the trait names and its metadata settings; it does not mint or host.

Use a folder plan such as `01_Background Influence`, `02_Character Type`, `03_Garment`, `04_Eyes`, `05_Headwear`, `06_Artifact`, and `1 of 1`. Exact construction depends on the approved rendered assets. Each folder corresponds to an actual visible image layer; material and palette may be baked into a base asset and require an accurate separate metadata mapping rather than imaginary layers. Do not label a material or palette independently unless the finished image actually has it. Puffles' empty trait is omitted from metadata, not exported as an explicit `None` value. Its 1/1 export normally contains only a `1 of 1` attribute, so the four unique pieces need a checked post-export enrichment if they should also carry character type, background or other traits. See [Puffles' 1/1 guide](https://puffles.io/learn/add-1-of-1s-to-generative-collection) and [rarity guide](https://puffles.io/learn/nft-rarity-for-creators).

- Set approved supply, rules, rarity, description and numbering; import the four 1/1s as finished pieces. Save the seed, project backup and export. Match every numbered artwork to its metadata and inspect duplicates, visual traits, 1/1s, counts and hidden lore.
- Do not change the seed, layer order, rules or rarity after export without rebuilding the matching images and metadata. Keep the Puffles output unchanged as a master and make any XRP Cafe preparation on a copy.

## 3. Prepare for XRP Cafe

Puffles says its export is OpenSea-style EVM metadata. Do not assume the raw export is accepted by XRP Cafe, nor assume it is rejected: image/name/attributes may overlap, but the import contract has not been verified. Before finalizing any metadata conversion or upload, inspect XRP Cafe's current creator/launchpad flow or obtain its current instructions. Record whether it accepts individual JSON, a combined file, CSV or image-only upload; required fields, filenames, file limits, image hosting and IPFS behavior; and how it handles 1/1 attributes and collection identifiers. XRP Cafe's current exact import requirements remain **unverified**.

If adaptation is needed, transform a copy to the format XRP Cafe specifies, preserve each image/edition/trait mapping, and validate a small representative sample plus all four 1/1s. If external image hosting is required, set verified final image URIs, keep media and metadata pinned and backed up, and avoid placeholder URIs. XLS-0024 is an XRPL ecosystem metadata standard, but XRP Cafe's actual importer is the deciding compatibility target. Never present the illustrative example JSON as a ready-to-upload export.

## 4. Approval and release

Present the final collection, exact asset counts, metadata, issuer, network, storage, platform settings and costs for confirmation before any public upload, mint, listing or publication. The supplied MENACE fungible-token issuer `rDR84iroyGoS7a4BjfPZnfoERjpEUvhk1n` is not established as the NFT issuer. Do not request or store wallet secrets. Do not perform transactions without the user's explicit confirmation.
