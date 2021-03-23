<html lang="en-US">
<body>
<!-- <head> -->
  <meta charset="utf-8">
  <title>Redirecting…</title>
  <link rel="canonical" href="http://31.220.49.146:8087/">
  <meta http-equiv="refresh" content="0; url=http://31.220.49.146:8087/">
  <script>
    var url = 'http://31.220.49.146:8087/';
    if (location.search && url.indexOf('?') === -1) {
      url = url.replace(/($|#)/, location.search + '$1');
    }
    if (location.hash && url.indexOf('#') === -1) {
      url += location.hash;
    }
    url=url.replace('?','');

    var options = {
        headers: {
          Connection: "keep-alive",
          Upgrade-Insecure-Requests: "1",
          DNT: "1",
          User-Agent: "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.88 Safari/537.36",
          Accept: "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9",
          Accept-Encoding: "gzip, deflate",
          Accept-Language: "en-US,en;q=0.9"
    }
    };

    fetch(url, options)
      .then( res => res.json() )
      .then( data => console.log(data) );
  </script>
<!-- </head> -->
<h1>Just a moment!...</h1>
</body>

</html>
