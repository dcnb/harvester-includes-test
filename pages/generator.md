---
title: Include Generator
layout: about
permalink: /generator.html
custom-foot: js/include-js.html
---

<div class="row justify-content-center">
  <div class="col-md-6">
    <p>Use the form below to generate "include" code for images, documents, and videos.</p>
    <div class="form-group pt-3">
    <select class="custom-select" id="include-type">
        <option value="">Select include type</option>
        <option value="image">Image</option>
        <option value="pdf">PDF</option>
        <option value="video">Video</option>
    </select>
    </div>
    <div id="form-content"></div>
  </div>
  <div class="col-md-10">
    <div id="include-output" class="pt-4"></div>
  </div>
</div>