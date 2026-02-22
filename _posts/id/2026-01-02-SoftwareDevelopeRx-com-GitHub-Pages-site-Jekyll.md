---
ref: GitHub-Pages-site-Jekyll
---

# SoftwareDevelopeRx.com - GitHub Pages site - Jekyll

Website [softwaredeveloperx.com](https://softwaredeveloperx.com/) dihandle dengan cara:

- Github Pages ke Repo [https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io](https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io)
- menggunakan Jekyll {bisa diakses di [https://github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)) atau di [https://jekyllrb.com](https://jekyllrb.com)}
- entry point: file `_config.yml`
- theme: `minima`

## Nice to have

- konfigurasi Github Pages ke Custom domain - softwaredeveloperx.com<br/>
  untuk Repo [https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io](https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io)
- file `CNAME`
- konfigurasi `Jekyll`

## Next step

- download theme `minima` di [https://github.com/jekyll/minima](https://github.com/jekyll/minima)
- extract pada _Root Folder_
- lakukan konfigurasi pada file [\_config.yml](https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io/blob/main/_config.yml)

### hasil extract theme: `minima`

![Jekyll--theme--minima](/A_images/web-softwaredeveloperx-com/Jekyll--theme--minima.png)

### konfigurasi Github Pages ke Custom domain - softwaredeveloperx.com

![Jekyll--theme--minima](/A_images/web-softwaredeveloperx-com/GitHub-Pages-Custom-domain.png)

### Deploy

proses Deploy bisa dilihat pada page berikut:

![GitHub-Pages-deploy.png](/A_images/web-softwaredeveloperx-com/GitHub-Pages-deploy.png)

## Summary: file added and changes

File-file yang saya tambahkan dan/atau ubah:

- file [\_config.yml](https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io/blob/main/_config.yml)
- file [index.md](https://github.com/softwaredeveloperx9/softwaredeveloperx9.github.io/blob/main/index.md)
- dan beberapa file pada beberapa Sub-Folder:

![GitHub-Pages-file-add-changes.png](/A_images/web-softwaredeveloperx-com/GitHub-Pages-file-add-changes.png)

## DO NOT: prefix \_

Underscore _ di Jekyll = tanda "ini folder/file sistem Jekyll, bukan konten publik".<br/>
Semua folder internal Jekyll pakai _:

```
_posts/      ← sistem
_layouts/    ← sistem
_includes/   ← sistem
_sass/       ← sistem
_drafts/     ← sistem
```

> [!WARNING]
> saya pernah membuat file layout - `a_new_post.html`, tetapi tidak bisa {karena alasan di atas}
