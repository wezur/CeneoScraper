# CeneoScrapper

|Składowa|Selektor|Zmienna|
|--------|--------|-------|
|opinia|div.js_product-review|review|
|id opinii|div.js_product-review\[data-entry-id\]|review_id|
|autor|.user-post__author-name|author|
|rekomendacja|.user-post__author-recomendation > em|recomendation|
|liczba gwiazdek|.user-post__score-count|score_count|
|treść|.user-post__text|content|
|data wystawienia|span.user-post__published > time\[datetime\]:nth-child(1)|publish_date|
|data zakupu|span.user-post__published > time\[datetime\]:nth-child(2)|purchase_date|
|dla ilu przydatna||useful|
|dla ilu nieprzydatna||useless|
|liczba zalet|review-feature|pros|
|liczba wad|review-feature|cons|