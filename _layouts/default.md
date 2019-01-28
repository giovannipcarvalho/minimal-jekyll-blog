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
        <li><a href="/">Home</a></li>
        <li><a href="/">About</a></li>
        <li><a href="/">Blog</a></li>
        <li><a href="/">Some</a></li>
        <li><a href="/">Other</a></li>
        <li><a href="/">Stuff</a></li>
        <li><a href="/">Here</a></li>
    </ul>
</header>

<content>
{{ content }}
</content>

</body>
</html>