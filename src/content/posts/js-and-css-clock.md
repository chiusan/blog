---
author: Chiusan
pubDatetime: 2026-11-22T10:56:00+08:00
title: JS and CSS Clock
slug: js-and-css-clock
featured: false
draft: false
tags:
  - js30
  - notes
description: About js30 JS and CSS Clock exercises.
---

## Notes

用 JS 和 CSS 來製作一個時鐘。

## Snippets

`transform-origin` 為 CSS 變形的軸心，預設為物件中心點。

`transform: totate()` 為旋轉物件，數值後要加角度（deg）。

`transition-timing-function: cubic-bezier()` 設定動畫轉場的貝茲曲線，可透過開發者工具來進行視覺化調整。

`Date()` 為取得時間的函數，須搭配 `new` 形成 `new Date()` 使用。

`date.getSeconds(), getMinutes(), getHours()` 可取得當前秒、分、時的時間。

`setInterval()` 有定時器的功能，後接兩個參數，一個是要執行的 function，另一個是時間（毫秒）。

## References

- [We build a CSS + JS Clock in Vanilla JS](https://www.youtube.com/watch?v=xu87YWbr4X0&list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH&index=2)
- [guahsu](https://github.com/guahsu/JavaScript30/tree/master/02_JS-and-CSS-Clock)
- [02 - JS and CSS Clock](https://github.com/chiusan/js30/tree/main/02-js-and-css-clock)
