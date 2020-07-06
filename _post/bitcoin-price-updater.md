---
layout: post
title:  Bitcoin price update pop-up
categories: JFreeChart Gson Java Apache
slug: bitcoin-price-updater
rank: 1
---

This personal project was primarily made for fun in 2019. 

It also served to experiment how to draw charts with Java using [JFreeChart](http://www.jfree.org/jfreechart/), how to use JSON resources (using [Gson library](https://en.wikipedia.org/wiki/Gson)) and how to consume an API with a GET request (using [Apache HttpClient library](http://hc.apache.org/index.html)).

The program displays a small window in a pop-up style with the current bitcoin price. The price is updated every minute and a chart will draw itself remembering the last 10 retrieved prices. Then every new update will delete the oldest stored price.

If the new updated price is higher than the previous one, the price will turn green, if it is lower, it will turn red, and if it stays the same the price stays (or turns) black. You can also zoom-in and out the chart with the scroll wheel or by selecting an area on the chart.


**Skills :**
- using HttpClient library to make a HTTP request
- consume a free API from an outside provider
- draw a dynamic chart with JFreeChart
- work with JSON data with the Gson library
- using a MVC architecture with controllers, models and view


**Architecture:**  
The design is open for extension if we want to add a new cryptocurrency by implementing AbstractCryptocurrencyController class. The default and unique current implementation is for Bitcoin.  


<a href="https://raw.githubusercontent.com/alexandrebulatovic/bitcoin_price_updater/master/design-diagrams/personal-project-bitcoin.PNG"> 
	<img src="https://github.com/alexandrebulatovic/bitcoin_price_updater/blob/master/design-diagrams/personal-project-bitcoin.PNG" width="750">
</a>


**Screenshots :**  
<a href="https://alexandrebulatovic.github.io/images/screen-8-php.png"> 
	<img src="https://alexandrebulatovic.github.io/images/screen-8-php.png" width="300">
</a>  
*[Click here to see the source code or download the executable file...](https://github.com/alexandrebulatovic/bitcoin_price_updater)*