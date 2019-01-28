<!DOCTYPE html>
<html>
<head>
    <title>Example</title>
    <link rel="stylesheet" type="text/css" href="{{ "/assets/style.css" | relative_url }}">
</head>
<body>

<header>
    <span class="logo"><a href="">site name</a></span> 
    <ul class="navigation">
        {% assign sorted = site.pages | sort: 'order' %}
        {% for page in sorted %}
        {% if page.title %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
        {% endif %}
        {% endfor %}
    </ul>
</header>

<content>
{{ content }}
</content>

</body>
</html>