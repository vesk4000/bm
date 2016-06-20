---
layout: default
title: Bitcoin madenciliği hakkında bilmeniz gereken her şey
toc:
  mdk: Madencilik Donanımı Karşılaştırması
  bmn: Bitcoin Madenciliği Nedir?
  blok-zinciri-nedir: Blok zinciri Nedir?
  yikn: Yapılan işin kanıdı nedir?
  mz: Bitcoin Madencilik Zorluğu nedir?
  hzp: Hesaplamadaki Zorluk Problemi
  zorluk: Zorluğa göre Bitcoin Ağı
  bo: Blok Ödülü
---


<center><iframe width="720" height="394" src="https://www.youtube.com/embed/GmOzih6I1zs" frameborder="0" allowfullscreen></iframe></center>

<div class="home-grid">
	<a href="/getting-started/" class="section">
		<img src="/images/icons/mining.png"> 
		<div class="section-title">New to Mining?</div> 
		<div class="section-view">Get started ›</div> 
	</a>
	<a href="/bitcoin-mining-hardware/" class="section">
		<img src="/images/icons/mining2.png"> 
		<div class="section-title">Mining Hardware</div> 
		<div class="section-view">Learn More ›</div> 
	</a>
	<a href="/best-bitcoin-cloud-mining-contract-reviews/" class="section">
		<img src="/images/icons/cloud.png"> 
		<div class="section-title">Cloud Mining</div> 
		<div class="section-view">Learn More ›</div> 
	</a>
</div>

<img class="icon-home" alt="bitcoin madenciliği" src="/images/icons/icon-big-bitcoinfrom.png">
<h2>Bitcoin Madenciliği Nasıl Çalışır</h2>
<p>Bitcoinler nereden geliyor? Kağıt paranın ne zaman basılacağına ve dağıtılacağına devlet karar verir. Ancak Bitcoin'in merkezi bir hükümeti yoktur.</p>

<p>Bitcoin'de, madenciler matematik problemlerini çözmek için <a href="/bitcoin-mining-software/">özel yazılımlar</a> kullanır ve sonucunda bir miktar yeni Bitcoin yaratılır. Aslında bu yeni paranın üretilmesi için çok zekice bir yöntemdirVe insanları madenci olmaya teşvik eder.</p>

<img class="icon-home" alt="bitcoin güvenlidir" src="/images/icons/icon-big-secure.png">
<h2>Bitcoin Güvenlidir</h2>

<p>Bitcoin madencileri ödemeleri doğrulayarak Bitcoin ağının güvenli kalmasını sağlar. Madencilik Bitcoin'in önemli bir parçasıdır ve Bitcoin ağını güvenli, adil ve sorunsuz tutar.</p>

<img class="icon-home" alt="bitcoin güvenlidir" src="/images/icons/icon-big-links.png">
<h2>Linkler</h2>
<ul>
	<li><a href="https://www.weusecoins.com/" target="_blank">We Use Coins</a> - Kripto-para birimleri hakkında her şeyi öğrenin.<br></li>
	<li><a href="https://www.reddit.com/r/Bitcoin/" target="_blank">Bitcoin Haberleri</a> - Bitcoin topluluğunun haberleri öğrendiği yer.<br></li>
	<li><a href="http://www.bitcoin.kn">Bitcoin Bilgiler Ses Kayıtları</a> - Bitcoin dünyasındaki en ünlü insanlarla röportajlar.</li>
</ul>

<hr id="mdk" style="width: 100%; margin: 20px 0; color: #eee;" />

<h2>Madenci Donanmıları Karşılaştırması</h2>

<p>Şimdilik, hash başına fiyat <b>(1)</b> ve elektriksel verimliliğe <b>(2)</b> göre en iyi Bitcoin madenci seçenekleri şunlardır:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

<hr style="width: 100%; margin: 20px 0; color: #eee;" />
<h2 id="bmn">Bitcoin Madenciliği Nedir?</h2>
<center><img src="/images/what-is-bitcoin-mining.png" width="700" height="auto">
<a href="/images/what-is-bitcoin-mining-high-resolution.png" target="_blank">Yüksek çözünürlüklü infografiği görselleştirin ve indirin</a></center>

{% include page-toc.html %}

