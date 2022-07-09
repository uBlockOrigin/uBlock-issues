# uBlock Origin (uBO) Issues

Here is the official community-maintained [issue tracker for uBO](https://github.com/uBlockOrigin/uBlock-issues/issues).

#### Filter list issues
Report any issues with filter lists or broken website functionality in the [uAssets issue tracker](https://github.com/uBlockOrigin/uAssets/issues).

#### Performance issues
Speculated performance issues will be marked as invalid and closed if they do not come with actual profiling data from [Firefox Profiler](https://profiler.firefox.com/)/[Chromium Profiler](https://developer.chrome.com/docs/devtools/evaluate-performance/reference/) + fully substantiated analysis supporting the claim.

#### WebRTC issues
Do not open any issues about WebRTC. uBO is not a VPN/proxy tool. Report WebRTC issues about VPN/proxy tools to the software provider.

#### uBO Legacy
Report issues specific to the uBlock legacy variant at https://github.com/gorhill/uBlock-for-firefox-legacy/issues.

#### Filter list requests
No new filter list requests are permitted. Such issues will be declined and closed.

#### Support forum
For any support, questions or help, visit [/r/uBlockOrigin](https://www.reddit.com/r/uBlockOrigin/).

# uBO dev builds

You can help with the development of uBO by using the development build to report new issues or regression bugs before stable releases of uBO are published.

Development builds:
- **Chromium**: install from <https://chrome.google.com/webstore/detail/ublock-origin-development/cgbcahbpdhpcegmbfconppldiemgcoii>
- **Firefox**: click the most recent `uBlock0_[version].firefox.signed.xpi` file from <https://github.com/gorhill/uBlock/releases>
- **Thunderbird**: download the `uBlock0_[version].thunderbird.xpi` package from <https://github.com/gorhill/uBlock/releases>, then drag-n-drop it into Thunderbird's Add-ons Manager pane (Thunderbird 65+ required)

Once you install a development build, it will automatically update when a new version is published.

# Chromium/Chrome 49 users

Chromium/Chrome 55 is now the minimum version, hence no longer compatible with this browser version. Users who would still like to install uBO can download 1.16.18 (the last working version) from the [releases](https://github.com/gorhill/uBlock/releases/tag/1.16.18) section of the uBO repository and install it by unpacking and loading it via Developer Mode.
