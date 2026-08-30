# Keyword consistency review — working vocabulary v0.9

This document records the full repository-wide consistency pass over the completed derived keyword assignments for `chinna-chinna-malargal`. Canonical transcription authority remains in `collections/<collection-id>/quotes/`; this review changes derived discovery metadata only.

## Scope and result

- Design reviewed: [`keyword-index-design.md`](keyword-index-design.md), version **0.1**
- Keyword batch files reviewed: **20**
- Quote range reviewed: `KQ-CCM-0001`–`KQ-CCM-0497`
- Quote rows reviewed: **497 / 497**
- Working vocabulary before review: **0.8 / 182 keys**
- Working vocabulary after review: **0.9 / 182 keys**
- Quote rows corrected: **21**
- Batch files with assignment corrections: **12**
- Vocabulary changes: **1 added stable key (`patience`) + 1 migration (`hindikkara-state` → `hindi-state`)**, with no net key-count change
- Canonical quote files changed by this pass: **none**
- Result: **consistency pass complete; ready for vocabulary freeze and consolidated keyword-index publication**

## Structural checks

The twenty batch files form one contiguous sequence from `KQ-CCM-0001` through `KQ-CCM-0497`: nineteen 25-quote batches followed by the 22-quote final batch.

The pass confirmed:

- **497 unique quote IDs**, with no gaps and no duplicates;
- every row contains **one to five** keyword keys;
- no row contains a duplicate keyword key;
- every assigned key exists in working vocabulary version **0.9**;
- PDF and printed-page values remain aligned with the canonical quote files;
- canonical verification states remain **496 `verified_from_scan`** and **1 `needs_review` (`KQ-CCM-0391`)**;
- `KQ-CCM-0391` remains indexed only from readable canonical content as `arrogance`; `speech`; its obscured terminal glyph remains unresolved and was not used to infer any keyword;
- no canonical quote text, punctuation, spelling, provenance or verification state was changed.

## Vocabulary consistency decisions

### Added key: `patience`

Repeated explicit `பொறுமை` had been represented inconsistently by the broad `character` key in earlier batches and by `self-restraint` in later batches. Because the concept recurs materially and is distinct from both measured action-restraint and continuing effort, version 0.9 adds:

- `patience` — `பொறுமை` — patience/forbearance explicitly expressed as `பொறுமை`, especially bearing provocation, pressure or delay without immediate reaction.

The six affected rows are `KQ-CCM-0183`, `KQ-CCM-0291`, `KQ-CCM-0292`, `KQ-CCM-0402`, `KQ-CCM-0431` and `KQ-CCM-0467`.

### Migration: `hindikkara-state` → `hindi-state`

`hindikkara-state` was a one-off key created solely to preserve the surface formulation `இந்திக்கார ராஜ்யமே` in `KQ-CCM-0124`, while `hindi-state` already represented the closely equivalent political formulation `இந்தி ராஜ்யம்` in `KQ-CCM-0074`. The keyword design forbids near-duplicate conceptual keys created only from lexical variation, while canonical wording itself must remain untouched.

Version 0.9 therefore retires `hindikkara-state`, broadens the discovery scope of `hindi-state` to cover both explicit formulations, and migrates the `KQ-CCM-0124` row. The canonical quote file continues to preserve `இந்திக்கார ராஜ்யமே` verbatim.

## Assignment corrections

