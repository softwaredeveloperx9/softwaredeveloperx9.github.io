---
ref: garis-webpage
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
