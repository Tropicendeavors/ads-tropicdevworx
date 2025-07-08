
# ads-tropicdevworx

This repository hosts the `app-ads.txt` file for verifying authorized ad traffic for apps published by TropicDevWorx. The file is served publicly via GitHub Pages at:

**https://ads.tropicdevworx.com/app-ads.txt**

---

## 📄 Contents

- `app-ads.txt` — Required by Google AdMob and other ad platforms to validate ad sellers for mobile apps.
- `index.html` — Simple landing page to avoid 404 errors at the root URL.
- `CNAME` — GitHub Pages configuration file pointing this repo to `ads.tropicdevworx.com`.

---

## ✅ Setup Checklist

1. 🔧 Make sure `app-ads.txt` is in the root of this repository.
2. 📝 Each app entry should follow this format:

   ```
   google.com, pub-7850230160732472, DIRECT, f08c47fec0942fa0
   ```

3. 🛠 Update your [Google Play Console](https://play.google.com/console/) > Store presence > Store settings:
   - Website: `https://ads.tropicdevworx.com`

4. 🔁 After changes, click **"Check for updates"** in AdMob under **App-ads.txt** section for each app.

---

## 🆕 Adding a New App

When launching a new app using AdMob or another ad platform:

- Add a new line to `app-ads.txt` using your pub ID
- Commit and push the change
- Wait up to 24–48 hours for AdMob to verify

---

## 🛠 Troubleshooting

- Ensure no typos in the `app-ads.txt` entries
- Use this tool to test availability: [app-ads.txt.dev](https://app-ads.txt.dev/lookup/ads.tropicdevworx.com)
- If AdMob shows a 404 or cannot verify, confirm:
  - The domain is correctly set in the Play Console
  - DNS is propagated
  - `index.html` is present to avoid root errors

---

## 🔗 Useful Links

- [Google's app-ads.txt guide](https://support.google.com/admob/answer/9363762)
- [GitHub Pages DNS config](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [app-ads.txt.dev Checker](https://app-ads.txt.dev)

---

## ✉️ Contact

For issues related to this file or verification, contact:  
📧 www.tropicdevworx.com/contact
