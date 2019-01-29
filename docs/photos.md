---
layout: default
images:
- image_path: /images/bird-at-lake.jpg
  title: bird at lake
  url: https://500px.com/photo/291003601/a-brown-headed-gull-at-pangong-tso-by-sumit-gupta
- image_path: /images/sambar.jpg
  url: https://500px.com/photo/291018359/curious-sambar-deer-by-sumit-gupta
  title: curious sambar
- image_path: /images/green-viper.jpg
  title: deadly and deceptive
  url: https://500px.com/photo/291099029/closeup-of-a-green-pit-viper-by-sumit-gupta
- image_path: /images/hoi-an.jpg
  title: Hoi an 
  url: https://500px.com/photo/291463653/a-dusk-in-the-old-town-h%E1%BB%99i-an-by-sumit-gupta
- image_path: /images/bird-on-branch.jpg
  title: bird on branch
  url: https://500px.com/photo/291030945/a-cormorant-is-looking-for-a-fish-by-sumit-gupta

- image_path: /images/borobudur.jpg
  title: borobudur
  url: https://500px.com/photo/291099029/closeup-of-a-green-pit-viper-by-sumit-gupta

- image_path: /images/hummingbird.jpg
  title: hummingbird
  url: https://500px.com/photo/291099029/closeup-of-a-green-pit-viper-by-sumit-gupta
---

<ul class="gallery">
  {% for image in page.images %}
  <li><a href="{{ image.url }}" target="_blank"> <img src="{{ image.image_path }}" alt="{{ image.title}}"/></a></li>
  {% endfor %}
</ul>
