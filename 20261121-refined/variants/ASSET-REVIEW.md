# PM.MARKET — variant image review, 21 November 2026

## Accepted asset scope

The compact release at commit `a4c418973856d0d7f106a127d1bb7d99215f3a38` contains 26 new JPEG infographics for 28 native variant UIDs. Each accepted generated PNG was visually checked against its owner-provided source photograph and native variant caption. JPEGs are 1254 × 1254, converted by ImageMagick without drawing, label replacement, or resizing. The PNG masters are preserved separately.

Twenty-five variants match the visible configuration/diameter/zone on their existing owner sources. This is correspondence to supplied photographs, not a physical inspection of current warehouse stock. Generated artwork is not photographic proof: the original owner image must remain in the live gallery alongside it. Full pixel identity of fine packaging print or QR codes has not been certified.

The three Classic variants below lack a visible exact SKU label. The common image explicitly says «Пример упаковки серии» and gives only the verified native family diameters 0.25 / 0.30 / 0.35 mm. Their exact physical-photo HOLD remains open.

| Variant UID | Native variant | Photo status |
|---|---|---|
| 694387810412 | Kwadron Classic 25/1RL | HOLD — exact SKU photo required |
| 185708344162 | Kwadron Classic 30/1RL | HOLD — exact SKU photo required |
| 128346466142 | Kwadron Classic 35/1RL | HOLD — exact SKU photo required |

## Corrected source associations

The old registry linked BROVI `100921419552` (30/1 RLMT(S), lips) to a brown brow 1RLLT(H) source. The accepted source is the real pink lip box already present in the parent gallery, visibly labelled 1RLMT(S) 0.30. Defender `579821214422` (30/1RLMT) previously pointed at the 35/1RLLT source. The accepted source is the existing owner image labelled #30 30/01RLMT, including its visible pen mark. No factory SKU label was changed to make a source fit.

BROVI `924933247602` carries `(S)` in the native catalogue name. Its source label reads 3 RSLT 0.25 without that suffix. The caption keeps the native name; `(S)` was not added to the pictured factory label.

`variant-source-claims-v2.json` is the current provenance manifest. It explicitly corrects two Boolean metadata flags from the immutable v1 manifest. JPEG bytes, original source URLs, and hashes are unchanged. The v1 manifest and upload intents remain available for audit.

## Publication boundary

All 26 JPEGs were uploaded once in four native Tilda image batches of 8 / 8 / 8 / 2, at most two batches concurrently. Per-batch intent was saved before dispatch. All returned CDN files matched accepted JPEG bytes by SHA-256. Uploads were unattached; this asset task wrote no catalogue Photo, price, stock, variant, taxonomy, or text fields. Catalogue binding and its native before/after verification are separate coordinated operations.

The binding receipt maps all 28 variant UIDs to a new CDN image and the correct owner original. Do not claim live publication solely from the upload receipt. After the catalogue phase, use the actual native after snapshot to verify each full gallery.

## Old images and gallery preservation

The pinned gallery plan removes 40 specifically reviewed misleading rasters if they are present. It preserves 27 existing owner originals and one neutral legacy Defender image. It must not delete other URLs introduced by an independently verified parent-cover phase. The old raster bytes are archived with a URL/SHA manifest; existing public asset paths are not renamed or removed.

## Files

- `variant-source-claims-v2.json`: accepted assets, source provenance, limits, and 28 UID bindings.
- `variant-native-cdn-bindings.json`: 26 CDN byte-verified images, 28 corrected bindings, and three remaining HOLDs.
- `variant-native-upload-receipts.json`: original intents, responses, and CDN verification evidence.
- `variant-github-readback.json`: immutable GitHub image URL/hash checks.
- `gallery-remediation-plan.json`: pinned 40-image blacklist and precise keep sets.
- `generation-prompts.json`: per-image requests and source-reference definitions.
- `master-preservation.json` and `masters/`: PNG retention metadata and original generated masters.

CRM photo statuses may be updated only after the coordinated native Photo after verifies the actual catalogue bindings. The earlier 18 uncertain product photos and the low-resolution Fresh Greens source remain separately qualified.
