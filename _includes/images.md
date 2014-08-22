
{% if page.postImages %}
  {% if include.param == "image1" %}
<a href="" class="{{page.postImages.image1-position}} image lightbox {{page.postImages.image1-size}}">
<img src="{{page.postImages.image1-url}}" alt="{{page.postImages.image1-title}}">
</a>
  {% elsif include.param == "image2" %}
<a href="" class="{{page.postImages.image2-position}} image lightbox {{page.postImages.image2-size}}">
<img src="{{page.postImages.image2-url}}" alt="{{page.postImages.image2-title}}">
</a>
{% elsif include.param == "image3" %}
<a href="" class="{{page.postImages.image3-position}} image lightbox {{page.postImages.image3-size}}">
<img src="{{page.postImages.image3-url}}" alt="{{page.postImages.image3-title}}">
</a>
{% elsif include.param == "image4" %}
<a href="" class="{{page.postImages.image4-position}} image lightbox {{page.postImages.image4-size}}">
<img src="{{page.postImages.image4-url}}" alt="{{page.postImages.image4-title}}">
</a>
{% elsif include.param == "image5" %}
<a href="" class="{{page.postImages.image5-position}} image lightbox {{page.postImages.image5-size}}">
<img src="{{page.postImages.image5-url}}" alt="{{page.postImages.image5-title}}">
</a>
  {% endif %}
{% endif %}
