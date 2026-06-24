# Node Bloom — How AI Search Chooses What to Cite

An interactive visualization of how AI answer engines — **ChatGPT, Perplexity,
Gemini, Claude** — crawl the open web through the classic indexes
(**Google, Bing, Brave**) and **cite** trusted sources inside their answers.
AEO/GEO, made visible.

Sources start as faint sparks. As an engine searches and cites them, they
**crystallize into faceted gems** — visibility earned through citation, not
ranking. The piece reads the shift from *ranked links* to *cited sources*.

**Built with:** vanilla JavaScript + HTML5 canvas. No libraries, no build step —
a single self-contained `index.html`.

**Concept & interaction**
- Cyan waves = an index crawling the open web
- Gold streams = a source cited *through* its index, then growing
- Click a source to add one, drag to reshape the web, click an engine to run a query
- `publish` injects fresh sources · `de-index` clears the web

---

Designed + coded by **Nora Genetti** — PlayPlayCode
[Portfolio](https://playplayplay.myportfolio.com/) ·
[LinkedIn](https://www.linkedin.com/in/ngenetti/) ·
SEOAICo.com
