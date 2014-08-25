{% if page.press != "no" %}
Request a Press Copy
----------------------
Please fill in your info below, and we'll send you a press copy

<br />

<form method="post" name="myemailform" action="{{ "/form-to-email.php" | prepend: site.baseurl }}">

<label for="Name">Enter Publication Name:</label> <input type="text" placeholder="Your Publication" name="name"><br />
<label for="Email">Enter Email Address: </label> <input type="text" placeholder="Your Email Address" name="email">
<input type="submit" value="Send Form">
</form>

{% endif %}
