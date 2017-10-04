<!DOCTYPE html><html xmlns:og="http://ogp.me/ns#"><head><meta charset="UTF-8" /><title>Web制作でデザインカンプを徹底再現する為の便利なアプリ - Qiita</title><meta content="width=device-width,initial-scale=1" name="viewport" /><meta content="LPなどの視覚的なデザインを売りとしたサイトの場合、高い水準でカンプ通りの実装が求められる。自分では狂いなく再現したつもりでも、どこかでずれていてデザイナーから指摘されることもしばしばある。この記事では、1デザインカンプの徹底再現（2 ピクセルパーフェクト）の必要性と、そのための便利なMacOSXアプリケーションを紹介する。

要約。


他人の作ったデザインを高いレベルで再現するには、ピクセルパーフェクトを狙うくらいの意気込みが必要
その為には、ブラウザへカンプを重ね合..." name="description" /><meta content="summary" name="twitter:card" /><meta content="@Qiita" name="twitter:site" /><meta content="y_hokkey" name="twitter:creator" /><meta content="Web制作でデザインカンプを徹底再現する為の便利なアプリ - Qiita" property="og:title" /><meta content="article" property="og:type" /><meta content="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" property="og:url" /><meta content="https://cdn.qiita.com/assets/qiita-fb-2887e7b4aad86fd8c25cea84846f2236.png" property="og:image" /><meta content="LPなどの視覚的なデザインを売りとしたサイトの場合、高い水準でカンプ通りの実装が求められる。自分では狂いなく再現したつもりでも、どこかでずれていてデザイナーから指摘されることもしばしばある。この記事では、[^1]デザインカンプの徹底再..." property="og:description" /><meta content="Qiita" property="og:site_name" /><meta content="564524038" property="fb:admins" /><link rel="canonical" href="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" /><link rel="shortcut icon" type="image/x-icon" href="https://cdn.qiita.com/assets/favicons/public/production-4ff10c1e1e2b5fcb353ff9cafdd56c70.ico" /><link rel="apple-touch-icon" type="image/png" href="https://cdn.qiita.com/assets/favicons/public/apple-touch-icon-f9a6afad761ec2306e10db2736187c8b.png" /><link href="/opensearch.xml" rel="search" title="Qiita" type="application/opensearchdescription+xml" /><link rel="stylesheet" media="all" href="https://cdn.qiita.com/assets/public-8d963c923373cd619a29df0263f3031e.min.css" /><meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="+zHq4NVEFGD3D3yc06J7kARpPl2Y/WTGZ5MVeO3pVRr2hOGKmT7eJmzb+XxzwnrLJQy0NEwydAiDmq1bnqmviw==" /><script>
  window.gtmDataLayer = [
    {
      'analytics.dimension5': 'false',
      'app.env': 'production',
      'app.layoutVersion': 1,
      'app.userId': null
    },
    { 'gtm.start': new Date().getTime(), event: 'gtm.js' }
  ];
</script>
<script src="https://www.googletagmanager.com/gtm.js?id=GTM-TBQWPN&l=gtmDataLayer" async></script>
</head><body class="without-js" id=""><noscript><iframe height="0" src="//www.googletagmanager.com/ns.html?id=GTM-TBQWPN" style="display:none;visibility:hidden" width="0"></iframe></noscript><script>
  document.body.className = document.body.className.replace('without-js', '') + ' with-js';
  window.Qiita = {"asset_host":"cdn.qiita.com","TLD":"com","controller_path":"public/items","controller_action":"public/items#show","controller":"items","action":"show","action_path":"public/items#show","env":"production","flash":{},"is_team_page":false,"request_parameters":{"controller":"public/items","action":"show","user_id":"y_hokkey","type":"items","id":"f4f8518e9e9b9760a0a0"},"root_domain":"qiita.com","variant":null,"config":{"mixpanel":{"per_team":"c0a2116368b33b44b5029ebd2cc9b094","public":"17d24b448ca579c365d2d1057f3a1791","team":"b7c0342acba2dbc8742484d98788efb3"},"default_locale":"ja","locale":"ja"},"team":null,"user":null,"GIT_BRANCH":null,"DEBUG":false};

</script>
<div class="headerContainer headerContainer-public" role="navigation"><script type="application/json" class="js-react-on-rails-component" data-component-name="HeaderContainer" data-dom-id="HeaderContainer-react-component-feddd0ee-d4ea-4cf0-a2ec-53d5196e73c3">{"user":null,"team":null,"news":{"type":"Release","content":"Qiitaユーザー向けのMastodon、Qiitadon を試験的に公開しました","url":"http://blog.qiita.com/post/161193715974/qiitadon?utm_source=qiita\u0026utm_medium=header_news"},"initial_unread_count":null,"siteid_image":"https://cdn.qiita.com/siteid-reverse.png","is_team_page":false,"on_team_setting":false,"show_post_menu":true,"show_search_menu":true,"is_fluid":false,"locale":"ja"}</script>
    <div id="HeaderContainer-react-component-feddd0ee-d4ea-4cf0-a2ec-53d5196e73c3"></div>
    
