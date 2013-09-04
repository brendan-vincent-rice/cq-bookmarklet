cq-bookmarklet
==============

**Remove the dam and sidekick from a page when in edit mode**

To use, create a new bookmark, give it a title ("Remove dam/sidekick") and use the following as the URL:

    javascript:location.href = location.href.replace('cf#/', '').split('?')[0] + '?wcmmode=disabled';
