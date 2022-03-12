--- 
layout: compress
---
<!doctype html>
<html lang="en">
    <title>{% if page.title %}{{ page.title }} – {% endif %}{{ site.title }}</title>
    {% include snap.html %}
    {% include header.html %}
    {% include meta.html %}
    <body class="snap">
        {% include copyright.html %}
        {% include navbar.html %}
        {% include loader.html %}
        {{ content }}
    </body>
    {% include footer.html %}
</html>