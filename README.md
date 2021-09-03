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
  background:url(https://torokoid.github.io/access-test/20210831_007.jpg) center/cover no-repeat; /*fixedをトル！*/
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

<h3><span class="white">JR宇都宮駅の西側にある、ハムショップのノード局にアクセスしやすいのはどちらのアンテナか、<br>実験しました。リグはFTM300Dで50Watt送信。<br>コースは宇都宮から１駅北上した岡本駅から東側の鬼怒川を渡って、南南東に進むルート。<br>東進、南下側で屋根上のアンテナ、Uターンして、北上、西進側でテールゲートのアンテナを試しました。</span></h3>
<a href="20210831_004.png" data-lightbox="abc"><img src="20210831_004.png" alt="サンプル画像" width="900" /></a>
<h3><span class="white">比較したのは、テールゲートのダイヤモンドSG7900と、最近見かける極太アンテナ。</span></h3>
<a href="20210831_001.jpg" data-lightbox="abc"><img src="20210831_001.jpg" alt="サンプル画像" width="900" /></a>
<h3><span class="white">SG7900はやけに長いので、走行中に揺れないように釣り糸で２方向に引っ張りました。</span></h3>
<a href="20210831_002.jpg" data-lightbox="abc"><img src="20210831_002.jpg" alt="サンプル画像" width="900" /></a>
<h3><span class="white">極太アンテナは、給電部高さ的には有利な位置にセット。</span></h3>
<a href="20210831_003.jpg" data-lightbox="abc"><img src="20210831_003.jpg" alt="サンプル画像" width="900" /></a>	
<h3><span class="white">SG7900のカタログデータ。</span></h3>
<a href="20210831_005.png" data-lightbox="abc"><img src="20210831_005.png" alt="サンプル画像" width="900" /></a>
<h3><span class="white">極太アンテナのカタログデータ。</span></h3>
<a href="20210831_006.png" data-lightbox="abc"><img src="20210831_006.png" alt="サンプル画像" width="900" /></a>
<br>
<h2><span class="yellow">結果はSG7900の圧勝でした。<br>極太アンテナは全域でノードにアクセス出来ず＆APRSの軌跡を残せずでした。<br>SG7900は基地局に対して車体の後ろに回った状態でもアクセス出来てました。<br>Amazonの口コミを見たら、極太アンテナは２mの波が出ないと書かれてます。</span></h2>
	<br>
<h2><span class="white">追加試験</span></h2>	
<h2><span class="yellow">自宅に上げたGPアンテナでハンディー機から波出せるかチェックしました。<br>物置から引っ張り出したGPはなんと1.2GHz対応で、N型接栓。セットの同軸もやけに太いものでしたが、ハンディー機の5Watt出力で宇都宮のノード局にすんなり接続。<br>給電点の高さは3m程度ですね。</span></h2>

<a href="20210831_011.jpg" data-lightbox="abc"><img src="20210831_011.jpg" alt="サンプル画像" width="400" /></a>	
<a href="20210831_012.JPG" data-lightbox="abc"><img src="20210831_012.JPG" alt="サンプル画像" width="400" /></a>

<h2><span class="yellow">現時点の結論は、車側の空中線が非力・・・給電点高さを確保してみましょう！</span></h2>
	<br><br>
<h3><span class="white">次のテストは、アンテナ角度変えられるマグネット基台で、屋根上に設置しアンテナを前に倒してみますかね〜自衛隊の車がよくやってるやつです。<br>基台の候補はこれ。</span></h3>
<a href="20210831_008.png" data-lightbox="abc"><img src="20210831_008.png" alt="サンプル画像" width="900" /></a>	
<h3><span class="white">9月1日にアンテナを倒す件を、いつもいろいろ教えて頂く四国のOM殿に聞いてみると、430は縦偏波だから厳しいかもね〜とのサジェッションいただきました。<br>ただ、ハンディー機を手持ちで使う時にかなり横にしても使えているので、試しにノード局に縦と横でアクセスする実験しました。動画は自宅２階からのアクセス実験映像です。</span></h3>

<iframe width="560" height="315" src="https://www.youtube.com/embed/i2nbK59qE9c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	
<iframe width="560" height="315" src="https://www.youtube.com/embed/nfo6nvLNa-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h3><span class="white">接続の成功確率がやや落ちますが、受診時のSはあまり変わりませんでした。<br>まあ、ハンディー機特有の性質かもしれないので、天気の良い時にでも車の屋根にSG9700を斜め設置して、給電点が上がった効果と偏波面寝せたマイナス効果の比較で、どちらが勝つか実験してみましょう。<br>電波がものに当たって反射すると、偏波面が回転する？と言うほのかな記憶にも期待中〜<br>本日9/1はここまでです。</span></h3>	
	
<br><br>
	
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<h2><span class="white">追加情報</span></h2>
<h2><span class="yellow">最近のアンテナのカタログに(DIGITAL対応)と書かれているのが気になったので、<br>メーカーにメールして確認しました。<br>結論は「関係ありません」とのこと。<br>以下メールやり取りの記録。問い合わせから返答まで、26分の速さにはびっくりです。</span></h2>
<a href="20210831_009.png" data-lightbox="abc"><img src="20210831_009.png" alt="サンプル画像" width="900" /></a>	
<h2><span class="white">この話を無線仲間にも伝える旨をお礼と共に打診しました。</span></h2>
<a href="20210831_016.png" data-lightbox="abc"><img src="20210831_016.png" alt="サンプル画像" width="900" /></a>
<br><br><br><br><br>

<h2><span class="yellow">YAESUのハンディー機がACアダプターで充電しながらの送信ができない様なので、<br>メーカーにメールで問い合わせしました。<br>結論は送信には未対応、オプションを使えば送信可能とのことでした。</span></h2>
<a href="20210831_013.png" data-lightbox="abc"><img src="20210831_013.png" alt="サンプル画像" width="900" /></a>
<h2><span class="white">これですね。</span></h2>
<a href="20210831_015.png" data-lightbox="abc"><img src="20210831_015.png" alt="サンプル画像" width="900" /></a>
	
<h2><span class="white">さらに、シガーライター電源のケースに何か回路が入っているのか？問い合わせました。</span></h2>
<a href="20210831_014.png" data-lightbox="abc"><img src="20210831_014.png" alt="サンプル画像" width="900" /></a>
<h2><span class="yellow">最後の問い合わせには、直接電話での回答が来ました。<br>結論は「ノイズ対策用フィルタ」と「トリクル充電回路が入っています」との事。<br>安定化電源を使うときはノイズは無いので直結で可、<br>トリクル充電回路は、無線機の状態によって、充電に98%、運用に2%などの割合調整をしているとの事でした。<br>最後の問い合わせに対して返信が来ないな〜と思っていたところに電話が来てびっくりでした。<br>さすが一流メーカーですね。サポートがしっかりしています。</span></h2>	


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
 Copyright 2021/08/31 S.Hada
	 </span></footer>
