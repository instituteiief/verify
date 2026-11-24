# IIEF Credential Verification

Official credential verification service of the International Institute of Economics and Finance.

Live at: https://verify.iiefinstitute.org

## Files

- `index.html` - public verification page
- `admin.html` - registry management page (generates registry.js)
- `registry.js` - the credential registry
- `CNAME` - custom domain configuration

## How to add a credential

1. Open `https://verify.iiefinstitute.org/admin.html`
2. Fill in the form and click "Generate registry.js"
3. Download the generated file
4. On GitHub: "Add file" -> "Upload files" -> upload `registry.js` -> "Commit changes"
5. The new credential becomes verifiable within a few minutes

## Statuses

- `valid` - green
- `expired` - amber (requires `expiryDate`)
- `revoked` - red (requires `revokeDate` and `revokeReason`)
