<html>
<head>
<title>X-wrestling</title>
<script type="text/javascript">
  var videoURLs = [
      "F:\wrestling\10.2. brad rochelle vs jeremy tyler.mp4"
  ];
  function getImageTag() {
    var img = '<img src=\"';
    var randomIndex = Math.floor(Math.random() * videoURLs.length);
    img += videoURLs[randomIndex];
    img += '\" alt="Image Failed to load"/>';
    return img;
  }
</script>
</head>
<body>
<script type="text/javascript">
  document.write(getImageTag());
</script>
</body>
</html>
