---
title: "Hugo ile Kişisel Blog Oluşturma Rehberi"
description: "Hugo static site generator kullanarak nasıl güzel bir blog oluşturabileceğinizi öğrenin"
date: 2024-01-15
draft: false
tags: ["hugo", "blog", "web-gelistirme", "static-site"]
categories: ["Teknoloji", "Web Geliştirme"]
author: "Gökhan Gürsoy"
readingTime: true
showToc: true
TocOpen: false
---

# Hugo ile Kişisel Blog Oluşturma Rehberi 🚀

Merhaba! Bu yazımda Hugo static site generator kullanarak nasıl güzel bir kişisel blog oluşturabileceğinizi adım adım anlatacağım.

## Hugo Nedir?

**Hugo**, Go programlama dili ile yazılmış hızlı ve modern bir static site generator'dır. Markdown dosyalarınızı HTML'e dönüştürür ve çok hızlı bir şekilde sitenizi oluşturur.

### Hugo'nun Avantajları

- ⚡ **Çok Hızlı** - Saniyeler içinde site oluşturur
- 🎨 **Tema Desteği** - Yüzlerce hazır tema
- 📝 **Markdown Desteği** - Kolay içerik yazımı
- 🔧 **Özelleştirilebilir** - Tam kontrol
- 🚀 **SEO Dostu** - Arama motorları için optimize

## Kurulum Adımları

### 1. Hugo'yu Kurun

macOS için:
```bash
brew install hugo
```

### 2. Yeni Site Oluşturun

```bash
hugo new site my-blog
cd my-blog
```

### 3. Tema Ekleyin

```bash
git init
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/papermod
```

### 4. Yapılandırma

`hugo.toml` dosyasını düzenleyin:

```toml
baseURL = 'https://yoursite.com/'
languageCode = 'tr'
title = 'Benim Blogum'
theme = 'papermod'

[params]
  author = "Adınız"
  ShowReadingTime = true
  ShowShareButtons = true
```

## İçerik Oluşturma

### Yeni Yazı Ekleme

```bash
hugo new posts/ilk-yazim.md
```

### Markdown Formatı

```markdown
---
title: "Yazı Başlığı"
date: 2024-01-15
tags: ["etiket1", "etiket2"]
---

İçerik buraya gelecek...
```

## Tema Özelleştirme

PaperMod teması birçok özellik sunar:

- 🌙 **Dark/Light Mode** - Otomatik tema değişimi
- 🔍 **Arama** - Hızlı içerik arama
- 📱 **Responsive** - Mobil uyumlu tasarım
- 🎨 **Özelleştirilebilir** - Renkler ve stiller

## Deployment

### GitHub Pages

1. Repository oluşturun
2. GitHub Actions ile otomatik deploy
3. Custom domain ekleyin

### Netlify

1. Netlify'a bağlayın
2. Otomatik build ve deploy
3. Form handling ve analytics

## Öneriler

### Performans İçin

- Resimleri optimize edin
- CSS/JS dosyalarını minify edin
- CDN kullanın

### SEO İçin

- Meta description ekleyin
- Open Graph etiketleri kullanın
- Sitemap oluşturun

## Sonuç

Hugo ile blog oluşturmak hem kolay hem de eğlenceli. Hızlı, güvenli ve özelleştirilebilir bir çözüm sunuyor.

### Kaynaklar

- [Hugo Resmi Sitesi](https://gohugo.io/)
- [PaperMod Tema](https://github.com/adityatelange/hugo-PaperMod)
- [Hugo Dokümantasyonu](https://gohugo.io/documentation/)

---

*Bu yazıyı beğendiyseniz, diğer yazılarımı da okumayı unutmayın!* 📚

**Etiketler:** #hugo #blog #web-gelistirme #static-site 