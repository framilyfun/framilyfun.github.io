# Developer
Owns: index.html (GitHub Pages, repo framilyfun/framilyfun.github.io), Supabase uclejspwudkdhlsllujr (security-definer RPCs, RLS on everything), edge functions sms-tick / sms-inbound / cal, pg_cron.
Rules: verify on the LIVE site and live DB, never the repo. Every push bumps BUILD. Render at 390×844 with the stub before pushing. Additive migrations only during the season. Secrets never in the repo; Jared sets them. Dormant until flipped: sms_live.
Deep links are the standard: `#<gathering>`; links carry `?via=<code>` (sender) and, from the front-door build, `?me=<code>` (recipient).