| Quote ID | Previous keyword assignment | Corrected keyword assignment | Consistency reason |
|---|---|---|---|
| `KQ-CCM-0015` | `basic-needs`; `housing`; `freedom` | `basic-needs`; `food`; `housing`; `freedom`; `slavery` | The canonical text explicitly lists food, clothing and housing and directly contrasts a free country with a slave country. `food` became available later; `slavery` was already a stable key and had been omitted. |
| `KQ-CCM-0077` | `scientific-achievement`; `god` | `scientific-achievement`; `god`; `mythology` | The Vamana-incarnation story is materially invoked in the canonical comparison; the later stable `mythology` key now captures it without importing outside detail. |
| `KQ-CCM-0081` | `fame` | `publicity` | The source explicitly says the person publicized himself. The later `publicity` key is more precise than the earlier broad fame assignment. |
| `KQ-CCM-0124` | `hindu-state`; `hindikkara-state`; `national-unity` | `hindu-state`; `hindi-state`; `national-unity` | One-off lexical duplicate migrated under the version 0.9 vocabulary rule; canonical `இந்திக்கார ராஜ்யமே` remains unchanged. |
| `KQ-CCM-0131` | `arrogance` | `arrogance`; `birds` | The sparrow is a central literal subject in the elephant comparison; the later stable `birds` key now records it without inferring an unstated human referent. |
| `KQ-CCM-0142` | `rationalism` | `astrology` | Palm-line reading is the explicit predictive/fortune-reading practice. The later precise divination key is better supported than the broader earlier rationalism fallback. |
| `KQ-CCM-0154` | `appearance`; `character` | `appearance`; `character`; `clouds` | Clouds taking multiple forms are the central explicit natural image; the later stable `clouds` key now applies directly. |
| `KQ-CCM-0183` | `character`; `jealousy` | `patience`; `jealousy` | Explicit `பொறுமை` is standardized to the new dedicated key rather than the broad character fallback. |
| `KQ-CCM-0200` | `wrongdoing`; `forgiveness` | `wrongdoing`; `forgiveness`; `rebirth` | Another birth is materially part of the canonical proposition; the stable `rebirth` key was introduced later. |
| `KQ-CCM-0211` | `money`; `violence` | `money`; `violence`; `women` | The canonical text explicitly describes dowry cruelty burning women; women are a materially affected social group. |
| `KQ-CCM-0218` | `rationalism`; `social-reform`; `art` | `superstition`; `social-reform`; `art` | The source explicitly names `மூடநம்பிக்கைகள்`; the later precise `superstition` key replaces an inferred rationalism label. |
| `KQ-CCM-0252` | `talent` | `talent`; `birds` | Chicken and pigeons are the complete literal flight comparison; the later stable bird key is directly supported. |
| `KQ-CCM-0259` | `equality` | `equality`; `women` | Male/female distinction and society's discriminatory treatment are explicit; the later `women` key records the gendered social condition. |
| `KQ-CCM-0273` | `deception`; `credulity` | `astrology`; `deception`; `credulity` | `ஆரூடம்` is explicitly named, so the stable divination key belongs alongside deception and credulity. |
| `KQ-CCM-0286` | `credulity` | `astrology`; `credulity` | The canonical text explicitly calls the lizard-cry belief `ஆரூடம்`; `astrology`/divination is therefore directly supported. |
| `KQ-CCM-0287` | `talent`; `equality` | `talent`; `equality`; `rebirth` | The source explicitly rejects talent as a `பூர்வஜென்ம பலன்`; the prior-birth proposition is directly recoverable. |
| `KQ-CCM-0291` | `character`; `jealousy`; `candle`; `fire` | `patience`; `jealousy`; `candle`; `fire` | Explicit `பொறுமை` is standardized to `patience`. |
| `KQ-CCM-0292` | `character`; `struggle`; `history`; `fire` | `patience`; `struggle`; `history`; `fire` | Explicit `பொறுமை` is standardized to `patience` while retaining the stated revolution/history/volcano frame. |
| `KQ-CCM-0402` | `self-restraint` | `patience`; `fire` | Long-contained `பொறுமை` is the direct concept; the erupting-volcano image is central and is aligned with the existing `fire` treatment of the same image elsewhere. |
| `KQ-CCM-0431` | `self-restraint` | `patience` | The source explicitly calls patience the shield against insults; this is more precise than general action-restraint. |
| `KQ-CCM-0467` | `duty`; `self-restraint`; `fire` | `duty`; `patience`; `fire` | Responsibility-aware `பொறுமை` is explicit and is standardized to the dedicated key. |

## Boundary decisions retained

The pass also re-read representative borderline assignments so that consistency work would not turn into over-indexing:

- `capitalism` remains limited to quotations that explicitly name `முதலாளித்துவம்`; references only to a `முதலாளி வர்க்கம்` or private-capital dominance, including `KQ-CCM-0248` and `KQ-CCM-0394`, retain the more directly supported class/labour keys.
- `emotion` is not backfilled merely from tears or smiling in `KQ-CCM-0264`; the source does not explicitly name a general emotion concept there.
- `astrology` is not assigned to `KQ-CCM-0164` solely from the culturally recognizable role of the `குடுகுடுப்பைக்காரன்`; the canonical wording does not itself identify the practice as astrology, omen-reading or divination.
- `women` is not redundantly added where a more specific women's-rights key already captures the explicit issue, such as `women-property-rights` in `KQ-CCM-0042`, and is not added merely because one individual woman appears without a group/condition proposition.
- `birds`, `clouds`, `trees`, `fire` and other natural-object keys remain limited to materially central explicit images rather than every incidental metaphorical noun.
- `modesty`, `humility`, `patience`, `self-restraint`, `resolve` and `perseverance` remain distinct: each now has a separate boundary based on the canonical concept actually stated.
- `credulity`, `superstition`, `astrology` and `rationalism` remain distinct; more precise later keys replace broad fallback assignments only where the canonical text directly supports them.

## Verification-state preservation

The pass did not alter source verification. `KQ-CCM-0391` remains the sole `needs_review` record. Its keyword row continues to use only the readable canonical content (`arrogance`; `speech`), and the obscured terminal glyph after the recorded readable text remains neither reconstructed nor used as metadata evidence.

## Next publication gate

The consistency requirement in [`keyword-index-design.md`](keyword-index-design.md) is now satisfied. The next activity is to:

1. freeze the consistency-reviewed controlled vocabulary as **version 1.0**;
2. publish the consolidated [`keyword.md`](keyword.md) index covering all **497 / 497** quote assignments;
3. retain all twenty sequential batch files and this review as audit history;
4. update [`README.md`](README.md) and the design status to record final publication.

No consolidated keyword index is published by this consistency-pass commit itself.