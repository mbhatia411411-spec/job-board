# Role Triage — live board

Static front-end for a personal job-search agent. Contains no credentials: the
page requires an access token (supplied in the URL fragment on first visit and
kept in browser storage), and all data comes from token-gated Supabase edge
functions. Source of truth is the private repo `job-search-agent`.
