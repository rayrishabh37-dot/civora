# CivicPrep USA — installable web app build

This package is an installable Progressive Web App (PWA) build, not just a mockup. It includes:
- Required first-launch onboarding/guidelines: welcome, test version guidance, study rules, privacy and terms acknowledgement
- Responsive Liquid Glass-inspired interface and swipe/drag cards
- Practice quiz, mock test, local progress, searchable sample bank, basic speech synthesis
- English/Hindi/Spanish interface basics
- PWA manifest, app icons, service worker cache for offline shell
- Official USCIS links for the current test guide and updates

## Run locally
Opening index.html directly allows browser testing, but installability and service worker require HTTPS hosting or localhost. Upload all files to a static host with HTTPS (e.g. a static site host) to install it from Safari/Chrome.

## Important production gap
The quiz still contains only a small verified sample bank, not the complete 128-question official set. It links directly to USCIS's official 128-question PDF. Before public release, add and verify the full question/answer data, test dynamic current-officeholder answers, and implement privacy policy/terms that match actual data handling. Login/cloud sync, live AI, speech recognition, online leaderboard, ads, and premium payments are not connected in this build. No app-store publishing has been performed.
