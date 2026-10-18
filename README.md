# EveryAyah recordings

Eight Hafs reciter collections containing original MP3 recordings and source verification records.

All 49,888 expected original archive ayah MP3s passed full macOS audio decoding, with zero failures and zero warnings. Original ZIP CRC, member hashes and whole-archive hashes were checked. This verifies media integrity; it does not mean every verse has been individually reviewed by a listener.

Four files are retained separately for review: Basfar 1:1 and Maher 1:1 have different archive/current-download versions; Minshawy 6:6 and Maher 29:63 match current source bytes but differ from the publisher MD5 entries. None failed decoding. See FILE-FLAGS.json and the detailed source comparison.

Five collections retain the publisher ZIPs, split into contiguous byte parts where necessary. Basfar, Minshawy and Maher use transport ZIPs containing unchanged original MP3 files, excluding only the four separately retained candidates. The eight main packages contain 49,884 ayah MP3s; the four candidates are in four-flagged-original-audio-candidates.zip.

For original ZIP parts, follow REASSEMBLY.json. For transport ZIP parts, follow PACKAGE.json. Concatenate parts in the recorded order and verify the complete archive hash before extraction.

Source records retain original URLs, HTTP validators where available, exact hashes, archive member dates and retrieval dates. Retrieval dates are distinct from publication dates.

Source: https://everyayah.com/data/
