---
author: Chiusan
pubDatetime: 2026-11-22T11:01:00+08:00
title: Flex Panel Gallery
slug: flex-panel-gallery
featured: false
draft: false
tags:
  - js30
  - notes
description: About js30 Flex Panel Gallery exercises.
---

## Notes

用 CSS 與 JS 製作一個會動畫展開圖片並展示的效果。

## Snippets

`e.propertyName` 可抓到觸發 `transitionend` 的屬性名稱，分別為 `font` 和 `flex`，但因 `transition: flex 0.7s..` 在 sarafi 是`flex`，而其他瀏覽器為 `flex-grow`，所以不能用 `e.property === 'flex'` 處理，這樣其中一方瀏覽器會抓不到值。

```js
function toggleActive(e) {
  if (e.propertyName.includes("flex")) {
    this.classList.toggle("open-active");
  }
}
```

## References

- [Flexbox + JavaScript Image Gallery](https://www.youtube.com/watch?v=9eif30i26jg&list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH&index=5)
- [guahsu](https://github.com/guahsu/JavaScript30/tree/master/05_Flex-Panel-Gallery)
- [05 - Flex Panel Gallery](https://github.com/chiusan/js30/tree/main/05-flex-panel-gallery)
