---
layout: ../layouts/PageLayout.astro
title: "歌單"
description: "我喜歡的音樂"
---

<!--
这里可以放你喜欢的音乐歌单。

使用 `{% media audio %}` 标签嵌入网易云音乐或 QQ 音乐歌单：

```markdown
{% media audio %}
- title: 我的歌单
  list:
    - https://music.163.com/#/playlist?id=你的歌单ID
{% endmedia %}
```
-->

{% media audio %}
- title: 我喜歡的音樂
  list:
    - https://music.163.com/playlist?id=821738734
- title: 超かぐや姫！
  list:
    - https://music.163.com/#/album?id=358640968
{% endmedia %}
