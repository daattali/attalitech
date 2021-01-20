---
layout: base
title: "AttaliTech | Expert R-Shiny Consulting"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
ext-js:
  - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# AttaliTech {#title}

## R-Shiny Consulting {#subtitle}

#### Led by World-Renowned Shiny Expert [Dean Attali](https://deanattali.com/) {#sub-subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Contact Us
</a>
{: .actionbtn-out :}

</div>

<div id="particles-js"></div>

</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
	<div class="section-title">What We Offer</div>
	<div id="services-list">
	  <div class="service">
      <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Complex dashboard.png" />
      <div class="service-text">Building or improving Shiny apps of any complexity</div>
    </div>
	  <div class="service">
      <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Successful completion of project.png" />
      <div class="service-text">Expert advice, training, and workshops in Shiny/R</div>
    </div>
    <div id="services-break"></div>
	  <div class="service">
      <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Bug tracking.png" />
      <div class="service-text">Code review and optimization of Shiny apps and workflows</div>
    </div>
	  <div class="service">
      <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Work risk-free.png" />
      <div class="service-text">Professional quality R packages and custom solutions</div>
    </div>
	</div>

    <a href="/contact" class="actionbtn">
      <span class="far fa-envelope" aria-hidden="true"></span>
      Contact Us
    </a>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="aboutme-section-out" class="page-section grey-section cut1">
  <div id="aboutme-section">
    <div class="section-title">About Dean</div>
	<div id="aboutme-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
</div>

<div id="clients-out" class="page-section cut2">
  <div id="clients">
    <div class="section-title">Clients</div>
    <div id="clients-subtitle">Clients range from startups to universities to Fortune 500 companies</div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer portfolio-buffer"></div>

<div id="portfolio-out" class="page-section grey-section">
  <div id="portfolio">
    <div class="section-title">
      Open-Sourced Shiny Apps
    </div>
    <div id="shinyapps-big">
      {% for app in site.data.portfolio %}
	    <div class="shinyapp">
          <a class="applink" href="{{ app.url }}">
            <img class="appimg" src="/assets/img/screenshots/{{ app.img }}" />
            <div class="apptitle">{{ app.title }}</div>
            <div class="appdesc">{{ app.description }}</div>
          </a>
        </div>
	  {% endfor %}
    </div>
  </div>
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Take Your Shiny Apps to the Highest Level</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>

