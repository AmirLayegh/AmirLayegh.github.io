---
permalink: /
title: "👋🏼 Hello there, I'm Amir!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🎓 I am currently pursuing my PhD in [Distributed Computing group of KTH Royal Institute of Technology](https://dcatkth.github.io/), where I have the privilege of conducting research under the guidance of [Amir H. Payberah](https://payberah.github.io/) and [Mihhail Matskin](https://www.kth.se/profile/misha).

🔍 My research primarily focuses on Information Extraction (IE) through the lens of Large Language Models (LLMs). This study area seeks to uncover structured knowledge from unstructured text. By employing techniques such as Named Entity Recognition (NER), Relation Extraction (RE), and Event Extraction (EE), we aim to identify and classify entities, understand their interrelations, and pinpoint events and their participants, all from plain text.

🏆 Prior to my doctoral studies, I was awarded a distinction MSc degree in Big Data Science from Queen Mary University of London ([QMUL](https://search.qmul.ac.uk/)), further enriching my expertise in data science and computational algorithms. I began my journey in technology with a Bachelor’s degree in Software Engineering from Ferdowsi University of Mashhad.

👨🏻‍🏫 Beyond my research, I am passionate about education and knowledge sharing. I serve as a teaching assistant for courses such as [Modern Methods in Software Engineering](https://www.kth.se/student/kurser/kurs/ID2207?l=en) and [Distributed Artificial Intelligence and Intelligent Agents](https://www.kth.se/student/kurser/kurs/ID2209?l=en).




<!-- ## Latest Blog Posts

### [Hands On Transformers](https://amirlayegh.github.io/posts/2023/10/blog-post-4/)
- **Date**: December, 2023
- **Excerpt**: Explore the intricacies of the Transformer architecture, a cornerstone of modern NLP, through detailed explanations and code examples.

### [Prompt Engineering Guide](https://amirlayegh.github.io/posts/2023/10/blog-post-3/)
- **Date**: November, 2023
- **Excerpt**: This guide compiles the latest papers, and models for prompt engineering to meet the growing interest in LLM development.

Visit the [Blog Section](https://amirlayegh.github.io/year-archive/) for more posts. -->

## Latest Blog Posts

{% for post in site.posts limit:2 %}
- [{{ post.title }}]({{ post.url | absolute_url }}) - *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}

[More Posts](https://amirlayegh.github.io/year-archive/)

<!-- ## Latest Blog Posts

{% for post in site.posts limit:2 %}
### [{{ post.title }}]({{ post.url | absolute_url }})
- **Date**: {{ post.date | date: "%B %d, %Y" }}
- **Excerpt**: {{ post.excerpt | strip_html | truncatewords: 20 }}
{% endfor %}

Visit the [Blog Section](https://amirlayegh.github.io/year-archive/) for more posts. -->
