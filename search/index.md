---
layout: search
title: Search Results
---

<section class="hero">
    <a href="#search" class="search-toggle js-header-toggle">Search</a>
    <form id="search" class="site-search" action="{{ site.baseurl }}/search/" method="get" role="search">
        <div class="content">
            <label for="site-search-text">Search</label>
            <input type="text" id="site-search-text" class="js-search-focus" name="query">
            <input class="submit" type="submit" value="Search">
        </div>
        <input type="hidden" name="show_organisations_filter" value="true">
    </form>
</section>
<!-- content for this page is in _layouts/search.html -->
