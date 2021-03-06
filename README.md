# EventListenerOptions
A [proposal](https://rawgit.com/RByers/dom/event-listener-options/dom.html#dictionary-eventlisteneroptions) to extend the DOM event pattern to allow authors to opt-in to uncancelable events, primarily to enable scroll performance optimizations.  The prior [stand-alone proposal](https://rbyers.github.io/EventListenerOptions/EventListenerOptions.html) is being re-worked into an [explainer document](https://github.com/RByers/EventListenerOptions/blob/gh-pages/explainer.md) and a [pull-request on the DOM specification](https://github.com/whatwg/dom/pull/82).  Discussion is occuring in [GitHub issues](https://github.com/RByers/EventListenerOptions/issues?q=is%3Aissue).  A polyfill exists [here](https://github.com/dtapuska/async_event_polyfill).

References:
 * One [discussion on public-pointer-events](https://lists.w3.org/Archives/Public/public-pointer-events/2015AprJun/0042.html)
 * [Discussion on WhatWG](https://lists.w3.org/Archives/Public/public-whatwg-archive/2015Jul/0018.html)
 * Earlier [scroll-blocks-on proposal](https://docs.google.com/document/d/1aOQRw76C0enLBd0mCG_-IM6bso7DxXwvqTiRWgNdTn8/edit#heading=h.wi06xpj70hhd) and discussion.
 * [Chromium bug](https://code.google.com/p/chromium/issues/detail?id=489802)
