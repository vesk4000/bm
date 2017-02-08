---
layout: post
title: Bitmain Antminer S9 Review - Bitcoin Mining
description: Bitmain Antminer S9 Review - Bitcoin Mining
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

<p><h2>AntMiner S9: Game Changer for Hobbyist Miners?</h2></p>

<p>Bitcoin’s Difficulty has recorded several strong and often <a href="/bitcoin-mining-for-beginners-how-to-mine-bitcoins/">consecutive monthly increases</a> since its creation, and especially from late November 2015. Difficulty has nearly tripled since then, climbing from 520,569,941GH/s to the current record high of 1,426,731,353 GH/s. This peak was reached on May 24th 2016. Such tremendous growth has been spurred by major investment into Bitcoin mining technology and operations.</p>

<p>While such growth is impressive, making Bitcoin the world’s most powerful computing network by far, one unintended consequence of such rapid growth has been increased centralisation. Profits have accumulated where mining is most profitable (China), with the result that several competing operations (eg. KNC) have been forced out the industry.</p>

<p>We have tried to calculate the amount of money that the Chinese have invested in mining, we estimate it to be in the hundreds of millions of dollars. Even with free electricity we cannot see how they will ever get this money back. Either they don’t know what they are doing, but that is not very likely at this scale or they have <a href="/what-is-hashcash/">some secret advantage</a> that we don’t know about. - Sam Cole, KNC CEO</p>

<p>The same Chinese competitive advantage has been doubly effective at squeezing the profit-dependent hobbyist miner from the market. At this stage, most home or office miners aren’t hashing to earn money but rather to support the network, aid decentralisation and possibly even to heat space.</p>

<p>With the block reward halving looming, the profitability of all but the most efficient operations will likely be challenged. Given that profits derived from the current generation of mining hardware are dwindling and will likely reach negative returns post-halving, can the new S9 change the game for smaller and hobby miners and restore their lost profitability?</p>

<h2>The S9’s 16 Nanometer Technological Advantage</h2>

<p>The on-going miniaturisation of semiconductors allows ever <a href="/what-is-proof-of-work/">greater computing power</a> and electrical efficiency, but the process cannot continue forever with the current technology. Many have remarked that Moore’s law no longer holds true, as the rate of computing speed advancement has slowed as it reaches the physical limitations of silicon semiconductor technology.</p>

<p>The 16 nm fabrication process used in the manufacture of the S9 is a major improvement upon the 28 nm design common to other modern mining devices. Although a 10nm process is on the horizon for 2017, further increases beyond that remain theoretical. Further, the design and manufacture of any 10nm Bitcoin mining hardware is likely to take at least a year.</p>

<h2>Power Supply</h2>

<p>The good news is that existing power supplies, at least those of sufficient wattage, are fully compatible with the S9.</p>

<h2>Recommended for use with the S9 are:</h2>

<p>The AntMiner APW-12 1600 Watt Bitcoin Miner PSU, which retails for just under $200 on Amazon, and</p>

<p>The EVGA SuperNOVA 1300 Watt GPU PSU , which sells for about $170 on Amazon. Note that the 1600 Watt EVGA PSU is significantly more expensive, by about $115, than Ant Miner’s equivalently-powered offering.</p>

<h2>Bitcoins / Month (Profitability)</h2>

<p>The S9 has more hashing power than any previous device crammed into its silicon; a massive 14 TH/s (TeraHash per second). A total of 189 chips, spread over 3 circuit boards, are combined to achieve this phenomenal hashrate. </p>

<p>Excluding a 15 brief TH/s spike which occurred late 2011, a single S9 unit boasts a <a href="/bitcoin-mining-pools-give-everyone-a-chance-to-be-involved-12/">hashrate equivalent to the peak</a> capacity of the entire Bitcoin network from its bootstrapping until mid-2012!</p>

<p>Let’s calculate the projected profits from all that hashpower via CoinWarz’ Bitcoin mining calculator :</p>

<p>Note that Power Cost will be specific to your location and that Difficulty changes every 2 weeks, usually to the upside… Although keep in mind that post-halving, it’s entirely possible that a lot of marginal miners will be forced to either upgrade to better hardware or shut down. </p>

<p>Your Pool Fees will be determined by your mining pool; although the S9 is plenty powerful, a single unit is highly unlikely to find any blocks when solo-mining. Finally, the Bitcoin to Dollar (USD) price is notorious for its constant state of flux.</p>

<p>According to the above inputs, the S9 will produce 0.285 BTC / $159 per month and 3.36 BTC / $1939 per year.</p>

<p>These puts Return on Investment (ROI) slightly above one year! Of course, such impressive results assume all factors stay constant which is hugely improbable in the ever-changing world of Bitcoin!</p>

<h2>Power Consumption</h2>

<p>The cutting-edge manufacturing process is what makes the S9 the most electrically-efficient mining device to date. It uses a mere 0.1 Joules per Gigahash, making it roughly 2.5 times more efficient than the Antminer S7. The total power consumption of the device works out to around 1350 watts, although this figure is subject to about 7% of variance. The S9 consumes about 300W more than the S7.</p>

<h2>Price</h2>

<p>The first batch of S9s will be <a href="/bitcoins-may-be-virtual-but-theyre-very-very-real-6/">available for order directly from Bitmain</a> from the 12th of June. At $2100 on Amazon, the S9 is far from cheap. However, the lower your electricity costs, the better your odds of the miner paying for itself within a reasonable timeframe. Naturally, much depends on the Difficulty and Bitcoin price.</p>

<p>As smaller manufacturing processes become standard across the industry and as other manufacturers release competing hardware, the S9’s price can be expected to fall appreciably over the coming months. Bi Wang is launching its 14nm chips sometime in winter 2016 and BitFury’s own 16nm architecture hardware, promising fantastic power efficiency at 0.06 J/GH, is also reported to be coming soon.</p>

<p>Judging value in this space is a complicated exercise, although it would appear that nothing vastly technologically-superior to the S9 is likely to be released in the near future. The release cycle of a new generation of mining hardware every few months is likely to decelerate from this point on, as manufacturers have transitioned to cutting-edge 16 and 14nm designs.</p>

<h2>Setup</h2>

<p>Apart from the power supply, the S9 is a self-contained unit. It requires no connection to another computer to interface with other Bitcoin nodes. Its onboard web management portal allows for a simplified setup and maintenance process.</p>

<h2>Temperature</h2>

<p>The S9 is air-cooled and its sturdy design is <a href="/some-fast-facts-about-bitcoin-mining-14/">fairly easy to maintain</a> and service. The S9 performs reliably in any well-ventilated space, whether a single or several unit(s) kept in a spare room or hundreds to thousands of units in a large mining center.</p>

<p>Verdict: Does Hobby Mining with an S9 make Business Sense?</p>

<p>Based on the data and results calculated above, yes.</p>

<p>But! as major miners upgrade to S9s and other advanced hardware, the resultant Difficulty increases are likely to erode future profitability.</p>

<p>On the other hand, the halving could bring about a higher Bitcoin price and reduced competition, increasing profitability.</p>

<p>Ultimately, the S9 is a great piece of hardware although currently rather expensive. It is likely to remain profitable for far longer than previous generations of ASIC miner, although ROI cannot be guaranteed given the inherent unpredictability of Bitcoin mining.</p>

