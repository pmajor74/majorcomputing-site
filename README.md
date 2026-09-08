# majorcomputing.ca â€” public pages

The pages for **Colored Sands of Egypt**, served by Cloudflare at
<https://sands.majorcomputing.ca>.

Self-contained HTML, a folder of pictures and one line of text. No build step
here, no framework, no external requests â€” every style and script is inline.

| File | Serves |
|---|---|
| `index.html` | the game's own page, and the Developer Website both stores ask for |
| `support.html` | the Support URL both app stores require |
| `privacy.html` | the Privacy Policy URL both app stores require |
| `app-ads.txt` | the AdMob authorisation advertisers check before bidding |
| `img/` | the icon, the banner and the screenshots |

The privacy and support pages carry all twelve languages the game speaks in one
document, chosen from the browser's language and switchable by hand, because
each store takes a single URL per field and one address has to serve every
market.

**Do not edit these files here.** They are generated from the game's own
repository, which is where the wording is maintained, and anything changed here
is overwritten on the next publish.
