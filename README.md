<div align="center">

# 📰 AI Günlük
### Global ve Türkiye Yapay Zeka Haberleri & Türkçe Hap Özetler

*Global ve Türkiye yapay zeka ekosistemini 7/24 tarayan, Google Gemini ile hap özetlere dönüştüren tam otonom haber ve radar platformu.*

<br/>

[![Canlı Platform](https://img.shields.io/badge/Canlı%20Platform-aigunluk.vercel.app-4F46E5?style=for-the-badge&logo=vercel&logoColor=white)](https://aigunluk.vercel.app)
[![AI Motoru](https://img.shields.io/badge/AI%20Motoru-Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://aigunluk.vercel.app)
[![Frekans](https://img.shields.io/badge/Otonomi-Günde%204x%20Canlı-10B981?style=for-the-badge&logo=githubactions&logoColor=white)](https://aigunluk.vercel.app)
[![Platform](https://img.shields.io/badge/Platform-PWA%20%E2%80%A2%20Web-0070F3?style=for-the-badge&logo=pwa&logoColor=white)](https://aigunluk.vercel.app)
[![Geliştirici](https://img.shields.io/badge/Geliştirici-@strangervibe-black?style=for-the-badge&logo=github)](https://github.com/strangervibe)

<br/>

<a href="https://aigunluk.vercel.app">
  <img src="https://img.shields.io/badge/🚀%20Canlı%20Platformu%20Aç-aigunluk.vercel.app-4F46E5?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Canlı Platformu Aç" />
</a>
&nbsp;
<a href="https://github.com/strangervibe/aigunluk">
  <img src="https://img.shields.io/badge/GitHub-Depoyu%20Yıldızla%20★-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo Yıldızla" />
</a>

<br/><br/>

<a href="https://aigunluk.vercel.app">
  <img src="https://aigunluk.vercel.app/icons/og-image.jpg" width="100%" alt="AI Günlük Sosyal Medya Önizleme Görseli" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />
</a>

</div>

---

## ✨ AI Günlük Nedir?

**AI Günlük**, yapay zeka dünyasında her gün yayınlanan yüzlerce makale, model lansmanı, teknik araştırma ve sosyal medya tartışmalarını takip etmeyi kolaylaştıran **otonom bir haber ve radar platformudur**.

Geleneksel haber sitelerinin aksine tık tuzağı (clickbait) başlıklara ve gereksiz laf kalabalığına yer vermez. Arka planda 7/24 çalışan akıllı veri motoru, dünya ve Türkiye gündemini tarar; **Google Gemini AI** ile her bir gelişmeyi **2 dakikada okunabilen net Türkçe hap özetlere ve maddelere (key points)** dönüştürür.

---

## 🌟 Öne Çıkan Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| 🤖 **Otonom AI Kürasyonu** | Global ve yerel onlarca teknoloji kaynağını (Hacker News, TechCrunch, ArXiv vb.) otomatik tarar ve yapay zeka ile önem sırasına dizer. |
| 💡 **Türkçe Hap Özetler (TL;DR)** | Her haber için 1-2 cümlelik vurucu özet ve en kritik 3 maddelik hap bilgi çıkartır. |
| 🔥 **Sosyal Radar (YouTube & X)** | Sosyal medyada en çok ses getiren yapay zeka videolarını, podcast'leri ve tartışmaları anlık akışa dahil eder. |
| ⚡ **Spotlight & Trend Havuzu** | Günün en çok etkileşim alan ve ekosistemi sarsan 1 numaralı lider haberini öne çıkarır. |
| 📱 **PWA & Çevrimdışı Okuma** | Telefon ve masaüstüne doğrudan uygulama olarak yüklenebilir. Çevrimdışı desteğiyle internet olmadan da son bülten okunabilir. |
| 📂 **Kategori & Akıllı Filtreleme** | Büyük Dil Modelleri (LLM), Ajanlar (Agents), Donanım, Açık Kaynak, Etik & Güvenlik gibi kategorilere anında erişim. |
| 🌙 **Obsidian Koyu Tasarım** | Göz yormayan modern cam efektli (glassmorphism) karanlık arayüz ve sıfır gecikmeli minimalist mimari. |

---

## 🏗️ Mimari & Teknolojik Altyapı

AI Günlük, yüksek hız ve sıfır sunucu bakım maliyeti hedefiyle modern Jamstack + Edge + Autonomous Cron prensiplerine göre inşa edilmiştir:

```
[Global & Yerel Kaynaklar]
         │
         ▼
[Python Scraper Engine] (Haberleri & RSS'leri çeker)
         │
         ▼
[Google Gemini AI Engine] (Kürasyon, Türkçe çeviri, hap özet & anahtar noktalar)
         │
         ▼
[Serverless Flat JSON] (today.json, trending.json, social_radar.json)
         │
         ▼
[Vercel Global Edge CDN] ──► [Kullanıcı: Ultra Hızlı PWA Arayüzü]
```

- **Ön Yüz (Frontend):** Vanilla JavaScript (ES6+), Modern CSS (Variables, Grid/Flexbox), PWA Service Worker.
- **Yapay Zeka (AI / LLM):** Google Gemini 3.5 Flash API.
- **Otomasyon & Pipeline:** GitHub Actions Cron (Günde 4 kez tam otonom çalışma).
- **Barındırma & Dağıtım:** Vercel Global Edge Network.
- **Veri Depolama:** Sıfır veritabanı maliyeti sağlayan flat JSON yapısı.

---

## 📲 Mobil Kurulum (PWA)

AI Günlük'ü uygulama mağazalarına ihtiyaç duymadan doğrudan telefonunuza kurabilirsiniz:

1. Telefonunuzun tarayıcısından (Safari / Chrome) **[aigunluk.vercel.app](https://aigunluk.vercel.app)** adresini açın.
2. Tarayıcı menüsünden **"Ana Ekrana Ekle"** (veya *"Uygulamayı Yükle"*) seçeneğine dokunun.
3. Artık ana ekranınızdan tek dokunuşla tam ekran ve uygulama akıcılığında haberleri takip edebilirsiniz.

---

## 📄 Vitrin Deposu Hakkında

> 🔒 **Gizlilik Notu:** Bu depo, AI Günlük projesinin **herkese açık vitrin, mimari şema ve dokümantasyon merkezidir**. Arka planda çalışan tescilli veri botu ve API pipeline kodları özel (private) depoda korunmaktadır.

---

<div align="center">

Geliştirici: [**@strangervibe**](https://github.com/strangervibe) • Vibe Coding ile inşa edildi.

[![GitHub](https://img.shields.io/badge/Geliştirici-strangervibe-181717?style=flat-square&logo=github)](https://github.com/strangervibe)
[![Niyaz](https://img.shields.io/badge/Diğer%20Proje-Niyaz%20Mobile-1B6B4A?style=flat-square&logo=appveyor)](https://github.com/strangervibe/Niyaz)
[![AI Günlük](https://img.shields.io/badge/Canlı-AI%20Günlük-4F46E5?style=flat-square&logo=vercel)](https://aigunluk.vercel.app)

</div>
