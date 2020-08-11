# CSS Handson

## CSSの書き方の流れ

HTMLのタグにCSSのクラスを当てることでデザインを加えることができます。  
しかし、結構ややこしいので、実際にやりながら見てみましょう！  

まずは、こんな感じでHTMLを書きましょう。

```
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>タイトル</title>
  <meta name="description" content="サイトの説明を記載します">
  <link rel="icon" href="favicon.ico">
</head>
<body>
    <div>
        <h1>ポートフォリオだよ</h1>
    </div>

    <div>
        <h2>whoami自己紹介</h2>
        <p>私は公立千歳科学技術大学の科技大太郎だよ。<br> なんつって</p>
    </div>

    <div>
        <h2>logoロゴ</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSq6KW6PvwJa8URGELal4IjFPENpJ0gr0JsVQ&usqp=CAU">
    </div>

    <div>
        <h2>contactアクセス</h2>
        <p>科技大@メールアドレスドットコム</p>
    </div>
</body>
</html>
```

ここにCSSを当てていきます。  
CSSのコードは以下の形で色のみをつけていきます。  

```
.main{
    background-color: hotpink;
}

.portfolio{
    background-color: blue;
}

.whoami{
    background-color: blueviolet;
}

.logo{
    background-color: brown;
}

.contact{
    background-color: chartreuse;
}

```

CSSを書いたらHTMLのタグに直接埋め込んでいきましょう。


```
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>タイトル</title>
  <meta name="description" content="サイトの説明を記載します">
  <link rel="icon" href="favicon.ico">
  <link rel="stylesheet" href="index.css">
</head>
<body>
<div class="main">
    <div class="portfolio">
        <h1>ポートフォリオだよ</h1>
    </div>

    <div class="whoami">
        <h2>whoami自己紹介</h2>
        <p>私は公立千歳科学技術大学の科技大太郎だよ。<br> なんつって</p>
    </div>

    <div class="logo">
        <h2>logoロゴ</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSq6KW6PvwJa8URGELal4IjFPENpJ0gr0JsVQ&usqp=CAU">
    </div>

    <div class="contact">
        <h2>contactアクセス</h2>
        <p>科技大@メールアドレスドットコム</p>
    </div>
</div>
</body>
</html>
```

