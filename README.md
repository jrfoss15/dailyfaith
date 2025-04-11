# dailyfaith
Daily motivational quotes and bible verses
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="refresh" content="0; url=https://www.biblegateway.com/passage/?search=John+3%3A16" />
  <script>
    const verses = [
      "John+3%3A16",
      "Romans+8%3A28",
      "Psalm+23%3A1",
      "Proverbs+3%3A5-6",
      "Isaiah+40%3A31",
      "Philippians+4%3A13",
      "Matthew+6%3A33"
      // Add more verses as you like
    ];
    const dayOfYear = Math.floor((new Date() - new Date(new Date().getFullYear(), 0, 0)) / 86400000);
    const verse = verses[dayOfYear % verses.length];
    const url = `https://www.biblegateway.com/passage/?search=${verse}`;
    window.location.href = url;
  </script>
</head>
<body>
  Redirecting to today’s Bible verse...
</body>
</html>
