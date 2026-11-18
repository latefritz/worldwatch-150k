# WORLD Watch — 150K Subscriber Growth Strategy

An independent, interactive interview presentation (not an official WORLD News Group website).

## Site
- Single-file static site: `index.html`
- Responsive, WORLD Watch-inspired colors
- Interactive 36-month subscriber calculator
- Six acquisition channels, trial funnel, and 90-day plan
- Editable sample budgets, cost per trial, churn, and conversion rates
- Scenario import/export saved locally in the browser (no backend)

## Data and confidentiality
All advertising spend, churn, and conversion assumptions are **illustrative placeholders**, not company-provided results.
The 40,000 current households and 150,000 target came from the interview brief.
**This repository is public.** Do not commit confidential WORLD data or internal reports.
The HTML includes a `noindex` directive, but that does not restrict access. Use Cloudflare Access or a private distribution route if the presentation should be restricted.

## Cloudflare Pages deployment (when ready)
1. Connect GitHub repository `latefritz/worldwatch-150k` to a new Cloudflare Pages project.
2. Choose a static site: no build command, site files in the repository root.
3. Verify the assigned `*.pages.dev` deployment URL before adding a custom domain.
4. Add `worldwatch.swisssales.com` under that Pages project's **Custom domains**.
5. Follow the DNS instructions for the subdomain only; do not change SwissSales root website DNS or the memorial website.

## Editing
Update `index.html` and commit changes. Cloudflare Pages can redeploy on commits.
Scenario inputs changed in-browser are saved to that browser only; they do not change the default numbers for visitors.
