---
layout: post
title: Is Bitcoin Mining Profitable in 2017?
description: Is Bitcoin Mining Profitable in 2017?
author: Melvin Draupnir
authorurl: https://weusecoins.com/melvin-draupnir/
published: true
---
<h2>Bitcoin Mining Hardware Comparison</h2>

<p>Currently, based on <b>(1)</b> price per hash and <b>(2)</b> electrical efficiency the best Bitcoin miner options are:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

<p>The early days of <a href="/banks-and-brokerages-should-be-mining-the-blockchain/">Bitcoin mining</a> are often described as a gold rush. Satoshi Nakomoto’s invention of Bitcoin, “a peer-to-peer electronic cash system,” opened up an entirely new frontier, not just of freedom but of profit. Those with a strong interest in such things, namely cypherpunks, cryptographers, technically-minded libertarians and assorted hackers, were first to stake their claim.</p>

<h2>But is there still gold in them thar hills?</h2>

<p>The fact is that Bitcoin mining has grown from a handful of early enthusiasts to a cottage industry to a specialised industrial-level venture. The easy money was scooped out long ago and what remains is buried under the cryptographic equivalent of miles of hard rock.</p>

<p>Today, only those with specialised, high-powered machinery are able to profitably extract bitcoins. While mining is still technically possible for anyone, those with underpowered setups will find more money is spent on electricity than is generated through mining.</p>

<h2>Common Mining Terms</h2>

<p>To understand Bitcoin mining in any depth, it helps to know a few basic technical terms:</p>

<p>Block: a group of Bitcoin transactions, as collected from <a href="/certain-traits-necessary-for-bitcoin-mining-success-21/">current pending transactions</a> and entered into an ever-growing record of blocks (aka “the blockchain”) by a miner. A new block is created on average every ten minutes.</p>

<p>Proof of Work Hashing: this is the function miners perform in order to define a new block. PoW hashing ensures the proper function of the Bitcoin blockchain. Miners compete to solve a cryptographic “puzzle,” known as a hash. There are no shortcuts in this process, which can only be solved with raw computational power. By correctly hashing the current block, miners prove their investment of work and are rewarded with a certain number of newly-created bitcoins.</p>

<p>Block Reward: the number of newly-created bitcoins. This number was initially set to 50, halved to 25 in late-2012 and will halve again to 12.5 in mid-2016. This halving process continues, approximately every four years (or every 210,000 blocks), until all 21 million bitcoins are created. This is the only way in which new bitcoins can be created; by miners according to the code’s rate and limit.</p>

<p>Hashrate: a measure of a miner’s computational power. The higher their relative power, the more solutions (and hence, block rewards) they’re likely to find. Initially measured in hash per second (H/s), due to the increasing speed of mining hardware. H/s was soon commonly pre-fixed with SI units as follows:</p>

<ul>
<li><p>Kilohash = KH/s (thousands of H/s), then</p></li>
<li><p>Megahash = MH/s (millions of H/s), then</p></li>
<li><p>Gigahash = GH/s (billions of H/s), then</p></li>
<li><p>Terahash = TH/s (trillions of H/s), and even</p></li>
<li><p>Petahash = PH/s (quadrillions of H/s).</p></li>
</ul>
<p>Difficulty: with hashrate shooting up over the years, it would seem blocks would be found by miners ever more rapidly. Bitcoin’s Difficulty measure is what prevents this from happening, ensuring blocks are found roughly every 10 minutes. When total hashrate rises, the Difficulty of POW hashing adjusts upwards - and the inverse also applies. Difficulty auto-adjusts every two weeks (or 2016 blocks).</p>

<p>BTC / XBT exchange rate: the current fiat price of Bitcoin; critical for calculating profitability.</p>

<p>W/xHash/s: Watts per hashrate per second. Electricity is the major on-going cost of Bitcoin mining. The price paid per Watt will greatly influence profitability.</p>

<p>Mining Pool: unless you command a tremendous hashrate, your odds of solving a block by yourself (i.e. “solo-mining”) are extremely low. By banding together with other miners in a so-called pool, your combined odds of solving a block rise proportional to the pool’s total hashrate. Whenever they <a href="/bitcoin-mining-pools-give-everyone-a-chance-to-be-involved-12/">solve blocks</a>, pools reward individual miners according to their contributed hashrate (minus commissions and the like).</p>

<h2>Calculating Mining Profitability</h2>

<p>With these terms in mind, it’s possible to calculate the current profitability of Bitcoin mining for your circumstances. Note that the future profitability of mining cannot be reliably predicted. This is due to the ever-changing nature of the Difficulty modifier and the BTC price, in particular.</p>

<p>To begin, we must select a suitable ASIC mining rig. To aid in selection, the Bitcoin Wiki provides a handy mining hardware comparison:</p>

<p>The AntMiner S7 is a modern mining rig which offers a good hashrate for its power consumption. It’s pretty much the cutting edge of mining tech so we’ll select it for our example. The S7 is available for$609 on Amazon or $450 from BitMain, shipping excluded. Power supply units will add another $150 or so to the price.</p>

