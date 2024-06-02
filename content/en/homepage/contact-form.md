---
title: "Sign up for the course"
weight: 99
header_menu: true
header_menu_title: "Sign up"
---

- All **classes will be approximately one hour long**, 
but may run a little longer depending on the amount of Q&A 
as these classes are highly interactive.

- **Classes will be held on Zoom and will also be recorded** and sent to you 
so you'll be able to re-watch each session any time you like

- Because this coaching is LIVE, **enrollment will be limited to a maximum number of participants**, so that you will get a chance to get personal feedback.

[//]: # (- **Your instructor**: Alberto Bailoni &#40;Certified Unified Mindfulness Coach by the time the course will start&#41;)


<div class="form-container">
<form action="https://formspree.io/f/YOUR_FORMSPREE_ENDPOINT" method="post" id="registration-form">
<label for="name">Name:</label>
<input type="text" id="name" name="name" required>
                
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>

<label for="location">Location:</label>
<input type="text" id="location" name="location" required>

<div class="g-recaptcha" data-sitekey="YOUR_SITE_KEY"></div>

<input type="submit" value="Submit">
</form>
</div>

<script src="https://www.google.com/recaptcha/api.js" async defer></script>
<script>
        document.querySelector('#registration-form').addEventListener('submit', function (e) {
            var captcha = document.getElementById('captcha').value;
            if (captcha !== '7') {
                e.preventDefault();
                alert('CAPTCHA validation failed!');
            }
        });
</script>
