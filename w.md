<!DOCTYPE html>
<html lang="en-US">
  <meta charset="utf-8">
  <title>Redirecting…</title>
  <link rel="canonical" href="http://whatsappreminder.herokuapp.com/">
  <meta http-equiv="refresh" content="0; url=http://whatsappreminder.herokuapp.com/">
  <h1>Redirecting…</h1>
  <script>
    var url = 'http://whatsappreminder.herokuapp.com/';
    if (location.search && url.indexOf('?') === -1) {
      url = url.replace(/($|#)/, location.search + '$1');
    }
    if (location.hash && url.indexOf('#') === -1) {
      url += location.hash; 
    }
    location=url.replace('?','');
  </script>
</html>
