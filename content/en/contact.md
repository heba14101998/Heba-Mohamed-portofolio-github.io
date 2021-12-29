---
title: "Contact"
featured_image: "images/contact.jpg"
omit_header_text: true
description: "I'd love to hear from you"
type: page
menu: main

---
{{< form-contact action="https://formspree.io/f/xvolgkzw"  >}}


<form
  action="https://formspree.io/f/xvolgkzw"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>