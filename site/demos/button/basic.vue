<docs>
---
title: 基础按钮
---

你可以通过指定type, size, round来指定按钮的样式

</docs>
<template>
  <div>
    <LyButton>default</LyButton>
    <LyButton type="primary">primary</LyButton>
    <LyButton type="success">success</LyButton>
    <LyButton type="info">info</LyButton>
    <LyButton type="warning">warning</LyButton>
    <LyButton type="danger">danger</LyButton>
    <LyButton type="link">link</LyButton>
  </div>
  <div style="margin-top: 20px">
    <LyButton size="small">small</LyButton>
    <LyButton>normal</LyButton>
    <LyButton size="large">large</LyButton>
  </div>
  <div style="margin-top: 20px">
    <LyButton round>type</LyButton>
    <LyButton round type="primary">primary</LyButton>
    <LyButton round type="success">success</LyButton>
    <LyButton round type="info">info</LyButton>
    <LyButton round type="warning">warning</LyButton>
    <LyButton round type="danger">danger</LyButton>
  </div>
</template>
