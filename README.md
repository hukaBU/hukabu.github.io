# hukabu.github.io

A demo site used to test ReachPlane: Hukabu Bakery, a fictional neighbourhood bakery. It is not a real shop.

It has one page of each kind the ReachPlane Deep Scan walks first, all with real text and linked from the navigation:

| Page | Kind |
|---|---|
| `/` | homepage |
| `/shop/` | category |
| `/products/sourdough-loaf.html`, `/products/butter-croissant.html` | product |
| `/pricing.html` | pricing |
| `/faq.html`, `/contact.html` | support |
| `/policies/refunds.html` | policies |

`sitemap.xml` lists every page. The facts are consistent from page to page (prices, hours, allergens, subscription rules), so an agent's answers can be checked against them.

ReachPlane writes the other files through its pull requests: `.well-known/semur-verify.txt` (ownership verification), `llms.txt`, `.well-known/ai-context.json` and `agent/`. Do not edit them by hand.
