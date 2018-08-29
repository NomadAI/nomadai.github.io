---
layout: page
title: Contact us
permalink: /contact/
---

<!--<form name="contactform" method="post" action="https://formspree.io/nomad.ai.ou@gmail.com">
  <input type="email" name="email" placeholder="Your email">
  <textarea name="message" placeholder="Your message"></textarea>
  <button type="submit">Send</button>
</form> -->

<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #4C668C;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #142E54;
}

.container {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
}
</style>


<div class="container">
  <form action="https://formspree.io/nomad.ai.ou@gmail.com">
    <label for="fname">Email</label>
    <input type="text" id="fname" name="email" placeholder="Your e-mail">
    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Your message.." style="height:200px"></textarea>
    <input type="submit" value="Submit">
  </form>
</div>