<p>Bitcoin madenciliği, ödemeleri herkese açık bir deftere (<b>blok zincirine</b>) kaydetme işlemidir. Geçmiş ödemelerin kaydedildiği yere blok zinciri denir çünkü blokların bulunduğu zincirdir. Bu blok zinciri, ağa bağlı diğer bilgisayarlara doğrulamaları için ödemeleri dağıtır.
<p>Bitcoin düğümleri <b>blok zincirini</b> doğru ödemelerden, çoktan başka bir yere ödenmiş tekrar-ödemeleri ayırmak için kullanır.
<h3 id="blok-zinciri-nedir">Blok inciri nedir?</h3>
<center><iframe width="700" height="394" src="https://www.youtube.com/embed/YIVAluSL9SU" frameborder="0" allowfullscreen></iframe></center>
<p><a href="http://bitcoinminer.com/">Bitcoin madenciliği</a> kasten kaynaklara-aç ve zor tasarlanmıştır, böylece her gün madencilerin bulduğu blok sayısı sabit kalır. Her blok geçerli olduğunu kanıtlamak için<a href="/what-is-proof-of-work/">İşin Kanıdı'nı</a> taşımak zorundadır. Diğer Bitcoin düğümleri, bir blok onlara ulaştığı zaman İşin Kanıdı'nı doğrularlar. Bitcoin <a href="/what-is-hashcash/">hashcash</a> adında bir İşin Kanıdı fonksiyonu kullanır.
<p>Madenciliğin en önemli amacı Bitcoin düğümlerine güvenli ve hatasız bir uzlaşma sağlamaktır. Madencilik ayrıca sisteme yeni Bitcoinler ekleyen bir mekanizmadır: Madenciler işlem ücretleri ve yeni yaratılmış Bitcoinlerle ödüllendirilir.
<p>This both serves the purpose of disseminating new coins in a decentralized manner as well as motivating people to provide security for the system.
<p>Bitcoin mining is so called because it resembles the mining of other commodities: it requires exertion and it slowly makes new currency available at a rate that resembles the rate at which commodities like gold are mined from the ground.
<h2 id="wipow">What is Proof of Work?</h2>
<center><img src="/images/what-is-proof-of-work.png" width="700" height="auto">
<a href="/images/what-is-proof-of-work-high-resolution.png" target="_blank">Visualize and Download High-Resolution Infographic</a></center></center>
<p>A <a href="/what-is-proof-of-work/">proof of work</a> is a piece of data which was difficult (costly, time-consuming) to produce so as to satisfy certain requirements. It must be trivial to check whether data satisfies said requirements.
<p>Producing a proof of work can be a random process with low probability, so that a lot of trial and error is required on average before a valid proof of work is generated. Bitcoin uses the Hashcash proof of work.
<h2 id="md">What is Bitcoin Mining Difficulty?</h2>
<center><img src="/images/what-is-bitcoin-mining-difficulty.png" width="700" height="auto">
<a href="/images/what-is-bitcoin-mining-difficulty-high-resolution.png" target="_blank">Visualize and Download High-Resolution Infographic</a></center>
<h3 id="tcdp">The Computationally-Difficult Problem</h3>
<p>Bitcoin mining a block is difficult because the SHA-256 hash of a block's header must be lower than or equal to the target in order for the block to be accepted by the network.
<p>This problem can be simplified for explanation purposes: The hash of a block must start with a certain number of zeros. The probability of calculating a hash that starts with many zeros is very low, therefore many attempts must be made. In order to generate a new hash each round, a nonce is incremented. See Proof of work for more information.
<h3 id="difficulty">The Bitcoin Network Difficulty Metric</h3>
<p>The <a href="/what-is-bitcoin-mining-difficulty/">Bitcoin mining network difficulty</a> is the measure of how difficult it is to find a new block compared to the easiest it can ever be. It is recalculated every 2016 blocks to a value such that the previous 2016 blocks would have been generated in exactly two weeks had everyone been mining at this difficulty. This will yield, on average, one block every ten minutes.
<p>As more miners join, the rate of block creation will go up. As the rate of block generation goes up, the difficulty rises to compensate which will push the rate of block creation back down. Any blocks released by malicious miners that do not meet the required difficulty target will simply be rejected by everyone on the network and thus will be worthless.
<h3 id="bw">The Block Reward</h3>
<p>When a block is discovered, the discoverer may award themselves a certain number of bitcoins, which is agreed-upon by everyone in the network. Currently this bounty is 25 bitcoins; this value will halve every 210,000 blocks. See Controlled Currency Supply.
<p>Additionally, the miner is awarded the fees paid by users sending transactions. The fee is an incentive for the miner to include the transaction in their block. In the future, as the number of new bitcoins miners are allowed to create in each block dwindles, the fees will make up a much more important percentage of mining income.
