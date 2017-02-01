---
layout: post
title: Is 2017 Profitable for Bitcoin Mining?
description: Is 2017 Profitable for Bitcoin Mining?
author: Melvin Draupnir
authorurl: https://www.weusecoins.com/melvin-draupnir/
published: true
---

<p>The short answer would be “It depends on how much you’re willing to spend”. Each person asking himself this will get a slightly different answer since <a href="/how-does-bitcoin-mining-really-operate/">Bitcoin Mining profitability</a> depends on many different factors. In order to find out Bitcoin mining profitability for different factors “mining profitability calculators” were invented.</p>

<p>These calculators take into account the different parameters such as electricity cost, the cost of your hardware and other variables and give you an estimate of your projected profit. Before I give you a short example of how this is calculated let’s make sure you are familiar with the different variables:</p>

<p><strong>Hash Rate</strong> – A Hash is the mathematical problem the miner’s computer needs to solve. The Hash Rate is the rate at which these problems are being solved. The more miners that join the Bitcoin network, the higher the network Hash Rate is.</p>

<p>The Hash Rate can also refer to your miner’s performance. Today Bitcoin miners (those super powerful computers talked about in the video) come with different Hash Rates. Miners’ performance is measured in MH/s (Mega hash per second), GH/s (Giga hash zper second), TH/s (Terra hash per second) and even PH/s (Peta hash per second).</p>

<p><strong>Bitcoins per Block</strong> – Each time a <a href="/bitcoin-mining-centralization/">mathematical problem is solved</a>, a constant amount of Bitcoins are created. The number of Bitcoins generated per block starts at 50 and is halved every 210,000 blocks (about four years). The current number of Bitcoins awarded per block is 25. However soon enough the block halving will occur and the reward will be downgraded to only 12.5 Bitcoins.</p>

<p><strong>Bitcoin Difficulty</strong> – Since the Bitcoin network is designed to produce a constant amount of Bitcoins every 10 minutes, the difficulty of solving the mathematical problems has to increase in order to adjust to the network’s Hash Rate increase. Basically this means that the more miners that join, the harder it gets to actually mine Bitcoins.</p>

<p><strong>Electricity Rate</strong> – Operating a Bitcoin miner consumes a lot of electricity. You’ll need to find out your electricity rate in order to calculate profitability. This can usually be found on your monthly electricity bill.</p>

<p><strong>Power consumption</strong> – Each miner consumes a different amount of energy. Make sure to find out the exact power consumption of your miner before calculating profitability. This can be found easily with a quick search on the Internet or through this list. Power consumption is measured is Watts.</p>

<p><strong>Pool fees</strong> – In order to mine you’ll need to join a mining pool. A mining pool is a group of miners that join together in order to mine more effectively. </p>

<p>The platform that brings them together is called a mining pool and it deducts some sort of a fee in order <a href="/bitcoin-mining-for-beginners-how-to-mine-bitcoins/">to maintain its operations</a>. Once the pool manages to mine Bitcoins the profits are divided between the pool members depending on how much work each miner has done (i.e. their miner’s hash rate).</p>

<p><strong>Time Frame</strong> – When calculating if Bitcoin mining is profitable you’ll have to define a time frame to relate to. Since the more time you mine, the more Bitcoins you’ll earn.</p>

<p><strong>Profitability decline per year</strong> – This is probably the most important and illusive variable of them all. The idea is that since no one can actually predict the rate of miners joining the network no one can also predict how difficult it will be to mine in 6 weeks, 6 months or 6 years from now. </p>

<p>This is one of the two reasons  no one will ever be able to answer you once and for all “is Bitcoin mining profitable ?”. The second reason is the conversion rate. In the case below, you can inset an annual profitability decline factor that will help you estimate the growing difficulty.</p>

<p><strong>Conversion rate</strong> – Since no one knows what the BTC/USD exchange rate will be in the future it’s hard to predict if Bitcoin mining will be profitable. If you’re into mining in order to accumulate Bitcoins only then this doesn’t need to bother you. But if you are planning to convert these Bitcoins in the future to any other currency this factor will have a major impact of course.</p>

<h2>Get a mining calculator</h2>

