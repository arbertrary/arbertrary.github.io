---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<html>
   <body style='overflow:hidden; width=50%'>
      <iframe name='my publications' 
          src='https://www.bibsonomy.org/user/abernstetter/myown?items=1000&resourcetype=publication&sortPage=year&sortPageOrder=desc&format=embed' 
          height='500px' 
          width='100%' 
          style='border: none; overflow:hidden;position:relative;'>
      <p>
        Unfortunately, your browser is not capable of showing embedded frames (iframes).
      </p>
      </iframe>
   </body>
</html>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
