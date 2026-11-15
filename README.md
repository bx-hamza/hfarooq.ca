# hfarooq.ca → hfarooq.com

A two-file GitHub Pages site whose only job is to send every request for
`hfarooq.ca` (and `www.hfarooq.ca`) to the same path on `https://hfarooq.com`.

GitHub Pages allows one custom domain per repository, so this folder is
deployed as its own repository, separate from the main site. GitHub serves
the redirect page for any path (via `404.html`) and provisions the HTTPS
certificate for free.

See the root `README.md` for the DNS records and deploy steps.