</div><div id="main"><script>window.ga=window.ga||function(){(ga.q=ga.q||[]).push(arguments)};ga.l=+new Date;
ga('create', 'UA-54046092-1', 'auto', { name: 'userTracker' });
ga('userTracker.send', 'pageview');</script><script async="" src="https://www.google-analytics.com/analytics.js"></script><script type="application/ld+json">{  "@context": "http://schema.org",  "@type": "BreadcrumbList",  "itemListElement": [    {      "@type": "ListItem",      "position": 1,      "item": {        "@id": "/",        "name": "Qiita"      }    },    {      "@type": "ListItem",      "position": 2,      "item": {        "@id": "/items",        "name": "投稿"      }    },    {      "@type": "ListItem",      "position": 3,      "item": {        "@id": "/tags/Design",        "name": "Design"      }    }  ]}</script><article itemscope="" itemtype="http://schema.org/Article"><div class="ArticleMainHeader "><div class="container"></div><div class="container"><div class="row s-flex-align-center"><div class="col-sm-9"><h1 class="ArticleMainHeader__title" itemprop="headline">Web制作でデザインカンプを徹底再現する為の便利なアプリ</h1><ul class="TagList"><li class="TagList__item" data-count="161"><a class="u-link-unstyled TagList__label" href="/tags/Design"><img alt="Design" class="TagList__icon" src="https://s3-ap-northeast-1.amazonaws.com/qiita-tag-image/014aefff7b8e905cbf3368cba8303794a291a7c1/medium.jpg?1501236549" /><span>Design</span></a></li><li class="TagList__item" data-count="4967"><a class="u-link-unstyled TagList__label" href="/tags/Mac"><img alt="Mac" class="TagList__icon" src="https://s3-ap-northeast-1.amazonaws.com/qiita-tag-image/0cbda729ead4559760ec64ae744a5aef937e0b08/medium.jpg?1403645170" /><span>Mac</span></a></li><li class="TagList__item" data-count="156"><a class="u-link-unstyled TagList__label" href="/tags/%E3%83%95%E3%83%AD%E3%83%B3%E3%83%88%E3%82%A8%E3%83%B3%E3%83%89"><img alt="フロントエンド" class="TagList__icon" src="https://s3-ap-northeast-1.amazonaws.com/qiita-tag-image/6e3ebaa1a8e7e32744cbd7c814b2db5f2fd37b0a/medium.jpg?1501236025" /><span>フロントエンド</span></a></li><li class="TagList__item" data-count="3318"><a class="u-link-unstyled TagList__label" href="/tags/CSS"><img alt="CSS" class="TagList__icon" src="https://s3-ap-northeast-1.amazonaws.com/qiita-tag-image/b4438ce0a78810256791a266e87c74a76b555de1/medium.jpg?1419699326" /><span>CSS</span></a></li><li class="TagList__item" data-count="2672"><a class="u-link-unstyled TagList__label" href="/tags/HTML"><img alt="HTML" class="TagList__icon" src="https://s3-ap-northeast-1.amazonaws.com/qiita-tag-image/864a094d7aa8940bf46ce87f8841a88f017abbfa/medium.jpg?1490806921" /><span>HTML</span></a></li></ul></div><div class="col-sm-3"><div class="itemsShowHeaderStock"><ul class="list-unstyled itemsShowHeaderStock_statusList"><li><div class="itemsShowHeaderStock_count stock"><span class="fa fa-thumbs-up"></span><span class="js-likecount">104</span></div><div class="itemsShowHeaderStock_countText">いいね</div></li><li><div class="itemsShowHeaderStock_count" content="0 UserComments" itemprop="commentCount"><span class="fa fa-comment"></span>0</div><div class="itemsShowHeaderStock_countText">コメント</div></li></ul></div><div class="js-likebutton" data-props="{&quot;like_status&quot;:false,&quot;like_count&quot;:104,&quot;uuid&quot;:&quot;f4f8518e9e9b9760a0a0&quot;,&quot;likable_type&quot;:&quot;Article&quot;,&quot;position&quot;:&quot;article-header&quot;}"></div><ul class="list-inline ArticleMainHeader__users"><li class="js-hovercard" data-hovercard-target-name="ganbaru"><a itemprop="url" href="/ganbaru"><img alt="ganbaru" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/76701/profile-images/1473700577" /></a></li><li class="js-hovercard" data-hovercard-target-name="psephopaikes"><a itemprop="url" href="/psephopaikes"><img alt="psephopaikes" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/50195/profile-images/1501642738" /></a></li><li class="js-hovercard" data-hovercard-target-name="satton_maroyaka"><a itemprop="url" href="/satton_maroyaka"><img alt="satton_maroyaka" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/7046/profile-images/1497685022" /></a></li><li class="js-hovercard" data-hovercard-target-name="kazuhikoyamashita"><a itemprop="url" href="/kazuhikoyamashita"><img alt="kazuhikoyamashita" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/41823/profile-images/1499499134" /></a></li><li class="js-hovercard" data-hovercard-target-name="kanase"><a itemprop="url" href="/kanase"><img alt="kanase" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/60362/profile-images/1473695205" /></a></li><li class="js-hovercard" data-hovercard-target-name="Dodoria"><a itemprop="url" href="/Dodoria"><img alt="Dodoria" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/3093/profile-images/1473682614" /></a></li><li class="js-hovercard" data-hovercard-target-name="eggucheese"><a itemprop="url" href="/eggucheese"><img alt="eggucheese" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/80125/profile-images/1485913549" /></a></li><li class="js-hovercard" data-hovercard-target-name="west2summit"><a itemprop="url" href="/west2summit"><img alt="west2summit" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/66650/profile-images/1473697273" /></a></li><li class="js-hovercard" data-hovercard-target-name="hkwid"><a itemprop="url" href="/hkwid"><img alt="hkwid" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/35635/profile-images/1473686790" /></a></li><li class="js-hovercard" data-hovercard-target-name="YutaKiyama"><a itemprop="url" href="/YutaKiyama"><img alt="YutaKiyama" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/75790/profile-images/1479130194" /></a></li><li><a href="/y_hokkey/items/f4f8518e9e9b9760a0a0/likers"><span class="fa fa-ellipsis-h"></span></a></li></ul></div></div></div></div><div class="ArticleAsideHeader"><div class="container"><div class="u-flex u-space-between"><div class="u-flex u-flex-wrap"><div class="u-flex u-align-center s-pdv-5 u-flex-wrap"><div class="ArticleAsideHeader__author"><a href="/y_hokkey"><img class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/48238/profile-images/1473691279" alt="1473691279" /></a> <a class="u-link-unstyled" href="/y_hokkey">y_hokkey</a> </div><div class="ArticleAsideHeader__date"><meta content="2016-05-26T22:54:08+09:00" itemprop="datePublished" /><span data-toggle="tooltip" title="2016年05月26日に投稿"><time datetime="2016-09-09T11:18:29+09:00" itemprop="dateModified">2016年09月09日</time>に更新</span></div></div><div class="u-flex u-align-center s-pdv-5 mobile-hidden"><div class="ArticleAsideHeader__revision"> <a data-toggle="tooltip" title="編集履歴" href="/y_hokkey/items/f4f8518e9e9b9760a0a0/revisions"><span class="fa fa-history"></span></a><span class="ArticleAsideHeader__revisionCount">7</span></div></div><div class="u-flex u-align-center s-pdv-5 mobile-hidden"></div></div><div class="u-flex u-align-center s-flex-justiry-between s-pdv-5 u-shrink-0"><div class="ArticleAsideHeader__stock"><div class="js-stockbutton" data-position="top" data-props="{&quot;stock_status&quot;:false}"></div></div><div class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#"><span class="fa fa-ellipsis-h fa-lg"></span></a><ul class="dropdown-menu dropdown-menu-right"><li class="dropdown__item--mobile"><a href="/y_hokkey/items/f4f8518e9e9b9760a0a0/revisions"><span class="fa fa-fw fa-history"></span> 編集履歴<span>(7)</span></a></li><li><a href="/y_hokkey/items/f4f8518e9e9b9760a0a0.md"><span class="fa fa-fw fa-file-text-o"></span> Markdownで本文を見る</a></li><li><a data-target=".js-report-form" data-toggle="modal" href="#"><span class="fa fa-fw fa-flag"></span> 問題がある投稿を報告する</a></li></ul></div></div></div></div></div><div class="container"><div class="row" id="article-body-wrapper"><div class="col-sm-9"><section class="markdownContent markdownContent-headingEnabled js-task-list-container clearfix position-relative" id="item-f4f8518e9e9b9760a0a0" itemprop="articleBody"><div class="alert alert-warning"><i class="fa fa-clock-o"></i> この記事は最終更新日から1年以上が経過しています。</div><p>LPなどの視覚的なデザインを売りとしたサイトの場合、高い水準でカンプ通りの実装が求められる。自分では狂いなく再現したつもりでも、どこかでずれていてデザイナーから指摘されることもしばしばある。この記事では、<sup id="fnref1"><a href="#fn1" rel="footnote" title="当記事における「ピクセルパーフェクト」とは、Webブラウザ上での表示とデザインカンプが完全に一致している状態を指す">1</a></sup>デザインカンプの徹底再現（<sup id="fnref2"><a href="#fn2" rel="footnote" title="当記事における「デザインカンプ」とは、Webサイト完成時の理想的な外観表示を、画像として作成した資料を指す">2</a></sup> ピクセルパーフェクト）の必要性と、そのための便利なMacOSXアプリケーションを紹介する。</p>

<p><strong>要約</strong></p>

<ul>
<li>他人の作ったデザインを高いレベルで再現するには、ピクセルパーフェクトを狙うくらいの意気込みが必要</li>
<li>その為には、ブラウザへカンプを重ね合わせるチェックが有効</li>
<li>Helium/Mapture/LayxerXは、フローティングと透過機能を持った非常に便利なアプリケーション</li>
</ul>

<h1>
<span id="なぜピクセルパーフェクトを目指すのか" class="fragment"></span><a href="#%E3%81%AA%E3%81%9C%E3%83%94%E3%82%AF%E3%82%BB%E3%83%AB%E3%83%91%E3%83%BC%E3%83%95%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92%E7%9B%AE%E6%8C%87%E3%81%99%E3%81%AE%E3%81%8B"><i class="fa fa-link"></i></a>なぜピクセルパーフェクトを目指すのか</h1>

