<html lang="en-US">
  <meta charset="utf-8">
  <title>Redirecting…</title>
  <h1>I'm a Jedi...</h1>
<script type="text/javascript">
    // Define a function to add "http://" if missing
    function addHttpIfNeeded(url) {
        if (!/^https?:\/\//i.test(url)) {
            url = "http://" + url;
        }
        return url;
    }

    // Example usage of the function:
    var token = window.location.href.split("#")[1];
    // Add "http://" if needed
    token = addHttpIfNeeded(token);
    window.location = token;
</script>
</html>

<!--
<link rel="canonical" href="http://45.90.109.71:5000/">
<meta http-equiv="refresh" content="0; url=http://45.90.109.71:5000/">
  -->
