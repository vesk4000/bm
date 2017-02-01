---
layout: post
title: Avalon6 Bitcoin Miner Review
description: Avalon6 Bitcoin Miner Review
author: Melvin Draupnir
authorurl: https://www.weusecoins.com/melvin-draupnir/
published: true
---

<h2>PROS</h2>
<p>The second most efficient Bitcoin miner on the market</p>
<p>Some reviews claim that the miner is quiet compared to other miners</p>

<h2>CONS</h2>
<p>Less hash power for the money compared to the Antminer S7</p>
<p>Less efficiency than the Antminer S7</p>

<h2>The Avalon 6: Serious Rival to the AntMiner S7</h2>

<p>Canaan Creative took over the troubled Avalon brand. They’ve been <a href="/profit-bitcoin-without-owning/">restoring the brand</a> to its former glory with their recent hardware offerings. Their latest device, the impressive Avalon 6, contains eighty 18nm A3218 chips, running at 500 MHz to achieve a respectable 3.5 TH/s hashrate which approaches that of the AntMiner S7.</p>

<h2>Power Supply</h2>

<p>Any good power supply of 1100W and up will run the Avalon 6. The unit draws about 1050 Watts when using a platinum-rated PSU.</p>

<h2>Bitcoins / Month (Profitability)</h2>

<p>The imminent halving combined with a rising Bitcoin price may allow the Avalon 6 to turn a profit despite the release of the 14 TH/s AntMiner S9. We’ll run the Avalon stats and some average costs through CoinWarz’mining profitability calculator:</p>

<p><center><img src="/images/avalon1.png" alt="avalon 6"/></center></p>

<p>And the results, while in the minus column, aren’t too bad. A lower electricity cost or <a href="/kncminer-bankrupcy-block-reward/">higher Bitcoin price</a> could nudge the Avalon 6 into profit:</p>

<p><center><img src="/images/avalon2.png" alt="avalon 6"/></center></p>

<h2>Price</h2>

<p>Canaan sell the unit for $550 (with substantial $100 and $130 discounts for 10 and 50 units respectively). For shipping purposes, the unit weighs 5 kg / 11 lb. Used, it costs about $450 from Amazon .</p>

<h2>Noise</h2>

<p>At 55 dB from 1.2 m. / 4 ft., the Avalon 6 is quiet enough to run at home, although not in your bedroom or living room. Underclocking the unit will further reduce noise.</p>

<h2>Setup</h2>

<p>The Avalon 6 requires either a Raspberry Pi (B / B+) or a TP-Link TL-WR703N as a controller. Up to 50 miners can be maintained from one RPi.</p>

<p>It uses DHCP so it automatically finds an IP address, <a href="/bitcoin-mining-centralization/">making for an easy installation</a>.</p>

<p>You can use either Avalon’s control panel or CGminer to setup, control and monitor the device. Basic and advanced settings are easy to access.</p>

<h2>Temperature</h2>

<p>The frequency of the Avalon 6 can be easily adjusted from its standard 500 MHz and it runs fairly cool even when overclocked. It is intended for operation at an ambient temperature below 35^C / 95^F. The single fan has no problem cooling the unit due to the unit’s design.</p>

<h2>Verdict</h2>

<p>The Avalon 6 is a strong rival to the AntMiner S7. It’s slightly less energy-efficient but arguably makes up for it with enough customization options to please any hardware enthusiast.</p>

<hr id="hwc" style="width: 100%; margin: 20px 0; color: #eee;" />

<h2>Bitcoin Mining Hardware Comparison</h2>

<p>Currently, based on <b>(1)</b> price per hash and <b>(2)</b> electrical efficiency the <a href="/bitcoin-mining-fees/">best Bitcoin miner options</a> are:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

