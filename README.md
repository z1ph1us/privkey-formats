# privkey-formats

Regex patterns for the private-key and seed-phrase formats used across common
blockchains. Each pattern is anchored and matches the encoded key string only.

See [`formats.txt`](formats.txt) for the full list, grouped by family (raw hex,
Bitcoin WIF, altcoin WIF, BIP32 extended keys, other chains). Example strings with keys
are included as comments.

## Notes
Patterns match format, not validity — a match is not a checksum-valid key.
