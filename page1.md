---

layout: template1

Population: 136.64 crores

EthnicGroup: South Indian Vysya

---

# Country: {{site.country}}
{{site.country}} is home to {{site.population}} people.

# Avatars of Lord Vishnu

{% for item in site.data.DataDemo %}
The {{item.incarnation}} Avatar in the form of {{item.type}} was to {{item.purpose}}.
{% endfor %}




