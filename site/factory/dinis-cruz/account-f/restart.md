# Restart: place.sao-bras-de-alportel (São Brás de Alportel)

A new session starts here without losing anything:

1. Pull `dev`. Read this folder (`agent.json`, `role.md`, `now.md`), then `history/PROVENANCE.md` and the latest debriefs under `history/board/team/`.
2. Read `board/guidance/README.md` ("New from Dinis") in https://github.com/PrompTugal/PrompTugal__News__Website (public, read-only; never push there), above all the places rows.
3. Make or reuse your key, published in `site/keys/`; set the signing config (ssh format, your key, `commit.gpgsign true`); end every commit with `Agent:` and `Claude-Session:` trailers.
4. Read the live signals for São Brás de Alportel from their public sources, each with source URL and read time (`date -u`), into `data/by-place/now/sao-bras-de-alportel.json`; update `data/by-place/sao-bras-de-alportel.json`.
5. Rewrite `agent.json` and `now.md`, commit, push to `dev`.
