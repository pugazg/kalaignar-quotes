# Theme consistency review — taxonomy v1.0

This document records the full consistency pass over the completed quote-level theme classification for `chinna-chinna-malargal`. It is **derived index metadata only**. Canonical transcription authority remains in `collections/<collection-id>/quotes/`.

## Scope and result

- Taxonomy version reviewed: **1.0**
- Theme batch files reviewed: **20**
- Quote range reviewed: `KQ-CCM-0001`–`KQ-CCM-0497`
- Quote rows reviewed: **497 / 497**
- Result: **pass complete; consolidated theme-index publication may proceed**
- Canonical quote files changed by this pass: **none**

## Structural checks

The twenty batch files form one contiguous sequence from `KQ-CCM-0001` through `KQ-CCM-0497`: nineteen 25-quote batches followed by the 22-quote final batch.

The pass confirmed:

- **497 unique quote IDs**, with no gaps and no duplicates;
- exactly **one primary theme** for every quote;
- **zero to two secondary themes** for every quote;
- every primary and secondary theme key belongs to the 16 stable keys defined in [`theme-taxonomy.md`](theme-taxonomy.md);
- canonical verification states remain **496 `verified_from_scan`** and **1 `needs_review` (`KQ-CCM-0391`)**;
- `KQ-CCM-0391` remains classified only from its readable canonical content and the unresolved terminal glyph is not resolved, normalized or promoted by theme work.

## Fallback review

Only **3 / 497** quotes use `other-unclear`, so the fallback is not overused. Each was re-read against its canonical quote file and retained:

| Quote ID | Decision | Reason |
|---|---|---|
| `KQ-CCM-0306` | retain `other-unclear` | Periyar, Anna and “we” are expressed through a sculpture/model relationship, but the text itself does not explicitly name a movement or another controlled subject without outside context. |
| `KQ-CCM-0343` | retain `other-unclear` | The text contrasts attention paid to sounds from a cheaper bullock cart and a costlier motor vehicle, but it states no broader economic, political or character proposition that can be assigned without inference. |
| `KQ-CCM-0403` | retain `other-unclear` | The text says only generic `இன உணர்வு`; it does not explicitly identify Tamil identity, a legal right, a movement or another controlled subject. The elephant/ant comparison remains a supported secondary theme. |

## Consistency corrections

The pass found **13 assignment inconsistencies**. The dominant pattern was over-extension of `ideals-commitment-struggle` to general courage, resolve, self-reliance or a purely physical image without an explicit ideal, cause, movement or struggle. This conflicts with the taxonomy's `T08` vs `T09` boundary and with the rule against inferring an unstated referent.

