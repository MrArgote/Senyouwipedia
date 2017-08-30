---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<style>
{% capture style %}

.box-links-to-major-actions {
  ul {
  margin: auto;
  text-align: center;
  }
  ul>a {
    display: inline-block;
    background-color:#FEE;
    background-image:linear-gradient(
    #FFF,
    #FEE
    );
    border-bottom: 0.2em solid #FB1;
    border-left: 0.1em solid #FE6;
    border-right: 0.1em solid #FE6;
    border-radius: 2.4em;
    color: #258;
    margin: 1em;
    padding: 2em;
  }
  li { list-style-type:none; }
}


{% endcapture %}
{{ style | scssify }}
</style>

<div class="box-links-to-major-actions">
  <ul>
    <a href="{{ site.baseurl }}/wiki">
      <li>Read</li>
    </a>
    <a href="https://github.com/MrArgote/Senyouwipedia/new/master/_wiki">
      <li>Write</li>
    </a>
  </ul>
</div>

