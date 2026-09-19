# Integrity

Version integrity is a requirement the framework places on itself (§15.3): a copy
that cannot be checked is a copy that can be quietly altered. The digest below is
the authority for whether a copy of v0.51 is intact.

| | |
|---|---|
| File | [`FUCKERY.md`](FUCKERY.md) |
| Version | v0.51 |
| Dated | 2026-09-10 |
| sha256 | `f58bb3071cc3eb94f4955557563a5a4f962d12960bacfd82768fff8e708c3bcb` |
| Size | 63,500 bytes · 540 lines · UTF-8 · LF |

Verify any copy before citing it:

```bash
sha256sum FUCKERY.md
```

A copy whose digest does not match that string is not v0.51, whatever its header says.

## Record

Two things happened to this file that are worth stating rather than erasing, because
§15.2 forbids silent edits and that has to apply to corrections as well.

1. **The digest was retracted, and the retraction was wrong.** An intermediate revision
   of the README removed the sha256 above, on the reasoning that it could not have been
   computed from the file. It had been. Running `sha256sum` over the author's copy
   returns exactly that digest, at exactly that size. It was restored.
2. **The file was renamed.** It was committed as `CANON.md` and is now `FUCKERY.md`.
   The bytes are unchanged, which the digest proves.
