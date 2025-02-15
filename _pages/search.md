---
title: Search
author: Victor Silva
layout: page
permalink: /search/
---

<div id="search-container">
  <input type="text" id="search-input" placeholder="">
  <ul id="results-container"></ul>
</div>

<script src="/assets/js/jekyll-search.min.js" type="text/javascript"></script>
<script type="text/javascript">
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
  searchResultTemplate: '<li><a href="{url}" title="{desc}">{title}</a></li>',
  limit: 50,
})
</script>
