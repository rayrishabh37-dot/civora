# Publish CivicPrep USA free using GitHub Pages

This publishes the current web-app build as a website. It does **not** publish an iOS App Store or Google Play app.

## Before publishing
- This build is an early web-app release, not a production-ready service.
- It currently has sample questions, not the complete verified 128-question bank.
- Login/cloud sync, live AI tutor, speech recognition, online leaderboard, ads, and premium payments are not connected.
- The current build stores progress on the device/browser. Review the privacy and terms screens before public release.
- Use USCIS as the source of truth for the correct test version and answers: https://www.uscis.gov/citizenship/testupdates
- Official 2025 civics questions PDF: https://www.uscis.gov/sites/default/files/document/questions-and-answers/2025-Civics-Test-128-Questions-and-Answers.pdf

## Publish steps (iPad or computer)
1. Sign in to GitHub. If you don't have an account, ask a parent/guardian to help with account setup and public publishing.
2. Create a **new public repository** named `civicprep-usa`.
3. Open the repository and choose **Add file → Upload files**.
4. Upload every file in this package, including `index.html`, `.nojekyll`, `manifest.webmanifest`, `service-worker.js`, and both icons. Upload the files themselves, not the ZIP file.
5. Tap **Commit changes**.
6. Open **Settings → Pages**.
7. Under the build/deployment source, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
8. Wait for the Pages URL to appear in Settings → Pages, then open it in Safari/Chrome.
9. Test onboarding, quiz, mock test, progress saving, and mobile layout.
10. On iPad/iPhone Safari, open the live site and use **Share → Add to Home Screen** if available.

GitHub Pages documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Important
Do not add API keys, passwords, private data, or secret credentials to a public repository. A public static site cannot securely protect secret keys. Do not enable paid services or collect users' personal information until a real backend, privacy policy, and adult-reviewed business setup are in place.
