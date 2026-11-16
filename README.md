# Sirius CX Dashboard (demo mock-up)

Static, single-page dashboard styled like an Atlassian/Jira dashboard, built for the Cyberdyne x Sirius
Atlassian demo. All data is illustrative and lives in the `DATA` object at the top of the script in `index.html`.

- Press **R** or click **Refresh** to toggle between "before" (Maya's case open, incident PSO-6 open)
  and "after" (case resolved, incident closed, CSAT +1). Or open `?state=after`.
- No build step. Deploy on Vercel as a static site (framework preset: Other).

## Help center + AI agent scenario (`/helpcenter`)

`helpcenter.html` simulates Maya's chat with the Sirius Care AI agent on the Sirius Help Center, then the handoff to Ava.
Controls: → or Space = next message, A = auto-play, B = "Behind the scenes" panel, R = restart, H = hide controls.
Edit the `SCRIPT` array to change the conversation; `CASE` and `INCIDENT` hold the work item keys.
