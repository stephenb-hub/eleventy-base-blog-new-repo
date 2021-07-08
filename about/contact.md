---
layout: layouts/post.njk
title: Contact us
templateClass: tmpl-post
eleventyNavigation:
  key: Contact us
  order: 4
---

Why dont you send us a message!
<br>
    <div id="fcf-form">
     <h3 class="fcf-h3">Contact us</h3>

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>