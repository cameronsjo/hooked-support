# Hooked — support site (moved)

Hooked's support page and privacy policy moved to <https://artificermade.com/hooked/> on 2026-10-04. They are published from `artificermade/artificermade.github.io` and generated in the app repo by `make support-site`.

This site, <https://cameronsjo.github.io/hooked-support/>, now only redirects, so links in older builds of the app keep working:

| Old address | Goes to |
| --- | --- |
| `/hooked-support/` | `https://artificermade.com/hooked/` |
| `/hooked-support/privacy.html` | `https://artificermade.com/hooked/privacy.html` |
| anything else | `https://artificermade.com/hooked/` |

GitHub Pages cannot send HTTP redirects, so each page uses a `<meta http-equiv="refresh">` with a plain link as the fallback. Do not publish content here again; change the pages in the app repo and publish them to the company site.
