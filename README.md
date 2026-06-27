<div align="center">

<img src="https://img.shields.io/badge/ARIA-AI%20Asistan-7b68ee?style=for-the-badge&logo=robot&logoColor=white" />

# 🤖 ARIA — Yapay Zeka Asistanı

**Gerçek zamanlı web araması · AI görsel üretimi · Sesli konuşma · Görsel analiz**

[![Groq](https://img.shields.io/badge/LLM-Groq%20Llama-6c63ff?style=flat-square)](https://groq.com)
[![Serper](https://img.shields.io/badge/Arama-Serper.dev-3ecf8e?style=flat-square)](https://serper.dev)
[![ModelsLab](https://img.shields.io/badge/Görsel-ModelsLab%20Flux-ff6b7a?style=flat-square)](https://modelslab.com)
[![License](https://img.shields.io/badge/Lisans-MIT-f5a623?style=flat-square)](LICENSE)

*Tek HTML dosyası · Sıfır kurulum · Tamamen ücretsiz*

[**🚀 Canlı Dene**](https://kullaniciadın.github.io/aria) &nbsp;·&nbsp; [**📖 Kurulum**](#-kurulum) &nbsp;·&nbsp; [**✨ Özellikler**](#-özellikler)

</div>

---

## ✨ Özellikler

| Özellik | Detay |
|---|---|
| 🧠 **Akıllı Sohbet** | Groq `llama-3.3-70b` — süper hızlı, akıllı |
| 🔍 **Gerçek Zamanlı Arama** | Serper.dev ile Google sonuçları — haberler, döviz, hava |
| 🎨 **AI Görsel Üretimi** | ModelsLab Flux — yüksek kalite resim oluşturma |
| 🖼️ **Görsel Analiz** | Yüklediğin görseli AI analiz eder |
| 🎤 **Sesli Konuşma** | Konuş → ARIA sesli cevap versin |
| 📍 **Konum Algılama** | Hava durumu için otomatik şehir tespiti |
| 📱 **Mobil Uyumlu** | Telefon ve masaüstünde mükemmel çalışır |

---

## 🚀 Kurulum

### Adım 1 — Groq API Anahtarı Al (Zorunlu · Ücretsiz)

> Groq, yapay zekanın çalışması için gerekli. Tamamen ücretsiz, kart istemiyor.

1. **[console.groq.com](https://console.groq.com)** adresine git
2. **"Sign Up"** tıkla → Google hesabınla giriş yap
3. Sol menüden **"API Keys"** tıkla
4. **"Create API Key"** butonuna bas → bir isim yaz → **"Submit"**
5. `gsk_...` ile başlayan anahtarı **hemen kopyala** (bir daha gösterilmez!)

### Adım 2 — Uygulamayı Aç

Uygulamayı açtığında bir kurulum ekranı çıkar:

- **Groq API Key** → 1. adımda aldığın anahtarı yapıştır *(zorunlu)*
- Serper ve ModelsLab → opsiyonel, boş bırakabilirsin
- **"Başla →"** tıkla

✅ Hepsi bu kadar! Anahtarlar sadece senin tarayıcında saklanır, hiçbir sunucuya gönderilmez.

### Opsiyonel API Anahtarları

| Servis | Ne İşe Yarar | Nasıl Alınır |
|---|---|---|
| **Serper.dev** | Google'da gerçek zamanlı arama | [serper.dev](https://serper.dev) → Sign Up → 2.500 ücretsiz |
| **ModelsLab** | AI ile resim oluşturma | [modelslab.com](https://modelslab.com) → Sign Up → 100/gün ücretsiz |

---

## 💡 Nasıl Kullanılır

| Yazmak istediğin | Ne olur |
|---|---|
| `Bugün hava nasıl?` | Konumunu algılar, anlık hava verir |
| `Dolar kaç TL şu an?` | Google'dan anlık kur getirir |
| `Bana bir orman resmi çiz` | AI ile yüksek kalite görsel üretir |
| Görsel yükle + soru sor | AI görseli analiz eder |
| 🎤 butonuna bas | Sesli konuşma modu açılır |

---

## 🛠️ Teknolojiler

```
Sohbet   → Groq llama-3.3-70b-versatile
Ses→Yazı → Groq Whisper large-v3-turbo  
Arama    → Serper.dev (Google SERP)
Görsel   → ModelsLab Flux
Konum    → OpenStreetMap Nominatim
```

---

## 📄 Lisans

MIT © 2026 — Özgürce kullan, paylaş, geliştir.
