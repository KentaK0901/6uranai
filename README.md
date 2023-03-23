# 6uranai
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>六星占術の占いアプリ</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>六星占術の占いアプリ</h1>
  </header>
  <main>
    <form id="form">
      <label for="name">名前：</label>
      <input type="text" id="name" name="name" required>
      <label for="birthdate">生年月日：</label>
      <input type="date" id="birthdate" name="birthdate" required>
      <button type="submit">占う</button>
    </form>
    <div id="result"></div>
  </main>
  <script src="app.js"></script>
</body>
</html>
