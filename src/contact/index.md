---
layout: base.njk
title: Contact
permalink: /contact/
---

<section class="contact">
  <div class="container flow">
    <div class="inner-container two-column">
      <!-- FurEver logo, replace with FurEver logo image -->
      <img src="/images/fur-ever-logo.png" alt="FurEver logo" width="400" height="400" class="contact-logo">
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
  .contact {
    background-color: var(--color-neutral-100); /* Light background for contact section */
    padding: var(--space-xl) 0;
  }

  .contact-logo {
    border-radius: 8px;
    max-width: 100%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .section-title {
    color: var(--color-primary);
    font-size: var(--font-size-lg);
    margin-top: var(--space-lg);
  }

  .form-container {
    background-color: var(--color-neutral-200); /* Lighter background for the form */
    padding: var(--space-lg);
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 600px;
    margin: auto;
  }

  .form-field {
    margin-bottom: var(--space-md);
  }

  .form-field label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: var(--font-weight-bold);
  }

  .form-field input,
  .form-field textarea {
    width: 100%;
    padding: var(--space-sm);
    border: 1px solid var(--color-neutral-500);
    border-radius: var(--radius-sm);
    font-size: var(--font-size-md);
    margin-top: 0.5rem;
  }

  .form-btn-container {
    display: flex;
    justify-content: center;
    margin-top: var(--space-lg);
  }

  .btn--primary {
    background-color: var(--color-accent); /* Using FurEver accent color */
    color: var(--color-neutral-100);
    padding: var(--space-md) var(--space-lg);
    border: none;
    border-radius: var(--radius-md);
    font-size: var(--font-size-lg);
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease;
  }

  .btn--primary:hover {
    background-color: var(--color-secondary);
    transform: scale(1.05);
  }

  .btn--primary:focus {
    outline: 2px solid var(--color-primary);
  }

  /* Responsiveness */
  @media (max-width: 767px) {
    .contact-logo {
      width: 100%;
      height: auto;
    }

    .inner-container {
      flex-direction: column;
      text-align: center;
    }

    .form-container {
      padding: var(--space-md);
    }
  }
</style>
