---
layout: page
title: "Contact"
permalink: /contact/
---

<form action="https://api.web3forms.com/submit" method="POST" style="display: flex; flex-direction: column; max-width: 370px;">
    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required style="margin-bottom: 10px; padding: 12px; height: 20px;">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required style="margin-bottom: 10px; padding: 12px; height: 20px;">

    <label for="message">Message:</label>
    <textarea id="message" name="message" required style="margin-bottom: 20px; padding: 12px; height: 120px;"></textarea>

    <button type="submit" style="padding: 12px; background-color: #007bff; color: white; border: none; cursor: pointer;">Send</button>
</form>
