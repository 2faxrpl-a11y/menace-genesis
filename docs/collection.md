# Collection specification

Status: working proposal, 2026-11-23. The prior chat available to us did not expose an established lineup or final collection parameters. All names below are creative proposals for owner review, not claims about established MENACE canon.

## Collection identity

- Working name: MENACE Genesis. Network: XRPL, subject to owner confirmation of network and NFT issuer.
- Supply, edition numbering, reserved inventory, distribution, pricing, launch date, rights, royalties, flags and taxon: **undecided**. Do not assign counts or percentages until approved.
- Nine character types are mutually exclusive. Four named rare characters are proposed as individual 1/1 editions within those nine types, not four additional types. Their rarity and allocation are not finalized.
- Each NFT receives one character type, one background influence, and one value per applicable trait category. The four rare editions get unique finished art and explicit provenance, not an automatically assigned random rarity.

## Proposed nine character types

| Type | Silhouette and personality | Signature material cue |
|---|---|---|
| Sentinel | Armored guardian, grounded stance | Brushed titanium |
| Phantom | Elusive figure, narrow silhouette | Smoked glass |
| Renegade | Defiant street warrior, asymmetric profile | Distressed leather |
| Oracle | Observant mystic, poised and composed | Polished obsidian |
| Architect | Precise builder, geometric silhouette | Ceramic alloy |
| Warden | Imposing protector, heavy shoulders | Weathered steel |
| Nomad | Resourceful traveler, layered drape | Woven technical fabric |
| Alchemist | Experimental maker, compact equipment | Patinated copper |
| Sovereign | Commanding leader, restrained regalia | Dark gold |

## Proposed rare characters

| Character | Type | Individual visual concept |
|---|---|---|
| The First Witness | Sentinel | Scarred armor carries an archival date as an engraving. |
| The Lost Ledger | Phantom | Fragmented translucent surfaces conceal a historical ledger reference. |
| The Consensus Crown | Sovereign | A crown of distinct interlocking forms suggests agreement. |
| The Exchange Keeper | Architect | A precision-built artifact suggests an order book. |

These are original creative concepts, subject to rights review and owner approval. No promised utility, investment return or affiliation is implied.

## Trait taxonomy

Use stable `trait_type` labels and controlled values; proposed choices are not a final rarity schedule.

| Trait | Proposed values / rule |
|---|---|
| Character Type | Exactly one of the nine types above. |
| Character | Named rare character or `Unnamed`; no duplicate named 1/1. |
| Background Influence | Exactly one approved influence per image; see art direction. |
| Material | Titanium, Smoked Glass, Leather, Obsidian, Ceramic Alloy, Steel, Technical Fabric, Copper, Dark Gold. |
| Palette | Obsidian, Steel Blue, Ember, Verdigris, Ivory, Imperial Gold. |
| Headwear | None, Hood, Visor, Crown, Helm. |
| Eyes | Natural, Luminous, Masked, Lens. |
| Garment | Armor, Coat, Robe, Harness, Mantle. |
| Artifact | None, Ledger Plate, Key, Compass, Order Book, Seal. |
| Lore Motif | One registered lore ID or `None`; verify actual artwork before metadata assignment. |
| Edition Class | Standard or One of One; counts TBD. |

Document which options are drawn and compatible per type before production. Avoid impossible intersections, hidden traits, duplicate renders, invented weights and invisible metadata. Each trait recorded must be visibly present; Puffles omits an empty trait from exported metadata; handle that absence consistently. Lore may be subtle but should be discoverable in the full-resolution art. A lore motif is not a second background influence.
