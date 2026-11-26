# PATH pilot

Static pages, no server, no data stored online.

- `/` — PATH Lite: the teen's assessment, daily check-in and results. Answers stay in the teen's browser.
- `/rater/#<CHILD-CODE>` — story form for raters. Produces a code the rater sends to the parent by WhatsApp.

- `/collector/` — the parent's collector page. Gathers rater codes and produces one child code. Stored only in the parent's browser; nothing is sent anywhere.

Codes are obfuscated, not encrypted.
