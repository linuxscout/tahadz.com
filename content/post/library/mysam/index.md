---
title: Mysam, Arabic tags manager
description: Mysam, Arabic tags manager
slug: mysam
date: 2024-09-01 00:00:00+0000
image: mysam.png
categories:
  - Library
languages:
  - Arabic
tags:
  - text-processing
  - NLP library
  - Arabic language
  - Word Tags
  - Open Source
  - Python
---

[Mysam Tag Manager](https://github.com/linuxscout/mysam-tagmanager) is library which provides a script to encode POS tags (Words features : morphology, syntax, semantic), as a brief tag string  called tag string.

We can convert between tag list <==> coded tag string.

We plan to use it in:

 * Morphology analysis  ([Qalsadi library](https://github.com/linuxscout/qalsadi) )
 *  Syntactic analysis  ( [Thaalab Library](https://github.com/linuxscout/thaalab-aranasyn) )
 * Tashkeel ( [Mishkal](https://github.com/linuxscout/mishkal) [Mishkal-site](http://tahadz.com/mishkal) )
 * LanguageTool - Style and Grammar Checker [LanguageTool](https://languagetool.org/).

It provides a special feature, make **traditional Inflection**.


The conversion can be do like:

 * Tags list:
    Noun, جامد, مضاف, مجرور, متحرك, ينون
 * Encoded tag string
    [N--;--I-;---H;----]
 * Inflection phrase
{اسم مجرور وهو مضاف، والضمير المتصل مبني في محل جر مضاف إليه}

** This not a Tagger library, but, a tags mangger for NLP **
