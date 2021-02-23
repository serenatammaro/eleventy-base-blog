---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

Contact Form
<div class="container">
  <label for="fname">First Name</label>
  <input type="text" id="fname" name="firstname" placeholder="Your name..">

  <label for="utype">You are</label>
  <select id="utype" name="usertype">
    <option value="following">Following</option>
    <option value="followed">Followed</option>
  </select>  
  <label for="email"><b>Email</b></label>
  <input type="text" placeholder="Enter email" name="email" required>
</div>