---
layout: post
title: "Tips: Menampilkan Garis merah pada WebPage"
date: 2026-02-10 09:30:00 +0700
categories: [kategori1, kategori2]
tags: [tag1, tag2, tag3]
author: SDR - Software DevelopeR
---

# Cara menampilkan Garis merah pada WebPage

Ada beberapa cara:
- menggunakan simple - `JavaScript`
- menggunakan `CSS`

## Menggunakan simple - `JavaScript`

Gunakan script berikut pada _console_:

```
document.querySelectorAll('*').forEach(el => {
    el.style.outline = '1px solid red';
});

```

## Menggunakan `CSS`

```
* {
  outline: 1px solid red !important;
}

```

atau:

```

* {
  border: 1px solid red !important;
}

```

hasil seperti berikut:

![Garis pada WebPage](/A_images/Outline-solid-red.png)
