# README

### Add links to previous and next post
https://github.com/jekyll/minima/pull/557/commits/122814997ed22e80e486e8bdd322f299bf6cdb29

Add to post.html
```
{%- if site.links_to_prev_next -%}
    {%- include links_to_prev_next.html -%}
  {%- endif -%}
```

update time to read formatting

TO-DO
- [Add favicon](https://github.com/pages-themes/cayman/issues/93)
- Change front page to default to site title (rather than page title)
- [Modify navigation](https://jekyllrb.com/tutorials/navigation)