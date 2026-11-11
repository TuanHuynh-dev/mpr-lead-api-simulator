# mpr-lead-api-simulator

Static test forms that post Leads to Salesforce Apex REST endpoints on the **IVC-Partial** API site
(`https://ivcl--partial.sandbox.my.salesforce-sites.com/api/services/apexrest/...`).

| Path | Form | Apex REST |
|---|---|---|
| `/` | Index | – |
| `/website/` | Website IVC | `APILeadIVCWebsite` |
| `/landing-page/` | Landing Page | `APILeadLandingpage` |
| `/lead-campaign/` | Lead Campaign (event) | `APILeadCampaignWebsite` |
| `/test-drive/` | Test Drive registration | `APINewTestDrive` |

Deployed on Vercel (static, no build). Submitting a form creates real records in the sandbox.
