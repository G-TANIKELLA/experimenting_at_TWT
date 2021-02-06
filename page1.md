---

layout: template1

Population: 136.64 crores

EthnicGroup: South Indian Vysya

---

# Country: {{site.Country}}
{{site.Country}} is home to {{site.Population}} people.

# Avatars of Lord Vishnu

{% for item in site.data.DataDemo %}
The {{item.incarnation}} Avatar in the form of {{item.type}} was to {{item.purpose}}.




