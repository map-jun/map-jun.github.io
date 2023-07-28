---
title: Bluetooth Low Energy
layout: single
permalink: /ble/
gallery_path: "assets/image"
author_profile: true
sidebar:
    nav: "sidebar-category"
---

{% capture fig_img %}
![ble-intro]({{ '/assets/images/2020-04-12-banniere-article-ble.jpg' | relative_url }})
{% endcapture %}

<figure style="width: 100%">
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>출처: https://elainnovation.com/what-is-ble.html</figcaption>
</figure>

본 시리즈에서는 저전력 블루투스 (<span style="color:#0174DF"><b>Bluetooth Low Energy, BLE</b></span>) 기술에 대해 소개하고, **[DevZone](https://devzone.nordicsemi.com/)** 사이트에서 제공하는 포스트를 토대로 공부한 내용들을 정리할 예정입니다.

**Notice:** 각 자료에 대한 저작권 및 지적재산권 (Copyright)은 관련 링크 및 원본 포스트 작성자에게 있으며, 해당 자료를 토대로 재구성한 포스트에 대한 저작권은 필자에게 있으므로, 공부 목적 이외의 상업적 무단 배포를 금지합니다.
{: .notice}

>If you have any questions, feel free to ask me !!

## 포스팅 항목

{% assign posts = site.categories.BLE %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}