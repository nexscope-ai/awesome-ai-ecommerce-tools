# Maintenance notes

Review date: November 11, 2026.

This review repairs navigation, removes stale price quotations, consolidates repeated destinations, and checks provider-facing descriptions. It is not a hands-on test of every product or a guarantee of ongoing availability. Product links in the README are the primary sources for the descriptions. Ordering is editorial, not a measured ranking. Nexscope entries are maintained by Nexscope; independent tools are not endorsements or partners by implication.

## Pricing and duplicates

- Removed undated price ranges and plan promises. Consult the provider for billing period, currency, seats, usage limits, trial eligibility, and taxes.
- Kept one external destination per product page; related categories refer to its primary entry. Distinct feature pages remain separate when they serve different research tasks.

## Corrections and sources

- Removed Sora from active video recommendations. [OpenAI’s discontinuation notice](https://help.openai.com/en/articles/20001152-what-to-know-about-the-sora-discontinuation) states the web/app ended April 26, 2026 and the API ended September 24, 2026.
- Replaced the third-party Seedance TV destination with the [ByteDance Seedance official page](https://seed.bytedance.com/en/seedance). Removed version-specific and free-tier promises.
- Replaced the outdated GPT Image link with [OpenAI image-generation documentation](https://developers.openai.com/api/docs/guides/image-generation).
- Updated Shopify Magic’s redirect to Sidekick, Answer Bot to Zendesk AI agents, Klear to Meltwater documentation, and Hootsuite’s listening entry to its current official page.
- Removed unsupported feature counts, blanket commercial-rights claims, stale model versions, and the unverified 50+ badge. Repeated Voiceflow and Dynamic Yield entries now cross-reference their primary descriptions.

## Automated access limitations

Some providers block automated requests or require browser/session access. A 403, rate limit, redirect-parser error, or TLS failure is not evidence that a product has shut down. The following retained destinations could not be fully fetched in this run; their live prices and complete feature sets are not certified here.

- `https://openai.com/api/` — HTTP Error 403: Forbidden
- `https://www.adobe.com/products/firefly.html` — <urlopen error [Errno 61] Connection refused>
- `https://www.adzooma.com` — HTTP Error 403: Forbidden
- `https://www.dynamicyield.com` — HTTP Error 403: Forbidden
- `https://www.midjourney.com` — <urlopen error [SSL: TLSV1_ALERT_PROTOCOL_VERSION] tlsv1 alert protocol version (_ssl.c:1129)>
- `https://www.netsuite.com` — HTTP Error 403: Forbidden
- `https://www.trendhunter.com/ai` — HTTP Error 403: Forbidden
- `https://www.triplewhale.com` — HTTP Error 403: Forbidden
