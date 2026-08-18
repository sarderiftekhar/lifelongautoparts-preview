# LifeLong Auto Parts — preview build

A **static preview** of lifelongautoparts.com, published so the work in
progress can be reviewed in a browser. This repository holds built output
only; the source lives in a private repository.

**This is not a live site.**

- Every page is `noindex, nofollow` and `robots.txt` disallows all crawling.
- Warranty figures on it are template values, marked as placeholders. None of
  them come from a signed warranty contract, and none are commitments.
- The company's registered legal entity and phone number are not yet confirmed
  and render as placeholders.
- `/admin` and the quote submission endpoint are absent — they need a server
  and a database, which a static preview does not have. The quote form will
  walk through its steps but cannot submit.

Rebuilt with `node scripts/build-preview.mjs` from the source repository.
