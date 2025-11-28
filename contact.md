---
title: /contact
layout: page
permalink: /contact
---

# Get in touch?

<form id="contact-form" onsubmit="showMessage(); return false;">
  <input type="text" id="name" name="name" placeholder="name:" autocomplete="off">
  <input type="text" id="email" name="email" placeholder="email:" autocomplete="off">
  <textarea rows="5" id="message" name="message" placeholder="message:" autocomplete="off"></textarea>
  <input type="submit" value="[ submit ]">
</form>

<div id="response-message" style="margin-top: 20px; font-family: monospace; color: #333;"></div>

<script>
  function showMessage() {
    var responseDiv = document.getElementById('response-message');
    responseDiv.innerHTML = "haha; thats not how it works. just send me hi on <a href='https://x.com/fedef26'>twitter</a> or email - <a href='mailto:harixh@yahoo.com'>harixh@yahoo.com</a>";
    responseDiv.style.display = 'block';
  }
</script>
