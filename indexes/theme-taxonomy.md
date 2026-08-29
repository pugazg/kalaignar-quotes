# Theme taxonomy

This file defines the controlled vocabulary for the repository's **derived theme index**. It is a discovery aid only. Canonical transcription authority remains in `collections/<collection-id>/quotes/`.

## Status

- Taxonomy version: **1.0**
- Scope: `chinna-chinna-malargal`
- Canonical quote range available for classification: `KQ-CCM-0001`–`KQ-CCM-0497`
- Theme assignment: **in progress — classified through `KQ-CCM-0050` (50 / 497)**
- Next classification batch: `KQ-CCM-0051`–`KQ-CCM-0075`
- Source verification states remain unchanged by classification: **496 `verified_from_scan`**, **1 `needs_review` (`KQ-CCM-0391`)**

## Classification principles

1. Classify from the **canonical quote text itself**. Do not use outside biography, historical context, modern political interpretation, OCR guesses, or inferred authorial intent to force a theme.
2. Theme labels are derived metadata and must never alter spelling, punctuation, wording, page provenance, quote IDs, or verification status.
3. Every classified quote receives exactly **one primary theme**.
4. A quote may receive **zero to two secondary themes** when the text clearly and independently supports them.
5. Choose the primary theme from the quote's dominant proposition, not merely from a passing example, metaphor, proper noun, or named institution.
6. Do not assign a theme solely because a named person, party, religion, language, or institution appears. The quoted statement must materially concern that subject.
7. When a quote is genuinely cross-cutting, prefer the most specific supported theme as primary and use a secondary theme rather than creating a new ad-hoc category.
8. If no controlled theme fits without interpretation, use `T16-other-unclear` and record a short classification note. Do not invent a meaning to avoid the fallback.
9. `KQ-CCM-0391` may be theme-classified only from its readable canonical content; classification must continue to preserve its `needs_review` state and must not imply resolution of the obscured terminal glyph.
10. Theme taxonomy changes require a version increment and a migration note before existing assignments are rewritten.

## Controlled themes

| ID | Stable key | Tamil label | Scope |
|---|---|---|---|
| `T01` | `social-justice-equality` | சமூகநீதி மற்றும் சமத்துவம் | Caste, social hierarchy, equality, reservation, representation, discrimination, dignity of disadvantaged communities, and removal of social exclusion. |
| `T02` | `rationalism-religion-superstition` | பகுத்தறிவு, மதம் மற்றும் மூடநம்பிக்கை | Rational inquiry, atheism/theism, religion, gods, temples, ritual, superstition, religious fanaticism, and criticism or defence of belief as discussed in the quote. |
| `T03` | `tamil-language-identity` | தமிழ், மொழி மற்றும் இனஅடையாளம் | Tamil language, linguistic rights, Tamil identity, language policy, cultural-linguistic belonging, and explicit Tamil ethnic/community identity. |
| `T04` | `movement-party-organization` | இயக்கம், கட்சி மற்றும் அமைப்பு | Political/social movements, party organization, cadre or membership, collective discipline, internal organization, movement continuity, and explicit organizational identity including the Dravidian movement/DMK where the quote materially concerns the organization. |
| `T05` | `democracy-governance-federalism` | ஜனநாயகம், ஆட்சி மற்றும் கூட்டாட்சி | Democracy, government, ruling/opposition roles, public administration, state power, elections, federalism/state autonomy, and institutional governance. |
| `T06` | `political-ethics-power-public-life` | அரசியல் நெறி, அதிகாரம் மற்றும் பொதுவாழ்வு | Conduct in politics/public life, office, power, opportunism, corruption, leadership ethics, political responsibility, and behaviour of public actors. |
| `T07` | `law-rights-justice` | சட்டம், உரிமை மற்றும் நீதி | Law, courts, legal process, rights, punishment, justice, injustice, constitutional/legal protection, and explicit claims about lawful or unlawful action. |
| `T08` | `ideals-commitment-struggle` | இலட்சியம், உறுதி மற்றும் போராட்டம் | Ideals, principles, perseverance, sacrifice, resistance, struggle, courage in pursuit of a cause, and remaining committed despite defeat or repression. |
| `T09` | `human-values-dignity-character` | மனிதநேயம், தன்மானம் மற்றும் பண்பு | Humaneness, self-respect, integrity, gratitude, humility, honesty, patience, compassion, moral character, and general ethical conduct not primarily political or legal. |
| `T10` | `friendship-loyalty-betrayal` | நட்பு, நம்பிக்கை மற்றும் துரோகம் | Friendship, loyalty, trust, betrayal, interpersonal faithfulness, and the moral consequences of disloyalty. |
| `T11` | `labour-poverty-economic-justice` | உழைப்பு, ஏழ்மை மற்றும் பொருளாதார நீதி | Labour, workers, poverty, wealth, material inequality, exploitation, economic hardship, production, and distribution of resources. |
| `T12` | `education-knowledge-literature-art-media` | கல்வி, அறிவு, இலக்கியம், கலை மற்றும் ஊடகம் | Education, learning, knowledge, science as knowledge practice, books, literature, poetry, art, writing, speech, journalism, press, and communication as the central subject. |
| `T13` | `family-love-gender-relations` | குடும்பம், காதல் மற்றும் பாலின உறவுகள் | Family, marriage, love, spouses, parents/children, women/men, gender relations, and domestic or intimate relationships when central to the quote. |
| `T14` | `life-death-time-experience` | வாழ்க்கை, மரணம், காலம் மற்றும் அனுபவம் | Life, death, ageing, time, memory, experience, fate, impermanence, and reflections on the course or meaning of human life. |
| `T15` | `nature-science-metaphor` | இயற்கை, அறிவியல் மற்றும் இயற்கை உருவகம் | Nature, animals, plants, weather, physical phenomena, scientific observation, or a natural-world comparison when that comparison itself is central to the statement. Use as secondary when nature is only a vehicle for another dominant theme. |
| `T16` | `other-unclear` | பிற / தெளிவற்றது | Fallback only when no other controlled theme fits without unsupported interpretation. Requires a short classification note. |

