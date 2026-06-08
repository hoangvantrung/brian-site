# brian.vn site

Static website for `brian.vn`, deployed with GitHub Pages.

## Files

- `index.html`: landing page
- `privacy.html`: general privacy policy for Brian VN apps
- `dodgem-privacy.html`: Dodgem privacy policy
- `terms.html`: terms of use
- `app-ads.txt`: AdMob publisher verification file shared across apps under the same publisher account
- `CNAME`: custom domain for GitHub Pages
- `.nojekyll`: serve static files directly

## Before publishing ads

Confirm that `app-ads.txt` uses the real AdMob publisher ID and that the root-domain file is publicly reachable. One `app-ads.txt` file can support multiple apps when they use the same AdMob publisher account.
