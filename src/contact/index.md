---
layout: base.njk
title: Contact
permalink: /contact/
---

<section class="contact">
  <div class="container flow">
    <div class="inner-container two-column">
      <!-- Keep the image of the logo as requested -->
      <img src="images/pawprint.jpg" alt="FurEver logo" width="400" height="400" class="contact-logo">
      <h2 class="section-title">Contact Us</h2>
    </div>
  </div>

  <div class="contact-info">
    <p class="contact-description">
      Thank you for your interest in FurEver Home Pet Rescue! We are dedicated to finding loving homes for our furry friends, and we'd love to hear from you. Whether you're interested in adopting a pet, volunteering, or simply learning more about what we do, we're here to help.
    </p>
    
    <h3 class="contact-subtitle">Our Address</h3>
    <p>1234 Pet Rescue Lane,</p>
    <p>City, State, 56789</p>

    <h3 class="contact-subtitle">Phone</h3>
    <p>(123) 456-7890</p>

    <h3 class="contact-subtitle">Email</h3>
    <p>info@fureverhome.org</p>
    
    <p>If you have any questions or would like to learn more, feel free to reach out via the form below or by contacting us directly. We look forward to hearing from you!</p>
  </div>

  <!-- Contact Form -->
  <div class="contact-form-container">
    <form name="contact" method="POST" data-netlify="true" id="contact-form">
      <input type="hidden" name="form-name" value="contact">

      <div class="contact-form-field">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name">
      </div>

      <div class="contact-form-field">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email address">
      </div>

      <div class="contact-form-field">
        <label for="message">Message:</label>
        <textarea id="message" name="message" required placeholder="How can we assist you?"></textarea>
      </div>

      <!-- Send Button -->
      <div class="contact-form-btn-container">
        <button type="submit" class="btn--primary">Send</button>
      </div>
    </form>
  </div>
</section>
