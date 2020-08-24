# Disable Text Highlights from Google Search Results

Google Chrome introduced a feature highlighting relevant text snippet
by relying on the new
[Scroll to Text Fragment](https://chromestatus.com/feature/4733392803332096) API.

It seems that at the moment there is no way to disable the feature.
Because of that, some users got annoyed by the functionality
(e.g. see [this issue](https://github.com/WICG/scroll-to-text-fragment/issues/122)
of the original standard proposal)

![Screenshots of Disable Text Highlights from Google Search Results extension](./screenshot.png)

### How can I disable this functionality?

In perfect case it would be possible to control "Scroll to Text Fragment"
from JavaScript interface

In that case it would be easy to override/reset the highlight pattern

However, currently it seems to be impossible to do so

As a consequence, this extension changes all the links on
Google-hosted pages, removing the part responsible for text highlighting