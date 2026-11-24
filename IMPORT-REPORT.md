# Import report: The Arts of Becoming

Imported from page.zip on 2026-11-24 with `openspace import html`.
Sources: the page's HTML and CSS. 0 requests.

## Summary

- **6** pages, **0** collection items in 0 collection(s)
- **0** media files (0.0 MB) downloaded into `media/`
- **0** redirects so old addresses keep working
- **13** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | The Arts of Becoming | 13 | 22 |
| `/the-arts` | `/the-arts` | There are many paths for becoming. | 6 | 11 |
| `/the-thread` | `/the-thread` | The Thread | 8 | 9 |
| `/journal` | `/journal` | Field notes from the living edge. | 4 | 5 |
| `/about` | `/about` | Kathleen Marie Rose | 4 | 6 |
| `/inquire` | `/inquire` | What is calling you? | 3 | 4 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying the original site's CSS or code.

- Brand color #472d1e (the site's accent color).
- Fonts on the original site: Fraunces / Hanken Grotesk → pairing "Fraunces & Hanken Grotesk" (Fraunces / Hanken Grotesk), same family for Fraunces and Hanken Grotesk. Licensed fonts can be uploaded in Site Styles → Fonts.
- Type scale on the original site: Heading 1 is 2.3× body text. Density "comfortable" from the section heights.
- Page background #fefdf5 on the original site → #fcfaf8 (text contrast 15.6:1).

Design check: 0 error(s), 4 warning(s).

- warning (/): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/the-arts): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/the-thread): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/inquire): “What is calling you?” has no clear call to action — nothing tells visitors what to do next.

## Needs attention

### Links

- Link to /the-thread.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/)_
- Text link to /the-arts.html led to a page that wasn't imported; the link was removed. _(/)_
- Link to /journal.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/)_
- Link to /about.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/)_
- Link to /inquire.html led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/, /the-arts, /the-thread, /journal, +1 more)_

## Not moved by the importer

- Scripts, animations and anything rendered only by JavaScript (try `--render` for script-built pages).
- Server-side features: shops, logins, search, comments.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://site.openspace.invalid` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the old hosting until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).


## Designed sections

No sections were made into designer components.

Sections that use OpenSpace's own section designs instead:

- /: CSS line 1: "--s1" isn't a CSS property; CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-arts: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /the-thread: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /journal: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /journal: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /journal: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /journal: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /about: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s4" isn't a CSS property
- /about: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /about: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /about: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s3" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /inquire: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /inquire: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
- /inquire: CSS line 1: "--s2" isn't a CSS property; CSS line 1: "--s5" isn't a CSS property
