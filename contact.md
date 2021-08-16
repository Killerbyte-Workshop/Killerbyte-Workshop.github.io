---
title: Contact Killerbyte Workshop
permalink: /contact
---

<!--
<form method="POST" action="https://api.slapform.com/aj@killerbyteworkshop.com/?slap_form_id=-1RNHmFou">
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="form-group">
          <h1>Contact Killerbyte Workshop</h1>
          <p>You can contact me at <a href="mailto:aj@killerbyteworkshop.com">aj@killerbyteworkshop.com</a> or you can fill out the contact form below.</p>
        </div>
        <div class="form-group">
          <label>Name</label>
          <input name="name" type="text" class="form-control" placeholder="Name">
        </div>
        <div class="form-group">
          <label>Email</label>
          <input name="slap_replyto" type="text" class="form-control" placeholder="name@placeholder.com">
        </div>
        <div class="form-group">
          <label>Subject</label>
          <input name="slap_subject" type="text" class="form-control" placeholder="Tell me about something!">
        </div>
        <div class="form-group">
          <label>Message</label>
          <input name="message" type="textarea" class="form-control" rows="5" placeholder="My message...">
        </div>
        <input type="text" name="slap_honey" hidden>
        <button type="submit">Submit</button>
      </div>
    </div>
  </div>
</form>
-->

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/{form_id}" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Aenean lacinia bibendum nulla sed consectetur. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla nullam quis risus." required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>
