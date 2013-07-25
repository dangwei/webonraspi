---
title: Blogs
description: My blogs
---

{{# posts_latest }}
<div class="post">
  <h1 class="title"><a href="{{url}}">{{title}}</a> <span class="date">{{ date }}</span></h1>

  {{{ summary }}}

  <div class="more">
    <a href="{{url}}" class="btn btn-small">Read more</a>
  </div>
</div>
{{/ posts_latest }}

<div class="pagination">
  <ul>
      <li><a href="/posts/2/">More...</a></li>
  </ul>
</div>
