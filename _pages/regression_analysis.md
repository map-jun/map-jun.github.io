---
title: 회귀분석(regression analysis)
layout: single
permalink: /regression/
author_profile: true
sidebar:
    nav: "sidebar-category"
---

<figure style="width: 150%" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/regression_analysis.png" alt="">
</figure>

**Notice:** 각 자료에 대한 저작권 및 지적재산권 (Copyright)은 관련 링크 및 원본 포스트 작성자에게 있으며, 해당 자료를 토대로 재구성한 포스트에 대한 저작권은 필자에게 있으므로, 공부 목적 이외의 상업적 무단 배포를 금지합니다.
{: .notice}

>질문 있으시면, 언제든 메일로 문의해 주세요!!😁

## 포스팅 항목

{% assign posts = site.categories.['regression_analysis'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}