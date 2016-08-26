---
title: Todo lo que necesitas saber para minar Bitcoin
---

<center>
<iframe width="720" height="394" src="https://www.youtube.com/embed/GmOzih6I1zs" frameborder="0" allowfullscreen></iframe>
<p>Una traducción esta en proceso! Revisa nuestro GitHub si quieres contribuir.</p>
</center>

<div class="home-grid">
	<a href="/getting-started/" class="section">
		<img src="/images/icons/mining.png"> 
		<div class="section-title">Quieres aprender a minar?</div> 
		<div class="section-view">Quieres aprender mas?›</div> 
	</a>
	<a href="/bitcoin-mining-hardware/" class="section">
		<img src="/images/icons/mining2.png"> 
		<div class="section-title">Equipo para minar</div> 
		<div class="section-view">Quieres aprender mas? ›</div> 
	</a>
	<a href="/best-bitcoin-cloud-mining-contract-reviews/" class="section">
		<img src="/images/icons/cloud.png"> 
		<div class="section-title">Minando en la nube electronica</div> 
		<div class="section-view">Quieres aprender mas? ›</div> 
	</a>
</div>

<img class="icon-home" alt="bitcoin mining" src="/images/icons/icon-big-bitcoinfrom.png">
<h2>Como Minar Bitcoin</h2>
<p>De donde vienen las bitcoins? Con el papel moneda, un gobierno decide cuando y como distribuir el dinero. Bitcoin no tiene un banco central.</p>

<p>Con Bitcon, mineros usan <a href="/bitcoin-mining-software/">programas especiales (en Ingles)</a> para que, despues de resolver problemas matematicos, estos mineros reciber cierto numero de bitcoins. Esta es una forma inteligente para producir esta divisa y provee un incentivo para que cada vez haya mas gente que se dedique a minar.</p>

<img class="icon-home" alt="bitcoin is secure" src="/images/icons/icon-big-secure.png">
<h2>Bitcoin es una divisa segura</h2>

<p>Mineros electronicos ayudan a mantener la red de Bitcoin segura ayudando a aprobar las transacciones de la divida. Minar es una parte importante e integra que garantiza que el proceso sea justo y al mismo tiempo mantiene la red de Bitcon estable, y segura.</p>

<img class="icon-home" alt="bitcoin is secure" src="/images/icons/icon-big-links.png">
<h2>Links</h2>
<ul>
	<li><a href="https://www.weusecoins.com/" target="_blank">Nosotros usamos monedas</a> - Aprende todo lo que necesitas saber de las cripto-divisas.<br></li>
	<li><a href="https://www.reddit.com/r/Bitcoin/" target="_blank">Noticias relacionadas al Bitcoin</a> - Donde nuestra comunidad encuentra noticias relacionadas al Bitcon.<br></li>
	<li><a href="http://www.bitcoin.kn">Podcast para conocer mas de Bitcoin</a> - Entrevistas con las personas que estan mas al tanto del mundo del Bitcoin</li>
</ul>

<hr id="hwc" style="width: 100%; margin: 20px 0; color: #eee;" />

<h2>Compara equipos de minado de Bitcoin</h2>

<p>Por lo pronto, basado en <b>(1)</b> precio por "hash" y <b>(2)</b> eficiencia electrica, los mejores mineros de Bitcoin son los siguientes:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

<hr style="width: 100%; margin: 20px 0; color: #eee;" />
<h2 id="wibm">Que significa minar Bitcoin?</h2>
<center><img src="/images/what-is-bitcoin-mining.jpg" width="700" height="auto">
<a href="/images/what-is-bitcoin-mining.jpg" target="_blank">Revisa y baja una copia de alta resolucion de este infografico</a></center>

{% include page-toc.html %}

