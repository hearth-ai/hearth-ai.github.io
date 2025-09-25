---
layout: default
title: Contact Us
description: Get in touch with the Hearth team. We'd love to hear from you and answer any questions you might have.
---

<div class="contact-hero">
    <div class="container">
        <h1>Join the Waitlist</h1>
        <p>Be the first to experience Hearth when we launch. Get early access and exclusive updates.</p>
    </div>
</div>

<section class="contact-content">
    <div class="container">
        <div class="waitlist-form">
            <form id="waitlist-form" action="https://formsubmit.co/da96a2026632ab98728ecb05052a0dc1" method="POST">
                <input type="hidden" name="_subject" value="New Waitlist Signup - Hearth">
                <input type="hidden" name="_next" value="https://hearth-ai.github.io/contact.html?success=true">
                <input type="hidden" name="_captcha" value="false">
                
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email address" required>
                </div>
                
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" placeholder="Enter your full name" required>
                </div>
                
                <div class="form-group">
                    <label for="family-size">Family Size</label>
                    <select id="family-size" name="family-size" required>
                        <option value="">Select family size</option>
                        <option value="1">Just me</option>
                        <option value="2">2 people</option>
                        <option value="3">3 people</option>
                        <option value="4">4 people</option>
                        <option value="5">5 people</option>
                        <option value="6+">6+ people</option>
                    </select>
                </div>
                
                <button type="submit" class="btn-primary">Join the Waitlist</button>
            </form>
            
            <div id="success-message" style="display: none; margin-top: 2rem; padding: 1rem; background: #d4edda; color: #155724; border-radius: 8px; text-align: center;">
                <strong>Thank you for joining our waitlist!</strong><br>
                We'll be in touch soon with updates about Hearth.
            </div>
            
            <script>
            // Check if redirected from successful submission
            if (window.location.search.includes('success=true')) {
                document.getElementById('waitlist-form').style.display = 'none';
                document.getElementById('success-message').style.display = 'block';
            }
            </script>
        
        </div>
    </div>
</section>
