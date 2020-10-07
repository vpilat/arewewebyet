+++
template = "page.html"
page_template = "topic.html"
title = "Topics"
+++

<div>
{% for page in section.pages %}
asdasd
  {% if page.extra.template == "topic.html %}
    <h2><a href="{{page.url}}">{{ page.title | safe }}</a>  
    {% include level.html level=page.level %}</h2>

    {% if page.intro %}
      {{page.intro | safe }}
    {% endif %}

{% endif %}
{% endfor %}

</div>
