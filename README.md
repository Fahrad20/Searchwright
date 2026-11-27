<h1 align="center">
  <img src="assets/hero.svg" width="100%" alt="Searchwright: SEO audits that show their evidence. Animated demo: an audit crawls a site, scores it and quotes the evidence for each finding; the fix command edits the code on a separate branch, checks every finding again and the score rises.">
</h1>

<p align="center"><b>English</b> · <a href="README.ru.md">Русский</a></p>

> **This is a showcase. The source code is private** and is not published here.
> For a demo or access, [open an issue](../../issues).

SEO audits for [Claude Code](https://claude.com/product/claude-code) that show
their evidence. 37 sub-skills and 20 sub-agents cover technical SEO, content
quality (E-E-A-T), schema markup, sitemaps, images, Core Web Vitals, local SEO,
backlinks, AI search (GEO), e-commerce, hreflang, search experience, topic
clustering, drift monitoring and Yandex Webmaster data. 9 optional extensions
add live data from third-party services.

<p align="center">
  <img src="assets/how-it-works.svg" width="100%" alt="How an audit works: code crawls the site and computes the score, the model explains and sets priorities, the fix command edits the code on a separate branch, and code checks every finding again.">
</p>

## What it does

- **Code measures, the model explains.** The score is computed by code, so the
  same site gives the same findings and the same number on every run. Each
  finding lists its addresses, a quote from the page and a way to check the fix.
- **Fixes, not only reports.** Findings become edits on a separate branch, and a
  finding counts as fixed only when its check no longer reports it.
- **Runs without a model.** The crawl, the score and the report need no model
  call and no API key, so they fit CI or a weekly schedule.
- **Google and Yandex.** Both sets of robots.txt rules, Search Console, Yandex
  Webmaster and Metrica, and growth opportunities from real search queries.
- **Russian language.** Lemma-based text analysis and reports in Russian or
  English.
- **Safe on pages it does not trust.** Every fetch is guarded against SSRF and
  DNS rebinding.
- **Tested like software.** More than 5,000 tests.

## Measured on a test site

<p align="center">
  <img src="assets/benchmark.svg" width="100%" alt="The benchmark run on a test site: 101 of 101 planted defects found, 0 false findings with 26 clean pages included, the same score and the same 81 findings on two runs, 500 pages from crawl to HTML report in 1.8 s, no model calls and no API keys.">
</p>

The test site was written together with the checks. The numbers show that every
check finds what it was built to find; they do not compare Searchwright with
other tools. Measured on 2026-11-19 on an Apple M1 Pro.

## Access and rights

Searchwright is not distributed from this repository. The text and images here
may not be reused without written permission, see [LICENSE](LICENSE).
