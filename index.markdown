---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Procedural Runtime Plugins
hero-text: The power of CityEngine in your favorite tool
description: Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

legal-title: Legal
legal-text: Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

related-topic-1-title: Related Topic 1
related-topic-1-text: when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently
related-topic-1-link: asdf1

related-topic-2-title: Related Topic 2
related-topic-2-text: when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently
related-topic-2-link: asdf2

related-topic-3-title: Related Topic 3
related-topic-3-text: when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently
related-topic-3-link: asdf3
---

<section class="hero">
  <div class="content">
    <div class="left-column horizontal center">
      <h1 class="hero-text">{{ page.hero-text }}</h1>
    </div>
    <div class="half">
    </div>
  </div>
</section>

<section class="intro-section">
  <div class="content">
    <div class="left-column">
      <p class="white">{{ page.description }}</p>
    </div>
  </div>
</section>

<section class="lightgrey">
  <div class="content vertical center">
    <h2 class="subtitle bottom-margin-70">CityEngine Plugins</h2>
    <div class="horizontal center">
      {% assign pluginsinorder = site.plugins | sort:'order-of-appearance' %}
      {% for item in pluginsinorder %}
        {% if item.draft == false %}
          {% if item.fullpreview == false %}
          <div class="horizontal small-teaser">
              <img src="{{ site.baseurl }}/assets/img/{{item.logo}}" class="inline-icon"/>
              <div class="vertical">
                  <h4 class="subtitle3">{{ item.platform }}</h4>
                  <h3 class="subtitle2">{{ item.title }}</h3>
                  <a class="link" href="{{ item.link }}">
                      <a href="{{item.name}}" class="text-small">
                          More<span> →</span>
                      </a>
                  </a>
              </div>
          </div>
          {% endif %}
        {% endif %}
      {% endfor %}
    </div>
  </div>
</section>

<section>
  <div class="content flex vertical center">
    <div flex horizontal>
    {% assign pluginsinorder = site.plugins | sort:'order-of-appearance' %}
    {% for item in pluginsinorder %}
      {% if item.draft == false %}
        {% if item.fullpreview == true %}
        <div class="content {% cycle '', 'reverse' %} horizontal bottom-margin-100">
            <div class="half">
                <img class="image-shadow" src="{{ site.baseurl }}/assets/img/{{item.teaser-image}}"/>
            </div>
            <div class="half vertical">
                <div class="horizontal">
                    <img src="{{ site.baseurl }}/assets/img/{{item.logo}}" class="inline-icon"/>
                    <div class="vertical">
                        <h4 class="subtitle3">{{item.platform}}</h4>
                        <h3 class="subtitle">{{item.name}}</h3>
                    </div>
                </div>
                <p>{{item.description}}</p>
                <a class="link">
                    <p class="link text">
                        More<span> →</span>
                    </p>
                </a>
            </div>
        </div>
        {% endif %}
      {% endif %}
    {% endfor %}
    </div>
  </div>
</section>

<section class="darkgrey">
  <div class="content horizontal">
    <div class="third">
      <h3 class="subtitle4 white">{{page.related-topic-1-title}}</h3>
      <p class="white">{{page.related-topic-1-text}}</p>
      <a href="related-topic-1-link" class="white">More<span> →</span></a>
    </div>
    <div class="third">
      <h3 class="subtitle4 white">{{page.related-topic-2-title}}</h3>
      <p class="white">{{page.related-topic-2-text}}</p>
      <a href="related-topic-2-link" class="white">More<span> →</span></a>
    </div>
    <div class="third">
      <h3 class="subtitle4 white">{{page.related-topic-3-title}}</h3>
      <p class="white">{{page.related-topic-3-text}}</p>
      <a href="related-topic-3-link" class="white">More<span> →</span></a>
    </div>
  </div>
</section>

<section>
  <div class="content">
    <h2 class="subtitle bottom-margin-30">{{ page.legal-title }}</h2>
    <p>{{page.legal-text}}</p>
  </div>
</section>
