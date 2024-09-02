---
title: مكتبة ميسم للوسوم
Mysam: Arabic tags manager
description: مكتبة ميسم لإدارة وسوم الكلمات العربية
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
  - Word Tag
  - Open Source
  - Python
---

 [مكتبة ميسم لإدارة وسوم الكلمات العربية](https://github.com/linuxscout/mysam-tagmanager) لتسيير وسوم الكلمات العربية في مجال المعالجة الآلية للغة،  ترميز وتفكيك
هذه المكتبة توفر سكريبت خاصا بترميز وسوم الكلمات (الخصائص الصرفية والنحوية والدلالية) في عبارة وسم مختصرة على شكل سلسلة حروف قصيرة مرمّزة نسميها سلسلة الوسوم.
يمكن التحويل بين قائمة الوسوم وسلسة الوسوم المختص
يمكن الاستفادة من هذه المكتبة من أجل ترميز الوسوم وفك ترميزها، سنستعملها في :

 *  التحليل الصرفي ([مكتبة قلصادي](https://github.com/linuxscout/qalsadi) )
 * التحليل النحوي ( [مكتبة ثعلب](https://github.com/linuxscout/thaalab-aranasyn) )
 * التشكيل ( برنامج مشكال[برنامج مشكال](https://github.com/linuxscout/mishkal) [ برنامج مشكال](http://tahadz.com/mishkal) )
 * التدقيق اللغوي النحوي (LanguageTool).

كما تقدّم خدمة متميزة في  **الإعراب بالطريقة القديمة **

** هذه ليست مكتبة للتوسيم، بل لإدارة الوسوم في معالجة اللغة**


**مثال **:

 * Tags list:
    Noun, جامد, مضاف, مجرور, متحرك, ينون
 * Encoded tag string
    [N--;--I-;---H;----]
 * Inflection phrase
{اسم مجرور وهو مضاف، والضمير المتصل مبني في محل جر مضاف إليه}


