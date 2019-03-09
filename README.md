# lets-not-be-arrested project

`JavaScript` は不正なプログラムを実行し、ユーザーの意図しない動作をする、危険なものです。

それにより、先日以下のようなアラートの無限ループを `JavaScript` で書いたサイトへのリンクを貼ったことで、ある女子中学生が警察に補導されました。

```
while (1) {
  alert("!");
}
```

## 逮捕されないために開発者が取れる最善策

### Google Analyticを削除

Google Analyticsを使ってユーザーの動向を把握すると逮捕されてしまうので、消しておきましょう。

該当するコードはこちらです。

```
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXXX-X"></script>
<script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
        dataLayer.push(arguments);
    }
    gtag('js', new Date());

    gtag('config', 'UA-XXXXXXXXX-X');
</script>
```

### JavaScriptを削除

`<script>` から `</script>` までを全て削除しましょう。

これでJavaScriptは動きません！


## あなた自身がJavaScriptの被害に遭わないために

### ブラウザでJavaScriptを無効に

#### Chrome

#### Firefox

アドレスバーに、 `about:config` と入力します。

`動作対象外です！` と警告が出ますが、逮捕されてしまう可能性があるので仕方ありません。同意しましょう。

検索バーに `javascript.enabled` と入力し、ダブルクリックで `false` に切替えてください。