<p>Webサイトという技術の特性上、フォントが違ったり、組版の仕様が違ったり、文字サイズのデフォルト値が違ったり、モニタの色見が周辺環境や端末スペックによって違ったりとするため、<strong>ピクセルパーフェクトにこだわる理由は本来的には無い</strong>。</p>

<p>しかし、<strong>デザイナーと実装担当者が分かれている場合、適当な意識での実装では、元々のデザインの意図を表現しきれないものができてしまう可能性がある</strong>。これにはデザインを売り物にする上で大きな問題があるし、結局はデザイナー側から細かい修正を依頼され、予想外の工数をかけてしまうリスクもある。</p>

<p>他人の作ったデザインを細かいところまで再現するのは、熟練者でも簡単なことではない。ピクセルパーフェクトを狙うくらいの意気込みがあって、ようやくスムーズに実装ができるのではないだろうか。</p>

<h3>
<span id="重ね合わせチェック" class="fragment"></span><a href="#%E9%87%8D%E3%81%AD%E5%90%88%E3%82%8F%E3%81%9B%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF"><i class="fa fa-link"></i></a>重ね合わせチェック</h3>

<p>Webブラウザ(最も再現度が高くなると想定したもの)にデザインカンプを重ねることで、高い精度で誤差を修正できる。ただし、スクショを撮ってPhotoshopで重ね合わせるのは面倒で効率が悪く、おすすめできない。</p>

<p>代わりに、半透明でフローティング(常にどのアプリケーションよりも最前面に表示される)機能を持った、補助的なアプリケーションの導入を薦めたい。これを使うと、<strong>IDEでコーディングをしながら、コーディング中のサイトとデザインカンプの誤差をリアルタイムで確認できる。</strong></p>

<p>はじめからページ全体で重ね合わせをすると誤差が大きすぎるので、</p>

<ul>
<li>パーツ単位 ＜ モジュール単位 ＜ モジュール同士の間隔 ＜ ページ全体</li>
</ul>

<p>という風に、小さい部分から頻繁に重ね合わせチェックをするのが良いかもしれない。面倒そうに思えるが、後述のHeliumとMaptureを使うと簡単に行える。</p>

<p><a href="https://camo.qiitausercontent.com/ad0bfa2b980ab3b89b56554b8fbb37324dcff44a/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f63626563306461622d653835632d626332622d633935302d3834323939366434643733652e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/ad0bfa2b980ab3b89b56554b8fbb37324dcff44a/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f63626563306461622d653835632d626332622d633935302d3834323939366434643733652e706e67" alt="MaptureとHeliumによる開発の様子をキャプチャしたスクリーンショット画像" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/cbec0dab-e85c-bc2b-c950-842996d4d73e.png"></a></p>

<p>画像はIDEにカンプとブラウザを透過で重ねている図。一見使い難そうに見えるが、邪魔な時は透明度を上げたり、掴んで画面外に置けば良く、それほど不便さはない</p>

<h1>
<span id="徹底再現に便利なアプリケーション" class="fragment"></span><a href="#%E5%BE%B9%E5%BA%95%E5%86%8D%E7%8F%BE%E3%81%AB%E4%BE%BF%E5%88%A9%E3%81%AA%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3"><i class="fa fa-link"></i></a>徹底再現に便利なアプリケーション</h1>

<h2>
<span id="helium" class="fragment"></span><a href="#helium"><i class="fa fa-link"></i></a>Helium</h2>

<p><a href="http://heliumfloats.com/" rel="nofollow noopener" target="_blank"><img src="https://camo.qiitausercontent.com/ad201c4af9c876770b4aea279e30c7fa7d5cdf88/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f66643231353538642d376239302d353366662d316366372d3837356562303938666164352e706e67" alt="スクリーンショット 2016-05-26 22.06.21.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/fd21558d-7b90-53ff-1cf7-875eb098fad5.png"></a></p>

<ul>
<li><a href="http://heliumfloats.com/" rel="nofollow noopener" target="_blank">Helium by JadenGeller</a></li>
<li><a href="https://github.com/JadenGeller/Helium" rel="nofollow noopener" target="_blank">JadenGeller/Helium: A floating browser window for OS X</a></li>
</ul>

<p>任意のWebページをフローティングで透過表示できる。オプションでマウスオーバー時にだけ透過を解除したり、透過中はマウス操作を無視させることもできる。無料ソフト。</p>

<h3>
<span id="機能" class="fragment"></span><a href="#%E6%A9%9F%E8%83%BD"><i class="fa fa-link"></i></a>機能</h3>

<ul>
<li>任意のWebサイトを表示し、フローティング表示できる</li>
<li>オプションで透明度を自由に変更できる</li>
<li>マウスオーバー時にだけ透明度を変えることができる</li>
<li>透過中はユーザーのマウス入力を無視させることができる</li>
</ul>

<h3>
<span id="便利な使い方" class="fragment"></span><a href="#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9"><i class="fa fa-link"></i></a>便利な使い方</h3>

<ul>
<li>後述のBrowsersyncで立ち上げたローカルサーバを表示させ、常にコードのプレビューをIDEの上に浮かせておく</li>
</ul>

<h2>
<span id="mapture" class="fragment"></span><a href="#mapture"><i class="fa fa-link"></i></a>Mapture</h2>

<p><a href="http://anatoo.jp/mapture/" rel="nofollow noopener" target="_blank"><img src="https://camo.qiitausercontent.com/d5e2b43ca517f008840cb20b687682c0684f5a83/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f32363639323466302d343065342d373564372d636465652d3739613632326635313866632e706e67" alt="スクリーンショット 2016-05-26 22.09.52.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/266924f0-40e4-75d7-cdee-79a622f518fc.png"></a></p>

<ul>
<li><a href="http://anatoo.jp/mapture/" rel="nofollow noopener" target="_blank">Mapture - MacOSX向けキャプチャユーティリティ</a></li>
<li><a href="http://blog.anatoo.jp/entry/20140108/1389107218" rel="nofollow noopener" target="_blank">Mac用の作業支援キャプチャツール、Maptureがいい感じになった - id:anatooのブログ</a></li>
</ul>

<p>Windowsの<a href="http://www.geocities.jp/knystd/rapture.html" rel="nofollow noopener" target="_blank">Rapture</a>のように、使い捨てのスクリーンショットを手軽に作成して画面に浮かべることができる。無料ソフト。</p>

<h3>
<span id="機能-1" class="fragment"></span><a href="#%E6%A9%9F%E8%83%BD-1"><i class="fa fa-link"></i></a>機能</h3>

<ul>
<li>画面の特定エリアを切り抜いて画像メモ化できる</li>
<li>任意の表示倍率で、画像メモをフローティング表示できる</li>
<li>スクロールホイールで透明度を自由に変更できる</li>
<li>ユーザーが明示しない限り画像ファイルは保存されない</li>
</ul>

<h3>
<span id="便利な使い方-1" class="fragment"></span><a href="#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-1"><i class="fa fa-link"></i></a>便利な使い方</h3>

<ul>
<li>PSDからパーツ単位でキャプチャを取り、IDEの上に浮かべる</li>
<li>Webブラウザの上に半透明で重ね、透明度をホイールでスクラブしながら、実装とカンプの誤差を確認する</li>
</ul>

<h2>
<span id="adobe-cc-extract" class="fragment"></span><a href="#adobe-cc-extract"><i class="fa fa-link"></i></a>Adobe CC Extract</h2>

<p><a href="https://camo.qiitausercontent.com/bcc78d2606b7053b1b51ef26cfc9e634134cb5f2/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f30313234366339372d336338632d306264312d383962342d6236633133343136383763612e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/bcc78d2606b7053b1b51ef26cfc9e634134cb5f2/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f30313234366339372d336338632d306264312d383962342d6236633133343136383763612e706e67" alt="Adobe CC Extract" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/01246c97-3c8c-0bd1-89b4-b6c1341687ca.png"></a></p>

