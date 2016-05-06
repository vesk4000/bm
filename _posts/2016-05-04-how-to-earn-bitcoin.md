---
layout: post
title: How to earn Bitcoin?
author: Bitcoin Mining
authorurl: /
published: true
toc:
  wrk: Work for Bitcoin
  sll: Sell for Bitcoin
  aff: Affiliate Programs
  gmg: Gambling
  min: Bitcoin Mining
  hrd: Hardware Mining
  cld: Cloud Mining
---

{% include page-toc.html %}

Introduction to bitcoin   


<h3 id="wrk">Work for Bitcoin</h3>

provide services for bitcoins

reddit.com/r/jobs4bitcoin
xbtfreelancer.com
coinality.com
cryptogrind.com

<h3 id="sll">Sell for bitcoin</h3>

Whenever you offer to sell anything on craigslist or any other classified, offer to accept payment in Bitcoin.

<h3 id='aff'> Affiliate Programs</h3>


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


