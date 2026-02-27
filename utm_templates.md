# UTM Templates & Tracking

Use these UTM query strings for campaigns to identify traffic sources and cities.

Template format:
- utm_source (platform): google, facebook, email
- utm_medium: organic, cpc, social, email
- utm_campaign: city_launch, gmb_post, summer_promo
- utm_content: ad_variation or creative
- utm_term: keyword

Examples:
- City landing (organic share): https://jcelectric.com/newport-beach.html?utm_source=google&utm_medium=organic&utm_campaign=city_launch&utm_content=site_link
- Paid search (Newport): https://jcelectric.com/newport-beach.html?utm_source=google&utm_medium=cpc&utm_campaign=newport_search&utm_content=adA&utm_term=ev+charger+installation
- GMB post (Laguna): https://jcelectric.com/laguna-beach.html?utm_source=gmb&utm_medium=organic&utm_campaign=gmb_posts

UTM conventions (recommended):
- Keep `utm_source` lowercase and consistent.
- Use `utm_campaign` to reference month + intent (e.g., mar2026_ev_launch).
- Use `utm_content` for A/B creative names (adA, adB).

Reporting:
- Link UTMs to Google Analytics and Google Ads.
- Use the `source/medium` and `campaign` dimensions to measure performance.

Call tracking:
- When using call tracking (CallRail or similar), configure dynamic number insertion to preserve UTM parameters for lead attribution.
