---
layout: page
title: Contact Us
share-title: AttaliTech | Contact Us
---

<script src="https://www.google.com/recaptcha/api.js" async defer></script>
<script>enableSubmitContact = function(){ document.getElementById("submit_contact").disabled = false; }</script>

For any R/Shiny consulting inquiries, please email [info@attalitech.com](mailto:info@attalitech.com?subject=Shiny consulting inquiry)

Note that before any work can be performed, a (virtual) meeting is usually held to gather requirements and discuss your needs.

<div style="text-align: center;">
<a href="https://calendly.com/attalitech/meeting" class="schedule-btn actionbtn">
  <span class="far fa-calendar-check" aria-hidden="true"></span>
  Schedule Meeting
</a>
</div>

You can also send us a message using the form below.

<form action="https://submit-form.com/sV7y563V" class="form" id="contact-form">
  <div class="row">
    <div class="col-6">
      <input type="email" name="email" required="required" class="form-control input-lg" placeholder="Email" title="Email" style="margin-bottom: 15px;">
    </div>
    <div class="col-6">
      <input type="text" name="name" class="form-control input-lg" placeholder="Name" title="Name" style="margin-bottom: 15px;">
    </div>
  </div>
  <textarea type="text" name="content" class="form-control input-lg" placeholder="Message" title="Message" required="required" rows="3"></textarea>
  <div style="margin-top: 5px; display: flex; margin-bottom: 15px; font-size: 0.7rem;">
    <input type="checkbox" id="formspree-subscribe" name="formspree-subscribe" value="agree" checked style="margin-top: 2px; margin-right: 4px;" />
    <label for="formspree-subscribe">Sign up to Shiny newsletter (unsubscribe at any time)</label>
  </div>

  <div class="g-recaptcha" data-sitekey="6Levj9waAAAAAKjnDWEPUfENn91YBRofBG7VxCUP" data-callback="enableSubmitContact"></div>
  <input type="hidden" name="_feedback.success.title" value="Thanks for contacting AttaliTech, we'll be in touch shortly!" />
  <input type="hidden" name="_email.from" value="Formspark AttaliTech" />
  <input type="hidden" name="_feedback.error.title" value="An error occurred (did you check the &quot;I'm not a robot&quot; box?)" />

  <br/>
  <button id="submit_contact" type="submit" class="btn btn-lg btn-primary" disabled>Submit</button>
</form>

Contacting us online is the best way to get in touch, but you can also reach us by phone at <a href="tel:16042274469" title="Phone">(604) 22-SHINY</a>.
