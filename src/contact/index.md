---
layout: base.njk
title: Contact
permalink: /contact/
---

<section class="contact">
  <div class="container flow">
    <div class="inner-container two-column">
     
      <img src="images/pawprint.jpg" alt="FurEver logo" width="400" height="400" class="contact-logo">
      <h2 class="section-title">Contact Us</h2>
    </div>
  </div>

  <div class="form-container">
    <form name="contact" method="POST" data-netlify="true" id="contact-form">
      <input type="hidden" name="form-name" value="contact">

      <div class="form-field">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
      </div>
      <div class="form-field">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-field">
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
      </div>

      <!-- Send Button -->
      <div class="form-btn-container">
        <button type="submit" class="btn--primary">Send</button>
      </div>
    </form>
  </div>
</section>

<style>
 