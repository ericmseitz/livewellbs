---
layout: default
title: Contact
---

<section class="py-5">
  <div class="container">
    <h2 class="fw-bold mb-4">Contact Live Well Belmont Shore</h2>
    <p class="lead mb-4">
      Have questions or want to get involved? Fill out the form below to join our list or send us a message.
    </p>

    <!-- Embedded Google Form (responsive) -->
    <div class="ratio ratio-4x3" style="max-width: 800px;">
      <iframe
        title="Live Well Belmont Shore — Join / Contact Form"
        src="https://docs.google.com/forms/d/e/1FAIpQLSc5nWUPPiG4oy_FVGWxxtE06QO8kV_MBfKVf0CFRiW10iG4kg/viewform?embedded=true"
        width="100%"
        height="900"
        frameborder="0"
        marginheight="0"
        marginwidth="0">
        Loading…
      </iframe>
    </div>

    <hr class="my-5">

    <h3 class="h5 fw-bold mb-3">Other ways to reach us</h3>
    <ul class="list-unstyled">
      {% if site.social.instagram %}
      <li class="mb-1">Instagram: <a href="https://instagram.com/{{ site.social.instagram }}" target="_blank" rel="noopener">instagram.com/{{ site.social.instagram }}</a></li>
      {% else %}
      <li class="mb-1 text-muted">Instagram: add your handle in <code>_config.yml</code> under <code>social.instagram</code></li>
      {% endif %}
    </ul>
  </div>
</section>
