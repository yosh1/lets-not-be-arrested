# lets-not-be-arrested project

## 逮捕されないためにあなたが取れる最善策

### JavaScriptを削除

`<script>` から `</script>` までを全て削除しましょう。

これでJavaScriptは動きません！

### Google Analyticを削除

Google Analyticsを使ってユーザーの動向を把握すると逮捕されてしまうので、消しておきましょう。

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

該当するコードはこちらです。
