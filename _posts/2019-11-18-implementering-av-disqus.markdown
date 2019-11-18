---
layout: post
comments: true
title:  "Implementering av Disqus"
date:   2019-11-18 03:26:46 -0100
categories: Q/A
---
<div class="post-style">
    <h2><strong>Arbetsgång: Disqus</strong></h2>
    <h3>Hur implementerade du Disqus på din sajt?</h3>
    <p>Jag utgick från ett par guider, både Disqus egna tutorial videos men fick också googla mig fram lite för att bättre förstå vilka filer som är bästa att placera koden i.<br>
    Nu ser det ut på följande sätt:</p>
    <ul>
        <li>_includes > disqus_comments.html</li>
        <li>_layouts > post.html</li>
        <li>_post > posts</li>
        <li>_config.yml</li>
    </ul>
    <p>I disqus_comments.html la jag till kodavsnittet varifrån Disqus laddas.<br>
    I post.html la jag in if satsen för att känna av om Disquse ska laddas in eller ej.<br>
    På samliga posts har jag satt comments till true för att ladda in Disqus.<br>
    I _config.yml la jag till shortname.</p>
</div>