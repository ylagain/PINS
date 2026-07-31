PINS PRIVACY POLICY — GITHUB PAGES SETUP

Recommended setup: use a separate PUBLIC repository that contains only this policy website.
Do not put your Unity source project, keystore, passwords, PlayFab secrets, or private files in it.

1. On GitHub, create a new public repository such as:
   PINS-Website

2. Upload:
   - privacy-policy.html
   - index.html (included; same policy, so the root URL also works)

3. In the repository, open:
   Settings > Pages

4. Under “Build and deployment”:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   Then click Save.

5. After GitHub publishes the site, use either:
   https://YOUR-USERNAME.github.io/PINS-Website/
   or
   https://YOUR-USERNAME.github.io/PINS-Website/privacy-policy.html

6. Test the URL in a private/incognito browser window while signed out of GitHub.

7. Put that URL in:
   - Google Play Console > App content > Privacy policy
   - The Privacy Policy button inside PINS

IMPORTANT BEFORE RELEASE
- Confirm the published page is publicly accessible and does not require a GitHub login.
- Keep Unity’s privacy/consent mechanism enabled, or implement a valid custom consent flow and pass the result to Unity Ads.
- Update the policy and Play Data Safety form whenever you add or remove SDKs or change data practices.
- This draft is practical compliance documentation, not legal advice.
