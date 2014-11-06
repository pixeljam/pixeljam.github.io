{% if page.press != "no" %}

Request a Copy {#additional}
----------------------
Please send us an email at press@pixeljam.com and we will send you over a copy; or fill out this nifty form:

<br />

<form action="//forms.brace.io/press@pixeljam.com">

<label for="Name">Enter Publication Name:</label>
      <input type="text" placeholder="Your Publication" name="name"><br />
<label for="Email">Enter Email Address: </label>
      <input type="email" placeholder="Your Email Address" name="_replyto">
<label for="TextArea">Anything else you'd like us to know?</label>
      <textarea name="message" class="form-control" rows="3"></textarea>
<label class="radio-inline">
      <input name="pick" type="radio" id="inlineCheckbox1" value="addToMailList">Add To The Pixeljam Mailing List?
</label>

<input type="hidden" name="_next" value="{{ "/thank-you.html" | prepend: site.baseurl }}" />
<input type="hidden" name="_subject" value="Press copy request for {{ page.title }}" />
<input type="submit" value="Send">
</form>

{% endif %}