<p>Miran Bitcoin es el proceso por el cual se añaden transacciones al registro de archivos de Bitcoin's o, como se conoce en ingles, <b>block chain</b>. Este registo de archivos se llama "block chain" porque es una cadena de bloques. El "block chain" se usa para confirmar y cotejar transacciones con el resto de la red Bitcoin cuando estas transacciones pasan.
<p>Los nodos de Bitcoin usan la <b>block chain</b> para separar las transacciones de Bitcoin que son legitimas con las ilicitas, que pasan cuando hay intentos de reusar las bitcoins que ya se gastaron en otro lado.
<h3 id="what-is-blockchain">Qué es el Blockchain?</h3>
<center><iframe width="700" height="394" src="https://www.youtube.com/embed/YIVAluSL9SU" frameborder="0" allowfullscreen></iframe></center>
<p><a href="http://bitcoinminer.com/">La mineria Bitcoin</a> está intencionalmente diseñada to be resource-intensive and difficult so that the number of blocks found each day by miners remains steady. Individual blocks must contain a <a href="/what-is-proof-of-work/">proof of work</a> to be considered valid. This proof of work is verified by other Bitcoin nodes each time they receive a block. Bitcoin uses the <a href="/what-is-hashcash/">hashcash</a> proof-of-work function.
<p>The primary purpose of mining is to allow Bitcoin nodes to reach a secure, tamper-resistant consensus. Mining is also the mechanism used to introduce Bitcoins into the system: Miners are paid any transaction fees as well as a "subsidy" of newly created coins.
<p>This both serves the purpose of disseminating new coins in a decentralized manner as well as motivating people to provide security for the system.
<p>Bitcoin mining is so called because it resembles the mining of other commodities: it requires exertion and it slowly makes new currency available at a rate that resembles the rate at which commodities like gold are mined from the ground.
<h2 id="wipow">What is Proof of Work?</h2>
<p>A <a href="/what-is-proof-of-work/">proof of work</a> is a piece of data which was difficult (costly, time-consuming) to produce so as to satisfy certain requirements. It must be trivial to check whether data satisfies said requirements.
<p>Producing a proof of work can be a random process with low probability, so that a lot of trial and error is required on average before a valid proof of work is generated. Bitcoin uses the Hashcash proof of work.
<h2 id="md">What is Bitcoin Mining Difficulty?</h2>
<h3 id="tcdp">The Computationally-Difficult Problem</h3>
<p>Bitcoin mining a block is difficult because the SHA-256 hash of a block's header must be lower than or equal to the target in order for the block to be accepted by the network.
<p>This problem can be simplified for explanation purposes: The hash of a block must start with a certain number of zeros. The probability of calculating a hash that starts with many zeros is very low, therefore many attempts must be made. In order to generate a new hash each round, a nonce is incremented. See Proof of work for more information.
<h3 id="difficulty">The Bitcoin Network Difficulty Metric</h3>
<p>The <a href="/what-is-bitcoin-mining-difficulty/">Bitcoin mining network difficulty</a> is the measure of how difficult it is to find a new block compared to the easiest it can ever be. It is recalculated every 2016 blocks to a value such that the previous 2016 blocks would have been generated in exactly two weeks had everyone been mining at this difficulty. This will yield, on average, one block every ten minutes.
<p>As more miners join, the rate of block creation will go up. As the rate of block generation goes up, the difficulty rises to compensate which will push the rate of block creation back down. Any blocks released by malicious miners that do not meet the required difficulty target will simply be rejected by everyone on the network and thus will be worthless.
<h3 id="bw">The Block Reward</h3>
<p>When a block is discovered, the discoverer may award themselves a certain number of bitcoins, which is agreed-upon by everyone in the network. Currently this bounty is 25 bitcoins; this value will halve every 210,000 blocks. See Controlled Currency Supply.
<p>Additionally, the miner is awarded the fees paid by users sending transactions. The fee is an incentive for the miner to include the transaction in their block. In the future, as the number of new bitcoins miners are allowed to create in each block dwindles, the fees will make up a much more important percentage of mining income.
