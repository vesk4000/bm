---
layout: post
title: Bitmain Antminer S5 Review - Bitcoin Mining
description: Bitmain Antminer S5 Review - Bitcoin Mining
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

<p>The Bitmain Antminer S5 is Bitmain Tech's second newest version of its Antminer series of Bitcoin miners</p>

<p><h2>PROS</p>

<p>Low cost miner, with second-hand units available for under $200</p>
<p>Relatively low power demand of 590 Watts</p>
<p>Good for learning and experimentation</p>

<p><h2>CONS</p>

<p>Noisy (~75dB) single fan design, although mods can quieten it</p>
<p>Spec hashrate of around 1155 GH/s is low by today’s standards</p>

<h2>The AntMiner S5: Still Relevant to Modern Mining?</h2>

<p>Bitmain released their AntMiner S5 Bitcoin miner in late 2014. At that time, it was one of <a href="/certain-traits-necessary-for-bitcoin-mining-success-21/">the fastest and most efficient ASIC miners</a> available, rivalled by the Spondoolies-Tech SP20. However, the S5 has long since been surpassed by newer models.</p>

<p>As a product of a 28nm fabrication process, the S5 can’t be reasonably expected to compete with modern 16nm or 14nm ASIC designs in terms of hashrate or power efficiency.</p>

<h2>Is there still a place for the venerable S5?</h2>

<p>If you’re a hobbyist miner on a budget, with no <a href="/avalon-wins-the-asic-race-sort-of-23/">interest in the profitability</a> of transmogrifying electricity into bitcoins, then the S5 is worth considering.</p>

<h2>Power Supply</h2>

<p>The S5 will draw between 560 to 590 Watts at around 115 Volts. Any sufficiently-powered ATX Power Supply Unit will run the S5 without problems. That means that your old PC power supply - or someone else’s second hand one - can be easily repurposed for Bitcoin mining.</p>

<p>Note that the <a href="/bitcoin-mining-its-about-solving-problems-27/">efficiency of power supplies</a> is rated as gold (10% of electricity wasted), silver (20% wasted) or bronze (30% wasted). The efficiency of power supplies is a worthy topic of investigation for any aspiring Bitcoin miner; inefficient, unrated power supplies will waste electricity and create extra noise and heat. A list of PSU ratings may be found here.</p>

<h2>Recommended for use with the S5:</h2>

<p>Ideally, get a PSU from the Corsair Enthusiast Series Bronze Certified PSU; either the 650 or 750 Watt model. The 650W model is available second hand for a little over $100. Corsair has a good reputation among Bitcoin miners and other tech enthusiasts for building reliable hardware. The Bronze series offers good value.</p>

<p>One thing to note is that under-clocking the S5 is difficult without a special, 9 Volt-capable PSU.</p>

<h2>Bitcoins per Month (Profitability)</h2>

<p>CoinWarz’ Bitcoin mining calculator is helpful for calculating the profitability of any Bitcoin miner, based on relevant data. Be sure to run your own calculations, using your local power rate, preferred mining pool and the price at which you intend to buy your S5.</p>

<p>The CoinWarz site will automatically fill in the current BTC-USD price, Difficulty and Block Reward. Note that in July 2016, the Block Reward will halve to 12.5 BTC for every block solved. In order to see any bitcoins from a single S5, you will need to join a Pool. The odds of solo-mining a block with a single or even several S5s are virtually zero.</p>

<p>The post-halving Reward, relatively expensive Power and AntPool’s Pool Fees are entered, along with <a href="/advertise/">the current Bitcoin price</a> and all the relevant stats of the AntMiner S5.</p>

<p>The results are, as expected, highly unprofitable:</p>

<p>Red bracketed numbers indicate negative returns.</p>

<p>Even if Bitcoin price were to double to a new all-time high around $1400, the returns would remain negative. However, if you’re able to bring your electricity costs below 10c per KWh, you could just about break even at the current price of ~$700. So, given a much higher Bitcoin price, cheap power, stable Difficulty and perhaps modifications to improve efficiency, profiting from a new or used S5 is not impossible…</p>

<h2>Power Efficiency</h2>

<p>The S5 will produce 1 Gigahash for every 0.51 Watts it consumes. This figure can be expressed as 0.51 J/GH. The S5’s real power consumption, as measured by your electric bill, will vary depending on your PSU’s efficiency and the ambient temperature.</p>

<p>0.51 J/GH is a lot more efficient than the S3 (0.78 J/GH) but a lot less efficient than the more expensive AntMiner S7 (0.25 J/GH) or S9 (0.098 J/GH) models. Traditionally, each new BitMain miner series doubles efficiency.</p>

<p>It’s possible to upgrade the S5’s hashrate, primarily by increasing its frequency (aka overclocking) but this increases the miner’s power and cooling requirements. There are ways, ranging from simple to extreme, to manage the overclocking burdens. Gains of up to ~400 GH/s are achievable but require serious effort. This video demonstrates oil immersion cooling.</p>

<h2>Price</h2>

<p>Used AntMiner S5s are available on eBay and Amazon in a price range between $190 and $299; most ship from America. New S5s ship from Bitmain in China for $413, although there may be a waiting period before stock becomes available.</p>

<p>Remember to factor in shipping costs and possible customs duties.</p>

<h2>Casing</h2>

<p>The S5 is open at the top and bottom and the sides are constructed of fairly lightweight plastic. This limits the placement of the unit and somewhat reduces its safety. One upside of the plastic casing is that the unit only weight 2.5 kg. / 6.5 lbs.</p>

<h2>Noise</h2>

<p>The noise from a stock S5’s 120mm fan has been <a href="/usb-bitcoin-miner-setup-guide/">compared to an industrial vacuum</a>. It’s definitely an unsuitable device to run in your living environment; it’ll drown out conversation and irritate people or pets.</p>

<p>The only solution is to replace the stock ~75 decibel fan with a quieter kind. Often a secondary fan is added to the back-end, where screw holes exist for this purpose.</p>

<h2>Setup</h2>

<p>The S5 will automatically search out an available IP address to use and features an intuitive control panel. The MinerLink software will allow you to monitor the status of your miner(s), easily configure your mining pool settings, upgrade the device’s firmware and share access privileges to the miner over a network connection.</p>

<h2>Temperature</h2>

<p>Onboard temperature must be maintained below 80^C / 175^F. Keeping the onboard temperature below 60^C / 140^F will prolong the lifetime of the S5. As with all miners, the lower the operating temperature, the higher they can be overclocked.</p>

<h2>Verdict</h2>

<p>The S5 is unlikely to ever turn a profit, so it’s hard to justify the cost of buying one new. That said, a cheap, second-hand S5 in decent condition is a great tool for learning the ropes of Bitcoin mining. It represents a low-cost introduction to the complex business of Bitcoin mining.</p>

<p>The S5 is also a good platform to experiment with hardware, firmware and software tweaks and mods. At roughly one tenth the price of the cutting-edge Antminer S9, the S5 is cheap enough to try potentially damaging operations like over/under-clocking and immersion cooling.</p>


 