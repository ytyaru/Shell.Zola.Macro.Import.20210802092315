+++
title = "当サイトについて"
#sort_by = "date"
#insert_anchor_links = "left"
#template = "about/section.html"
#page_template = "about/page.html"
+++

　当サイトは静的サイトジェネレータ[zola][]について書きなぐったものである。また、自作のテーマも配布する。

[zola]:https://www.getzola.org/

# ライセンス

## サイト

　当サイトにおける記事の著作権は私、[ytyaru](@/author/index.md)にある。無断で複製しないこと。

　ただし紹介は自由である。URLは好きにコピペしてよい。

　引用も引用元として当サイト記事のURLが付随すればOK。たとえばURL「`{{ config.base_url }}`」に書いてある「`静的サイトジェネレータzolaについて書きなぐる。`」という文章を引用したければ以下のように書くこと。

```html
<q cite="{{ config.base_url }}">静的サイトジェネレータzolaについて書きなぐる。自作テンプレートも配布する。</q>
<br>
<cite>引用元：<a href="{{ config.base_url }}">{{ config.base_url }}</a></p>
```

```html
<blockquote>
<p>静的サイトジェネレータ<code>zola</code>について書きなぐる。自作テンプレートも配布する。</p>
<p><cite>引用元：<a href="{{ config.base_url }}">{{ config.base_url }}</a></p></cite>
</blockquote>
<a href="{{ config.base_url }}">ytyaru-zola</a>
```

### コード

　断りがないかぎり、当サイトの記事で紹介したコードはすべて[CC0][]ライセンスである。自由にコピペしてよい。たとえば記事で以下のように紹介してあるコードが対象。

```html
<html>
  <body>
  </body>
</html>
```

[CC0]:http://creativecommons.org/publicdomain/zero/1.0/deed.ja

<a href="http://creativecommons.org/publicdomain/zero/1.0/deed.ja"><img src="https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg" height="" title="Criative Commons Zero"></img></a>

<!--[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)-->

<!--[![CC0](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)-->
<!--[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)-->

# 寄付

<!--

　よろしければ寄付をしていただけるととても嬉しいです。メールアドレス欄に``を入力すると私に届きます。

* [Amazon ギフト券 15円〜](https://www.amazon.co.jp/Amazon%E3%82%AE%E3%83%95%E3%83%88%E5%88%B8-1_JP_Email-Amazon%E3%82%AE%E3%83%95%E3%83%88%E5%88%B8-E%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%BF%E3%82%A4%E3%83%97-Amazon%E3%83%99%E3%83%BC%E3%82%B7%E3%83%83%E3%82%AF/dp/B004N3APGO/ref=as_li_ss_il?s=gift-cards&ie=UTF8&qid=1547605920&sr=1-1&linkCode=li2&tag=aecaaais-22&linkId=c8d5776fbcac877f23e88d0a7f4c4397&language=ja_JP)


name|id|項目
----|--|----
amount|gc-order-form-amount|金額(15円〜)
emails|gc-order-form-recipients|受取人のEメールアドレス

document.getElementById("gc-order-form-amount").value="15";
document.getElementById("gc-order-form-recipients").value="yttry0-amazon-gift@gmail.com";

javascript:(function(){var T=prompt('更新間隔?(秒)','60');if(T&&!isNaN(T)){var F='<html><iframe src="https://www.amazon.co.jp/Amazon%E3%82%AE%E3%83%95%E3%83%88%E5%88%B8-1_JP_Email-Amazon%E3%82%AE%E3%83%95%E3%83%88%E5%88%B8-E%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%BF%E3%82%A4%E3%83%97-Amazon%E3%83%99%E3%83%BC%E3%82%B7%E3%83%83%E3%82%AF/dp/B004N3APGO/ref=as_li_ss_il?s=gift-cards&ie=UTF8&qid=1547605920&sr=1-1&linkCode=li2&tag=aecaaais-22&linkId=c8d5776fbcac877f23e88d0a7f4c4397&language=ja_JP"></iframe></html>';var W=open();with(W.document){write(F);close();}var H='<html><script>function R(){parent.frames[0].location="'+location+'";}setInterval("R()",'+T*1000+');</script></html>';with(W.frames[1].document){write(H);close();}}})();

<iframe srcdoc="<p>フレーム表示される内容です。詳しくは、<a href=&quot;http://example.com/?p=1&amp;amp;r=1&quot;>こちらのページ</a>をご確認ください。</p>" src="http://example.com/"></iframe>

javascript:(function(){var T=prompt('更新間隔?(秒)','60');if(T&&!isNaN(T)){var F='<html><frameset rows="*,0"><frame src="'+location+'"><frame></frameset></html>';var W=open();with(W.document){write(F);close();}var H='<html><script>function R(){parent.frames[0].location="'+location+'";}setInterval("R()",'+T*1000+');</script></html>';with(W.frames[1].document){write(H);close();}}})();

-->

