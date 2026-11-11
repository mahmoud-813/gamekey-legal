# GameKey Legal — upload directly to GitHub Pages

This ZIP contains the **entire public-facing legal website** for GameKey VI. It is designed for actual app users reading Privacy Policy and Terms of Use on phones, tablets and computers.

## Upload to your existing public repository

Repository: https://github.com/mahmoud-813/gamekey-legal

1. Extract `GameKey_Legal_Website_Upload.zip` into a normal folder.
2. In the repository on GitHub, open **Add file → Upload files** (or **uploading an existing file** on an empty repository).
3. Select ALL extracted **files** and upload them **at the repository root**. Do not upload the ZIP itself and do not nest them inside a folder.
4. Commit the changes to the `main` branch.
5. Open **Settings → Pages** in the repository.
6. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then **Save**.
7. Once GitHub finishes publishing (sometimes several minutes), visit the website URLs below and check them on your phone.

## Public website addresses

- Homepage: https://mahmoud-813.github.io/gamekey-legal/
- Privacy Policy: https://mahmoud-813.github.io/gamekey-legal/privacy.html
- Terms of Use: https://mahmoud-813.github.io/gamekey-legal/terms.html
- Privacy Choices: https://mahmoud-813.github.io/gamekey-legal/choices.html
- Support: https://mahmoud-813.github.io/gamekey-legal/support.html

These addresses only work after GitHub Pages has published the files. The website is self-contained: no website builder, JavaScript, cookies created by our site, external fonts, images or tracking scripts are included. GitHub Pages as host may still process normal web requests/logs.

## Files in this upload

- `index.html` — landing page with quick links for app users
- `privacy.html` — detailed Privacy Policy
- `terms.html` — Terms of Use
- `choices.html` — readable privacy choices guide
- `support.html` — support/contact page
- `404.html` — helpful missing-page page
- `styles.css` — matching, responsive GameKey style
- `.nojekyll` — disables Jekyll processing for this static site
- `README.md` — these upload and publishing instructions (for you, not an in-app page)

## IMPORTANT: before submitting GameKey to Apple

The site can be uploaded now, but **final public App Store publication requires a few updates**:

1. **Add a working, privately monitored support/privacy email** to the Privacy Policy, Terms and Support page. We have not put the personal email visible in account screenshots onto a publicly accessible website without the owner's permission. The current pages explain that a private contact method will be available before public launch.
2. Verify who the publisher is when the Apple Developer enrollment is approved (individual or organization) and use accurate legal details without inventing them.
3. Test the production app with final AdMob SDK/UMP and Apple tracking flow; keep advertising disclosures consistent with the actual data and consent implementation. Test ad previews are simulated, and live ads are currently disabled in remote policy.
4. Add the Privacy Policy URL to App Store Connect and link **Privacy Policy** and **Terms of Use** in GameKey Settings (the App.tsx legal-links update was prepared in an earlier download).
5. Check third-party game art/map/code/brand rights. A disclaimer is not a substitute for permission.
6. Review the policies for legal compliance with an appropriate professional if needed. They are informational drafts, not legal advice.

**Why no email address yet?** This website is public. A personal email address should not be published without express authorization.

## Optional App Store links

- App Store Connect Privacy Policy URL: `https://mahmoud-813.github.io/gamekey-legal/privacy.html`
- Optional App Store Connect Privacy Choices URL: `https://mahmoud-813.github.io/gamekey-legal/choices.html`
- Suggested Support URL: `https://mahmoud-813.github.io/gamekey-legal/support.html`

## Notes on future AdMob monetization

The privacy and terms pages cover a planned bottom banner, occasional full-screen ads, possible frequency changes via Supabase, Google-managed consent, and Google advertising data processing. No promise of an exact ads-per-day rate is made. Before live ads are enabled, the UMP privacy messages, any required ATT prompt, app privacy disclosures, AdMob review, and app-ads.txt setup must be verified against the published app.
