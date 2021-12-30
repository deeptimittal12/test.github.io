---
layout: page

key: sg-group
lang: de

# sg data moved to _data/sg-group.yml, img in img/team

---


# xxx 

<h1>Steuerungsgruppe</h1>

{% for member in site.data.sg-group.current %}
<div class="team-member">
    <img src="{{ site.baseurl }}/{{ member.image}}" />
    <div class="team-member-info">
        {{ member.text.de | markdownify }}
    </div>
</div>
{% endfor %}

