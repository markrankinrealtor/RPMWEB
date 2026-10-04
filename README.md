# RPMWEB — Rankin Property Management

Static website source, including all pages, calculators, shared navigation, contact information, images, and the supplied Rankin logo.

## Run locally

From the repository folder, run:

```sh
python3 -m http.server 8765 --directory dist
```

Open http://localhost:8765. Serve `dist/` as the site root so navigation and asset paths work correctly. No build step or package installation is required.

## Files

- `dist/`: complete HTML, CSS, JavaScript, and image source.
- `page-registry.json`: original content page directory.
- `.openai/hosting.json`: existing Sites hosting identity.

## Current website

https://rankin-property-management.mark-rankinrealtor.chatgpt.site

Contact: support@rankinpropertymanagement.com · (513) 676-3959.

The logo appears in page headers, footers, and browser icons. Hosting access is configured separately from this public source repository.

## Integrations

Contact forms prepare an email for the visitor to review and send. Rental feeds, online payments, resident and owner portals, and CRM delivery require separate provider connections. Calculators and checklists do not persist visitor data.
