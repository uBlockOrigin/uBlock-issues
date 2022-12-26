# uBlock Origin (uBO) Issues

This repository is the official community-maintained issue tracker for [uBO](https://github.com/gorhill/uBlock).

#### Support Forum

For support, questions, or help, visit [/r/uBlockOrigin](https://www.reddit.com/r/uBlockOrigin/).

#### Filter List Issues

Report any issues with filter lists or broken website functionality in the [uAssets issue tracker](https://github.com/uBlockOrigin/uAssets/issues).

#### Filter List Requests

New filter list requests are not permitted and will be declined and closed.

#### uBO Lite (uBOL) Issues

Report issues specific to the Chromium Manifest Version 3 (MV3) variant in the [uBOL issue tracker](https://github.com/uBlockOrigin/uBOL-issues/issues).

#### uBO Legacy Issues

Report issues specific to the legacy variant in the [uBO Legacy issue tracker](https://github.com/gorhill/uBlock-for-firefox-legacy/issues).

#### Performance Issues

Speculated performance issues will be marked as invalid and closed if they do not come with actual profiling data from the [Firefox Profiler](https://profiler.firefox.com/)/[Chromium Profiler](https://developer.chrome.com/docs/devtools/evaluate-performance/reference/) and a fully substantiated analysis supporting the claim.

#### WebRTC Issues

Do not open any issues about WebRTC leaking local IP addresses. Supported modern browsers do not cause undue local IP address leaks through WebRTC, and uBO is not a VPN/proxy tool. If you are experiencing such an issue, report it to the browser or VPN/proxy tools software provider or, if needed, both.

# uBO Development Builds

You can use the development build to help report new issues and regressions before the stable release is published.

Once you install a development build, it will automatically update when a new version is published.

- **Chromium**: Install from the [Chrome Web Store](https://chrome.google.com/webstore/detail/ublock-origin-development/cgbcahbpdhpcegmbfconppldiemgcoii).

- **Firefox**: Click the most recent `uBlock0_[version].firefox.signed.xpi` file from the [uBO Releases page](https://github.com/gorhill/uBlock/releases).

- **Thunderbird**: Download the most recent `uBlock0_[version].thunderbird.xpi` file from the [uBO Releases page](https://github.com/gorhill/uBlock/releases), then drag-n-drop it into Thunderbird's Add-ons Manager pane (Thunderbird 65+ required).
