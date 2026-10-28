# the-quant (redirect)

This repository is only a redirect. The Quant Sports, the landing page for the sports analytics sites, moved on
28 October 2026 from https://pchattani.github.io/the-quant/ to https://pchattani.github.io/the-quant-sports/
(repository `pchattani/the-quant-sports`, built by `pchattani/quant-sports`).

- `index.html` sends `/the-quant/` to `/the-quant-sports/`, keeping the query string and hash.
- `404.html` does the same for deeper paths, keeping the path after `/the-quant/`.

Both fall back to a meta refresh and a visible link when JavaScript is off.

The name `the-quant` is reserved for The Quant umbrella (projects beyond sports); this redirect will be replaced then.
