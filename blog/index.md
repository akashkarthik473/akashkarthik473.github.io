---
layout: page
title: Blog
description: Read about my coding journey and Formula SAE/Spartan Racing adventures
---

# Blog 📝

Welcome to my blog! Here I share my experiences, learnings, and adventures in coding and Formula SAE/Spartan Racing at San Jose State University.

## Categories

- **[Coding](/blog/categories/coding/)** - Programming projects, tutorials, and tech insights
- **[Formula SAE](/blog/categories/formula-sae/)** - Racing team updates, car development, and competition experiences
- **[Learning](/blog/categories/learning/)** - Educational content and skill development
- **[Projects](/blog/categories/projects/)** - Showcase of my coding projects

## Recent Posts

{% raw %}{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %-d, %Y" }}*
{% if post.categories.size > 0 %}
**Categories:** {% for category in post.categories %}[{{ category }}](/blog/categories/{{ category | downcase }}/){% unless forloop.last %}, {% endunless %}{% endfor %}
{% endif %}

{{ post.excerpt | strip_html | truncatewords: 50 }}

---
{% endfor %}{% endraw %}

## Subscribe

Want to stay updated? You can:
- Follow me on [GitHub](https://github.com/akashkarthik473) for project updates
- Connect on [LinkedIn](https://linkedin.com/in/akash-karthik473) for professional updates
- Check back here regularly for new posts!

---

*Have a topic you'd like me to write about? Feel free to [reach out](mailto:akashkarthik473@gmail.com)!* 