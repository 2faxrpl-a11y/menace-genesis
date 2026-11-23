# MENACE Genesis — source-aligned production plan

Status: draft derived from `references/starter-v0.1/`; the complete blueprint and approved artwork have not been located or reviewed. This is a production framework, not a declaration of approved designs.

## Visual foundation

One highly detailed cinematic 3D MENACE character is the focal point, readable at avatar scale and rewarding close inspection. The starter proposes a master at 6144 × 6144 or higher and a display export of at least 2048 × 2048, preferably 4096 × 4096. Test whether hidden details remain legible at the eventual export size. Each image uses exactly one restrained original street-art or optical-illusion background treatment; no multi-artist collage. A commissioned XRPL artist collaboration is a separate possible treatment, subject to rights and approval.

The nine draft character families are **Goggle Punk, Shadow Hood, Fang Beanie, Stitched Bunny, Chaos Pigtails, Street Reptile, Patchwork Bear, Horned Rebel, Skull Skater**. Their detailed appearance must be established from the missing artwork rather than invented from their names. The starter lists Wigz Menace as a concept with name and rarity pending, plus three unfilled special slots. It does not prove that any of the four is approved or will be a 1/1.

## Trait design and preparation

The source catalog defines Character Family, Face Material, Eyes, Mouth, Headwear, Outfit, Jewelry, Signature Mark, Background Theme, Lighting, Lore Depth and Rarity Tier. Use the source JSON for exact draft values. Some traits may be baked into renders rather than independent layers. The planned jewelry selection is zero to two; how it is represented in Puffles and downstream metadata requires a real import test. Avoid a `None` value combined with an actual jewelry item.

For each finished asset record: file path, source, status (unreviewed / approved / rejected), revision, canvas, family and compatible variants. Human review must check goggles against eyes, hoods against ears, accessories against fur, silhouettes, shadow consistency, and each background. An approval belongs to a particular file and revision. Keep rejected source art separate; no assets have been classified yet.

## Rarity framework

Supply and the four special allocations are unresolved. After approval, define an edition budget: total supply = standard editions + confirmed special editions. For each trait category, set intended counts or relative weights and explicit constraints. For jewelry, account for zero, one or two pieces without conflating individual occurrences and edition counts. Keep an independent list of actual planned editions and reconcile rarity counts with the generated export; Puffles weights are relative and need not produce exact counts. Do not advertise a tier as rare until its resulting counts and definition are verified. Record the approved seed, rules and settings for reproducibility. Check visual uniqueness, not just metadata combinations.

## Metadata review

Use Puffles after the assets and distribution are ready. Preserve its original export and review a copy for the downstream XRP Cafe import format, which remains unverified. Verify unique edition names and IDs, image-to-metadata pairing, all visible attributes, no conflicting or duplicate trait values, valid image references, and absence of placeholders. Puffles can omit empty traits and gives finished 1/1s a single 1/1 attribute by default; inspect and enrich the four records only if the final approved taxonomy requires it. Public metadata should not disclose clue answers or exact locations. Verify final output against the actual XRP Cafe importer before any upload.

## Lore and release

Maintain a private production record per motif: fact, authoritative source, verified wording, image/edition, exact placement, reviewer and final-size visual check. `docs/lore.md` provides candidate sourced facts, not evidence they are in finished artwork. The NFT issuer remains unspecified; the supplied fungible-token issuer is not proof of NFT issuer. No upload, mint, listing or publication without explicit approval.
