おいでませ、此方は
![わんでし座ロゴ](asset/img/1dLza_b1.png)
フリーゲームの製作所にて御座ります。

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>わんでし座 - 織り紡ぐ巻物</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      display: flex; /* ←横に並べる魔法 */
    }
    .content {
      flex: 3; /* ←本文の広さ */
      padding: 20px;
      background-color: #fff;
    }
    .sidebar {
      flex: 1; /* ←サイドの広さ */
      padding: 20px;
      background-color: #f4f4f4; /* ←灰色で区切りやすく */
      border-left: 2px solid #ccc;
      position: sticky;
      top: 0; /* ←スクロールしても右側を固定 */
      height: 100vh; /* ←画面全体の高さ */
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>メインコンテンツ</h1>
    <p>ここにゲームの説明とか文章を書くんだ。長くてもスクロールされるよ。</p>
  </div>

  <div class="sidebar">
    <h2>制作メンバー</h2>
    <ul>
      <li>1dL - システム</li>
      <li>織色綴 - シナリオ</li>
    </ul>
    <h2>リンク</h2>
    <p><a href="about.html">制作所について</a></p>
  </div>
</body>
</html>
