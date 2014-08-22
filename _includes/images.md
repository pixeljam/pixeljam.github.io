
{% if page.postImages %}
  {% if include.param == "image1" %}
<a href="{{page.postImages.image1-url}}" class="{{page.postImages.image1-position}} image lightbox {{page.postImages.image1-size}}">
<img src="{{page.postImages.image1-url}}" alt="{{page.postImages.image1-title}}">
</a>
  {% elsif include.param == "image2" %}
<a href="{{page.postImages.image2-url}}" class="{{page.postImages.image2-position}} image lightbox {{page.postImages.image2-size}}">
<img src="{{page.postImages.image2-url}}" alt="{{page.postImages.image2-title}}">
</a>
{% elsif include.param == "image3" %}
<a href="{{page.postImages.image3-url}}" class="{{page.postImages.image3-position}} image lightbox {{page.postImages.image3-size}}">
<img src="{{page.postImages.image3-url}}" alt="{{page.postImages.image3-title}}">
</a>
{% elsif include.param == "image4" %}
<a href="{{page.postImages.image4-url}}" class="{{page.postImages.image4-position}} image lightbox {{page.postImages.image4-size}}">
<img src="{{page.postImages.image4-url}}" alt="{{page.postImages.image4-title}}">
</a>
{% elsif include.param == "image5" %}
<a href="{{page.postImages.image5-url}}" class="{{page.postImages.image5-position}} image lightbox {{page.postImages.image5-size}}">
<img src="{{page.postImages.image5-url}}" alt="{{page.postImages.image5-title}}">
</a>
{% elsif include.param == "image6" %}
<a href="{{page.postImages.image6-url}}" class="{{page.postImages.image6-position}} image lightbox {{page.postImages.image6-size}}">
<img src="{{page.postImages.image6-url}}" alt="{{page.postImages.image6-title}}">
</a>
{% elsif include.param == "image7" %}
<a href="{{page.postImages.image7-url}}" class="{{page.postImages.image7-position}} image lightbox {{page.postImages.image7-size}}">
<img src="{{page.postImages.image7-url}}" alt="{{page.postImages.image7-title}}">
</a>
{% elsif include.param == "image8" %}
<a href="{{page.postImages.image8-url}}" class="{{page.postImages.image8-position}} image lightbox {{page.postImages.image8-size}}">
<img src="{{page.postImages.image8-url}}" alt="{{page.postImages.image8-title}}">
</a>
{% elsif include.param == "image9" %}
<a href="{{page.postImages.image9-url}}" class="{{page.postImages.image9-position}} image lightbox {{page.postImages.image9-size}}">
<img src="{{page.postImages.image9-url}}" alt="{{page.postImages.image9-title}}">
</a>
{% elsif include.param == "image10" %}
<a href="{{page.postImages.image10-url}}" class="{{page.postImages.image10-position}} image lightbox {{page.postImages.image10-size}}">
<img src="{{page.postImages.image10-url}}" alt="{{page.postImages.image10-title}}">
</a>
  {% endif %}
{% endif %}
