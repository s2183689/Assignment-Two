---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/overriding-theme-defaults
list_title: Team Members
layout: home
---

<h1>Welcome to Project X</h1>

We are currently at the stage of submitting Assignment 2.  The only content here at this stage is the team profile.

<h2>Assignment Progress</h2>
<img src="/assets/progress.svg" style="width:100%;">

When assignments 3, 4 and 5 are completed this site will be updated and styled to match the final product design of our project.


<h2>Team Members</h2>

Feel free to read a little about each of us.

<ul>
  {%- for post in site.posts -%}
  <li><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></li>
  {%- endfor -%}
</ul>


