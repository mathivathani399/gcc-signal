# GCC Signal — India GCC Intelligence Workspace

> **Live demo:** Add your published GitHub Pages URL here after deployment.

GCC Signal is an interactive frontend prototype exploring how teams researching India's Global Capability Centre (GCC) ecosystem could gather public signals, compare locations, review state-policy references, assess provider claims, and prepare a decision brief.

> **Prototype status:** This is a static, browser-based demo using a small sample dataset. It is not a production service and does not have a backend, central database, login, live news ingestion, AI model integration, or shared team accounts. City scores are illustrative hypotheses, not audited benchmarks. Policy information must be verified against current official notifications and qualified advice.

## Try it

Once deployed with GitHub Pages, open the public website URL shown in the repository's **Settings → Pages** section. The site is built from `index.html` and requires no package installation or build step.

To run locally, download `index.html` and open it in a modern browser such as Chrome, Edge, or Firefox.

## Main workflows

- **Overview:** inspect selected India GCC market indicators and sample signals.
- **Signal desk:** search and filter signals by city, type, and confidence; open sources; save signals; add a new signal as unverified.
- **Location lab:** adjust decision weights and compare directional city-fit scores.
- **Policy library:** review a policy reference and a verification checklist.
- **Provider evidence:** compare public provider capability statements and use a diligence checklist without presenting unverified performance rankings.
- **Decision brief:** set a mandate, include saved evidence and export a Markdown decision brief.

## Technology

- HTML5
- CSS (responsive layout)
- Vanilla JavaScript
- Browser `localStorage` for saved signal IDs
- No external JavaScript framework or package dependencies

## Deploy with GitHub Pages

1. Create a **public** repository on GitHub (for example, `gcc-signal`).
2. Upload `index.html` and `README.md` to the repository's **root** directory. Keep the filename exactly `index.html`—GitHub Pages uses it as the website entry point.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **`main`** and folder **`/(root)`**, then click **Save**.
6. Wait for the Pages deployment to finish. Return to **Settings → Pages** and open the published site URL.
7. Test the published URL in a private/incognito window and on a phone before sharing it.

GitHub's official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site and https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Current limitations

- The example signal records are defined in the HTML; there is no automated source ingestion or live refresh.
- User-added signals exist only in the current page session and will disappear after a refresh. Saved signal IDs are stored locally in that browser and are not shared with other users.
- No authentication, backend, database, team workspace, alert delivery, or connected AI service is implemented.
- Location ratings are seeded directional inputs to demonstrate the scoring interaction. Replace them with comparable, mandate-specific data before using for an actual site-selection decision.
- Policy cards are research starting points, not legal, tax, or investment advice. Verify current policy versions, eligibility, caps, and application conditions with official sources and qualified advisers.
- Public provider descriptions are not independent evidence of delivery performance. No provider performance ranking is claimed.

## Selected source links included in the prototype

- Zinnov–Nasscom, India GCC Landscape FY2026: https://zinnov.com/centers-of-excellence/zinnov-nasscom-india-gcc-landscape-2026-report/
- JLL, India GCC office leasing in 2025: https://www.jll.com/en-in/newsroom/india-s-gcc-expansion-hits-record-31-million
- JLL, India office market research: https://www.jll.com/en-in/insights/market-dynamics/india-office
- Government of Karnataka, GCC policy portal: https://registration.eitbt.karnataka.gov.in/gcc/register
- ICAI, state-policy summary: https://global.icai.org/state-policy.html
- EY India, GCC services: https://www.ey.com/en_in/services/consulting/global-capability-centers
- Zinnov services: https://zinnov.com/en-in/
- SansoviGCC directory (competitor reference): https://www.sansovi.com/gcc/directory/

## Assignment context

Created as a product-strategy prototype for a Product Intern assignment. The goal is to demonstrate the proposed workflow and evidence standards, not to claim production readiness or complete market coverage.
