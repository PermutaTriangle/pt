---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

![Mutate]({{ site.baseurl }}/assets/img/mutation.png){:align="right" height="200px"}
The study of permutation patterns is a very active area of research and has
connections to many other fields of mathematics as well as to computer science
and physics. One of the main questions in the field is the enumeration problem:
Given a particular set of permutations, how many permutations does the set have
of each length? The main goal of this research group is to develop a novel
algorithm which will aid researchers in finding structures in sets of
permutations and use those structures to find generating functions to enumerate
the set. Our research interests lead also into various topics in discrete
mathematics and computer science.

### Members
<ul>
  {% for author in site.authors %}
  {% if author.status == 'member' %}
    <li>
      <p><a href="{{ site.baseurl }}{{ author.url }}">{{ author.name }}</a>,  {{ author.position }}</p>
    </li>
    {% endif %}
  {% endfor %}
</ul>

### Current students
<ul>
  {% for author in site.authors %}
  {% if author.status == 'student' %}
    <li>
      <p><a href="{{ site.baseurl }}{{ author.url }}">{{ author.name }}</a>,  {{ author.position }}</p>
    </li>
    {% endif %}
  {% endfor %}
</ul>