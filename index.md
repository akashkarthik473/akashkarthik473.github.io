---
layout: page
title: Welcome to My Journey
description: Computer Science student at San Jose State University sharing my experiences in coding and Formula SAE/Spartan Racing
---

# Welcome to My Journey! 🚀

Hi there! I'm **Akash Karthik**, a Computer Science student at **San Jose State University**. I'm passionate about coding, engineering, and racing - specifically Formula SAE/Spartan Racing!

## What I'm Up To

### 💻 Coding Journey
I'm constantly learning and building new projects. From web development to algorithms, I love exploring different aspects of computer science and sharing what I learn.

### 🏎️ Formula SAE / Spartan Racing
As part of the software team in Spartan Racing, I'm involved in designing and building the controls software. It's an incredible hands-on  experience that combines mechanical, electrical, and software knowledge.

## Recent Blog Posts

{% raw %}{% assign recent_posts = site.posts | slice: 0, 3 %}
{% for post in recent_posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %-d, %Y" }}*
{{ post.excerpt | strip_html | truncatewords: 30 }}
{% endfor %}{% endraw %}

[View all posts →](/blog/)

## Quick Links

- **[About Me](/about/)** - Learn more about my background and interests
- **[Blog](/blog/)** - Read about my coding and racing adventures
- **[Projects](/projects/)** - Check out my projects
- **[Formula SAE](/formula-sae/)** - Updates on our racing team

## Get in Touch

- 📧 Email: [akashkarthik473@gmail.com](mailto:akashkarthik473@gmail.com)
- 💼 LinkedIn: [Akash Karthik](https://linkedin.com/in/akash-karthik473)
- 🐙 GitHub: [@akashkarthik473](https://github.com/akashkarthik473)

---