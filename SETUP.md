# GitHub profile and portfolio refresh

This package contains two separate updates:

1. `profile/README.md` is the special GitHub profile README.
2. `website/index.html` is the new personal portfolio homepage for `seyedhojjathosseini.github.io`.

## 1. Publish the GitHub profile README

GitHub displays a profile README when a **public** repository exists with the exact same name as the account login.

1. Open GitHub and create a new repository named `seyedhojjathosseini`.
2. Set it to **Public**.
3. Add `profile/README.md` as the repository's root `README.md`.
4. Save the GitHub Bio and Website fields using `profile/PROFILE_SETTINGS.txt`.
5. Pin the strongest reviewed project repositories to the profile.

The account does not currently have this special profile repository in its visible public repository list.

## 2. Replace the personal website homepage

Repository: `seyedhojjathosseini/seyedhojjathosseini.github.io`

1. Back up the current repository contents first.
2. Replace the root `index.html` with `website/index.html`.
3. Replace the old `hojat.html` and `hojat2.html` files with the contents of `website/retired-demo.html` (keep their existing filenames when uploading).
4. Keep the old background image only if you still need it; the new design does not depend on it.
5. Check the GitHub Pages deployment and test the page on desktop and mobile.

## Safety note about the old files

The old `index.html` contained browser fingerprinting and collection of browser/device information, attempted to request geolocation, and sent the collected information to a Telegram endpoint. The old `hojat.html` and `hojat2.html` contained obfuscated or direct external script loading from `xss.report` and cookie-display code. The replacement homepage contains no analytics, fingerprinting, geolocation requests, telemetry collection, or third-party JavaScript. The old demo pages should be retired rather than left publicly executable.

## Editorial notes

- The portfolio deliberately avoids naming an employer or exposing internal SOC details.
- It does not claim project usage statistics, certifications, or outcomes that have not been verified.
- `soarsystems` is the public company website repository; it is not the private SOAR product source repository.
- Before pinning any repository, review its complete contents, README, license, and security posture.
