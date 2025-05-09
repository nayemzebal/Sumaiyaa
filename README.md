<!DOCTYPE html>

<html lang="ja">

<head>
<meta charset="UTF-8">
<title>ページレイアウトの作成</title>
<style>
  /* ==============　ページ全体の書式指定　============== */
  *{
    margin: 0px;
    padding: 0px;
  }
  body{
    background-color: #666666;
  }
  #container{
    width: full;
    margin: 0px auto;
    background-color: #FFFFFF;
    border-left: 5px solid #FF9933;
    border-right: 5px solid #FF9933;
  }

  /* ===============　ヘッダーの書式指定　=============== */
  header{
    height: 200px;
    background-image: url("coverbd.jpg");
  }
  #header-title{
    padding-top: 135px;
    padding-left: 15px;
    color: #FFFFFF;
    font: bold 44px sans-serif;
  }

  /* ===============　メニューの書式指定　=============== */
  nav ul{
    list-style-type: none;
    display: flex;
    background-image: url("menu-back.png");
  }
  nav a{
    display: block;
    width: 140px;
    padding: 10px 0px;
    text-align: center;
    text-decoration: none;
    color: #FFFFFF;
    font: bold 14px/20px sans-serif;
  }
  nav a:hover{
    background-color: #FF3300;
  }

  /* ================　メインの書式指定　================ */
  #main{
    height: 500px;    /* 一時的に指定 */
    padding: 30px;
  }

  /* ================　各要素の書式指定　================ */
  h1{
    background-color: #006633;
    border-radius: 5px;
    border-left: solid 15px #000000;
    padding: 6px 10px 4px;
    margin-bottom: 20px;
    box-shadow: 5px 5px 10px #999999;
    font: bold 18px sans-serif;
    color: #FFFFFF;
  }

  /* ===============　フッターの書式指定　=============== */
  footer{
    background-color: #000000;
    padding: 10px;
    font: 12px sans-serif;
    text-align: right;
    color: #FFFFFF;
  }
</style>
</head>

<body>
<div id="container">    <!-- 全体を囲むdiv -->

<!-- ====================　ヘッダー　==================== -->
<header>
  <div id="header-title">バングラデシュの旅</div>
</header>

<!-- ====================　メニュー　==================== -->
<nav>
  <ul>
    <li><a href="sights.html">バングラデシュの紹介</a></li>
    <li><a href="event.html">イベント情報</a></li>
    <li><a href="photo.html">バングラデシュのの写真</a></li>
    <li><a href="link.html">リンク集</a></li>
    <li><a href="contact.html">お問い合わせ</a></li>
  </ul>
</nav>

<!-- =====================　メイン　===================== -->
<div id="main">
  <h1>新着情報</h1>
  ※ここにページの内容を記述
</div>

<!-- ====================　フッター　==================== -->
<footer>
  <p>バングラデシュの旅</p>
  <p>Copyright (C) 2019 Yusuke Aizawa All rights reserved.</p>
</footer>

</div>                  <!-- 全体を囲むdiv -->
</body>

</html>
