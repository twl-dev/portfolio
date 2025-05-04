---
title: "Contact Me"
date: 2024-10-01
layout: "contact"
---

I'd love to hear from you! Please fill out the form below and I will get back to you as soon as possible.

<form
  action="https://formspree.io/f/mwpedjgn"
  method="POST"
  class="contact-form"
>
  <div class="form-group">
    <label for="name">Your Name:</label>
    <input type="text" id="name" name="name" required>
  </div>
  
  <div class="form-group">
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email" required>
  </div>
  
  <div class="form-group">
    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject">
  </div>
  
  <div class="form-group">
    <label for="message">Your Message:</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>
  
  <button type="submit" class="submit-btn">Send Message</button>
</form>

<style>
.contact-form {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  background: #222;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.3);
  color: #fff;
}

.form-group {
  margin-bottom: 20px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
  color: #ddd;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px;
  background-color: #333;
  border: 1px solid #444;
  border-radius: 4px;
  font-size: 16px;
  color: #fff;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #666;
  box-shadow: 0 0 5px rgba(255,255,255,0.1);
}

.submit-btn {
  background-color: #4d8;
  color: #222;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
  font-weight: bold;
}

.submit-btn:hover {
  background-color: #5e9;
}
</style>

Thank you for reaching out!