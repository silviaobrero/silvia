---
layout: base
title: Silvia Obrero
subtitle: Let me teach you Spanish!
meta-title: "Hi, I'm Silvia"
use-site-title: true
cover-img:
  - "/assets/img/chalkboard.jpg"
css:
  - /assets/css/index.css
---

<div id="header" markdown="1">

# Silvia Obrero {#title}

## Let me teach you Spanish! {#subtitle}

</div>

<div id="main-sections" style="margin-top:-30px;">

<div id="services-out" class="page-section">
  <div id="services">
	<div class="section-title">Services</div>
	<div id="services-list">
	  <span class="service" markdown="1">Teaching Spanish Language to people of all ages and levels</span>
	  <span class="service" markdown="1">Offering reinforcement classes for your kids Spanish school lessons</span>
	  <span class="service" markdown="1">In person, one on one and group classes in Dubai, UAE</span>
	  <span class="service" markdown="1">Online classes for international students around the world</span>
	</div>

    <a href="/contact" class="contact-me-btn actionbtn">
      <span class="far fa-envelope" aria-hidden="true"></span>
      CONTACT
    </a>
  </div>
</div>

<div id="aboutme-section-out" class="page-section">
  <div id="aboutme-section">
    <div class="section-title">About Silvia</div>
	<div id="aboutme-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
</div>


<div id="qualifications-out" class="page-section">
  <div id="qualifications">
    <div class="section-title">Silvia's Credentials</div>
    <div id="qualifications-list" markdown="1">
{% for info in site.data.qualifications %}
<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
  <a href="/contact" class="contact-me-btn actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    CONTACT
  </a>
</div>

</div>

