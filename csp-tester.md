---
layout: default
title: CSP Tester
permalink: /csp-tester
---

This extension for Firefox and [Chromium](https://en.wikipedia.org/wiki/Chromium_%28web_browser%29) based browsers helps web developers to test web application functionality
with [Content Security Policy](https://www.w3.org/TR/CSP2/) (version 2.0) enabled.

![](/assets/images/csp-tester_2.0.png)

Typical workflow looks like:

1. Open the extension window by clicking on the toolbar icon
2. Add into the URL Pattern a regular expression for the site that you want to test, for example `*://yoursite.com/*` (CSP Tester uses [Chrome Match Patterns](https://developer.chrome.com/extensions/match_patterns))
3. Tick the e.g. "self" checkbox, check "Active" and Save the changes
4. Open the Developer Tools and navigate to the tested site
5. Confirm a number of CSP violations reported in the Developer Tools Console as well as possible visual changes
6. Make changes in the policy based on these reports

You can install CSP Tester from [Firefox's AMO](https://addons.mozilla.org/firefox/addon/csp-tester/) or [Google Chrome Web Store](https://chrome.google.com/webstore/detail/csp-tester/ehmipebdmhlmikaopdfoinmcjhhfadlf). The license is GPLv2. Feel free to review the source code and report issues (and sent PRs ;) at [GitHub](https://github.com/oxdef/csp-tester)
