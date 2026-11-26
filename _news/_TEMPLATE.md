---
# HOW TO ADD NEWS
# Copy this file into _news/ and name it after the date and topic,
# e.g. _news/2026-09-15-conference-talk.md. (Files starting with "_",
# like this one, are ignored by the site.)
#
# SHORT ITEM (one line in the news list, no page of its own):
#   set inline: true, delete the title line and everything below the
#   closing "---" except one sentence.
#
# FULL STORY (clickable title in the news list, opens its own page):
#   keep inline: false and a title, then write the story below.
#   Put photos in assets/img/news/ and show them with the blocks below.

layout: post
title: Title of the news story
date: 2026-09-15
inline: false
related_posts: false
---

Write the story here. Normal Markdown works: **bold**, _italic_, [links](https://example.com).

<!-- One photo with a caption -->
<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/news/photo1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Caption for the photo.</div>

<!-- Two or three photos side by side: add one "col-sm" block per photo -->
<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/news/photo2.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/news/photo3.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Caption for this row of photos.</div>
