# Salesforce · ANZ territory strategy

Salesforce-branded adaptation of EliottLS/Stripe_Territory_Plan_w_ChatGPT_Codex. Built with React and Vite, using the supplied Salesforce SMB & Growth AE interview cheat sheet (14 October 2026).

## Develop

Node.js 22+ and npm:

```sh
npm ci
npm run dev
```

## Validate

```sh
npm test
npm run build
CHROMIUM_PATH=/usr/bin/chromium npx playwright test
```

If Chromium is not installed, use `npx playwright install chromium` and omit CHROMIUM_PATH.

## Included

- Salesforce logo and blue colour palette, with the original territory workspace layout.
- Overview, quarterly actuals, searchable account explorer and editable account briefs.
- CSV / XLSX import with preview and validation; CSV and Markdown export.
- Salesforce products, four-tier ANZ strategy and 30/60/90 ramp at 30% / 60% / 100%.
- Adjustable scenario forecast with sales-cycle eligibility.
- Interview playbook: V2MOM, six personal stories, discovery agenda, objections and panel questions.
- Weekly 110% funnel calculator: $1.2M illustrative annual quota, $25K ASP, 25% win rate and 13 weeks.

Sample accounts and their signals are fictional. The uploaded cheat sheet is a content source, not independently verified product documentation. Confirm current availability, edition inclusions and AUD pricing. Personal story figures are supplied by the candidate and need reconciliation where noted. The calendar-quarter actuals panel is explicitly separate from Salesforce fiscal quarters.

All imports, account notes, contacts and targets stay in browser-local storage. There is no backend, CRM integration or automatic enrichment. The playbook funnel is independent of the persisted ramp forecast. The forecast assumes starting pipeline is eligible to close in 90 days; newly generated pipeline must fit its sales cycle inside the horizon. Default starting pipeline ($300K) and sales cycle (30 days) are illustrative planning inputs, not inherited customer data.

Logo: Devicon Salesforce asset, https://github.com/devicons/devicon/blob/master/icons/salesforce/salesforce-original.svg. Salesforce marks belong to Salesforce. This is an independent interview demonstration.

## GitHub Pages

A deployment workflow is included. After pushing this project to `main`, choose **Settings → Pages → GitHub Actions** in the Salesforce repository. Deployment is not performed by local build or test commands.
