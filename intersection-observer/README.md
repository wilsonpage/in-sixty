The `IntersectionObserver` is used to detect when an element crosses-over (intersects) or gets within a given range of a `root` element.

It's primary use-case is to observe when elements are within (or close to) a scroll viewport, to trigger lazy-loading of content or purposes of telemetry (ad impressions). The `IntersectionObserver` API negates the need to perform costly measurements inside `'scroll'` handlers, which is a very common cause of jank on the web today.

Currently the `IntersectionObserver` is only available in Chrome Canary, but there is a bug [3] tracking Gecko implementation.

LINKS

[1] Live Demo (requires Chrome Canary) - https://wilsonpage.github.com/in-sixty/intersection-observer
[2] Explainer - https://github.com/WICG/IntersectionObserver/blob/gh-pages/explainer.md
[3] Gecko Bug - https://bugzilla.mozilla.org/show_bug.cgi?id=1243846