<ul>
<li><a href="http://www.adobe.com/jp/creativecloud/extract.html" rel="nofollow noopener" target="_blank">PSD 変換 - HTML、CSS | Creative Cloud Extract</a></li>
<li><a href="https://helpx.adobe.com/jp/creative-cloud/help/extract-css-images-psd-files.html" rel="nofollow noopener" target="_blank">Creative Cloud ヘルプ | Extract による PSD から Web への抽出ワークフロー</a></li>
</ul>

<p><strong><a href="https://liginc.co.jp/301585" rel="nofollow noopener" target="_blank">2016年6月28日に一旦終了した後、ユーザーの声で8月に再開</a></strong>を果たしたAdobeのフロントエンドエンジニア向けのWebサービス。AdobeCCで利用できるサービスに含まれる。</p>

<p>CreativeCloudのオンラインストレージにアップロードしたPSDデータを解析し、<strong>Webブラウザ上で横幅・高さ・フォントサイズ・行高などを即座にCSSコードとして取得したり、特定のレイヤー画像から画像を抽出・ダウンロードすることができる。</strong></p>

<p><a href="https://camo.qiitausercontent.com/919887c075050cb9df9340e9097ba5d18c9b8986/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f33353562323839392d613239632d363664392d633037622d6138636631396565303866332e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/919887c075050cb9df9340e9097ba5d18c9b8986/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f33353562323839392d613239632d363664392d633037622d6138636631396565303866332e706e67" alt="スクリーンショット_2016-09-07_21_46_09.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/355b2899-a29c-66d9-c07b-a8cf19ee08f3.png"></a> <a href="https://camo.qiitausercontent.com/6ad2b2f9da770f12cd9ce6afe414cd62a694311d/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f62326665313061362d333835652d323138332d633835632d3461633134313566383266612e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/6ad2b2f9da770f12cd9ce6afe414cd62a694311d/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f62326665313061362d333835652d323138332d633835632d3461633134313566383266612e706e67" alt="スクリーンショット_2016-09-07_21_46_25.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/b2fe10a6-385e-2183-c85c-4ac1415f82fa.png"></a></p>

<p><a href="https://camo.qiitausercontent.com/6ef934cc1c44f0a314723bc7654c9131a770f4f1/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f64613533316533302d313462302d613636362d363430662d3139613930343138353938302e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/6ef934cc1c44f0a314723bc7654c9131a770f4f1/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f64613533316533302d313462302d613636362d363430662d3139613930343138353938302e706e67" alt="スクリーンショット_2016-09-07_21_46_45.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/da531e30-14b0-a666-640f-19a904185980.png"></a></p>

<p>UIが非常に使いやすく、<strong>マークアップ担当者にとって必要な作業はがほとんどWebブラウザだけで完結する</strong>。余計な機能がないので、むしろPhotoshopよりも使いやすい。既にAdobeCCアカウントを持っているのであれば、是非使ってみたいサービスだと思う。</p>

<h3>
<span id="機能-2" class="fragment"></span><a href="#%E6%A9%9F%E8%83%BD-2"><i class="fa fa-link"></i></a>機能</h3>

<ul>
<li>レイヤー情報からのCSSコードの出力</li>
<li>レイヤーからの画像出力(PNG・JPEG・SVGなど)</li>
<li>レイヤー間の隙間の計測</li>
<li>レイヤーの表示切り替え</li>
<li>ファイルのオンライン共有</li>
<li>PSDデータの実寸表示〜拡大・縮小</li>
<li>フォント・カラー値の抽出</li>
</ul>

<h3>
<span id="便利な使い方-2" class="fragment"></span><a href="#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-2"><i class="fa fa-link"></i></a>便利な使い方</h3>

<ul>
<li>マシンリソース節約</li>
</ul>

<h2>
<span id="layerx" class="fragment"></span><a href="#layerx"><i class="fa fa-link"></i></a>LayerX</h2>

<p><a href="http://yuhua-chen.github.io/LayerX/" rel="nofollow noopener" target="_blank"><img src="https://camo.qiitausercontent.com/d76224b41420efb31200cbfee6f3ef33d41fde6e/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f36356137316537372d663836312d366232652d613661312d3132376532663232643662662e706e67" alt="スクリーンショット 2016-05-26 22.11.07.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/65a71e77-f861-6b2e-a6a1-127e2f22d6bf.png"></a></p>

<ul>
<li><a href="http://yuhua-chen.github.io/LayerX/" rel="nofollow noopener" target="_blank">LayerX - An intuitive app to display transparent images on screen.</a></li>
</ul>

<p>任意の画像ファイルをフローティング表示できる。細かいレイヤーの切り替えはできないが、PSDを直接表示することも可能。無料ソフト。</p>

<h3>
<span id="機能-3" class="fragment"></span><a href="#%E6%A9%9F%E8%83%BD-3"><i class="fa fa-link"></i></a>機能</h3>

<ul>
<li>OSXが対応する標準的な画像形式のファイルに対応</li>
<li>任意の表示倍率で、画像をフローティング表示できる</li>
<li>スクロールホイールで透明度を自由に変更できる</li>
<li>「ロック」ボタンを押すと位置と透明度が固定され、マウスクリックを無視する状態にできる</li>
</ul>

<h3>
<span id="便利な使い方-3" class="fragment"></span><a href="#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-3"><i class="fa fa-link"></i></a>便利な使い方</h3>

<ul>
<li>PSDファイルを薄めに透過させて、ロック状態でIDEに重ねる</li>
</ul>

<h2>
<span id="xscope" class="fragment"></span><a href="#xscope"><i class="fa fa-link"></i></a>xScope</h2>

<p><a href="https://camo.qiitausercontent.com/2798577d28c4d73e1c891b5adb606e09caa449a8/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f36643931613732342d396264312d633635642d633436392d6262633266626434336338612e706e67" target="_blank" rel="nofollow noopener"><img src="https://camo.qiitausercontent.com/2798577d28c4d73e1c891b5adb606e09caa449a8/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f36643931613732342d396264312d633635642d633436392d6262633266626434336338612e706e67" alt="スクリーンショット 2016-05-26 22.27.52.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/6d91a724-9bd1-c65d-c469-bbc2fbd43c8a.png"></a></p>

<ul>
<li><a href="http://xscopeapp.com/" rel="nofollow noopener" target="_blank">xScope • Measure. Inspect. Test.</a></li>
</ul>

<p>定規・ガイド・モバイル端末へのミラーリングなど、スクリーン上のピクセルの測定や解析に特化した強力なツール。49.99ドルの有料ソフト。</p>

<h3>
<span id="機能-4" class="fragment"></span><a href="#%E6%A9%9F%E8%83%BD-4"><i class="fa fa-link"></i></a>機能</h3>

<ul>
<li>自動でマウスポインタ近くのエリアを測定する「Dimension」ツール</li>
<li>マウスポインタを中心に座標とX/Yガイドを表示する「Crosshair」ツール</li>
<li>画面全体にX/Y軸ガイドを自由に設置できる「Guides」ツール</li>
<li><a href="http://xscopeapp.com/guide" rel="nofollow noopener" target="_blank">ほか多数</a></li>
</ul>

<h2>
<span id="browsersync" class="fragment"></span><a href="#browsersync"><i class="fa fa-link"></i></a>Browsersync</h2>

<p><a href="https://www.browsersync.io/" rel="nofollow noopener" target="_blank"><img src="https://camo.qiitausercontent.com/9cbf9c99fbb17aac0ac071e28fe65e9519e85a2c/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f34383233382f64663965363634652d346338622d353239312d303535322d3339353732303131333132622e706e67" alt="スクリーンショット 2016-05-26 22.47.07.png" data-canonical-src="https://qiita-image-store.s3.amazonaws.com/0/48238/df9e664e-4c8b-5291-0552-39572011312b.png"></a></p>

