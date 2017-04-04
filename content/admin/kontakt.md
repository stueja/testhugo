+++
date = "2017-04-04T11:45:58+02:00"
draft = false
title = "kontakt"
weight = 0

+++

<form method="post" action="#">
    <div class="field half first">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" />
    </div>
    <div class="field half">
        <label for="email">Email</label>
        <input type="text" name="email" id="email" />
    </div>
    <div class="field">
        <label for="message">Nachricht</label>
        <textarea name="message" id="message" rows="4"></textarea>
    </div>
    <ul class="actions">
        <li><input type="submit" value="Absenden" class="special" /></li>
        <li><input type="reset" value="Zurücksetzen" /></li>
    </ul>
</form>