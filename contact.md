---
layout: page
title: "Contact"
permalink: /contact/
---

<p style="margin-bottom: 20px;">Find me on [LinkedIn](https://www.linkedin.com/in/danieloran/), or...</p>
    
<form action="https://api.web3forms.com/submit" method="POST" style="display: flex; flex-direction: column; width: 100%; max-width: 400px;">

    <input type="hidden" name="access_key" value="a7b7d727-327e-4893-81d4-c9c46757a742">

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required style="margin-bottom: 10px; padding: 12px; height: 20px;">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required style="margin-bottom: 10px; padding: 12px; height: 20px;">

    <label for="message">Message:</label>
    <textarea id="message" name="message" required style="margin-bottom: 20px; padding: 12px; height: 120px;"></textarea>

    <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

    <button type="submit" style="padding: 12px; background-color: #007bff; color: white; border: none; cursor: pointer;">Send</button>
    
</form>
