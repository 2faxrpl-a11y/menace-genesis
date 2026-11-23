# MENACE Genesis — trait design bible

Working creative lineup, 23 November 2026. These are production designs for review, not finished image assets. All nine are original characters in one visual universe. Supply and rarity weights remain open. Each standard NFT has one character type and one background influence; rare characters are four distinct 1/1 artworks within the nine types.

## Shared visual DNA

A formidable, stylized character with a recognizable face, expressive eyes and deliberate attitude. Premium cinematic 3D: sculpted forms, convincing surfaces, restrained wear, detailed seams and subtle imperfections. Square, centered bust-to-mid-torso portrait; the head and shoulders dominate the frame. Use the same camera position, scale and neutral key-light direction throughout the collection. Preserve clean edges and negative space. Characters must read at thumbnail size; micro-engravings reward zooming. Avoid text labels, watermarks, logos, random numbers, excessive clutter and franchise likenesses.

## Nine character blueprints

| Type | Face and silhouette | Default outfit and finish | Signature personality |
|---|---|---|---|
| Sentinel | Broad angular helmet; firm jaw and forward gaze | Segmented titanium chest armor, exposed dark underlayer | Resolute guardian |
| Phantom | Narrow, elongated head; partially translucent facial shell | Close-fitting smoked-glass collar and shadowed coat | Silent observer |
| Renegade | Crooked grin; one raised brow; asymmetric head profile | Worn leather jacket with one reinforced shoulder | Defiant rebel |
| Oracle | Calm face; smooth sweeping brow; focused eyes | Draped obsidian mantle with delicate inlaid seams | Patient visionary |
| Architect | Squared temples; precise geometric cheek plates | Ceramic alloy structured jacket and modular chest pieces | Methodical builder |
| Warden | Wide heavy brow; compact, imposing neck | Scarred steel armor with thick shoulder guards | Unyielding protector |
| Nomad | Weathered features; alert eyes; lean silhouette | Layered technical-fabric cloak and high collar | Resourceful traveler |
| Alchemist | Curious expression; asymmetric lens mount | Patinated copper harness with small sealed vessels | Experimental maker |
| Sovereign | Symmetrical face; elevated crown silhouette; steady gaze | Dark-gold trimmed mantle, restrained geometric regalia | Commanding leader |

Faces are distinct sculpts, not a recolored shared head. Each base sculpt includes the face and neck; headwear, eye equipment and clothing are separate only where edges and shadows align convincingly.

## Trait catalog

Each listed value is a unique design to make. Values may be limited by compatibility below; no rarity or production counts are implied. `None` is an empty slot; Puffles omits it from exported attributes, so audit the absence consistently. Lore details are tracked privately, so public attributes do not give away their location.

### Background Influence — exactly one

| Value | Design direction |
|---|---|
| Monolithic Architecture | One dark monumental wall with broad carved planes and a soft vertical light. |
| Industrial Machinery | A single out-of-focus machine housing with restrained steel forms. |
| Desert Landscape | One minimal dune horizon in muted sand and a dusty atmosphere. |
| Deep Ocean | A dark teal water column with faint suspended particles and no ruins or spacecraft. |
| Celestial Space | A restrained star field with one soft celestial glow and no terrestrial skyline. |
| Urban Night | One blurred city wall and sparse reflected night light; no readable signs. |

Choose one setting per image. Color, atmospheric light and the character's wearable lore do not add another setting.

### Headwear

- **None** — full base head visible.
- **Hood** — sculpted fabric arch that frames the face without covering eyes.
- **Visor** — raised, low-profile forehead plate; separate from eye lenses.
- **Crown** — restrained geometric points, centered and not touching the frame.
- **Helm** — protective shell with face opening, shaped to the specific head.

### Eyes

- **Natural** — visible expressive eyes with no equipment or supernatural glow.
- **Luminous** — visible eyes with subtle internal light and catchlights.
- **Masked** — opaque fitted eye mask; no visible eye underneath.
- **Lens** — single or paired optical lens with readable glass and frame.

### Garment

- **Armor** — rigid chest and shoulder plates with a dark flexible underlayer.
- **Coat** — tailored outer layer, lapels and seams, open enough to read the torso.
- **Robe** — draped front panels with layered fabric folds.
- **Harness** — structured straps and fittings over a fitted underlayer.
- **Mantle** — high-collared shoulder wrap with a clear central opening.

### Artifact

