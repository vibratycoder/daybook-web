# Daybook — public site

Static pages for the Daybook app, served by GitHub Pages at
<https://vibratycoder.github.io/daybook-web/>.

- `privacy.html` — privacy policy (linked from the App Store listing and in-app)
- `email-confirmed.html` — landing page for the Supabase sign-up confirmation link
  (`emailRedirectTo` in `src/app/sign-in.tsx` of the private app repo)
- `index.html` — redirects to the privacy policy

Source of truth for these files is the `docs/` folder of the private `Notle` repo;
copy changes here and push to publish.
