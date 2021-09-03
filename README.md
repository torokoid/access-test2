# access-test2
<html lang="ja">
 <head>
  <meta charset="utf-8" />
	 

<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }

 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}

	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://torokoid.github.io/access-test2/20210903_002.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
 
</head>
<body>

<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
	
<p><a href="https://torokoid.github.io/access-test">access-test</a>>access-test2</p>
	
<!—表題の表示、背景黄色、流れ文字の例—>
<h1><span class="yellow"><marquee behavior="alternate">!!! GPアンテナ、給電点高さ違い、傾きでの性能比較 !!!</marquee></span></h1>
	
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h2><span class="white">宇都宮のハムショップノードまで約10km弱の距離から、アクセステスト。</span></h2>
<a href="20210903_001.JPG" data-lightbox="abc"><img src="20210903_001.JPG" alt="サンプル画像" width="900" /></a>
<h2><span class="white">トランクリッドをノード局側に向けています。<br>屋根上のアンテナはややゲインが落ちますが、これで効果が無ければ、屋根にあげる価値なしとします。</span></h2>
<a href="20210903_003.JPG" data-lightbox="abc"><img src="20210903_003.JPG" alt="サンプル画像" width="900" /></a>
<h3><span class="white">SG7500とSG7900のカタログデータ。</span></h3>
<a href="20210903_009.JPG" data-lightbox="abc"><img src="20210903_009.JPG" alt="サンプル画像" width="900" /></a>
<a href="https://torokoid.github.io/access-test/20210831_005.png" data-lightbox="abc"><img src="https://torokoid.github.io/access-test/20210831_005.png" alt="サンプル画像" width="900" /></a>
	
<h2><span class="white">屋根上だと、S3でアクセスしました。</span></h2>
<a href="20210903_007.JPG" data-lightbox="abc"><img src="20210903_007.JPG" alt="サンプル画像" width="900" /></a>	
<h2><span class="white">アンテナを寝せた状態でのアクセステスト、流石にこれではアクセスしませんでした。</span></h2>
<a href="20210903_004.JPG" data-lightbox="abc"><img src="20210903_004.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210903_005.JPG" data-lightbox="abc"><img src="20210903_005.JPG" alt="サンプル画像" width="900" /></a>
<h2><span class="white">アンテナの寝せ方を電波がノード局方向に出る様にした状態でのアクセステスト。</span></h2>
<a href="20210903_006.JPG" data-lightbox="abc"><img src="20210903_006.JPG" alt="サンプル画像" width="900" /></a>
<h2><span class="white">寝せた状態だと、S1でアクセスしました。</span></h2>
<a href="20210903_008.JPG" data-lightbox="abc"><img src="20210903_008.JPG" alt="サンプル画像" width="900" /></a>

<h2><span class="white">最後にトランクリッドのSG7900でアクセステスト<br>こちらもS1でアクセスしました。</span></h2>
	
<iframe width="560" height="315" src="https://www.youtube.com/embed/F1DE_HqGI5U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>	

<h1><span class="yellow">結果は給電点を上げれば効果がある。<br>ただしアンテナ長さを克服するために寝るとやはりSが落ちる。<br>短いアンテナを屋根上にあげるテストはできていないが、<br>SG7500の垂直置きでもS1 → S3で、Sが2しか上がらないので、<br>短いアンテナでは期待薄。<br>結論：しばらくはトランクリッドのSG9700で行きますかね〜！。</span></h1>	


<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<p align="right"><marquee direction="left" scrollamount="5" width="85%">以上、ここまでご覧いただき、ありがとうございました！ (^_^)/~hada</marquee></p>

<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<br><br>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 

<!-- フッタ -->
 <footer><span class="white">
 Copyright 2021/09/03 S.Hada
	 </span></footer>
