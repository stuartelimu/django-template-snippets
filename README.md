# django-template-snippets README

A collection of built-in template tags and filters for django templates.

## Installation
Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.
```
ext install StuartElimu.django-template-snippets
```

## Cheat sheet
The `|` character shows the cursor positions where you can insert or change content.

All unknown abbreviations will be transformed to HTML tag, e.g. foo → `<foo></foo>`.

### Template tags

blk 
```
{% block content %}{% endblock content %}
```
There are a couple of options for different types of block e.g title, content.

---

com
```
{% comment %}|{% endcomment %}
```


csrf
```
{% csrf_token %}
```


ext
```
{% extends 'base.html' %}
```
By default `base.html` is suggested but you can change the name of the file.

---

for 
```
{% for | in | %}
    |
{% endfor %}
```


foremp 
```
{% for | in | %}
    |
{% empty %}
    |
{% endfor %}
```

if
```
{% if | %}
    |
{% endif %}

```
incl
```
{% include 'partial.html' %}
```

ld
```
{% load static %}
```

sta
```
{% static 'images/hi.jpg' %}
```
url
```
{% url '|' | %}
```
wi
```
{% with |=| %}
    |
{% endwith %}
```
{{
```
{{ | }}
```

{#
```
{# | #}
```

## Usage

![](usage.gif)

## Release Notes

### 0.0.1

Initial release of django-template-snippets.

### 0.2.0

Add more template tags, change syntax and update README.md with cheat sheet.



