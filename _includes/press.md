{% if page.press != "no" %}

Request a Copy {#additional}
----------------------
Please send us an email at press@pixeljam.com and we will send you over a copy; or fill out this nifty form:

<br />

<form method="POST" action="//formspree.io/press@pixeljam.com">

  <div class="pressCopy">
    <label for="Name">
    <span>Publication Name:</span>
          <input type="text" placeholder="Your Publication" name="name">
    </label>
    <label for="Email">
    <span>Email Address:</span>
          <input type="email" placeholder="Your Email Address" name="_replyto">
     </label>
    <label for="TextArea">
    <span>Anything else you'd like us to know?</span>
          <textarea name="message" class="form-control" rows="3"></textarea>
    </label>
    <label class="checkbox-inline">
          <span>Add To The Pixeljam Mailing List?</span>
          <input name="pick" type="checkbox" id="inlineCheckbox1" value="Add Me To Mailing List - Yes!">
    </label>
    
  </div>

  <input type="hidden" name="_next" value="//pixeljam.com/press-copy-request-thank-you.html" />
  <input type="hidden" name="_subject" value="Press copy request for {{ page.title }}" />
  <input class="btn" type="submit" value="Send">
</form>

{% endif %}