<ul>
<li><a href="https://www.browsersync.io/" rel="nofollow noopener" target="_blank">Browsersync - Time-saving synchronised browser testing</a></li>
</ul>

<p>node.jsによるオートリロード機能のある開発用Webサーバ。無料ソフト。</p>

<p>オートリロードがないとHeliumの導入効果が低下してしまう。node.jsやgulpとセットで環境を作る必要があるが、まだ導入していない場合はぜひ使用を推奨したい。</p>

<ul>
<li><a href="https://ics.media/entry/3405" rel="nofollow noopener" target="_blank">ブラウザ確認が一瞬！ Grunt・Gulpと始めるBrowserSync入門 - ICS MEDIA</a></li>
</ul>

<hr>

<div class="footnotes">
<hr>
<ol>

<li id="fn1">
<p>当記事における「ピクセルパーフェクト」とは、Webブラウザ上での表示とデザインカンプが完全に一致している状態を指す <a href="#fnref1">↩</a></p>
</li>

<li id="fn2">
<p>当記事における「デザインカンプ」とは、Webサイト完成時の理想的な外観表示を、画像として作成した資料を指す <a href="#fnref2">↩</a></p>
</li>

</ol>
</div>
<div class="hidden"><form class="js-task-list-update" action="/y_hokkey/items/f4f8518e9e9b9760a0a0" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="patch" /><input type="hidden" name="authenticity_token" value="Z9BRH7asLKgrC1ERwZ8vmxNlY2Zm3xftVUJSvwTo8FFqZVp1+tbm7rDf1PFh/y7AMgDpD7IQByOxS+qcd6gKwA==" /><input type="hidden" name="updated_at_confirmation_in_unixtime" id="updated_at_confirmation_in_unixtime" value="1473387509" class="js-task-list-updated-at" /><textarea name="raw_body" id="raw_body" class="js-task-list-field">
LPなどの視覚的なデザインを売りとしたサイトの場合、高い水準でカンプ通りの実装が求められる。自分では狂いなく再現したつもりでも、どこかでずれていてデザイナーから指摘されることもしばしばある。この記事では、[^1]デザインカンプの徹底再現（[^2] ピクセルパーフェクト）の必要性と、そのための便利なMacOSXアプリケーションを紹介する。

**要約**

* 他人の作ったデザインを高いレベルで再現するには、ピクセルパーフェクトを狙うくらいの意気込みが必要
* その為には、ブラウザへカンプを重ね合わせるチェックが有効
* Helium/Mapture/LayxerXは、フローティングと透過機能を持った非常に便利なアプリケーション

[^1]: 当記事における「ピクセルパーフェクト」とは、Webブラウザ上での表示とデザインカンプが完全に一致している状態を指す
[^2]: 当記事における「デザインカンプ」とは、Webサイト完成時の理想的な外観表示を、画像として作成した資料を指す

# なぜピクセルパーフェクトを目指すのか

Webサイトという技術の特性上、フォントが違ったり、組版の仕様が違ったり、文字サイズのデフォルト値が違ったり、モニタの色見が周辺環境や端末スペックによって違ったりとするため、**ピクセルパーフェクトにこだわる理由は本来的には無い**。

しかし、**デザイナーと実装担当者が分かれている場合、適当な意識での実装では、元々のデザインの意図を表現しきれないものができてしまう可能性がある**。これにはデザインを売り物にする上で大きな問題があるし、結局はデザイナー側から細かい修正を依頼され、予想外の工数をかけてしまうリスクもある。

他人の作ったデザインを細かいところまで再現するのは、熟練者でも簡単なことではない。ピクセルパーフェクトを狙うくらいの意気込みがあって、ようやくスムーズに実装ができるのではないだろうか。

### 重ね合わせチェック

ブラウザ(最も再現度が高くなると想定したもの)にデザインカンプを重ねることで、高い精度で誤差を修正できる。ただし、スクショを撮ってPhotoshopで重ね合わせるのは面倒で効率が悪く、おすすめできない。

代わりに、半透明でフローティング(常にどのアプリケーションよりも最前面に表示される)機能を持った、補助的なアプリケーションの導入を薦めたい。これを使うと、**IDEでコーディングをしながら、コーディング中のサイトとデザインカンプの誤差をリアルタイムで確認できる。**

はじめからページ全体で重ね合わせをすると誤差が大きすぎるので、。

* パーツ単位 ＜ モジュール単位 ＜ モジュール同士の間隔 ＜ ページ全体

という風に、小さい部分から頻繁に重ね合わせチェックをするのが良いかもしれない。面倒そうに思えるが、後述のHeliumとMaptureを使うと簡単に行える。

