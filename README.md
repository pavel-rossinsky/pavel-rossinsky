Hands-on solutions architect focused on commerce platforms, product data and applied AI. My work spans checkout, catalogues, payment flows, PIM/ERP integration and the plumbing between them.

What interests me most is how a technology stack actually earns money for a business, and whether it does so honestly. Commerce is often won or lost in unglamorous places: one checkout step too many, a catalogue nobody can search, or supplier data that arrives wrong and gets corrected by hand forever. Pushing a metric up by making the customer's life worse can work too — for a quarter. I'd rather build the version that survives close inspection.

## Production systems

**TAKKT Group — product data and platform architecture.** I designed and built an AI-assisted product-data enrichment system supporting more than 30,000 live product pages in three languages, with back-translation, invariant checks and human review. The harder problem underneath is mapping suppliers' incompatible catalogue structures into a consistent product model across PIM, ERP and storefront.

I also led a cross-functional team of eight through the migration to Shopware 6, drove the infrastructure move to AWS with the hosting partner, and remain technically responsible for the resulting platform across Shopware, PIM and middleware.

**Planet Sports — commerce platform architecture.** For six years I owned the architecture and operation of a seven-market retail platform with roughly 1.2 million SKUs and a Black Friday peak of about 38,000 orders in one day.

## Public work

Most of the production systems above are proprietary. The public slice of my work is narrower and mostly upstream in Shopware and PHP:

- **Page-generation performance:** [traced a bottleneck to the database abstraction layer and benchmarked the fix](https://github.com/shopware/shopware/issues/2854#issuecomment-1321561956).
- **Shopware core and tooling:** a [database index change shipped with Shopware 6.5](https://github.com/shopware/shopware/pull/2875#issuecomment-1347952219), plus [pull requests in core around rate limiting and administration configuration](https://github.com/shopware/shopware/pulls?q=is%3Apr+author%3Apavel-rossinsky) and [fixes in developer tooling](https://github.com/FriendsOfShopware/FroshTools/pulls?q=is%3Apr+author%3Apavel-rossinsky).
- **PHP-FPM:** followed a slow request down to an FPM pool flag that reports as enabled when it is not, resulting in [a bug report against PHP itself](https://github.com/php/php-src/issues/10117).

I care deeply about typography, rasterisation, image formats and compression. It goes back to studying information systems at the Belarusian State Technological University within its Faculty of Publishing and Printing — a background that still shapes how I think about catalogue quality.

**Languages:** English · German · Russian  
[LinkedIn](https://www.linkedin.com/in/pavel-rossinsky/) · [X](https://x.com/pavelrossinsky)
