# Fingerprints

Each entry is one line in the format `YYYY-MM-DD · <64-character SHA-256>`.

- The date is the day that week's manifest was sealed.
- The fingerprint is the SHA-256 of the manifest file, in lowercase hexadecimal.
- Entries are separated by a blank line and are only ever added at the end. None is edited or removed.
- An entry ending in `· TEST: procedure trial, not a record` is a procedure test and is not part of the record.

---
