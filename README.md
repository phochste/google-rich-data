We moved https://codeberg.org/phochste/google-rich-data

# Google Rich Snippets

See also https://developers.google.com/search/docs/appearance/structured-data/article.

To test the results: https://search.google.com/test/rich-results (use the "code" tab).

## Remarks

- I'm using `description` instead of title because Google apparently prefers this for https://schema.org/ScholarlyArticle (and also in Google SEO).
- One can express a `description` as a string in JSON-LD or a array of hashes containing `@value` and `@language` properties.
