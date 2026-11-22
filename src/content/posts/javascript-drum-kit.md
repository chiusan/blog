---
author: Chiusan
pubDatetime: 2026-11-22T10:22:00+08:00
title: JavaScript Drum Kit
slug: javascript-drum-kit
featured: false
draft: false
tags:
  - js30
  - notes
description: About js30 JavaScript Drum Kit exercises.
---

## Notes

透過 JS 實現當按下按鍵時，播放出對應鼓聲與視覺特效的效果。

## Snippets

element.classList 可以回傳 element 的 class 值。

```js
classList.add(); // 新增 className
classList.remove(); // 移除 className
```

HTML 的 `audio` 標籤與指定音源。

可以用 JS 的 `element.play()` 和 `element.currentTime` 的達成播放及指定播放秒數的作用。

```html
<audio src="sounds/example.mp3"></audio>
```

## References

- [Make a JavaScript Drum Kit in Vanilla JS!](https://www.youtube.com/watch?v=VuN8qwZoego&list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH)
- [guahsu](https://github.com/guahsu/JavaScript30/tree/master/01_Java-Script-Drum-Kit)
- [01 - JavaScript Drum Kit](https://github.com/chiusan/js30/tree/main/01-javascript-drum-kit)
