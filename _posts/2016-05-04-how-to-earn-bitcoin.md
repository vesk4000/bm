---
layout: post
title: How to earn Bitcoin?
author: Bitcoin Mining
authorurl: /
published: true
toc:
  intro: Introduction to Earning in Bitcoin
  wrk: Work for Bitcoin
  sll: Sell for Bitcoin
  aff: Affiliate Programs
  gmg: Gambling
  min: Bitcoin Mining
  hrd: Hardware Mining
  cld: Cloud Mining
---

{% include page-toc.html %}

<h3 id="intro"> Introduction to Earning in Bitcoin</h3>

Bitcoin is the most popular digital currency in the world today. It is built using very complicated cryptographic principles, and supported by countless individuals and companies from all around the world. By early 2016, total Bitcoin market capitalization had crossed USD 7 Billion, making it almost as valuable as the GDP of a small country like Bahamas. 

With such a huge amount of world's capital available in the form of Bitcoins, opportunities to earn bitcoins are increasing by the day. In this article we will discuss these same opportunities to earn bitcoins. 

We will start with the easiest, or the one that is applicable for the maximum number of people, and then move to the tougher ones. In the end we will cover earning bitcoins by mining. It definitely is not an easy way to earn bitcoins, but we do have a number of easier ones we will discuss first. So lets start with 'earning bitcoins by offering your services'

<h3 id="wrk">Work for Bitcoin</h3>

Perhaps the easiest way to earn bitcoins is to work online or in real life for bitcoins. Because of the huge size of the bitcoin eco-system, a number of such opportunities and jobs are available. With Billions of dollars invested in Bitcoin by tens of thousands of people, there is a real market in Bitcoin that has jobs for freelancers, software developers, writers, and other who get paid in bitcoins for their services. 

Software development, writing, design, making websites or apps, audio transcription, are some of the most active types of jobs. You can easily discover the types of jobs by going over the more popular job boards for bitcoin related work. You can look for jobs on the following job boards or forums:

* reddit.com/r/jobs4bitcoins

* xbtfreelancer.com

* coinality.com

* cryptogrid.com



<h3 id="sll">Sell for bitcoin</h3>

You can also get Bitcoin by selling your old laptops, phones or other items for Bitcoins. Such types of transactions are happening more and more, and a lot of buyers are already buying anything from iPhones to even cars by paying with Bitcoins. For Americans, Craigslist.com is the best best when you want to contact such buyers. You can mention in your ad that you are willing to take payment in Bitcoin. This way if anyone wants to buy the item for you for Bitcoin, they can contact you and make an offer. 


<h3 id='aff'> Affiliate Programs</h3>

Affiliate programs allow a promoter of a business or product to earn money or bitcoins by refering new clients to the said businesse or product. For example, amazon.com has a popular affiliate program, where you can earn commission ranging from 2% to 20% for refering clients to products listed on amazon.com. Amazon normally pays in dollars, but there are a number of other sites and businesses which pay you in bitcoin for acting as their affiliate. 

<h3 id='gmg'> Gambling </h3>



<h3 id="min">Bitcoin Mining</h3>

Is of two types

<h3 id="hrd">Hardware Mining</h3>
Is when you own your own hardware, and manage it yourself

For a more in-depth information on how to setup your hardware mining equipment, have a look at the <a href="/antminer-s3-bitcoin-miner-setup/">Antminer setup page.</a> 

### Bitcoin Mining Hardware Comparison

Currently, based on (1) price per hash and (2) electrical efficiency the best Bitcoin miner options are: 

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>


<h3 id="clf">Cloud Mining</h3>
Is when you use cloud services such as Amazon AWS. 

{% for service in site.data.cloud %} 
{% if service.desc_btc != null %}
{% if service.url != null %}{{ service.company }}: {% else %}{{ service.company }}: {% endif %}{{ service.desc_btc }}
{% endif %} {% endfor %}


