---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications & preprints
------
1. An Alternative Approach to Computing $\beta(2k + 1)$. (With N. Tanabe) Integers 23 (2023). [pdf](http://math.colgate.edu/~integers/x72/x72.pdf) & [link to journal's site.](http://math.colgate.edu/~integers/vol23.html)
2. Walking to Infinity on the Fibonacci Sequence. (With S. Miller, F. Peng, T. Popescu) Fibonacci Quart. 60 (2022), no. 5, pp. 293-299. [pdf](https://www.fq.math.ca/Papers1/60-5/miller2.pdf) & [link to journal's site.](https://www.fq.math.ca/60-5.html) 
3. Modeling Random Walks to Infinity on Primes in $\mathbb{Z}[\sqrt{2}]$.  (With B. Li, S. Miller, D. Sarnecki, T. Popescu)
J. Integer Seq. 25 (2022), 21 pp. [pdf](http://ploynawapan.github.io/files/miller11.pdf) & [link to journal's site.](https://cs.uwaterloo.ca/journals/JIS/vol25.html)
4. Walking to Infinity Along Some Number Theory Sequences. (With Steven J. Miller, Fei Peng, Tudor Popescu, and the Polymath REU program) arXiv preprint, arXiv:2010.14932. [link to arXiv.](https://arxiv.org/abs/2010.14932)
------ 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
