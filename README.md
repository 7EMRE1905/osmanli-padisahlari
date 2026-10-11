# 👑 Osmanlı Padişahları Web Sitesi

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/Lisans-MIT-green.svg?style=for-the-badge)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Canlı_Demo-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://7emre1905.github.io/osmanli-padisahlari/)
[![Padişahlar](https://img.shields.io/badge/Osmanlı_Hanedanı-36_Padişah-gold?style=for-the-badge)]()

Osmanlı İmparatorluğu'nun kuruluşundan (1299 - Osman Gazi) son dönemine (1922 - Mehmed Vahdeddin) kadar tahta geçen **36 Osmanlı Padişahı** ve **Fetret Devri** hakkında ayrıntılı ansiklopedik bilgiler sunan, saf HTML5 & CSS3 ile hazırlanmış açık kaynak web ansiklopedisi.

---

## 🌐 Canlı Ön Gösterim (Live Demo)

Projeyi bilgisayarınıza indirmeden doğrudan web tarayıcınızda (telefon, tablet veya bilgisayar) canlı olarak gezebilirsiniz:

👉 **[https://7emre1905.github.io/osmanli-padisahlari/](https://7emre1905.github.io/osmanli-padisahlari/)**

_(Alternatif doğrudan bağlantı: [Anasayfa.html](https://7emre1905.github.io/osmanli-padisahlari/Anasayfa.html))_

---

## 📖 Projenin Hikayesi

> 💡 **Bir Lise 10. Sınıf Proje Ödevinden Açık Kaynak Mirasına:**  
> Bu proje, lise 10. sınıf döneminde Bilişim Teknolojileri Web Tasarımı dersi için hazırlanmış bir proje ödevidir. saf HTML ve CSS kullanılarak hazırlanmıştır.
>
> Yıllar sonra nostaljik bir hatıra olarak arşivden çıkarılmış; eksik kalan tüm padişah sayfaları ve Fetret Devri sıfırdan tamamlanarak Wikipedia ve Türk Tarih Kurumu düzeyinde zengin ve kapsamlı ansiklopedik metinlerle donatılmıştır.
>
> Amacımız; web geliştirmeye yeni adım atan genç arkadaşlara saf (Vanilla) HTML/CSS ile nasıl sayfa mimarisi, kronolojik gezinti (navigation) ve görsel uyum kurulabileceğini göstermek ve tarih araştırması yapan öğrencilere derli toplu açık kaynak bir başvuru kılavuzu sunmaktır.

---

## ✨ Özellikler

- 📜 **36 Padişah + Fetret Devri (37 Sayfa):** Osman Gazi'den VI. Mehmed Vahdeddin'e kadar eksiksiz kronolojik anlatım.
- 📚 **Derin Ansiklopedik İçerik:** Her padişahın şehzadelik dönemi, tahta çıkışı, askerî seferleri, ıslahatları, mimari eserleri, edebi/musiki yönü ve ayrıntılı aile şeceresi (eşleri, şehzadeleri, hanım sultanları).
- 🔄 **Bağlantılı Gezinti (Navigation):** Her padişah sayfasında bir önceki ve bir sonraki padişaha tek tıkla geçiş sağlayan gezinme tablosu.
- 🖼️ **Özgün Portre Arşivi:** 36 padişahın ve armanın tamamını içeren yuvarlak portre çerçevesi (`rounded-image`) tasarımı.
- ⚡ **Sıfır Kurulum & Sıfır Bağımlılık:** `npm`, `node`, `webpack` veya veritabanı gerektirmez. Doğrudan tarayıcıda çalışır.
- 🌍 **GitHub Pages Uyumlu:** `index.html` yönlendirmesi sayesinde GitHub Pages üzerinden tek tıkla yayınlanabilir.

---

## ⚙️ GitHub Pages Nasıl Aktif Edilir?

Projeyi kendi GitHub hesabınızda ücretsiz yayına almak için:

1. GitHub'da deponuzun (reponun) en üstündeki **Settings (Ayarlar)** sekmesine tıklayın.
2. Sol menüden **Pages** seçeneğine gelin.
3. **Build and deployment > Source** kısmında **"Deploy from a branch"** seçili olsun.
4. **Branch** açılır menüsünden `None` yerine **`main`** seçin, klasör olarak `/ (root)` seçip **Save** butonuna tıklayın.
5. 1-2 dakika içinde sayfanın yukarısında canlı linkiniz belirecektir:  
   `https://<kullanici-adiniz>.github.io/osmanli-padisahlari/`

---

## 📂 Dosya Yapısı

```bash
osmanli-padisahlari/
├── index.html                 # GitHub Pages kök yönlendiricisi
├── Anasayfa.html              # Tüm padişahların listelendiği ana vitrin tablosu
├── styles.css                 # Klasik, temiz CSS stil dosyası
├── resimler/                  # Padişah portreleri ve Osmanlı arması/logoları
├── osman-gazi.html            # 1. Padişah - Osman Gazi
├── orhan-gazi.html            # 2. Padişah - Orhan Gazi
├── murad-i.html               # 3. Padişah - I. Murad (Hüdavendigâr)
├── yildirim-beyazit.html       # 4. Padişah - Yıldırım Bayezid
├── fetret-devri.html          # Fetret Devri (1402 – 1413)
├── i-mehmed.html              # 5. Padişah - Çelebi Mehmed
├── ...                        # Diğer tüm padişah sayfaları (Toplam 37 sayfa)
├── mehmed-vahdeddin.html      # 36. Padişah - VI. Mehmed Vahdeddin
├── LICENSE                    # MIT Lisansı
└── README.md                  # Proje dokümantasyonu
```

---

## 🚀 Yerel Olarak Nasıl Çalıştırılır?

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/7EMRE1905/osmanli-padisahlari.git
   ```
2. Klasörün içindeki `Anasayfa.html` veya `index.html` dosyasına çift tıklayın.
3. Tarayıcınızda açılan sayfadan dilediğiniz padişahı incelemeye başlayın!

---

## 📚 Kaynakça

Sitedeki tarihsel bilgiler ve veriler aşağıdaki güvenilir kaynaklar referans alınarak derlenmiştir:

- [Türk Tarih Kurumu (TTK) - Osmanlı Padişahları](https://ttk.gov.tr/osmanli-padisahlari/)
- [Wikipedia - Osmanlı Padişahları Listesi](https://tr.wikipedia.org/wiki/Osmanl%C4%B1_padi%C5%9Fahlar%C4%B1_listesi)
- [İstanbul Gedik Üniversitesi - Kronolojik Sıralama ve Dönemler](https://uzemigunsem.gedik.edu.tr/osmanli-padisahlari-kronolojik-siralama-ve-donemleri-hakkinda-kisa-bilgiler)

---

## 📜 Lisans

Bu proje **MIT Lisansı** ile lisanslanmıştır. Kodları inceleyebilir, kopyalayabilir, okul ödevlerinizde ve kendi projelerinizde serbestçe kullanabilirsiniz.

Geliştirici: **Yusuf Emre** ([@7EMRE1905](https://github.com/7EMRE1905))
