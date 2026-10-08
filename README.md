# Low Lumen developer website

Static public developer website for current and future apps. Hosted on GitHub Pages from the root of the `main` branch. No package installation, framework, tracking scripts or custom workflow is required. `.nojekyll` disables Jekyll processing.

## Public URLs

- Developer website: https://eeron36.github.io/
- Chomp Shift support: https://eeron36.github.io/chomp-shift/support/
- Chomp Shift privacy: https://eeron36.github.io/chomp-shift/privacy/
- Authorized ad sellers: https://eeron36.github.io/app-ads.txt

For the iOS listing, use the homepage as the Marketing URL, the support page as the Support URL and the privacy page as the Privacy Policy URL. AdMob's consent message uses the privacy page URL.

## Updates

Edit the HTML/CSS, preview and check the pages, then commit and push. GitHub Pages publishes the website. New apps should have their own support and privacy pages describing their actual data practices.

The app-ads.txt entry uses the owner's supplied AdMob publisher number, in Google's documented direct-publisher format. Compare it with the personalized snippet in AdMob before release. Publishing this file does not establish AdMob verification or enable live ads; the app still needs a store listing and Google's checks.

## Privacy maintenance

The policy describes the current Chomp Shift development build as inspected on 2026-10-08: local saves, Google demo ad requests, consent handling, no tracking permission prompt, no game account or developer analytics backend. Recheck it against the final native build, actual ad partners, publisher identity, support retention practices, and App Store privacy disclosures before release. This website is not an App Store release or a guarantee of legal compliance.

Only the website and its app icon are in this repository. The game's source, account credentials, private correspondence and payment details are not published here.
