# git_htmlcss
<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charset="UTF-8">
        <title>HTML/CSSの学習</title>
        <link rel="stylesheet" href="stylesheet.css">
    </head>
    <body>
        <div id="header">
            <h1><a href="index.html"><img id="corridor" src="images/corridor.jpg" alt="大学の廊下" /></a></h1>
        </div>
        <div id="wrapper">
            <div id="nav">
                <ul>
                    <li><a href="home.html">ナビ1</a></li>
                    <li><a href="#">ナビ2</a></li>
                    <li><a href="#">ナビ3</a></li>
                    <li><a href="#">ナビ4</a></li>
                    <li><a href="#">ナビ5</a></li>
                </ul>
            </div>
             <div id="container">
                <div id="main">
              <div class="post">
                    <p>ここは文章が入ります。<br />今は、適当な文章を入れてあります。これをダミーテキストといいます。</p>
                </div>
                <div class="post clearfix">
                    <h2>小見出し1</h2>
                    <img class="left" src="images/classroom.jpg" alt="授業風景" />
                    <p>
                        コンテンツ1の本文になります。
                        コンテンツ1の本文になります。
                    </p>
                    <p><a href="#">→コンテンツ1のページへ</a></p>
                </div>
                <div class="post clearfix">
                    <h2>小見出し2</h2>
                    <img class="right" src="images/scale.jpg" alt="天秤" />
                    <p>
                        コンテンツ2の本文になります。
                        コンテンツ2の本文になります。
                    </p>
                    </div>
               </div>
                <div id="side">
                    <div class="box">
                        <h2>サイドメニュー1</h2>
                        <div class="boxBody">
                            <ul>
                                <li>項目1</li>
                                <li>項目2</li>
                                <li>項目3</li>
                                <li>項目4</li>
                            </ul>
                        </div>
                    </div>
                    <div class="box">
                        <h2>サイドメニュー2</h2>
                        <div class="boxBody">
                            <ul>
                                <li>項目1</li>
                                <li>項目2</li>
                                <li>項目3</li>
                                <li>項目4</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="footer">
            <p>&copy; 20xx ○○ All Rights Reserved.</p>
        </div>
    </body>
</html>
