---
layout: post
title: Bitmain Antminer S7 Review - Bitcoin Mining
description: Bitmain Antminer S7 Review - Bitcoin Mining
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


<p>The Bitmain Antminer S7 is Bitmain Tech's latest version of its Antminer series of Bitcoin miners.</p>

<h2>PROS</h2>

<p>High 4.73 TH/s hashrate, and efficient at 0.25 Joule per GH/s</p>
<p>Reasonably priced at $440 new (plus shipping)</p>
<p>Popular miner with plentiful guides and parts available</p>

<h2>CONS</h2>

<p>Eclipsed by 16nm miners (AntMiner S9) and forthcoming 14nm miners</p>
<p>High power consumption of ~1350 Watts demands high-end PSU</p>
<p>Quite noisy at 62dB</p>

<h2>The AntMiner S7: Bitcoin Mining Mainstay</h2>

<p>Bitmain’s AntMiner S7 has proven so popular since its release in mid-2015 that it’s now reached its 19th batch of production. The S7 assumed market dominance for good reason; <a href="/what-is-ethereum-cloud-mining/">it offers a high hashrate</a> for the amount of power it consumes. If you view any modern industrial mining operation, chances are you’ll see racks of AntMiner S7s hashing away. The S7 is also a popular choice among hobbyist miners for its reasonable price and strong performance.</p>

<p>The S7 is powered by a 28nm BM1385 ASIC chip. 135 of these chips are spread across 3 boards and kept cool by dual fans (or a single fan in the case of a particular batch). <a href="/usb-bitcoin-miner-setup-guide/">The strong metal casing features</a> a tongue and groove system which allows for the neat arrangement of multiple miners.</p>

<h2>Power Supply</h2>

<p>Recommended for use with the S7 is Bitmain’s high quality 1600 Watt APW3 power supply unit, designed specifically for use with Bitcoin miners. This PSU is highly efficient, losing only 7% of electricity between outlet and miner. The APW3 requires a minimum 205 Volts to function and does not ship with the necessary 16A power cord.</p>

<p>Although not cheap at $140 plus shipping, the APW3 is a <a href="/certain-traits-necessary-for-bitcoin-mining-success-21/">good choice in terms of future</a> upgradability as it can also run the power-hungry AntMiner S9. It’s also possible to use any ATX PSU of sufficient Wattage to run the S7.</p>

<p>The S7-LN includes its own PSU; a 1000W Enermax, rated Gold (above 80% efficiency). As the S7-LN only draws about 700W, this PSU has excess capacity even when overclocking the unit above its default 600M frequency. It also adds quite a lot of weight to the unit, increasing its shipping cost. While an integral PSU makes for a compact and convenient miner, there are few other reasons to recommend such a setup. The S7-LN also excludes a cord.</p>

<h2>Bitcoins / Month (Profitability)</h2>

<p>With Difficulty rising and the halving of block rewards imminent, the S7 is reaching the end of its profitability for those without access to cheap power… although if Bitcoin’s exchange rate rises sufficiently, the S7’s profitability may well be extended beyond expectations.</p>

<p>Courtesy of CoinWarz’ Bitcoin mining calculator, we’ll take a peek at some likely returns for an S7 and S7-LN. We’re assuming an average household Power Cost of 15c per kWh, a Pool Fee of 2.5% (as charged by AntPool) and a post-halving Block Reward of 12.5 BTC per block mined:</p>

<p>For greatly increased accuracy, <a href="/bitcoin-mining-pools-give-everyone-a-chance-to-be-involved-12/">perform your own custom calculation</a>!</p>

<p>The results aren’t great:</p>

<p>$18 will be lost per month and $223 annually.</p>

<p>From this rough calculation (which appears not to factor in the Hardware Costs field), it’s clear that nobody who pays a regular price for their electricity will be getting rich off an S7. With careful tweaking, it may be possible to profit from an S7 even at 15c power. This assumes that Bitcoin’s price doesn’t fall and Difficulty doesn’t jump… risky assumptions indeed!</p>

<p>The same calculations adjusted for the Hash Rate and Power consumption of the S7-LN produces slightly more encouraging results:</p>

<p>Only $6 is lost per month and $77 annually.</p>

<h2>Power Consumption</h2>

<p>The S7 draws a minimum of 1293 Watts at a room temperature of 25^C / 77^F. Naturally, the hotter the environment, the more energy the fan(s) will consume to cool the unit. The S7 is twice as efficient as the S5 at converting all this energy into bitcoins; it requires a modest 0.25 Joules of power per Gigahash.</p>

<p>As mentioned, the LN (“Lite”) version draws only 700W. It likewise consumes 0.25 J/GH.</p>

<h2>Price</h2>

<p>Shortly after release, the S7 was priced at nearly $2000, a little below the current cost of the S9. It has since been discounted steeply and is available from Bitmain at $440 (when in stock), plus shipping. It can also be bought new at $545 or second-hand at $500 from Amazon.</p>

<p>Bitmain sells the S7-LN for $291 and Amazon has it going for $439 new or $409 used.</p>

<p>These prices can be expected to fall further as the S9 and other superior mining hardware becomes the new standard. It’s also possible to buy modded S7(-LNs) with upgraded efficiency and diminished noise and heat levels.</p>

<h2>Setup</h2>

<p>Both S7’s have DHCP capability, meaning they’ll automatically seek out an IP address to use. Setting them up via the MinerLink GUI is a simple process, requiring only your mining pool credentials to begin mining. The units will automatically begin hashing upon powering up, which can be helpful in the event of power failure. S7 connectivity is via Ethernet only.</p>

<h2>Temperature</h2>

<p>Both S7 versions will operate well below an ambient temperature of 40^C / 77^C. They are both cooled by dual 12038 fans. Keeping the room in which they’re placed cool and dry will <a href="/usb-bitcoin-miner-setup-guide/">extend the life of these miners</a>. A dry basement is an ideal location.</p>

<h2>Verdict: Is the S7 Right for You?</h2>

<p>If you hope to make profit but can’t wait for the S9 (or other forthcoming miners from different companies) to become affordable, the S7 is likely your best option. With access to inexpensive power and perhaps some intelligent tweaking, it’s possible that the S7 will pay for itself and become profitable. The S7-LN is slightly more efficient and certainly better suited to the home miner who can’t tolerate a lot of fan noise or cable clutter.</p>
