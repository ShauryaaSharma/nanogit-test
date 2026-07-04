# Lore — sample decisions

A couple of made-up "decisions" so Lore has something concrete to remember from
this PR.

- **Decision:** Store PR titles, bodies, and review threads (not just titles).
  **Why:** the richest "why" usually lives in the review discussion.
- **Decision:** Scope memory per GitHub account, keyed as `gh:<login>`.
  **Why:** so one org's Canon never leaks into another's, while every repo under
  an account stays searchable together.
- **Decision:** Strip bot boilerplate (Vercel deploy comments) before storing.
  **Why:** base64 status blobs poison the embeddings and hurt recall.
