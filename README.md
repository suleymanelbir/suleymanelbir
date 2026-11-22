# Merhaba, ben Süleyman Elbir 👋

**Yazılım geliştirici · iş akışı mimarı · algoritmik trader**

Kurumsal güvenlik, sunucu yönetimi ve otomasyon alanında web ve mobil ürünler geliştiriyorum.
Ürünlerin çoğu kurumların kendi sunucusunda çalışan (self-hosted) sistemler. Kodları özel
depolarda tutuluyor, bu yüzden aşağıda her ürünün canlı sayfasına bağlantı veriyorum.

📄 **Özgeçmiş (CV):** [Suleyman_Elbir_CV.pdf](cv/Suleyman_Elbir_CV.pdf)

## 🚀 Ürünlerim

### 🔐 Kurumsal ve geliştirici ürünleri

| Ürün | Ne yapar | Bağlantı |
|---|---|---|
| **Veilo** | Self-hosted, uçtan uca şifreli, kapalı ağ kurumsal mesajlaşma platformu | [veilo.tr](https://veilo.tr/) |
| **Voltbox** | Sunucunun parolayı hiç görmediği (sıfır bilgi) kurumsal parola ve sır yönetimi | [volt.veilo.tr](https://volt.veilo.tr/) · [panel](https://vault.veilo.tr) |
| **Axon** | Kurumsal cihaz ve sunucu yönetimi: tüm cihazlar tek panelden | [axon.veilo.tr](https://axon.veilo.tr/) |
| **Radar** | Çok sunuculu altyapılar için self-hosted saldırı tespiti, korelasyon ve otomatik tepki (SOAR) | [radar.veilo.tr](https://radar.veilo.tr/) |
| **Veilo Enterprise Gateway** (kurumsal Authenticator) · *kapalı test aşamasında* | Kurum içi MFA: telefonda sayı eşleştirmeli onay, donanım anahtarı, RADIUS/VPN entegrasyonu | [gateway.veilo.tr](https://gateway.veilo.tr/) |
| **Veilo Authenticator** (bireysel) · *kapalı test aşamasında* | Bulutsuz, hesapsız, çevrimdışı çalışan Android 2FA uygulaması (TOTP/HOTP) | [auth.veilo.tr](https://auth.veilo.tr) · [depo](https://github.com/suleymanelbir/veilo-authenticator) |
| **Repo Analyzer** · *davetle erişim* | GitHub depolarını güvenlik açısından tarayan, açık kaynak projeleri keşfedip karşılaştıran geliştirici aracı (giriş gerektirir, kod kapalı) | [githup.veilo.tr](https://githup.veilo.tr) |

Kurumsal ürünlerin ayrıntılı tanıtımı: [veilo-ecosystem](https://github.com/suleymanelbir/veilo-ecosystem)

### 🏙️ Şehir ve kamu

| Ürün | Ne yapar | Bağlantı |
|---|---|---|
| **KentNabzı** · *prototip: Konya merkez* | Açık uydu verisinden (Sentinel-2) kentsel büyüme izleme: yıllık yapılaşma haritası, ruhsat/yerinde inceleme için aday listesi ve mahalle büyüme sıralaması. Belediye, OSB ve altyapı kurumları için | [kentnabzi.elbirbot.web.tr](https://kentnabzi.elbirbot.web.tr/) |

### 🎓 Eğitim (ücretsiz)

| Ürün | Ne yapar | Bağlantı |
|---|---|---|
| **Mümin Kur'an** | Kur'an okuma, ezber ve sesli tekrar; kök analizi ve alıştırmalar (Android) | [Google Play](https://play.google.com/store/apps/details?id=com.selbir.hafizapp) |
| **Tecvid Okulu** | 30 tecvid kuralını ayet üzerinde renkli gösteren, dinleten ve sınavla pekiştiren uygulama (Android + web) | [Google Play](https://play.google.com/store/apps/details?id=com.selbir.tecvidokulu) |
| **Git Macerası** | Git ve GitHub'ı hikâye içinde, gerçek bir terminalde öğreten web oyunu | [git-oyunu.elbirbot.web.tr](https://git-oyunu.elbirbot.web.tr/) |
| **Mucitkent** | Çocuklar ve gençler için internet, robotik ve dijital güvenlik oyunu | [mucitkent.elbirbot.web.tr](https://mucitkent.elbirbot.web.tr/) |

Kur'an ve Tecvid uygulamalarının sayfaları ve gizlilik politikaları: [projeler](https://github.com/suleymanelbir/projeler)

## 📈 Algoritmik işlem (kapalı kaynak)

Kripto piyasalarında (Binance, Hyperliquid) çalışan kendi algoritmik işlem sistemlerimi geliştiriyorum.
Kodlar, stratejiler ve sonuçlar özeldir; burada yalnızca sistemlerin ne yaptığı anlatılır.
Bu bölüm yatırım tavsiyesi değildir.

| Sistem | Ne yapar |
|---|---|
| **Elbirbot** | Vadeli işlem (futures) botunun komuta paneli: salt okunur kokpit, Grafana "Market MRI" panoları, Telegram denetimli duraklatma düğmesi; Cloudflare Access ile korunur |
| **Arbitraj botu** | XAU/PAXG fonlama oranı toplama (cash-and-carry arbitraj), Hyperliquid + Binance |
| **Binance Futures botları** | Çoklu gösterge (EMA, ADX, RSI, ATR, hacim, VWAP) ile erken trend tespiti, yapılandırılabilir risk yönetimi, long/short, scalping ve grid stratejileri |
| **Dominans ve düşen/yükselen taraması** | CoinMarketCap dominans göstergeleri ve yükselen/düşen coin tespiti ile kaldıraçlı işlem |
| **Spot ve opsiyon botları** | Spot işlem ve opsiyon işlemleri için araçlar |
| **Coinpano** | FastAPI + PostgreSQL tabanlı coin takip paneli ([coinpano.com](https://coinpano.com)) |

Altyapı: Python · systemd · Docker · PostgreSQL · Grafana · Telegram bildirimleri

## 🛠️ Çalıştığım teknolojiler

Linux · Docker · PostgreSQL / SQL · n8n · Tailscale · GitHub Actions · Android · Python

## 📫 İletişim

suleymanelbir@gmail.com

---

## 🇬🇧 English summary

I'm a software developer, workflow architect and algorithmic trader based in Turkey. I build
self-hosted enterprise security and management products, plus Android apps. Most of the code
lives in private repositories, so each product links to its live page above.

**Enterprise & developer**
- **Veilo**: self-hosted, end-to-end encrypted, closed-network enterprise messaging
- **Voltbox**: zero-knowledge enterprise password and secrets vault
- **Axon**: enterprise device and server management from one panel
- **Radar**: self-hosted intrusion detection, correlation and automated response (SOAR)
- **Veilo Enterprise Gateway** (enterprise Authenticator, in closed testing): in-house MFA with number-matching push approval, hardware keys and RADIUS/VPN integration
- **Veilo Authenticator** (personal, in closed testing): offline, cloudless two-factor authentication app for Android
- **Repo Analyzer** (invite-only, closed source): scans GitHub repositories for security issues and compares open-source projects

**City & public sector**
- **KentNabzı** (prototype, Konya city centre): urban growth monitoring from open satellite data (Sentinel-2): yearly built-up maps, inspection candidate lists and neighbourhood growth rankings for municipalities and utilities. [kentnabzi.elbirbot.web.tr](https://kentnabzi.elbirbot.web.tr/)

**Education (free)**
- **Mümin Kur'an** and **Tecvid Okulu**: Quran reading/memorization and Tajweed learning apps on Google Play
- **Git Macerası** and **Mucitkent**: educational web games (Git/GitHub; internet, robotics and digital safety for kids)

I build algorithmic trading systems for crypto markets (Binance, Hyperliquid). Code and strategies are private; this is not investment advice.

- **Elbirbot**: control cockpit for the futures bot (read-only dashboards, Grafana "Market MRI", Telegram-audited pause button, Cloudflare Access)
- **Arbitrage bot**: XAU/PAXG funding-rate farming (cash-and-carry) on Hyperliquid + Binance
- **Binance Futures bots**: multi-indicator early trend detection, configurable risk management, long/short, scalping and grid strategies
- **Dominance and movers scanner**: CoinMarketCap dominance signals and rising/falling coin detection
- **Spot and options bots**, and **Coinpano**: a FastAPI + PostgreSQL coin tracker

Stack: Python, systemd, Docker, PostgreSQL, Grafana, Telegram alerts.

Stack: Linux, Docker, PostgreSQL, n8n, Tailscale, GitHub Actions, Android, Python.
Contact: suleymanelbir@gmail.com
