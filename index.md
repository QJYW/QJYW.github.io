=====================

## Little Q

### Podcast lover

![ChangeMe](https://www.apple.com/v/apple-podcasts/c/images/overview/hero_icon__c135x5gz14mu_large_2x.png)

<img src="./figures/DSC04160.JPG" width="150">


[My GitHub](https://github.com/qjyw)

[About this site](https://qjyw.github.io/about)

=====================

### In A Nutshell

> Affogato food truck sint, kinfolk yr cornhole single-origin coffee artisan chambray banh mi. Selfies authentic cred crucifix, flexitarian thundercats cronut pug disrupt health goth. Crucifix magna ex, etsy kale chips tote bag jean shorts.

Please refer to my [post]({% post_url 2023-06-16-my_thoughts %})

=====================

### Podcast review

{% for tag in site.tags %}
  {% if tag[0] == "podcast" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  {% endif %}
{% endfor %}

=====================

### Series review