<p>Next, we need to enter the S7’s specs and cost, as well as other info such as power cost and pool fees, into a suitable number-cruncher. CoinWarz.com offers a good mining profitability calculator, which automatically fills in the current BTC price, Difficulty and block reward info.</p>

<p>We are using the default power cost of 10c (USD), which is standard for China, but likely to be much higher elsewhere. To determine your own power cost, check worldwide electricity prices or your utility bill for the exact price. The 2.5% Pool Fee is for AntPool. Smaller pools will generally offer lower or even no fees, but keep in mind they will seldom find blocks. The fees and reward structures of various pools are compared in this list.</p>

<p>Once all the necessary info is entered, hit Calculate for the profitability result:</p>

<p>Not a bad result! $800 per year and you can use the miner’s excess heat to warm your home.</p>

<h2>The American Scenarios</h2>

<p>Before getting too excited, let’s recalculate using the average power cost per kWh in the USA (~12.5c) and the 12.5 BTC block reward which becomes the new standard in 45 days or so (see Bitcoin Clock for an up-to-date estimate):</p>

<p>It’s not looking so great now. It appears the <a href="/avalon-wins-the-asic-race-sort-of-23/">average American miner</a> makes only $500 a year, assuming difficulty and price hold steady. However, this is a dangerous assumption! As this article was being written, Bitcoin’s hashrate unexpectedly jumped by a massive 30 percent!</p>

<p>The compensatory Difficulty spike, expected on the day following reports of this spike, completely alters the previous equation:</p>

<p>If we bump up the Difficulty in the mining calculator by the corresponding 30%, all profit evaporates! $500 is lost over one year’s worth of mining.</p>

<p>Unexpected Profit Loss: Difficulty Spikes, Price Crashes, Equipment Failures, Power Cuts, Shipping Delays & More</p>

<p>The above example serves as a perfect illustration of the risks inherent in Bitcoin mining. It’s quite possible that even some big, corporate miners will take strain from such a steep Difficulty spike. The home miner really has no chance to compete in such a challenging environment, unless they have access to free or extremely low-cost electricity…</p>

<p>Also bear in mind that the rate of obsolescence in Bitcoin mining hardware is extremely fast! If (pre-)ordering any such equipment, be aware that potential manufacturing, shipping, customs or other delays could end up being very costly as difficulty rises or price falls during the interim.</p>

<p>There are plenty of other things which can wrong, and <a href="/bitcoin-mining-learn-foreign-exchange-traders/">such downside risks</a> must always be factored into any sound business plan.</p>

<h2>The Chinese Scenarios</h2>

<p>For interest’s sake, let’s examine the situation of Chinese miners, who represent the bulk of Bitcoin mining power for good reason. The results may help us better predict the post-halving Bitcoin environment, as this article attempts to do.</p>

<h2>Hobby Miners</h2>

<p>Certain Chinese regions are over-supplied with electricity, which is also often subsidized. This makes for a really low power cost, which we’ll assume to be 7c for a miner in the right province. Further, most mining hardware is fabricated in China and so can likely be purchased cheaper (and received sooner) by denizens of the Middle Kingdom. We’ll assume a ¾ hardware price.</p>

<h2>Results:</h2>

<p>A small-time Chinese miner with a single S7 connected to AntPool could have made over $1000 annually before the Difficulty spike. That’s twice the profit of their American counterpart!
After the halving and Difficulty spike, the same miner would lose about $40 per year. For a Bitcoin enthusiast, this is an easily-acceptable loss.</p>

<h2>Industrial Miners</h2>

<p>Large-scale mining operations will locate proximate to cheap power sources in remote provinces. Hydro-electric power from dams is a popular option. We can assume a very low power cost for such enterprises, let’s say 5c. Such operations also buy hardware in bulk so we’ll assume they get S7s at half-price, $325. </p>

<p>One thousand S7 units seems a plausible number, which allows us to simply add three zeros to hash rate, hardware and power costs. Finally, such setups often run their own pools and so we’ll assume zero pool fees.</p>

<h2>Results:</h2>

<ul>
<li><p>Before the halving and Difficulty spike, the operation would net $1.4m annually.</p></li>
<li><p>After the halving and Difficulty spike, the operation would profit by about $200k annually.</p></li>
</ul>
<p>$200k isn’t great considering the initial hardware investment is $325k. Given the other costs involved in mining, such as property, salaries, maintenance, etc. it appears that marginal mining operations will be forced out of business post-halving. Only those with the latest and greatest hardware and the cheapest electricity are likely to survive. The only wild card is the Bitcoin price. If it rises sufficiently it’ll allow less efficient miners to keep the lights on for longer.</p>

<h2>Conclusion</h2>

<p>The average home miner will struggle to recoup the cost of mining hardware and electricity. Profitability is highly unlikely given the current circumstances. The situation may improve in future once ASIC mining hardware innovation reaches the point of diminishing returns. </p>

<p>That, coupled with cheap, hopefully sustainable power solutions may once again make Bitcoin mining profitable to small individual miners around the world. This would also greatly improve the decentralisation of the Bitcoin network, hardening it against legislative risk.</p>