- **None** — no separate handheld or mounted object.
- **Ledger Plate** — small rectangular archival plate fixed to the chest.
- **Key** — original angular key suspended from a chest fitting.
- **Compass** — circular mechanical orientation instrument attached at the shoulder.
- **Order Book** — compact hinged artifact with paired columns of abstract marks.
- **Seal** — raised geometric medallion with a clean border.

Keep artifacts within the bust frame and clear of the face. Never present a made-up hash or address as a real ledger record.

### Material and palette

Material describes the dominant visible character surface: **Titanium**, **Smoked Glass**, **Leather**, **Obsidian**, **Ceramic Alloy**, **Steel**, **Technical Fabric**, **Copper**, or **Dark Gold**. Palette describes the dominant finished image color: **Obsidian** (charcoal), **Steel Blue**, **Ember**, **Verdigris**, **Ivory**, or **Imperial Gold**. Each must remain visually identifiable; color accents do not become extra palette values.

## Compatibility map

Defaults are starting points, not exclusive combinations. A renderer must make a compatible version for each head and garment. Avoid covering the defining face, eye trait or artifact. A crown is reserved for Sovereign standard editions and The Consensus Crown; helmets must be fitted to Sentinel or Warden. `None` is allowed for headwear and artifact on all types.

| Character type | Garment options | Headwear options | Eye options | Dominant material |
|---|---|---|---|---|
| Sentinel | Armor, Harness | None, Visor, Helm | Natural, Luminous, Lens | Titanium |
| Phantom | Coat, Mantle | None, Hood, Visor | Natural, Luminous, Masked | Smoked Glass |
| Renegade | Coat, Harness | None, Hood, Visor | Natural, Masked, Lens | Leather |
| Oracle | Robe, Mantle | None, Hood, Visor | Natural, Luminous, Masked | Obsidian |
| Architect | Armor, Coat, Harness | None, Visor | Natural, Luminous, Lens | Ceramic Alloy |
| Warden | Armor, Mantle | None, Visor, Helm | Natural, Luminous, Masked | Steel |
| Nomad | Coat, Robe, Mantle | None, Hood, Visor | Natural, Masked, Lens | Technical Fabric |
| Alchemist | Coat, Harness | None, Hood, Visor | Natural, Luminous, Lens | Copper |
| Sovereign | Armor, Robe, Mantle | None, Visor, Crown | Natural, Luminous, Masked | Dark Gold |

Artifacts and backgrounds are available across types only when the finished asset is visibly readable and lighting remains coherent. Palette may be selected independently, but reject combinations that erase the defining material. Implement rules in Puffles only after assets exist and verify previews; Puffles' exact rule capabilities and handling of no-trait slots must be checked in the studio.

## Four rare character art briefs

These are bespoke complete images, not layers randomly mixed with the standard collection. Each has a distinct pose and one background influence. Counts are exactly one each if adopted; no additional rarity claims are made.

1. **The First Witness** — Sentinel. A timeworn titanium guardian with a repaired chest plate, quiet forward gaze and a subtle `JUN 2012` inscription on the plate. Monolithic Architecture background. Source: lore L01.
2. **The Lost Ledger** — Phantom. Smoked-glass figure with a fractured collar and a tiny `32570` engraved on an archive plate. Deep Ocean background. This references the earliest available ledger, not the genesis ledger. Source: lore L04.
3. **The Consensus Crown** — Sovereign. Dark-gold leader whose crown contains distinct interlocking forms; an unobtrusive two-field `INDEX` / `HASH` engraving sits inside the collar. Celestial Space background. Source: lore L05. Crown is a metaphor, not a technical diagram of consensus.
4. **The Exchange Keeper** — Architect. Ceramic-alloy builder holding a small hinged order book with paired abstract columns. Industrial Machinery background. Source: lore L03; marks are illustrative, not real trade data.

## Production handoff

1. Sculpt nine base characters and render one approved master per type using the shared camera and lighting. Capture full-resolution and thumbnail reviews.
2. Produce fitted transparent variants for each compatible headwear, eyes, garment and artifact. Keep occlusion and shadow passes registered. Test compositing before making every combination; use finished renders where layer assembly degrades the 3D result.
3. Create six background masters. Label files using exact catalog values. Do not add invisible traits to metadata.
4. Create the four 1/1 masters separately; inspect engraved lore at full resolution and compare against [lore.md](lore.md).
5. Import an approved sample set to Puffles and test alignment, combinations and output. Record asset versions, rules and seed before a final build. Set counts only once collection supply is decided.

No finished trait images, Puffles project, rarity weights, collection supply or mint have been created by this document.
