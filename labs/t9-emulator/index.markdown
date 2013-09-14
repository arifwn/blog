---
layout: page
title: "T9 Predictive Text Input Emulator"
date: 2013-09-14 16:27
comments: true
sharing: true
footer: true
---

<iframe style="
    width: 340px;
    height: 500px;
    padding: 20px 5px 5px 5px;
    background: white;
    border: none;
    box-shadow: inset 0 0 7px rgba(0,0,0,0.7);
" src="http://arifwn.github.io/t9-emulator/embed.html"></iframe>
<a href="http://arifwn.github.io/t9-emulator/" target="_BLANK">Open in New Window</a>

This is a <a href="http://en.wikipedia.org/wiki/T9_(predictive_text)">T9 Predictive Text Input Emulator</a>, implemented using <a href="http://en.wikipedia.org/wiki/Trie">Trie</a>.

Hint: use cycle button to cycle through all matching words.

Limitation
----------

* It's not context-aware or grammar-aware. No smart result ordering.

Sample words
------------

* testing: 8378464
* super: 78737
* mario: 62746
* legend: 534363
* and many more (over 2MB of english words)...

Links
-----

* [Github Project](https://github.com/arifwn/t9-emulator)
* [Javascript Trie Prediction](https://github.com/jrolfs/javascript-trie-predict/blob/master/predict.js)

[Back to Labs]({{ root_url }}/labs/)