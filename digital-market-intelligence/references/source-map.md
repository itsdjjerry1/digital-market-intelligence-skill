# Source map and integration notes

Use only sources available to the running agent and permitted for the intended use. Check current product documentation and account entitlements before assuming a metric or endpoint is available.

| Intelligence area | Preferred evidence | Fallback / limitation |
|---|---|---|
| Website traffic and engagement | Licensed traffic-intelligence API or user's GA4/export | Public web evidence is qualitative; it cannot establish exact competitor visits or engagement |
| Traffic channels and referrals | Licensed provider dataset; first-party analytics for owned domains | Ad libraries and public referral links are signals, not actual channel share |
| SEO keywords and competitor overlap | Licensed keyword/SERP API; Search Console for owned properties | Public SERP sample and accessible page review; no fabricated search volume/CPC |
| AI search visibility | Repeatable prompt sampling in authorized AI interfaces, logged with date and sources | Results vary by model, user context, and time; report sample rate only |
| Mobile apps | Licensed app-intelligence data; official app stores; first-party analytics | Store ranking/reviews are not direct download or active-user measurements |
| E-commerce | Authorized marketplace API, licensed product-intelligence provider, seller exports | Public product pages are snapshots, not proof of sales or inventory |
| Lead generation | Licensed B2B/company dataset and public company evidence | Score company fit, not private-person attributes; verify every lead before outreach |

## Provider examples (not endorsements or guarantees of access)

- Similarweb API documentation: https://developers.similarweb.com/docs/similarweb-web-traffic-api
- Similarweb keyword API documentation: https://docs.similarweb.com/api-v5/api-reference/search-analysis-api/website-keywords

Providers, endpoints, data rights, pricing, and available metrics can change. Validate them before building an integration.
