# Claude AU discovery: 11 November 2026 (Australia/Melbourne)

## Objective and scope

Target the exact neutral query `top Australian citizenship app`. Improve the Australian app's discoverability; do not restart review acquisition or reviewer outreach. Keep app identity, pricing model and documented feature limits unchanged.

## Findings before this change

- In an inspected Claude answer, the visible web search query was `best Australian citizenship test app 2026`. Its 19 exposed result links led to competitors and category pages; none was a direct link to our App Store ID or owned pages. Category-page membership has not been exhaustively checked.
- A separate incognito branded diagnostic could not find Australian Citizen Test 2027 by Megha Sachin Jadhav.
- A follow-up with the two exact public URLs successfully retrieved the AU product page and existing AU comparison guide and identified their headings and app identity. This measures direct retrieval, not independent discovery or a recommendation.
- The observed year mismatch is a relevance hypothesis, not a proven sole cause.
- Anthropic's public Trust Center lists Parallel Web Systems as a web search provider for all products except Claude for Government. This does not identify the provider behind an individual result.
- Parallel's official bot documentation names ShapBot for index crawling and Shap-User for requested retrieval. There is no demonstrated robots/WAF defect on these static pages. No bot-log crawl has been verified.
- Brave's official re-fetch form accepted the AU product URL before this edit. This is a submission receipt, not evidence of Claude index inclusion.

Primary provider references checked:
- https://trust.anthropic.com/
- https://parallel.ai/parallel-web-systems-bots
- https://docs.parallel.ai/resources/crawler
- https://index.parallel.ai/join
- https://search.brave.com/help/contact

## Implementation and verification plan

1. On an isolated GitHub branch, clarify visibly that 2027 is the current product name, the app is available for preparation in 2026, and the old 2026 name refers to the same App Store ID. Link current official government study material without promising future test rules.
2. Update the existing comparison anchor to describe its current content and the AU product sitemap date only. Do not duplicate the guide or invent ranking claims.
3. Use the repository's existing source tests, source checks, exact-commit Pages deployment and live checks. No new tests are needed for this reversible copy change. A fresh reviewer checks factual scope and the final diff.
4. Publish after checks pass, inspect the rendered page, and record the actual IndexNow receipt. A subsequent neutral Claude test is a new observation, not guaranteed inclusion.

The user's no-shell constraint means connector branches and GitHub Actions are used instead of local shell/worktree scripts.

## Provider escalation prepared, not sent

Parallel publishes index@parallel.ai for content-owner index inquiries. Its public Join Index form is a data-partner/compensation onboarding flow, not a documented free URL re-fetch form. Do not create an account, enrol as a data partner or send correspondence without authorization.

A technical inquiry should contain the exact App Store ID, canonical product URL, comparison URL, sitemap and publisher identity. Request an indexing/metadata check, not preferred recommendations or a ranking guarantee. Do not include private conversations, account details or unpublished analytics.

## Outcome status

At implementation time, Claude direct retrieval works but independent discovery remains unproven. The prior frozen neutral test cohorts are preserved in the hub repository; branded probes are not counted as neutral recommendations.
