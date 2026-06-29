# 🚀 Gelişmiş Tailwind CSS Kişisel Portfolyo & Blog
Bu proje; modern, minimalist ve tamamen **Tailwind CSS (Utility-First)** mimarisi kullanılarak geliştirilmiş, yerel hafıza (LocalStorage) destekli kişisel bir portfolyo ve blog ana sayfa tasarımıdır. Projede ham JavaScript kod kalabalığından kaçınılarak, dinamik özelliklerin büyük çoğunluğu doğrudan Tailwind CSS ve HTML5'in yerleşik yetenekleriyle çözülmüştür.

## ✨ Öne Çıkan Özellikler

* **Utility-First Yaklaşımı:** Projede harici hiçbir geleneksel CSS dosyası kullanılmamış, tüm tasarım atomik Tailwind sınıfları ile doğrudan HTML üzerinde inşa edilmiştir.
* **Sıfır JS ile Genişleyen Akordeon Kart Yapısı:** Blog/Proje kartlarında tıklandığında içeriğin açılıp kapanması, JavaScript `click` eventleri yerine HTML'in yerleşik `<details>` ve `<summary>` etiketleri ile Tailwind'in `group-open:` durum (state) yöneticisi birleştirilerek **pure CSS** mantığıyla çözülmüştür.
* **Yumuşak Geçişler & Responsive:** Tüm cihaz ekranlarına (Mobil, Tablet, Masaüstü) tam uyumlu (Responsive) yapı ve temalar arası geçişlerde gözü yormayan `transition-colors duration-300` animasyonları.

## 🛠️ Kullanılan Teknolojiler

* **HTML5** (Semantik etiket yapısı: `<nav>`, `<header>`, `<main>`, `<article>`, `<details>`, `<summary>`)
* **Tailwind CSS v3** (Play CDN üzerinden dinamik Just-In-Time derleme ile entegre edilmiştir)
