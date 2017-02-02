---
layout: post
title: Spondoolies-Tech SP20 Jackson Review
description: Spondoolies-Tech SP20 Jackson Review
author: Melvin Draupnir
authorurl: https://www.weusecoins.com/melvin-draupnir/
published: true
---

<hr id="hwc" style="width: 100%; margin: 20px 0; color: #eee;" />

<h2>Bitcoin Mining Hardware Comparison</h2>

<p>Currently, based on <b>(1)</b> price per hash and <b>(2)</b> electrical efficiency the best Bitcoin miner options are:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

<p><h2>The SP20 Jackson is a Bitcoin ASIC miner made by Spondoolies-Tech. The miner's claimed hash rate is 1.3-1.7TH/s.</h2></p>

<h2>PROS</h2>

<p>1.7 TH/s max hashrate tops its nearest rival, the AntMiner S5</p>
<p>Costs just $110, can be purchased on eBay or Amazon</p>
<p>Quiet at low speeds, generating ~52 dB from 1 meter</p>

<h2>CONS</h2>

<p>Spondoolies co. has closed, meaning limited availability & support</p>
<p>The unit runs quite hot, especially at higher speed</p>
<p>At 0.9W/GH, its efficiency is poor compared to the S5’s 0.25W/GH</p>

<h2>The Spondoolies SP20: Better Value than the AntMiner S5?</h2>

<p>Spondoolies unfortunately shut down on May 4th 2016. In late 2014, they released the SP20. <a href="/bitgold-goldmoney-review/">Spondoolies crammed</a> a total of eight 28nm RockerBox ASIC mining chips onto 2 circuit boards within a compact form factor. The SP20 is a neat miner, powerful for its low price with a size and noise level suitable for home miners. The major drawback is its relative inefficiency. The SP20 draws a lot of power for its hashrate, which is low by modern standards.</p>

<h2>Power Supply</h2>

<p>Any ATX PSU of sufficient wattage (1200W+) will run the SP20 without problems. In keeping with the SP20’s flexible design, you may also use dual lower wattage (750W+) PSUs to replace a single powerful PSU.</p>

<h2>Bitcoins / Month (Profitability)</h2>

<p>Unless you have free electricity, it’s highly unlikely the SP20 will ever pay for itself, never mind <a href="/spondoolies-tech-SP20-bitcoin-miner-setup/">make a profit</a>. If we enter the SP20’s stats and some average costs into the CoinWarz mining profitability calculator:</p>


<p>Far less than a single BTC will be mined in a year, making the SP20 a waste of electricity.</p>

<h2>Price</h2>

<p>The SP20 costs in the region of $110 from eBay.</p>

<h2>Casing</h2>

<p>The SP20 has a solid, rectangular metal housing which is easy to stack or store.</p>

<h2>Noise</h2>

<p>The SP20’s 120mm fan is quieter than the models in either the SP10 or SP30 models. Although it get noisier <a href="/banks-and-brokerages-should-be-mining-the-blockchain/">the faster and hotter</a> the SP20 runs, it’s quiet enough to run in a home.</p>

<h2>Setup</h2>

<p>Spondoolies’ <a href="/how-to-setup-bitcoin-mining-hardware-bitmain-antminer/">user interface provides</a> all the configuration settings and monitoring information you’re likely to need. The SP20 simplicity itself to setup. The GUI displays temperatures and hashrate for each individual chip, plus other vital info. You can even use it to adjust voltages (within reason) on the board, to find that sweet spot between hashrate, power and heat.</p>

<p>The SP20 connects via Ethernet only.</p>

<h2>Temperature</h2>

<p>This unit should be operated in environments below 35^C / 95^F. Due to its high power consumption, it generates a lot of heat. At high processing speeds, the heat will cause the fan to become much louder.</p>

<h2>Verdict</h2>

The Spondoolies SP20 was a great mining device in its day. <a href="/what-is-dash-mining/">With the Bitcoin network’s</a> current Difficulty, it no longer makes economic sense to run an SP20 given its low efficiency. The AntMiner S5 is far more power-efficient and costs around the same. Unless there’s some specific hardware mod you’d like to perform with the SP20, it’s not a great purchase except as a piece of mining memorabilia.</p>
