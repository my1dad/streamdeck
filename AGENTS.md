# StreamDeck — official platform targets

Use only these. Do not create alternate remotes, Vercel projects, or Supabase projects.

| Role | Target |
| --- | --- |
| Git / pushes | https://github.com/my1dad/streamdeck.git (`origin`, branch `main`) |
| Deploy | Vercel team `my-dollar-a-day-server` (`team_IVNBcd2tFVDDvDoaqHlwiJOT`), project [`streamdeck`](https://vercel.com/my-dollar-a-day-server/streamdeck) (`prj_YAbmbxAC7cUxH1uYDqVTyJ1es12R`) |
| SQL / backend | https://qtmtxwjnipoxtqmxtwtb.supabase.co (ref `qtmtxwjnipoxtqmxtwtb`) |

`NEXT_PUBLIC_SUPABASE_URL` must always be `https://qtmtxwjnipoxtqmxtwtb.supabase.co`.

Never use `https://xrwvaelhmibhslmfvxrs.supabase.co`.

If Supabase MCP `get_project_url` is not `https://qtmtxwjnipoxtqmxtwtb.supabase.co`, stop and reconnect — do not run SQL.
