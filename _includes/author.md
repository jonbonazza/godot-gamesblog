{% assign author = site.authors[page.author] %}
{% if author %}
Written by {{ author.name }}
{% else %}
Author unknown
{% endif %}
