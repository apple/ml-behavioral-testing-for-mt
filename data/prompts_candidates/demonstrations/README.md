Notes
=====

- For `numbers_decimal` and `numbers_integer`, separate candidate sets were generated for textual and numerical formats. These were then merged for pass-rate computation.
- Similarly, `physical_units` were merged from `symbol` and `textual` forms.
- Candidate sets for `names` were only generated for Japanese where transliteration is needed; elsewhere, the candidate set was set to contain only the source side (i.e., expecting an exact copy of the source word).
- Similarly for emoji, no candidate sets were generated. Instead, the source-side emoji are expected to be copied over unchanged.