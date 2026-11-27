<div align="center">

# ✈️ PilotPing

### Your flight companion, even when you're away from the cockpit.

**Flight monitoring · IVAO & VATSIM alerts · Landing analysis · Flight history**

[![Latest release](https://img.shields.io/github/v/release/erencevikk/PilotPing?style=flat-square&label=Latest%20release)](https://github.com/erencevikk/PilotPing/releases/latest)
![Windows](https://img.shields.io/badge/Windows-x64-0078D4?style=flat-square)
![MSFS](https://img.shields.io/badge/MSFS-2020%20%7C%202024-1465A3?style=flat-square)
![X-Plane](https://img.shields.io/badge/X--Plane%2012-Experimental-orange?style=flat-square)

**[⬇ Download Windows Installer](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Setup.exe)** · **[📦 Download Portable ZIP](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Portable.zip)**

[Latest Release](https://github.com/erencevikk/PilotPing/releases/latest) · [Report a Bug](https://github.com/erencevikk/PilotPing/issues/new) · [Türkçe ↓](#türkçe)

</div>

---

## 🌍 English

### Meet PilotPing

[Watch the PilotPing demo on YouTube (in Turkish, with Turkish captions)](https://youtu.be/O55r6WOE1uM)

PilotPing is a **Windows flight simulation companion** for Microsoft Flight Simulator 2020 & 2024. Stay informed of supported IVAO/VATSIM messages, configure Away and Present notifications, and review locally recorded flights and landings.

It is a companion, **not a replacement for your ATC client or pilot responsibilities**. Features depend on available simulator telemetry, compatible network clients and your setup.

### ✨ Features

| Feature | Description |
| :-- | :-- |
| 📩 **IVAO & VATSIM alerts** | Optional Telegram notifications for supported IVAO Altitude and VATSIM vPilot messages. |
| 🧑‍✈️ **Away / Present** | Automatic and manual modes with configurable alerts. |
| 🛫 **Flight monitoring** | Selected flight event monitoring and manual top-of-descent reminders. Experimental, off-by-default automatic MSFS pause before the manual TOD. |
| 🗺️ **SimBrief** | Optional planned-route import. |
| 🛬 **Landing analysis** | Recorded landing metrics and 2D replay when enough data exists. |
| 📒 **Flight history** | Local flight log with CSV/JSON export. |
| 🌐 **Bilingual** | English and Turkish interface. |

### ⬇ Download v1.0.8

**What’s new in v1.0.8.** The card shown when PilotPing starts with MSFS or Windows now has the creator's photo, scales with Windows display scaling and stays for 12 seconds (not yet seen in a live MSFS start). Starting PilotPing yourself opens the welcome window. The v1.0.7 change that shows MSFS altitude as the altimeter reading has automated tests only and is not yet compared with a cockpit altimeter. ⚠️ **Automatic pause is still experimental** and not verified in a live MSFS session. It is off by default. Stay near the computer, watch your descent, do not use it online, and resume inside MSFS if the sim stays paused.

| Package | Download |
| :-- | :-- |
| Windows Installer (.exe) | **[Install PilotPing](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Setup.exe)** |
| Portable (.zip) | [Portable ZIP](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Portable.zip) |
| Checksums | [SHA-256](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-SHA256SUMS.txt) |
| Source archive | [Source ZIP](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Source.zip) |

Use the **[latest releases page](https://github.com/erencevikk/PilotPing/releases/latest)** for updates.

### 🚀 Quick Start

1. Run the installer, or extract Portable ZIP and launch `PilotPing.exe`.
2. Launch MSFS 2020/2024 and check the simulator connection in PilotPing.
3. Configure notification preferences and optional integrations in Settings.
4. For Telegram alerts, set up your own bot/chat credentials.
5. If using IVAO or VATSIM, test client message detection before relying on notifications.
6. Review flight history and landing data after your flight.

Both Windows packages include the x64 SimConnect client.

### 🧩 Compatibility

| Simulator / Integration | Support | Notes |
| :-- | :-- | :-- |
| MSFS 2020 | ✅ Supported | SimConnect on Windows |
| MSFS 2024 | ✅ Supported | SimConnect on Windows |
| IVAO Altitude | ✅ Supported integration | Supported messages and client setup required |
| VATSIM vPilot | ✅ Supported integration | Supported messages and client setup required |
| VATSIM xPilot / swift | Client detection only | Telegram message forwarding is unavailable for these clients |
| Telegram | ✅ Optional | Requires user configuration |
| SimBrief | ✅ Optional | Planned-route import |
| X-Plane 12.1.1+ | 🧪 Experimental | Basic telemetry, feature coverage more limited than MSFS |

**X-Plane:** Uses the X-Plane Web API for basic parameters such as altitude, speed, position and fuel. Aircraft-specific autopilot status detection is available for ToLiss and Zibo. Select **Settings → Simulator → X-PLANE**, then check **Diagnostics**.

### 🔔 Updates, Privacy & Support

- **Updates:** Follow [GitHub Releases](https://github.com/erencevikk/PilotPing/releases/latest). Do not assume unattended auto-update.
- **Privacy:** Flight history is stored locally. If Telegram alerts are enabled, configured alert content is transmitted through Telegram.
- **Support:** [Open an issue](https://github.com/erencevikk/PilotPing/issues/new) with app version, simulator version and steps to reproduce. Remove tokens, chat IDs and other secrets from logs.
- **Verification:** Compare downloaded package checksums against the official SHA-256 file.

---

## 🇹🇷 Türkçe

### PilotPing nedir?

[PilotPing tanıtımını ve Telegram bildirim demosunu YouTube’da izle](https://youtu.be/O55r6WOE1uM)

PilotPing, **Microsoft Flight Simulator 2020 ve 2024** için geliştirilmiş bir Windows uçuş yardımcı uygulamasıdır. Desteklenen IVAO/VATSIM mesajlarını takip etme, Away/Present bildirimleri, uçuş geçmişi ve iniş analizi özelliklerini tek yerde toplar.

PilotPing, ATC istemcisinin ya da pilotun uçuşu takip etme sorumluluğunun yerine geçmez. Özelliklerin kapsamı simülatör verilerine, desteklenen istemcilere ve yapılandırmaya bağlıdır.

### ✨ Özellikler

| Özellik | Açıklama |
| :-- | :-- |
| 📩 **IVAO ve VATSIM uyarıları** | Desteklenen IVAO Altitude ve VATSIM vPilot mesajları için isteğe bağlı Telegram bildirimi. xPilot ve swift algılanabilir, ancak bu istemcilerden Telegram’a mesaj aktarımı desteklenmiyor. |
| 🧑‍✈️ **Away / Present** | Otomatik ve manuel pilot varlığı yönetimi. |
| 🛫 **Uçuş takibi** | Seçili uçuş olayları ve manuel TOD hatırlatmaları. Deneysel, varsayılan kapalı otomatik MSFS durdurma. |
| 🗺️ **SimBrief** | İsteğe bağlı planlanan rota aktarımı. |
| 🛬 **İniş analizi** | Kaydedilen iniş ölçümleri ve veri mevcutsa 2D tekrar. |
| 📒 **Uçuş geçmişi** | Yerel kayıtlar ve CSV/JSON dışa aktarma. |
| 🌐 **Dil desteği** | Türkçe / İngilizce arayüz. |

### ⬇ İndir v1.0.8

**v1.0.8’de yenilikler.** PilotPing MSFS veya Windows ile başladığında çıkan kart artık geliştiricinin fotoğrafını gösteriyor, ekran ölçeğine göre büyüyor ve 12 saniye kalıyor (gerçek bir MSFS açılışında henüz görülmedi). PilotPing'i elle açınca hoş geldin penceresi çıkıyor. v1.0.7'de gelen, MSFS irtifasını altimetre değeri olarak gösterme değişikliği yalnızca otomatik testlerden geçti; kokpit altimetresiyle henüz karşılaştırılmadı. ⚠️ **Otomatik durdurma hâlâ deneyseldir**, gerçek MSFS oturumunda doğrulanmadı. Varsayılan olarak kapalıdır. Bilgisayarın yakınında ol, alçalışı takip et, online uçuşta kullanma; sim duraklatılmış kalırsa MSFS içinden devam ettir.

**[Windows Kurulum Dosyası (.exe)](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Setup.exe)** · **[Portable ZIP](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-Portable.zip)** · **[En Güncel Sürüm](https://github.com/erencevikk/PilotPing/releases/latest)**

### 🚀 Kurulum

1. `PilotPing-v1.0.8-Setup.exe` kurulum dosyasını çalıştır veya Portable ZIP’i bir klasöre çıkarıp içindeki `PilotPing.exe` dosyasını aç.
2. MSFS 2020/2024'ü başlat ve simülatör bağlantısını denetle.
3. Ayarlar'dan dili, bildirimleri ve isteğe bağlı entegrasyonları yapılandır.
4. Telegram bildirimleri için bot ve sohbet bilgilerini gir.
5. IVAO/VATSIM mesaj algılamasını gerçek uçuş öncesinde test et.
6. Uçuş bittiğinde uçuş geçmişini ve iniş analizini incele.

**Deneysel X-Plane 12.1.1+ desteği:** X-Plane Web API üzerinden temel telemetriyi okur. ToLiss ve Zibo için uçağa özel otopilot durumu algılama desteği vardır. **Ayarlar → Simülatör → X-PLANE** bölümünü seç ve **Tanılama** ekranından doğrula. Telemetri kapsamı MSFS'ten daha sınırlıdır.

### 🛠 Güncellemeler ve Destek

- [Yeni sürümler ve değişiklikler](https://github.com/erencevikk/PilotPing/releases/latest)
- [Hata bildir / özellik öner](https://github.com/erencevikk/PilotPing/issues/new)
- [İndirme dosyalarının SHA-256 doğrulaması](https://github.com/erencevikk/PilotPing/releases/download/v1.0.8/PilotPing-v1.0.8-SHA256SUMS.txt)

Uçuş kayıtları yerel saklanır. Telegram etkinse seçtiğin bildirim içerikleri Telegram üzerinden iletilir. Hata raporlarında bot tokenı, Chat ID veya özel bilgi paylaşma.

---

<div align="center">

**Developed by Eren Çevik** · Built for the flight simulation community

[Download](https://github.com/erencevikk/PilotPing/releases/latest) · [Feedback](https://github.com/erencevikk/PilotPing/issues/new) · [Back to top ↑](#️-pilotping)

</div>