<p>In order to calculate all of these parameter and get an answer to our question we will use a <a href="/how-to-setup-bitcoin-mining-hardware-bitmain-antminer/">mining profitability calculator</a>.  here’s a simple mining calculator from 99Bitcoins:</p>

<p><center><img src="/images/mining-calculator-ofir-beigel.jpg" alt="mining-calculator-ofir-beigel"/></center></p>

<p>However, now let’s take a look at a more complex example were we include more factors:</p>

<p>Today one of the most advanced miners out there is the Antminer S9. It’s what is known as an ASIC mining rig.  It has a mining rate of 14 TH/s. If we use the simple Bitcoin mining calculator (shown above) you will see that at today’s difficultly you will earn around 1 Bitcoin a month.</p>

<p>But of course this doesn’t take into account the hardware cost, electricity cost, pool fees, etc. Let’s try to calculate all of these together.</p>

<p><center><img src="/images/mining-with-s9-ofir-beigel.png" alt="mining-with-s9-ofir-beigel"/></center></p>

<p>This data was taken from an advanced Bitcoin mining calculator using the following stats: 2% mining pool fees, 25 Bitcoins as a block reward, 14 TH/s hash rate, 1375W power consumption. </p>

<p>So after 12 months we should be making around $6,000. However we haven’t deducted the hardware cost yet, so it’s more like $ 3,400. Also, pretty soon the block reward goes down to 12.5 so we’ll actually only be breaking even.</p>

<p>Of course this result can change depending on your own electricity cost, the change in mining difficulty and most importantly the change in the price of Bitcoin.</p>

<p>So you’re probably not going to get rich by mining Bitcoins at home unless you buy some heavy duty equipment and have very low electricity costs. Here’s a list of the most efficient Bitcoin mining hardware out there today. There’s not a lot of variety to pick from since home mining is a dying art.</p>

<h2>Bitcoin Mining Hardware Comparison</h2>

<p>Currently, based on <b>(1)</b> price per hash and <b>(2)</b> electrical efficiency the best Bitcoin miner options are:</p>

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

<p>So even though home mining is an expensive business there are still other option that may be relevant for you to get into the mining game at a lower cost.</p>

<h2>How to mine Bitcoins with cloud mining</h2>

<p>There a new concept called “cloud mining“. This means that you do not buy a physical mining rig but rather rent computing power from a different company and get paid according to how much power you own. At first this sounds like a really good idea, since you don’t have all of the hassle of <a href="/usb-bitcoin-miner-setup-guide/">buying expensive equipment</a>, storing it, cooling it, etc.</p>

<p>However, when you do the math it seems that non of these cloud mining sites are profitable in the long run. Those that do seems profitable are usually scams that don’t even own any mining equipment, they are just elaborate Ponzi schemes.</p>

<p>If you do want to take a look at cloud mining I suggest using Genesis Mining – the only cloud mining company that has been around long enough to prove it’s not a scam. But make sure to do the month before putting your money into any of these plans.</p>

<h2>Mining Altcoins as an alternative to Bitcoin</h2>

<p>One more option you can consider is mining Altcoins instead of Bitcions. Today there are hundreds of Altcoins available on the market and some of them are still real easy to mine. The problem is that because there are so many Altcoins it’s hard to tell which ones are worth investing your time in. Some good examples for Altcoins are Litecoin, Dogecoin and Peercoin.</p>

<p>In order to understand which Altcoins are profitable you can find website indexes such as CoinChoose that give you a complete Altcoin breakdown. On CoinChoose you can see the difficulty for each Altocoin, where can you exchange them and what are the chances to profit Bitcoins by mining each specific Altcoin. </p>

<h2>So is Bitcoin Mining Profitable ?</h2>

<p>My guess is that in the long run you could make a profit from Bitcoin mining but only if you invest a considerable amount of money in a good mining rig (e.g. Antminer s9) or take your time to “hack” through making a profit with CEX.IO. </p>

<p>I’d currently stay away from Altcoins but that’s my own personal opinion. If you don’t have the time or the money – stay away from mining and just invest in buying Bitcoins for the long run.</p>

<hr id="hwc" style="width: 100%; margin: 20px 0; color: #eee;" />