| Quote ID | Previous assignment | Corrected assignment | Consistency reason |
|---|---|---|---|
| `KQ-CCM-0048` | primary `ideals-commitment-struggle`; secondary `nature-science-metaphor`, `life-death-time-experience` | primary `life-death-time-experience`; secondary `nature-science-metaphor` | The text explicitly contrasts perishable bodies with histories that outlast destruction; no ideal or cause is stated. |
| `KQ-CCM-0059` | primary `ideals-commitment-struggle`; secondary `life-death-time-experience` | primary `human-values-dignity-character`; secondary `life-death-time-experience` | Bravery and cowardice are presented as general character qualities, not as courage tied to a stated cause. |
| `KQ-CCM-0067` | primary `ideals-commitment-struggle`; secondary `nature-science-metaphor` | primary `human-values-dignity-character`; secondary `nature-science-metaphor` | Inner firmness versus fear is a general character proposition; no ideal or cause is stated. |
| `KQ-CCM-0097` | primary `ideals-commitment-struggle`; secondary `nature-science-metaphor` | primary `nature-science-metaphor`; no secondary | Stove, fire, pot, heat and rice are the complete explicit scene; a human or cause-oriented referent would be inferred rather than stated. |
| `KQ-CCM-0125` | primary `ideals-commitment-struggle`; secondary `nature-science-metaphor` | primary `human-values-dignity-character`; secondary `nature-science-metaphor` | Inner resolve for passing through hardship is general character; no cause or ideal is named. |
| `KQ-CCM-0146` | primary `ideals-commitment-struggle`; no secondary | primary `nature-science-metaphor`; no secondary | The canonical text is the running/jumping maxim itself; it does not state the broader cause-oriented meaning required for `T08`. |
| `KQ-CCM-0177` | primary `human-values-dignity-character`; secondary `ideals-commitment-struggle` | primary `human-values-dignity-character`; no secondary | Courage and prudence are explicit general character qualities; victory alone does not establish a cause or ideal. |
| `KQ-CCM-0179` | primary `ideals-commitment-struggle`; secondary `life-death-time-experience` | primary `life-death-time-experience`; secondary `education-knowledge-literature-art-media` | The quote itself is about enduring historical memory after defeat; assigning a cause would depend on outside history. |
| `KQ-CCM-0241` | primary `ideals-commitment-struggle`; secondary `family-love-gender-relations`, `nature-science-metaphor` | primary `human-values-dignity-character`; secondary `family-love-gender-relations`, `nature-science-metaphor` | Success through one's own action is a self-reliance/character proposition; no ideal or cause is stated. |
| `KQ-CCM-0262` | primary `ideals-commitment-struggle`; secondary `human-values-dignity-character` | primary `human-values-dignity-character`; no secondary | A self-presented extremist collapsing before money is an explicit hypocrisy/weakness judgment; no specific principle or cause is named. |
| `KQ-CCM-0275` | primary `ideals-commitment-struggle`; secondary `human-values-dignity-character` | primary `human-values-dignity-character`; no secondary | Grand heroic vows collapsing before money are a character-consistency criticism without a stated ideal or cause. |
| `KQ-CCM-0359` | primary `ideals-commitment-struggle`; secondary `human-values-dignity-character` | primary `human-values-dignity-character`; no secondary | Hesitation versus determined confidence before defeat or victory is a general character contrast. |
| `KQ-CCM-0453` | primary `education-knowledge-literature-art-media`; secondary `ideals-commitment-struggle`, `human-values-dignity-character` | primary `education-knowledge-literature-art-media`; secondary `human-values-dignity-character` | The younger generation is urged to learn, act and work deeply, but no explicit ideal, cause, movement or struggle supports `T08`. |

No taxonomy key was added, removed or redefined; taxonomy version **1.0** therefore remains unchanged.

## Boundary review

The pass rechecked the explicit taxonomy boundaries across all twenty batches:

- `social-justice-equality` vs `law-rights-justice`: assignments consistently keep caste, hierarchy, representation and reservation centered in social justice while using legal rights/law as primary only when the legal claim itself dominates.
- `movement-party-organization` vs `political-ethics-power-public-life`: organization identity, discipline and continuity remain distinct from office, opportunism, corruption and conduct in power.
- `democracy-governance-federalism` vs `law-rights-justice`: governance/state structure remains distinct from law, punishment and legal rights.
- `ideals-commitment-struggle` vs `human-values-dignity-character`: the 13 corrections above remove the identified cases where general courage, resolve or self-reliance had been treated as cause-oriented commitment.
- `education-knowledge-literature-art-media` vs `nature-science-metaphor`: science/learning/literature remains distinct from natural or physical observations and comparisons; the corrections to `KQ-CCM-0097` and `KQ-CCM-0146` also enforce the no-inference rule for purely explicit physical imagery.

## Publication readiness

After the corrections recorded above, quote-level theme assignments are structurally complete and internally consistent under taxonomy version 1.0. The next theme-index activity is to publish the **consolidated theme index** for all `KQ-CCM-0001`–`KQ-CCM-0497` assignments, while continuing to preserve `KQ-CCM-0391` as `needs_review`.
