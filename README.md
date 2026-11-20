# EDM Games · Woof Box - Dog Sudoku

Static developer website. No build step, external fonts, JavaScript, or site analytics.

## Publish with GitHub Pages

Repository Settings → Pages → Build and deployment → Source: Deploy from a branch → main → / (root) → Save.

After deployment, verify:

- https://edenming.github.io/
- https://edenming.github.io/privacy.html
- https://edenming.github.io/app-ads.txt

Use the privacy URL in Play Console and add an accessible privacy-policy link inside the game. Use the homepage as the developer website in the Play store listing. Then verify the app-ads.txt entry in AdMob against the personalized snippet from the account. Publishing this file alone does not link or approve an AdMob app.

## Release checks

- Confirm the actual AdMob/UMP SDK versions, consent implementation, teen protections, and Google Play Data Safety answers match the privacy policy. Publishing this policy does not implement consent or age handling.
- Check whether Android backup is enabled in the final merged manifest. The policy distinguishes system backups from developer-operated cloud saves.
- Reconfirm the publisher ID and app-ads.txt snippet in AdMob.
- There is no account, own level telemetry, or BigQuery integration at present. Update disclosures and obtain any required consent BEFORE introducing new processing.
- The public contact address is edenmings@gmail.com. Do not commit identity documents, banking information, signing keys, credentials, or player data.
- Review policy wording when game behavior changes. This is a factual disclosure draft, not legal certification.

Last content review: 2026-11-20.
