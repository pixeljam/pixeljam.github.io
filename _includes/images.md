{% if page.postImages %}
  {% if include.param == "image1" %}
    {% if page.postImages.image1-url contains 'http' %}
<a href="{{page.postImages.image1-url}}" class="{{page.postImages.image1-position}} image lightbox {{page.postImages.image1-size}}">
<img src="{{page.postImages.image1-url}}" alt="{{page.postImages.image1-title}}">
</a>
    {% else %}
  <a href="{{ page.postImages.image1-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image1-position}} image lightbox {{page.postImages.image1-size}}">
  <img src="{{ page.postImages.image1-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image1-title}}">
  </a>
    {% endif %}

  {% elsif include.param == "image2" %}
    {% if page.postImages.image2-url contains 'http' %}
  <a href="{{page.postImages.image2-url}}" class="{{page.postImages.image2-position}} image lightbox {{page.postImages.image2-size}}">
  <img src="{{page.postImages.image2-url}}" alt="{{page.postImages.image2-title}}">
  </a>
    {% else %}
<a href="{{ page.postImages.image2-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image2-position}} image lightbox {{page.postImages.image2-size}}">
<img src="{{ page.postImages.image2-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image2-title}}">
</a>
    {% endif %}


{% elsif include.param == "image3" %}
  {% if page.postImages.image3-url contains 'http' %}
<a href="{{page.postImages.image3-url}}" class="{{page.postImages.image3-position}} image lightbox {{page.postImages.image3-size}}">
<img src="{{page.postImages.image3-url}}" alt="{{page.postImages.image3-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image3-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image3-position}} image lightbox {{page.postImages.image3-size}}">
  <img src="{{ page.postImages.image3-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image3-title}}">
  </a>
  {% endif %}

{% elsif include.param == "image4" %}
  {% if page.postImages.image4-url contains 'http' %}
<a href="{{page.postImages.image4-url}}" class="{{page.postImages.image4-position}} image lightbox {{page.postImages.image4-size}}">
<img src="{{page.postImages.image4-url}}" alt="{{page.postImages.image4-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image4-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image4-position}} image lightbox {{page.postImages.image4-size}}">
  <img src="{{ page.postImages.image4-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image4-title}}">
  </a>
  {% endif %}


{% elsif include.param == "image5" %}
  {% if page.postImages.image5-url contains 'http' %}
<a href="{{page.postImages.image5-url}}" class="{{page.postImages.image5-position}} image lightbox {{page.postImages.image5-size}}">
<img src="{{page.postImages.image5-url}}" alt="{{page.postImages.image5-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image5-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image5-position}} image lightbox {{page.postImages.image5-size}}">
  <img src="{{ page.postImages.image5-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image5-title}}">
  </a>
  {% endif %}

{% elsif include.param == "image6" %}
  {% if page.postImages.image6-url contains 'http' %}
<a href="{{page.postImages.image6-url}}" class="{{page.postImages.image6-position}} image lightbox {{page.postImages.image6-size}}">
<img src="{{page.postImages.image6-url}}" alt="{{page.postImages.image6-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image6-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image6-position}} image lightbox {{page.postImages.image6-size}}">
  <img src="{{ page.postImages.image6-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image6-title}}">
  </a>
  {% endif %}

{% elsif include.param == "image7" %}
  {% if page.postImages.image7-url contains 'http' %}
<a href="{{page.postImages.image7-url}}" class="{{page.postImages.image7-position}} image lightbox {{page.postImages.image7-size}}">
<img src="{{page.postImages.image7-url}}" alt="{{page.postImages.image7-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image7-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image7-position}} image lightbox {{page.postImages.image7-size}}">
  <img src="{{ page.postImages.image7-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image7-title}}">
  </a>
  {% endif %}

{% elsif include.param == "image8" %}
  {% if page.postImages.image8-url contains 'http' %}
<a href="{{page.postImages.image8-url}}" class="{{page.postImages.image8-position}} image lightbox {{page.postImages.image8-size}}">
<img src="{{page.postImages.image8-url}}" alt="{{page.postImages.image8-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image8-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image8-position}} image lightbox {{page.postImages.image8-size}}">
  <img src="{{ page.postImages.image8-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image8-title}}">
  </a>
  {% endif %}

{% elsif include.param == "image9" %}
  {% if page.postImages.image9-url contains 'http' %}
<a href="{{page.postImages.image9-url}}" class="{{page.postImages.image9-position}} image lightbox {{page.postImages.image9-size}}">
<img src="{{page.postImages.image9-url}}" alt="{{page.postImages.image9-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image9-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image9-position}} image lightbox {{page.postImages.image9-size}}">
  <img src="{{ page.postImages.image9-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image9-title}}">
  </a>
  {% endif %}


{% elsif include.param == "image10" %}
  {% if page.postImages.image10-url contains 'http' %}
<a href="{{page.postImages.image10-url}}" class="{{page.postImages.image10-position}} image lightbox {{page.postImages.image10-size}}">
<img src="{{page.postImages.image10-url}}" alt="{{page.postImages.image10-title}}">
</a>
  {% else %}
  <a href="{{ page.postImages.image10-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" class="{{page.postImages.image10-position}} image lightbox {{page.postImages.image10-size}}">
  <img src="{{ page.postImages.image10-url | prepend: page.imageFolder | prepend: "/images/" | prepend: site.baseurl  }}" alt="{{page.postImages.image10-title}}">
  </a>
  {% endif %}

{% endif %}
{% endif %}