## Boundary rules

### `T01` vs `T07`

Use `T01` when the core claim is about social hierarchy, caste, equality, reservation, representation, or exclusion. Use `T07` when the core claim is about legal rights, courts, punishment, or justice as a legal/institutional principle. A quote may carry both when both are explicit.

### `T04` vs `T06`

Use `T04` for the functioning, identity, discipline, continuity, or membership of a movement/party/organization. Use `T06` for political conduct, opportunism, office, power, corruption, or public ethics. Merely naming a party does not make `T04` primary.

### `T05` vs `T07`

Use `T05` for governance, state institutions, democracy, ruling/opposition functions, federalism, or administration. Use `T07` for law, legal rights, punishment, courts, or justice. If a law is discussed mainly as an instrument of government, `T05` may be primary and `T07` secondary.

### `T08` vs `T09`

Use `T08` when courage, sacrifice, perseverance, or commitment is tied to an ideal, cause, movement, or struggle. Use `T09` for general personal character or ethics without a cause-oriented struggle.

### `T12` vs `T15`

Use `T12` for science as knowledge, education, learning, literature, art, writing, or media. Use `T15` for natural phenomena or scientific/natural observation used as subject matter or metaphor. If a nature image only illustrates another point, make `T15` secondary or omit it.

## Assignment record format

The theme index should use one row per quote with stable machine-readable keys:

```text
Quote ID | Primary theme | Secondary theme(s) | PDF | Printed | Verification status | Classification note
```

Secondary themes should be stored as zero, one, or two stable keys separated consistently. The classification note should normally be blank and used only for boundary decisions, `T16-other-unclear`, or other cases that would otherwise be difficult to audit.

## Review protocol

Theme assignment should proceed in small sequential batches. After each batch:

- confirm every quote ID in the batch appears exactly once;
- preserve the canonical verification state;
- check primary/secondary theme keys against this controlled vocabulary;
- review borderline assignments against the boundary rules above;
- never edit canonical quote text as part of thematic classification.

After all 497 quotes are classified, perform a full consistency pass for duplicate IDs, missing IDs, invalid theme keys, overuse of `T16-other-unclear`, and inconsistent primary/secondary choices before publishing the consolidated theme index.
