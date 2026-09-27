# Seven-app Ad Hoc installer

Public distribution of these seven signed testing binaries was explicitly authorized by the account owner on 27 September 2026. This repository contains only the installer, seven OTA manifests, signed QA IPAs and non-secret build metadata. It does not contain the private app source repositories or signing credentials.

Open https://d6hg9t4jpj-sys.github.io/seven-app-install/ in Safari on the registered iPhone, then use each Install button. Installation remains restricted by Apple's embedded Ad Hoc provisioning profiles; those profiles contain registered-device identifiers and are publicly downloadable as part of the approved IPA publication.

All seven packages use Google demo advertising inventory and preserve age, ownership and consent safeguards. Builds have passed signature and registered-device profile checks but are not yet physically tested on the iPhone. See `builds.json` for exact versions and hashes.

No App Store submission or public App Store release is performed by this repository. Do not delete an existing published app to force an installation; preserve app data and historic paid-acquisition evidence.

`robots.txt` and noindex metadata discourage indexing, but do not provide access control. Binaries are deliberately public as approved; do not add secrets or unrelated files.
