---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-embed">
  <p class="notice--info">
    <strong>Note:</strong> If the PDF doesn't display below, please <a href="{{ base_path }}/files/CV.pdf" target="_blank">click here to download it</a>.
  </p>
  <iframe src="{{ base_path }}/files/CV.pdf" width="100%" height="800px" frameborder="0"></iframe>
</div>

<style>
.cv-embed {
  margin-top: 2em;
}

.cv-embed .notice--info {
  margin-bottom: 1.5em;
}

.cv-embed iframe {
  border: 1px solid #e0e0e0;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

@media (max-width: 768px) {
  .cv-embed iframe {
    height: 600px;
  }
  
  .cv-download .btn {
    font-size: 1em;
    padding: 0.6em 1.5em;
  }
}
</style>