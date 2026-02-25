# FinCare Account Deletion Page

This page fulfills Google Play's **Account Deletion URL** requirement for the FinCare Android app. It is designed to be hosted and linked from your app's Data safety section in Play Console.

## Google Play Compliance

The page includes:

- ✅ **App/developer name** — References "FinCare" as shown on your store listing
- ✅ **Prominent deletion steps** — Clear, numbered instructions for users to request account deletion
- ✅ **Data disclosure** — Specifies what data is deleted vs. retained
- ✅ **Retention period** — Notes the retention period for legally required data (e.g., financial records)

## Before Publishing

1. **Update the support email** — Replace `privacy@fincare.app` in `account-deletion.html` with your actual support/privacy email address.

2. **Review data types** — Adjust the "What Data We Delete" and "Data We May Retain" tables to match your app's actual data practices. Update based on what you collect and how you handle it.

3. **Add Privacy Policy & Terms links** — Replace the `#` placeholders in the footer with your real URLs.

## Hosting Options

Host this page at a public URL and add that URL in Play Console under **App content → Data safety → Delete account URL**.

### Option 1: GitHub Pages
1. Create a GitHub repo and push this folder
2. Enable GitHub Pages in repo Settings
3. Your URL will be: `https://yourusername.github.io/repo-name/account-deletion.html`

### Option 2: Firebase Hosting
```bash
firebase init hosting
firebase deploy
```

### Option 3: Your own domain
Upload `account-deletion.html` to your web server (e.g., `https://fincare.app/account-deletion` or `https://fincare.app/delete-account`).

## File

- `account-deletion.html` — Single, self-contained HTML file (no external dependencies)
