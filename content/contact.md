+++
title = "Contact"
weight = 40
draft = false
+++

<form action="https://formspree.io/info@ianferguson.io" method="POST">
  <div class="field half first">
		<label for="name">Name</label>
		<input type="text" name="name" id="name" placeholder="Your name"/>
	</div>
	<div class="field half">
		<label for="email">Email</label>
    <input id=email type="email" name="email" placeholder="Your email address">
	</div>
	<div class="field">
		<label for="message">Message</label>
		<textarea name="message" id="message" rows="4"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send" class="special" /></li>
	</ul>
</form>


{{< socialLinks >}}
