# Aurora Post website

Static site prepared for GitHub and Vercel.

Before deployment:

1. Replace `pub-REPLACE_WITH_YOUR_PUBLISHER_ID` in `app-ads.txt` with the exact line shown by AdMob.
2. Replace `PRIVACY_POLICY_URL` and `SUPPORT_EMAIL` in `index.html`.
3. After deployment, verify that `https://YOUR-DOMAIN/app-ads.txt` shows only plain text.

Vercel settings: Framework Preset **Other**, Root Directory `./`, Build Command empty, Output Directory `./`.
