# test1
<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8">
    <title>スタンダードレイアウト</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header class="header">
      <h1 class="logo">
        <a href="/">SAMPLE SITE</a>
      </h1>
      <nav class="global-nav">
        <ul>
          <li class="nav-item active"><a href="#">HOME</a></li>
          <li class="nav-item"><a href="#">HOME</a></li>
          <li class="nav-item"><a href="#">ABOUT</a></li>
          <li class="nav-item"><a href="#">NEWS</a></li>
          <li class="nav-item"><a href="#">TOPICS</a></li>
          <li class="nav-item"><a href="#">DOCS</a></li>
          <li class="nav-item"><a href="#">BLOG</a></li>
        </ul>
      </nav>
    </header>
    <div class="wrapper　clearfix">
      <main class="main">
        <h2 class="hidden">HOT TOPIC</h2>
        <a href="#" class="hot-topic clearfix">
          <img class="image" src="./images/hot-topic.jpg" alt="コーディング画面">
          <div class="content">
            <h3 class="title">実務で使えるHTML/CSS<br>モダンコーディングTIPS</h3>
            <p class="desc">Webフロントエンドの進化の勢いはとどまるところを知りません．新しい要素が増えて大幅に表現力がHTML5/CSS3を活用して</p>
            <time class="date" datetime="2015-09-01">2015.09.01 THU</time>
          </div>
        </a>
        <div class="hot-topic">

        </div>
        <h2 class="heading">NEWS</h2>
        <ul class="scroll-list">
           <li class="scroll-item">
             <a href="#">
                <time class="date" datetime="2015-08-23">2015.08.23 SUN</time>
                <span class="category news">NEWS</span>
                  <span class="title">WORKSを発見しました．</span>
             </a>
           </li>
           <li class="scroll-item">
             <a href="#">
                <time class="date" datetime="2015-08-12">2015.08.12 WED</time>
                <span class="category news">TOPIC</span>
                  <span class="title">CSSでここまでできる！？ほんとに使えるCSSセレクタ10選</span>
             </a>
           </li>
        </ul>
        <div class="news">

        </div>
        <h2 class="hidden">ARTICLES</h2>
        <div class="clearfix">
          <a href="#" class="article-box">
             <h3 class="title">実務で使えるHTML/CSS</h3>
             <p class="desc">新しい要素が増えて大幅に表現力がHTML5</p>
             <time class="date" datetime="2015-06-17">2015.06.17 WED</time>
             <img class="image"　src="./images/article.jpg" alt="コーディング画面">
          </a>
          <a href="#" class="article-box">
             <h3 class="title">実務で使えるHTML/CSS</h3>
             <p class="desc">新しい要素が増えて大幅に表現力がHTML5</p>
             <time class="date" datetime="2015-06-17">2015.06.17 WED</time>
             <img class="image"　src="./images/article.jpg" alt="コーディング画面">
          </a>
          <a href="#" class="article-box">
             <h3 class="title">実務で使えるHTML/CSS</h3>
             <p class="desc">新しい要素が増えて大幅に表現力がHTML5</p>
             <time class="date" datetime="2015-06-17">2015.06.17 WED</time>
             <img class="image"　src="./images/article.jpg" alt="コーディング画面">
          </a>
        </div>
        <div class="articles">

        </div>
      </main>
      <div class="sidemenu">
        <h2 class="heading">RANKING</h2>
        <ol class="ranking">
          <li class="ranking-item">
            <a href="#">
              <img class="image" src="./images/ranking.jpg" alt="グラフの画像">
              <span class="order"></span>
              <p class="text">HTML/CSSコーディングと切っても切れないWebブラウザのシェア動向をチェックしよう</p>
            </a>
          </li>
          <li class="ranking-item">
            <a href="#">
              <img class="image" src="./images/ranking.jpg" alt="グラフの画像">
              <span class="order"></span>
              <p class="text">HTML/CSSコーディングと切っても切れないWebブラウザのシェア動向をチェックしよう</p>
            </a>
          </li>
          <li class="ranking-item">
            <a href="#">
              <img class="image" src="./images/ranking.jpg" alt="グラフの画像">
              <span class="order"></span>
              <p class="text">HTML/CSSコーディングと切っても切れないWebブラウザのシェア動向をチェックしよう</p>
            </a>
          </li>
        </ol>
        <h2 class="heading">DOCUMENTS</h2>
        <ul class="documents">
          <li>
            <h3 class="title">HTNL5</h3>
            <ul>
              <li><a href="#">追加された要素</a></li>
              <li><a href="#">削除された要素</a></li>
              <li><a href="#">意味が変わった要素</a></li>
              <li><a href="#">HTML5のコンテンツモデル</a></li>
            </ul>
          </li>
          <li>
            <h3 class="title">CSS3</h3>
            <ul>
              <li><a href="#">追加されたプロパティ</a></li>
              <li><a href="#">追加されたセレクタ</a></li>
              <li><a href="#">追加された単位</a></li>
            </ul>
          </li>
          <li>
            <h3 class="title">JavaScript</h3>
            <ul>
              <li><a href="#">JavaScriptの言語仕様</a></li>
              <li><a href="#">ECMAScriptとは？</a></li>
              <li><a href="#">jQueryとは？</a></li>
            </ul>
          </li>
          <li>
            <h3 class="title">Sass, Less, Stylus</h3>
            <p>準備中</p>
          </li>
          <li>
            <h3 class="title">TypeScript</h3>
            <p>準備中</p>
          </li>
        </ul>
        <h2 class="hidden">SEARCH</h2>
        <form class="serch-box">
          <input class="serch-box" type="text" name="serch" placeholder="SEARCH">
          <input  class="serch-box" type="submit" value="検索">
          <p　class="text">サイト内の文章を検索できます．</p>
        </form>
      </div>
    </div>
    <footer class="footer">
      <ul class="horizontal-list">
        <li class="horizontal-item"><a href="#">ABOUT ME</a></li>
        <li class="horizontal-item"><a href="#">SITE MAP</a></li>
        <li class="horizontal-item"><a href="#">SNS</a></li>
        <li class="horizontal-item"><a href="#">CONTACT</a></li>
      </ul>
      <p class="copyright">Copyright c 2015 SAMPLE SITE</p>
    </footer>
  </body>
</html>
