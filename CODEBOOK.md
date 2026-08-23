# Codebook

The file `data/citation-register.csv` contains 48 research records and 11 fields.

| Field | Meaning |
|---|---|
| `speaker` | Writer, speaker, or attributed author associated with the record. Pseudonymous or disputed attributions are retained cautiously. |
| `date` | Date attached to the document or event in the documentary source. |
| `document` | Letter, essay, convention speech, research note, or bounded-search record. |
| `source_url` | Stable or scholarly access point used to verify the record where available. |
| `classical_episode` | Ancient figure, institution, episode, or political comparison relevant to the record. |
| `likely_channel` | Intermediary/source route when it can be established or responsibly inferred; uncertainty is preserved. |
| `rhetorical_use` | Detailed description of how the material functions in context. |
| `notes` | Research notes, quotation context, limitations, or interpretive cautions. |
| `record_status` | Whether the row is active evidence or a bounded no-hit/search-status record. |
| `use_primary` | Normalized high-level use code such as `cautionary`, `aspirational`, `analytical`, `research_process`, or `absent`. |
| `verification_status` | Provenance/verification category for the evidence or search result. |

## Coding cautions

The register is not a probability sample. `use_primary` is an interpretive normalization, not an objective measurement. `likely_channel` is sometimes a documented source chain and sometimes a qualified inference; the wording of the field and notes should be read together. A bounded no-hit means only that no relevant use was located within the defined search, not that no such reference exists anywhere in the historical record.
