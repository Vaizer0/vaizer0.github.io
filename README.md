# Truth Novel — Lord of Truth

Standalone single-page reader for the Arabic Truth Novel source.

The published page is assembled by GitHub Actions from .site/part-*.html into a single index.html before deployment. The embedded Lua plugin metadata and source parsing logic are included for reference, and the page loads the live chapter list/content from truthnovel.top.

Translation is optional and runs in the browser through an OpenAI-compatible Web2API endpoint. The default is http://127.0.0.1:8081/v1, matching the uploaded Web2API example; no Gemini API key is embedded in the public site.

GitHub Pages deployment is defined in .github/workflows/pages.yml.