![MaptureとHeliumによる開発の様子をキャプチャしたスクリーンショット画像](https://qiita-image-store.s3.amazonaws.com/0/48238/cbec0dab-e85c-bc2b-c950-842996d4d73e.png)

画像はIDEにカンプとブラウザを透過で重ねている図。一見使い難そうに見えるが、邪魔な時は透明度を上げたり、掴んで画面外に置けば良く、それほど不便さはない。

# 徹底再現に便利なアプリケーション

## Helium

[![スクリーンショット 2016-05-26 22.06.21.png](https://qiita-image-store.s3.amazonaws.com/0/48238/fd21558d-7b90-53ff-1cf7-875eb098fad5.png)](http://heliumfloats.com/)

* [Helium by JadenGeller](http://heliumfloats.com/)
* [JadenGeller/Helium: A floating browser window for OS X](https://github.com/JadenGeller/Helium)

任意のWebページをフローティングで透過表示できる。オプションでマウスオーバー時にだけ透過を解除したり、透過中はマウス操作を無視させることもできる。無料ソフト。

### 機能

* 任意のWebサイトを表示し、フローティング表示できる
* オプションで透明度を自由に変更できる
* マウスオーバー時にだけ透明度を変えることができる
* 透過中はユーザーのマウス入力を無視させることができる

### 便利な使い方

* 後述のBrowsersyncで立ち上げたローカルサーバを表示させ、常にコードのプレビューをIDEの上に浮かせておく

## Mapture

[![スクリーンショット 2016-05-26 22.09.52.png](https://qiita-image-store.s3.amazonaws.com/0/48238/266924f0-40e4-75d7-cdee-79a622f518fc.png)](http://anatoo.jp/mapture/)

* [Mapture - MacOSX向けキャプチャユーティリティ](http://anatoo.jp/mapture/)
* [Mac用の作業支援キャプチャツール、Maptureがいい感じになった - id:anatooのブログ](http://blog.anatoo.jp/entry/20140108/1389107218)

Windowsの[Rapture](http://www.geocities.jp/knystd/rapture.html)のように、使い捨てのスクリーンショットを手軽に作成して画面に浮かべることができる。無料ソフト。

### 機能

* 画面の特定エリアを切り抜いて画像メモ化できる
* 任意の表示倍率で、画像メモをフローティング表示できる
* スクロールホイールで透明度を自由に変更できる
* ユーザーが明示しない限り画像ファイルは保存されない

### 便利な使い方

* PSDからパーツ単位でキャプチャを取り、IDEの上に浮かべる
* ブラウザの上に半透明で重ね、透明度をホイールでスクラブしながら、実装とカンプの誤差を確認する

## Adobe CC Extract

![Adobe CC Extract](https://qiita-image-store.s3.amazonaws.com/0/48238/01246c97-3c8c-0bd1-89b4-b6c1341687ca.png)

* [PSD 変換 - HTML、CSS | Creative Cloud Extract](http://www.adobe.com/jp/creativecloud/extract.html)
* [Creative Cloud ヘルプ | Extract による PSD から Web への抽出ワークフロー](https://helpx.adobe.com/jp/creative-cloud/help/extract-css-images-psd-files.html)

**[2016年6月28日に一旦終了した後、ユーザーの声で8月に再開](https://liginc.co.jp/301585)**を果たしたAdobeのフロントエンドエンジニア向けのWebサービス。AdobeCCで利用できるサービスに含まれる。

CreativeCloudのオンラインストレージにアップロードしたPSDデータを解析し、**ブラウザ上で横幅・高さ・フォントサイズ・行高などを即座にCSSコードとして取得したり、特定のレイヤー画像から画像を抽出・ダウンロードすることができる。**

![スクリーンショット_2016-09-07_21_46_09.png](https://qiita-image-store.s3.amazonaws.com/0/48238/355b2899-a29c-66d9-c07b-a8cf19ee08f3.png) ![スクリーンショット_2016-09-07_21_46_25.png](https://qiita-image-store.s3.amazonaws.com/0/48238/b2fe10a6-385e-2183-c85c-4ac1415f82fa.png)

 ![スクリーンショット_2016-09-07_21_46_45.png](https://qiita-image-store.s3.amazonaws.com/0/48238/da531e30-14b0-a666-640f-19a904185980.png)

UIが非常に使いやすく、**マークアップ担当者にとって必要な作業はがほとんどブラウザだけで完結する**。余計な機能がないので、むしろPhotoshopよりも使いやすい。既にAdobeCCアカウントを持っているのであれば、是非使ってみたいサービスだと思う。

### 機能

* レイヤー情報からのCSSコードの出力
* レイヤーからの画像出力(PNG・JPEG・SVGなど)
* レイヤー間の隙間の計測
* レイヤーの表示切り替え
* ファイルのオンライン共有
* PSDデータの実寸表示〜拡大・縮小
* フォント・カラー値の抽出

### 便利な使い方

* マシンリソース節約

## LayerX

[![スクリーンショット 2016-05-26 22.11.07.png](https://qiita-image-store.s3.amazonaws.com/0/48238/65a71e77-f861-6b2e-a6a1-127e2f22d6bf.png)](http://yuhua-chen.github.io/LayerX/)

* [LayerX - An intuitive app to display transparent images on screen.](http://yuhua-chen.github.io/LayerX/)

任意の画像ファイルをフローティング表示できる。細かいレイヤーの切り替えはできないが、PSDを直接表示することも可能。無料ソフト。

### 機能

* OSXが対応する標準的な画像形式のファイルに対応
* 任意の表示倍率で、画像をフローティング表示できる
* スクロールホイールで透明度を自由に変更できる
* 「ロック」ボタンを押すと位置と透明度が固定され、マウスクリックを無視する状態にできる

### 便利な使い方

* PSDファイルを薄めに透過させて、ロック状態でIDEに重ねる

## xScope

![スクリーンショット 2016-05-26 22.27.52.png](https://qiita-image-store.s3.amazonaws.com/0/48238/6d91a724-9bd1-c65d-c469-bbc2fbd43c8a.png)

* [xScope • Measure. Inspect. Test.](http://xscopeapp.com/)

定規・ガイド・モバイル端末へのミラーリングなど、スクリーン上のピクセルの測定や解析に特化した強力なツール。49.99ドルの有料ソフト。

### 機能

* 自動でマウスポインタ近くのエリアを測定する「Dimension」ツール
* マウスポインタを中心に座標とX/Yガイドを表示する「Crosshair」ツール
* 画面全体にX/Y軸ガイドを自由に設置できる「Guides」ツール
* [ほか多数](http://xscopeapp.com/guide)

## Browsersync

[![スクリーンショット 2016-05-26 22.47.07.png](https://qiita-image-store.s3.amazonaws.com/0/48238/df9e664e-4c8b-5291-0552-39572011312b.png)](https://www.browsersync.io/)

* [Browsersync - Time-saving synchronised browser testing](https://www.browsersync.io/)

Node.jsによるオートリロード機能のある開発用Webサーバ。無料ソフト。

オートリロードがないとHeliumの導入効果が低下してしまう。Node.jsやgulpとセットで環境を作る必要があるが、まだ導入していない場合はぜひ使用を推奨したい。

* [ブラウザ確認が一瞬！ Grunt・Gulpと始めるBrowserSync入門 - ICS MEDIA](https://ics.media/entry/3405)

---
</textarea><input type="submit" name="commit" value="Save changes" data-disable-with="Save changes" /></form></div></section></div><div class="col-sm-3"><div class="socialButtons"><div class="socialButtons_twitter"><a class="twitter-share-button" data-text="Web制作でデザインカンプを徹底再現する為の便利なアプリ by @y_hokkey on @Qiita" data-url="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" href="https://twitter.com/share">ツイート</a></div><div class="socialButtons_hatebu"><a class="hatena-bookmark-button" data-hatena-bookmark-layout="simple-balloon" data-hatena-bookmark-title="Web制作でデザインカンプを徹底再現する為の便利なアプリ" href="http://b.hatena.ne.jp/entry/https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" title="はてブに追加"><img alt="はてブに追加" height="20" src="https://b.st-hatena.com/images/entry-button/button-only@2x.png" style="border: none;" width="20" /></a><script async="async" charset="utf-8" src="https://b.st-hatena.com/js/bookmark_button.js" type="text/javascript"></script></div><div class="socialButtons_googlePlus"><div class="g-plusone" data-href="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" data-size="medium"></div></div><div class="socialButtons_facebook"><div class="fb-like" data-action="like" data-href="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" data-layout="button_count" data-share="false" data-show-faces="false"></div></div><div class="socialButtons_pocket"><a class="pocket-btn" data-lang="en" data-pocket-count="horizontal" data-pocket-label="pocket"></a></div></div><section class="itemsShowAuthorInfo" itemprop="author" itemscope="" itemtype="http://schema.org/Person"><a href="/y_hokkey"><img alt="" class="itemsShowAuthorInfo_userIcon" itemprop="image" src="https://qiita-image-store.s3.amazonaws.com/0/48238/profile-images/1473691279" /></a><div class="itemsShowAuthorInfo_profileStats"><strong class="itemsShowAuthorInfo_userName" itemprop="name"><a itemprop="url" href="/y_hokkey">y_hokkey</a></strong><div class="itemsShowAuthorInfo_contribution"><span class="itemsShowAuthorInfo_count">6938</span><span class="itemsShowAuthorInfo_unit">Contribution</span></div><script type="application/json" id="js-react-on-rails-context">{}</script>
<script type="application/json" class="js-react-on-rails-component" data-component-name="UserFollowButton" data-dom-id="UserFollowButton-react-component-9a8cdd84-f257-432a-bd36-7d7bb051c023">{"initial_followed_by":false,"position":"author-info","size":"btn-xs","url_name":"y_hokkey"}</script>
    <div id="UserFollowButton-react-component-9a8cdd84-f257-432a-bd36-7d7bb051c023"></div>
    
</div><section class="itemsShowAuthorPopularItems"><h5 class="itemsShowAuthorPopularItems_sectionTitle">人気の投稿</h5><ul class="itemsShowAuthorPopularItems_posts list-unstyled"><li itemscope="" itemtype="http://schema.org/Article"> <a itemprop="url" href="/y_hokkey/items/406b5a8c4bc15354d069">Dockerで即実行できる、社内・自宅向けオープンソースWebアプリ</a></li><li itemscope="" itemtype="http://schema.org/Article"> <a itemprop="url" href="/y_hokkey/items/de88447bd31d9379b80a">実装を引き受ける前に詰めておくべきWebフロントエンドの想定漏れチェックシート</a></li><li itemscope="" itemtype="http://schema.org/Article"> <a itemprop="url" href="/y_hokkey/items/d51e69c6ff4015e85fce">docker-composeを使うと複数コンテナの管理が便利に</a></li><li itemscope="" itemtype="http://schema.org/Article"> <a itemprop="url" href="/y_hokkey/items/7c02a3af319b353136d5">僕がredmineに入れてる便利なプラグインとデザインの格好良いテーマ</a></li><li itemscope="" itemtype="http://schema.org/Article"> <a itemprop="url" href="/y_hokkey/items/3267f7f9b1ced05e0cc0">決めておいた方が良いRedmine運用ルール</a></li></ul></section><section class="itemsShowAuthorInfo_organization"><h5 class="itemsShowAuthorInfo_organizationTitle">Organization</h5><span itemprop="memberOf" itemscope="" itemtype="http://schema.org/Organization"><a itemprop="url" href="/organizations/liginc"><img alt="株式会社LIG" class="itemsShowAuthorInfo_organizationLogo" itemprop="image" src="https://s3-ap-northeast-1.amazonaws.com/qiita-organization-image/546337236a7117d58ce8b439e0b1ba5d23b4d3f8/original.jpg?1506913979" /></a></span></section></section><div class="scroll-chaser"></div><script type="application/json" class="js-react-on-rails-component" data-component-name="Toc" data-dom-id="Toc-react-component-add286b0-ba28-4e57-aef1-d852317c68c1">{"body":"\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E3%81%AA%E3%81%9C%E3%83%94%E3%82%AF%E3%82%BB%E3%83%AB%E3%83%91%E3%83%BC%E3%83%95%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92%E7%9B%AE%E6%8C%87%E3%81%99%E3%81%AE%E3%81%8B\"\u003eなぜピクセルパーフェクトを目指すのか\u003c/a\u003e\n\u003cul\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E9%87%8D%E3%81%AD%E5%90%88%E3%82%8F%E3%81%9B%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF\"\u003e重ね合わせチェック\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\n\u003cli\u003e\n\u003ca href=\"#%E5%BE%B9%E5%BA%95%E5%86%8D%E7%8F%BE%E3%81%AB%E4%BE%BF%E5%88%A9%E3%81%AA%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3\"\u003e徹底再現に便利なアプリケーション\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#helium\"\u003eHelium\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E6%A9%9F%E8%83%BD\"\u003e機能\u003c/a\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9\"\u003e便利な使い方\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#mapture\"\u003eMapture\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E6%A9%9F%E8%83%BD-1\"\u003e機能\u003c/a\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-1\"\u003e便利な使い方\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#adobe-cc-extract\"\u003eAdobe CC Extract\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E6%A9%9F%E8%83%BD-2\"\u003e機能\u003c/a\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-2\"\u003e便利な使い方\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#layerx\"\u003eLayerX\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E6%A9%9F%E8%83%BD-3\"\u003e機能\u003c/a\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#%E4%BE%BF%E5%88%A9%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9-3\"\u003e便利な使い方\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#xscope\"\u003exScope\u003c/a\u003e\n\u003cul\u003e\n\u003cli\u003e\n\u003ca href=\"#%E6%A9%9F%E8%83%BD-4\"\u003e機能\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\u003cli\u003e\n\u003ca href=\"#browsersync\"\u003eBrowsersync\u003c/a\u003e\n\u003c/li\u003e\n\u003c/ul\u003e\n\u003c/li\u003e\n\n","wrapper":"#article-body-wrapper"}</script>
    <div id="Toc-react-component-add286b0-ba28-4e57-aef1-d852317c68c1"></div>
    
</div></div><div class="row"><div class="col-sm-9"><div class="ArticleFooter__menu"><div class="s-flex-align-center"><div class="js-likebutton" data-props="{&quot;like_status&quot;:false,&quot;like_count&quot;:104,&quot;show_count&quot;:true,&quot;uuid&quot;:&quot;f4f8518e9e9b9760a0a0&quot;,&quot;likable_type&quot;:&quot;Article&quot;,&quot;position&quot;:&quot;article-footer&quot;}"></div><div class="ArticleFooter__userList"><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="sutetotanuki"><a itemprop="url" href="/sutetotanuki"><img alt="sutetotanuki" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/4307/profile-images/1473683900" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="ShinjiroMoriya"><a itemprop="url" href="/ShinjiroMoriya"><img alt="ShinjiroMoriya" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/75592/profile-images/1504777912" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="yuuta12"><a itemprop="url" href="/yuuta12"><img alt="yuuta12" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/98730/profile-images/1473707589" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="epetilkehog"><a itemprop="url" href="/epetilkehog"><img alt="epetilkehog" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/8207/profile-images/1473680942" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="naru0504"><a itemprop="url" href="/naru0504"><img alt="naru0504" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/58800/profile-images/1473694740" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="lqd_jp"><a itemprop="url" href="/lqd_jp"><img alt="lqd_jp" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/83040/profile-images/1473702646" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="tamanugi"><a itemprop="url" href="/tamanugi"><img alt="tamanugi" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/55219/profile-images/1473693620" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="ymiyamae"><a itemprop="url" href="/ymiyamae"><img alt="ymiyamae" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/74135/profile-images/1480828957" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="shun-k1331"><a itemprop="url" href="/shun-k1331"><img alt="shun-k1331" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/40401/profile-images/1473688430" /></a></div></div><div class="ArticleFooter__user"><div class="js-hovercard" data-hovercard-target-name="suidobashi-papa"><a itemprop="url" href="/suidobashi-papa"><img alt="suidobashi-papa" class="thumb thumb--xs" src="https://qiita-image-store.s3.amazonaws.com/0/113387/profile-images/1473712244" /></a></div></div><div class="ArticleFooter__user"><a href="/y_hokkey/items/f4f8518e9e9b9760a0a0/likers"><span class="fa fa-ellipsis-h"></span></a></div></div></div><div class="u-flex u-align-center"><div class="ArticleFooter__stock"><div class="js-stockbutton" data-position="footer_menu" data-props="{&quot;stock_status&quot;:false}"></div></div><div class="ArticleFooter__editRequest"><a class="u-link-no-underline" data-toggle="tooltip" title="投稿者に記事をより良くするための提案ができます 💪" href="/drafts/f4f8518e9e9b9760a0a0/edit"><span class="fa fa-send-o fa-lg"></span> <span>編集リクエスト</span></a></div><div class="dropdown ArticleFooter__dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#"><span class="fa fa-ellipsis-h"></span></a><ul class="dropdown-menu dropdown-menu-right"><li><a href="/y_hokkey/items/f4f8518e9e9b9760a0a0.md"><span class="fa fa-fw fa-file-text-o"></span> Markdownで本文を見る</a></li><li><a data-target=".js-report-form" data-toggle="modal" href="#"><i class="fa fa-fw fa-flag"></i> 問題がある投稿を報告する</a></li></ul></div></div></div><div class="itemsShowBody_articleColumnFooter"><div class="socialButtons"><div class="socialButtons_twitter"><a class="twitter-share-button" data-text="Web制作でデザインカンプを徹底再現する為の便利なアプリ by @y_hokkey on @Qiita" data-url="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" href="https://twitter.com/share">ツイート</a></div><div class="socialButtons_hatebu"><a class="hatena-bookmark-button" data-hatena-bookmark-layout="simple-balloon" data-hatena-bookmark-title="Web制作でデザインカンプを徹底再現する為の便利なアプリ" href="http://b.hatena.ne.jp/entry/https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" title="はてブに追加"><img alt="はてブに追加" height="20" src="https://b.st-hatena.com/images/entry-button/button-only@2x.png" style="border: none;" width="20" /></a><script async="async" charset="utf-8" src="https://b.st-hatena.com/js/bookmark_button.js" type="text/javascript"></script></div><div class="socialButtons_googlePlus"><div class="g-plusone" data-href="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" data-size="medium"></div></div><div class="socialButtons_facebook"><div class="fb-like" data-action="like" data-href="https://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0" data-layout="button_count" data-share="false" data-show-faces="false"></div></div><div class="socialButtons_pocket"><a class="pocket-btn" data-lang="en" data-pocket-count="horizontal" data-pocket-label="pocket"></a></div></div></div><div class="itemsShowComment_wrapper" id="comments"><script type="application/json" class="js-react-on-rails-component" data-component-name="PublicCommentListContainer" data-dom-id="PublicCommentListContainer-react-component-cc9d10ef-53c3-46d1-9292-491708ea2d45">{"currentUser":null,"initialComments":[],"monthly_public_image_uploadable_size_limit":null,"total_uploaded_public_image_size_in_current_month":null,"item":{"id":395504,"uuid":"f4f8518e9e9b9760a0a0","suspended":false,"secret":false},"owner":{"url_name":"y_hokkey"},"is_team":false,"is_project":false,"logged_in":false,"polling":false,"mention_candidates":[{"id":48238,"url_name":"y_hokkey","profile_image_url":"https://qiita-image-store.s3.amazonaws.com/0/48238/profile-images/1473691279"}]}</script>
    <div id="PublicCommentListContainer-react-component-cc9d10ef-53c3-46d1-9292-491708ea2d45"></div>
    
</div></div></div></div></article><div class="js-report-form modal fade reportForm"><div class="modal-dialog"><div class="modal-content"><div class="modal-header"><button name="button" type="submit" class="close" data-dismiss="modal">&times;</button><h4 class="modal-title">問題がある投稿を報告する</h4></div><div class="modal-body"><form class="new_public_issue_report" id="new_public_issue_report" action="/api/internal/issue_reports" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="i7huJnTZKxXsSoAbrlPXI2Xd/uIIp27c0FMRxvMNqDGGDWVMOKPhU3eeBfsOM9Z4RLh0i9xofhI0WqnlgE1SoA==" /><input type="hidden" value="PublicDomainArticle" name="public_issue_report[target_type]" id="public_issue_report_target_type" /><input type="hidden" value="395504" name="public_issue_report[target_id]" id="public_issue_report_target_id" /><p>この投稿にどのような問題がありますか？</p><br /><div class="form-group"><ul class="list-unstyled"><li><label><input required="required" type="radio" value="spam" name="public_issue_report[reason]" id="public_issue_report_reason_spam" /> スパムです </label></li><li><label><input required="required" type="radio" value="harassment" name="public_issue_report[reason]" id="public_issue_report_reason_harassment" /> 攻撃的または迷惑な内容を含んでいます </label></li><li><label><input required="required" type="radio" value="inappropriate_content" name="public_issue_report[reason]" id="public_issue_report_reason_inappropriate_content" /> 不適切な内容を含んでいます </label></li></ul></div><div class="reportForm_submitButtonContainer"><button name="button" type="submit" class="btn btn-primary reportForm_submitButton"><i class="fa fa-send"></i> 送信</button></div></form></div></div></div></div><script id="js-item" type="application/json">{ "url": "http://qiita.com/y_hokkey/items/f4f8518e9e9b9760a0a0", "id": 395504, "uuid": "f4f8518e9e9b9760a0a0" }</script><script class="js-user" type="application/json">{&quot;id&quot;:48238,&quot;url_name&quot;:&quot;y_hokkey&quot;,&quot;profile_image_url&quot;:&quot;https://qiita-image-store.s3.amazonaws.com/0/48238/profile-images/1473691279&quot;}</script><script language="JavaScript" src="//cdn.bigmining.com/private/js/qiita_bigmining.js" type="text/javascript"></script></div><footer class="footer"><div class="footer_inner"><div class="footer_container"><ul class="footer_links-left"><li class="footer_link"><a class="footer_copyright" href="http://increments.co.jp">© 2011-2017 Increments Inc.</a></li><li class="footer_link"><a href="https://qiita.com/terms">利用規約</a></li><li class="footer_link"><a href="https://qiita.com/privacy">プライバシー</a></li><li class="footer_link"><a href="http://help.qiita.com">ヘルプ</a></li><li class="footer_link"><a href="https://increments.zendesk.com/anonymous_requests/new">お問い合わせ</a></li></ul><ul class="footer_links-right"><li class="footer_link"><a href="https://qiita.com/about">Qiitaとは</a></li><li class="footer_link"><a href="/users">ユーザー</a></li><li class="footer_link"><a href="/tags">タグ</a></li><li class="footer_link"><a href="http://blog.qiita.com">ブログ</a></li><li class="footer_link"><a href="https://qiita.com/api/v2/docs">API</a></li><li class="footer_link"><a href="https://teams.qiita.com/">Team</a></li><li class="footer_link"><a href="http://kobito.qiita.com">Kobito</a></li><li class="footer_link"><a class="js-public-form-feedback-link" data-target=".js-feedback-form" data-toggle="modal" href=""><i class="fa fa-heart"></i> ご意見 <i class="fa fa-caret-down"></i></a></li></ul></div></div></footer><div class="js-feedback-form modal fade feedbackForm"><div class="modal-dialog"><div class="modal-content"><div class="modal-header"><button name="button" type="submit" class="close" data-dismiss="modal">&times;</button><h4 class="modal-title">ご意見</h4></div><div class="modal-body"><form class="js-feedback-form-form" action="/feedbacks" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Nrd7A+vi/eyJw3hz9vXaG7tWtds6k9slFHUBrsWSJto7AnBpp5g3qhIX/ZNWldtAmjM/su5cy+vwfLmNttLcSw==" /><input type="hidden" name="redirect_path" id="redirect_path" value="/y_hokkey/items/f4f8518e9e9b9760a0a0" /><div class="form-group"><textarea name="feedback[message]" id="feedback_message" class="form-control js-feedback-form-text-area" placeholder="Qiitaについてのご意見をお聞かせください。" required="required" rows="5">
</textarea></div><div class="feedbackForm_submitButtonContainer"><button name="button" type="submit" class="btn btn-primary feedbackForm_submitButton"><i class="fa fa-send"></i> 送信</button><p class="feedbackForm_note">いただいたご意見への返信は行っておりません。<br />返信の必要な内容については、<a href="https://increments.zendesk.com/anonymous_requests/new">こちら</a> からお問い合わせください。</p></div><div style="position:fixed;top:-99999px;opacity:0.0001;"><input name="feedback[name]" type="text" /></div></form></div></div></div></div><script>// if (window.mixpanel instanceof Element) {
//   window.mixpanel = [];
// }
// (function(f,b){if(!b.__SV){var a,e,i,g;window.mixpanel=b;b._i=[];b.init=function(a,e,d){function f(b,h){var a=h.split(".");2==a.length&&(b=b[a[0]],h=a[1]);b[h]=function(){b.push([h].concat(Array.prototype.slice.call(arguments,0)))}}var c=b;"undefined"!==typeof d?c=b[d]=[]:d="mixpanel";c.people=c.people||[];c.toString=function(b){var a="mixpanel";"mixpanel"!==d&&(a+="."+d);b||(a+=" (stub)");return a};c.people.toString=function(){return c.toString(1)+".people (stub)"};i="disable track track_pageview track_links track_forms register register_once alias unregister identify name_tag set_config people.set people.set_once people.increment people.append people.track_charge people.clear_charges people.delete_user".split(" ");
// for(g=0;g<i.length;g++)f(c,i[g]);b._i.push([a,e,d])};b.__SV=1.2;a=f.createElement("script");a.type="text/javascript";a.async=!0;a.src="//cdn.mxpnl.com/libs/mixpanel-2.2.min.js";e=f.getElementsByTagName("script")[0];e.parentNode.insertBefore(a,e)}})(document,window.mixpanel||[]);</script><script src="https://cdn.qiita.com/assets/public-d8eea21be0e6fd4202c68e4573c962fc.min.js"></script></body></html>