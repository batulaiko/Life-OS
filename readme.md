# ⚡ Life OS // Gamified Habit, Gym & Life Architecture Tracker

[License: MIT](https://www.google.com/search?q=LICENSE)
[Vanilla JS](https://www.google.com/search?q=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FWeb%2FJavaScript)
[PWA Ready](https://www.google.com/search?q=https%3A%2F%2Fweb.dev%2Fprogressive-web-apps%2F)

### 🌐 Language / Dil Seçimi

[**🇹🇷 Türkçe**](#-türkçe)  |  [**🇬🇧 English**](#-english)

# 🇹🇷 Türkçe

[English Version 🇬🇧](#-english)

**Life OS**, günlük alışkanlıklarınızı, antrenman ve postür programlarınızı, gömülü egzersiz videolarınızı, vücut kompozisyonunuzu, kitap okuma hedeflerinizi ve odaklanma seanslarınızı tek bir çatı altında toplayan, **Progressive Web App (PWA)** standartlarında geliştirilmiş oyunlaştırılmış bir kişisel gelişim işletim sistemidir.

Harici hiçbir kütüphane, veritabanı sunucusu veya Node.js kurulumu gerektirmez. İster bilgisayarınızda doğrudan tarayıcıda açın, ister GitHub Pages üzerinden telefonunuza (Android / Samsung Galaxy / iOS) bağımsız bir uygulama (PWA) olarak yükleyin.

## 🎯 Temel Özellikler

### 1. 📋 Günlük Alışkanlık Takibi & Tam Özelleştirme (CRUD)

* **12 Varsayılan Temel Alışkanlık + Sınırsız Ekleme/Düzenleme:** Erken uyanış, antrenman, kitap okuma, günlük planlama, dopamin detoksu, soğuk duş, derin çalışma ve esneme alışkanlıkları hazır gelir; **`+ Alışkanlık`** ve **`✏️`** butonlarıyla dilediğiniz alışkanlığı kendi RPG kategorisi (`STR`, `INT`, `WILL`, `VIT`) ve XP değeriyle ekleyebilir, düzenleyebilir veya silebilirsiniz.

* **Aktif Seri (Streak) & Tarih Koruması:** Her alışkanlık için aralıksız gün serisini hesaplar. Geçmiş günleri inceleyebilir, **`Bugün`** butonuyla anında bugüne dönebilir ve gelecek tarihlerin yanlışlıkla işaretlenmesini önleyen korumayla verilerinizi temiz tutabilirsiniz.

* **Ruh Hali & Uyku Sürgüsü:** Günlük zihinsel durumunuzu (Mood 1–5) ve uyku sürenizi (saat) kaydederek biyolojik toparlanmanızı haritalandırır.

### 2. 🏋️‍♂️ Bilimsel Antrenman, Postür Rehberleri & Gömülü YouTube Oynatıcı

* **7 Hazır Bilimsel Program Şablonu:**

  1. **💪 3 Günlük Başlangıç Full Body:** Tüm ana kas gruplarını haftada 3 kez dengeli uyaran temel program.

  2. **🔥 Tabata Round HIIT & Kondisyon:** 20 sn maksimum efor / 10 sn dinlenme × 8 tur (4 dk) metabolik yağ yakım serisi.

  3. **⚡ SOTA (State of the Art) Karın & Core:** Omurga fleksiyonu, oblik rotasyonu ve derin *transversus abdominis* vakum serisi.

  4. **🔥 Jeff Nippard — Push / Pull / Legs (PPL):** Çekiş, Bacak ve İtiş günlerine bölünmüş kanıta dayalı hipertrofi protokolü.

  5. **⚡ StrongLifts 5×5:** Doğrusal güç artışı sağlayan temel bileşik kaldırışlar (Squat, Bench Press, OHP, Pendlay Row, RDL).

  6. **🏋️ 3 Günlük Fonksiyonel & Postür Programı:** Skolyoz, lordoz ve asimetri eğilimi olanlar için omurga dostu fonksiyonel kuvvet.

  7. **🧘 Upper Stretch / 🦵 Lower Stretch / 🦴 Pelvik Tilt & Lordoz (APT) Protokolleri:** Yuvarlak omuz, ileri baş duruşu, arka bacak kısalığı ve Anterior Pelvik Tilt düzeltici tam (15–20 dk) ve hızlı (5 dk) modlar.

* **🎬 Gömülü YouTube Video Oynatıcı (Error 153 Korumalı HTTPS Relay):**

  * Herhangi bir egzersiz satırına dokunduğunuzda açılan akordiyon panelde hareketin **16:9 gömülü YouTube videosu** doğrudan uygulama içinde oynatılır.

  * **Saniye Aralığı Desteği (`⏱️ 00:15 — 00:50`):** Videolar doğrudan hareketin formunun gösterildiği saniyeden başlar.

  * **HTTPS Relay Mimarisi:** Videolar `cdn.embedly.com` HTTPS Relay katmanı üzerinden yüklendiği için hem yerel `.html` dosyasında (`file:///`) hem de GitHub Pages ve mobil tarayıcılarda **YouTube Error 153** hatası almadan çalışır.

* **➕ Program & Egzersiz Editörü + 🌐 Otomatik Dil Çevirisi:**

  * **`➕ Yeni` / `✏️ Düzenle`:** Kendi antrenman programlarınızı oluşturabilir, klavyeden istediğiniz emojiyi ikon olarak atayabilir, gün ekleyip silebilir ve her program için **3 Sabit Bilimsel Açıklama Alanını** (*Programın Amacı*, *Uygulama Metodolojisi*, *İlerleme Protokolü*) düzenleyebilirsiniz.

  * **🌐 Tek Tıkla Ücretsiz Çeviri (TR ↔ EN):** Türkçe yazdığınız program açıklamalarını ve egzersiz form notlarını **`🌐 Çevir`** butonuyla veya kaydederken otomatik olarak İngilizceye (veya tam tersine) çevirebilirsiniz. Egzersiz adları uluslararası standartta ortak İngilizce terminolojiyle korunur.

### 3. 📏 Vücut Ölçüleri, PR Takibi & 4 Bilimsel Yağ Oranı Formülü

* **PR & Ağırlık Yönetimi:** Tüm programlardaki egzersizler otomatik olarak PR listesine gelir; ayrıca **`✍️ Özel Hareket Yaz...`** seçeneğiyle istediğiniz hareketi ekleyebilir, tahmini **1RM** (1 Tekrar Maksimum) değerinizi görebilir ve kayıtları sonradan düzenleyip silebilirsiniz.

* **Manuel Giriş veya 4 Bilimsel Formülle Yağ Oranı Hesaplama:**

  1. **U.S. Navy Çevre Ölçümü Formülü:** Boy, boyun, bel ve kalça çevre ölçümlerine dayalı altın standart.

  2. **YMCA Formülü:** Vücut ağırlığı ve bel çevresi tabanlı pratik hesaplama.

  3. **CUN-BAE Akademik Denklemi:** Yaş, cinsiyet ve VKİ (BMI) korelasyonlu klinik denklem.

  4. **Deurenberg BMI Formülü:** Yaş ve cinsiyet çarpanlı klasik formül.

* **Profil Hafızası & Anlık Metrikler:** Boy, yaş ve cinsiyet bilgileriniz ilk girişten sonra otomatik hatırlanır; Yağ Oranı (%), Yağsız Kas Kütlesi (LBM kg), Omuz, Göğüs ve Sağ/Sol Kol ölçümleriniz tabloda arşivlenir ve her satır düzenlenebilir (`✏️`) veya silinebilir (`✕`).

### 4. 📚 Bitirilen Kitaplar Logu (Bookworm)

* Okuma alışkanlığının yanındaki tek tıkla açılan **"📚 Kitap Bitti"** butonu ile kitap adı, sayfa sayısı, başlangıç/bitiş tarihleri (kaç günde bittiği otomatik hesaplanır) ve özet notlarınızı kaydedebilirsiniz.

* Tüm okuma geçmişiniz **📊 Analiz** sekmesinde kronolojik olarak listelenir ve rozet ilerlemenize doğrudan etki eder.

### 5. ⏱️ Arka Plan Korumalı Çok Turlu Pomodoro & Akademik Rutinler

* **Kesintisiz Zamanlayıcı:** 25 dakika odaklanma / 5 dakika dinlenme döngüleri gerçek sistem saatine (`Date.now()`) kilitlidir; sekme arka plana atılsa veya telefon ekranı kapansa bile süre kaybı yaşanmaz.

* **Özelleştirilebilir Günlük Rutinler:** *🌅 Sabah Rutini*, *⚡ Derin Çalışma*, *🔋 Öğleden Sonra* ve *🌙 Akşam Kapanış* sekmelerinin başlıklarını değiştirebilir, her rutine yeni adım kartları ekleyebilir, düzenleyebilir veya silebilirsiniz.

### 6. 🏆 RPG Karakter Stat Dengesi & 7 Kademeli Rozetler

* **4 Karakter Niteliği (STR, INT, WILL, VIT):** Radar grafiği üzerinde hem güncel denge yüzdesi (`%`) hem de tamamlanan görevlerden biriken toplam sayısal puanlar (`140 Puan`) gösterilir.

* **7 Kademeli Rütbe Sistemi & Mini Bar Chart:**

  * 🥉 Bronz → 🥈 Gümüş → 🥇 Altın → 🏆 Platin → 💎 Diamond → 🔥 Elite → 👑 Legendary

  * Her rozet kartının içinde uzun vadeli hedefleri (`5 → 12 → 24 → 40 → 60 → 85 → 120`) gösteren basamaklı ilerleme çubukları yer alır.

### 7. 🎨 8 Özel Arayüz Teması & %100 Çift Dil

* **Temalar:** 🌑 AMOLED Dark, ☀️ Light Mode, 🌸 Cotton Candy (Toz Pembe), 🔮 Cyberpunk Neon, 🌲 Emerald Forest, 🌅 Sunset Mocha & Gold, 🌊 Deep Ocean & Coral, ❄️ Nordic Slate & Ice.

* **Çift Dil:** Tek tıkla tüm antrenmanlar, egzersiz notları, menüler, rozetler ve rehberler dahil %100 Türkçe 🇹🇷 veya İngilizce 🇬🇧.

### 8. ☁️ Çift Yönlü Bulut Senkronizasyonu & Veri Gizliliği

* **Google Drive Auto-Sync + 🔒 Gizli Güvenlik Anahtarı (`SECRET_KEY`):** Google Apps Script Webhook üzerinden kendi Google Drive'ınıza otomatik yedekleme yapar; belirlediğiniz parola olmadan hiç kimse verilerinizi okuyamaz veya üzerine yazamaz.

* **GitHub Gist Sync:** Kişisel erişim token'ınız (`ghp_...`) ile gizli (secret) bir Gist üzerinden bulut yedekleme.

* **Yerel JSON Yedek & Sıfırlama Kontrolleri:** Tek tıkla tüm verinizi `.json` olarak indirebilir veya Ayarlar'dan yalnızca Alışkanlıkları, Programları ya da Rutinleri varsayılan haline sıfırlayabilirsiniz.

## 📱 PWA Kurulumu ve Telefona Yükleme Rehberi

Tarayıcı güvenlik protokolleri gereği (Google Chrome, Samsung Internet ve Apple Safari), bir web uygulamasının **Progressive Web App (PWA)** olarak algılanıp ana ekrana bağımsız uygulama simgesiyle kurulabilmesi için **HTTPS bağlantısı** üzerinden sunulması gerekir.

Bu repoda PWA için gereken tüm dosyalar hazır durumdadır:

* `index.html` / `LifeOS_Gamified_Habit_Gym_Tracker.html` (Ana uygulama dosyası)

* `manifest.json` (Uygulama adı, tema renkleri, başlangıç URL'si ve ikon tanımları)

* `sw.js` (Çevrimdışı çalışma ve Service Worker önbelleklemesi)

* `icon-192.png` & `icon-512.png` (Yüksek çözünürlüklü altın ⚡ Life OS ikonları)

### 🚀 GitHub Pages ile 1 Dakikada HTTPS Yayını ve Yükleme:

1. Bu depoyu GitHub hesabınıza pushlayın.

2. GitHub'da reponuzun **Settings → Pages** sekmesine gidin.

3. **Branch:** `main` (veya `master`), **Folder:** `/ (root)` seçip **Save** butonuna tıklayın.

4. Yaklaşık 30 saniye içinde `https://<kullanici-adiniz>.github.io/<repo-adi>/` adresinde uygulamanız canlı olarak yayınlanır.

5. **Telefonda Yükleme:**

   * **Samsung Internet / Chrome:** Linki açtığınızda adres çubuğunda **"Yükle"** simgesi çıkar ya da uygulama içindeki **Ayarlar > "Telefona Yükle"** butonuna dokunabilirsiniz.

   * **Safari (iOS):** Linki açın → Paylaş (Share) butonuna dokunun → **"Ana Ekrana Ekle"** seçeneğini seçin.

## ☁️ Google Drive Auto-Sync Kurulumu (6 Adım)

Uygulamanın verilerinizi kendi Google Drive hesabınızda `LifeOS_AutoSync_Data.json` adıyla güvenle saklaması için:

1. **script.google.com** adresine gidip sol üstten **"+ Yeni Proje"** oluşturun ve editördeki mevcut kodu silin.

2. Uygulama içerisindeki **Ayarlar > 2. Tab (Bulut & Sync)** ekranındaki kodu kopyalayıp editöre yapıştırın.

3. Kodun 2. satırındaki `const SECRET_KEY = "123456";` kısmına kendi belirlediğiniz gizli parolayı yazıp üstteki **💾 Kaydet (Ctrl+S)** butonuna basın.

4. Üst araç çubuğundaki **`▷ Çalıştır (Run)`** butonuna tıklayın. Açılan pencerede **İzinleri İncele → Google Hesabınızı Seçin → Gelişmiş (Advanced) → '... (güvenli değil) sayfasına git' → İzin Ver (Allow)** adımlarını onaylayın.

5. Sağ üstteki mavi **"Dağıt" (Deploy) → "Yeni dağıtım" (New deployment)** butonuna basın. Sol üstteki çark (⚙️) ikonundan **"Web uygulaması"** seçin:

   * **Yürüten (Execute as):** *Ben (Me)*

   * **Erişimi olanlar (Who has access):** *Herkes (Anyone)*

   * **Dağıt** butonuna tıklayın.

6. Size verilen `https://script.google.com/macros/s/.../exec` linkini uygulamanın **Web App URL** kutusuna, belirlediğiniz parolayı da **🔒 Gizli Güvenlik Anahtarı** kutusuna yapıştırın.

> **💡 İpucu:** Script kodunda veya parolanızda değişiklik yaparsanız, Google'ın güncel kodu çalıştırması için Apps Script editöründe sağ üstten **Dağıt → Dağıtımları yönet → ✏️ Kalem (Düzenle) → Sürüm: "Yeni sürüm" → Dağıt** yapmanız gerekir.

[Yukarı Çık ⬆️](#-language--dil-seçimi)

# 🇬🇧 English

[Türkçe Versiyon 🇹🇷](#-türkçe)

**Life OS** is an all-in-one, gamified personal operating system built to **Progressive Web App (PWA)** standards. It unifies daily habit tracking, evidence-based strength & posture programs with embedded YouTube video demonstrations, body composition modeling, reading logs, and deep work timers into an engaging RPG-style progression.

Zero build steps, zero `node_modules`, and zero external runtime dependencies. Open it directly in your browser or deploy it to GitHub Pages for instant PWA installation on Android, Samsung Galaxy, or iOS devices.

## 🎯 Key Features

### 1. 📋 Daily Habit Tracking & Full Customization (CRUD)

* **12 Foundational Habits + Unlimited Custom Habits:** Pre-loaded with 12 science-backed habits (early wake-up, workouts, reading, time-blocking, dopamine detox, hydration, deep work, and posture stretches). Use the **`+ Habit`** and **`✏️`** buttons to add, edit, or delete habits with custom RPG categories (`STR`, `INT`, `WILL`, `VIT`) and XP rewards.

* **Streak Engine & Future-Date Guard:** Automatically calculates consecutive daily streaks, provides a 1-tap **`Today`** jump button when browsing past logs, and prevents accidental checkmarks on future dates.

* **Wellness Sliders:** Log daily mood (1–5 scale) and sleep duration (hours) to monitor neurological and physical recovery.

### 2. 🏋️‍♂️ Evidence-Based Workout & Posture Guide with Embedded YouTube Player

* **7 Built-In Science-Backed Programs:**

  1. **💪 3-Day Beginner Full Body:** Stimulates all major muscle groups 3× per week with balanced volume.

  2. **🔥 Tabata Round HIIT & Conditioning:** Dr. Izumi Tabata's 20s work / 10s rest × 8 rounds (4-min block) metabolic protocol.

  3. **⚡ SOTA (State of the Art) Abs & Core:** 360-degree core hypertrophy combining loaded spinal flexion, oblique rotation, and stomach vacuum holds.

  4. **🔥 Jeff Nippard — Push / Pull / Legs (PPL):** High-threshold hypertrophy split organized into Pull, Legs, and Push days.

  5. **⚡ StrongLifts 5×5:** Linear strength progression across foundational barbell compounds (Squat, Bench Press, OHP, Pendlay Row, RDL).

  6. **🏋️ 3-Day Functional & Posture Routine:** Spine-friendly unilateral and anti-rotational training for individuals managing lordosis, mild scoliosis, or rounded shoulders.

  7. **🧘 Upper Stretch / 🦵 Lower Stretch / 🦴 Pelvic Tilt & Lordosis (APT) Protocols:** Dedicated 15–20 min full routines and 5-min rapid modes to correct Forward Head Posture, Rounded Shoulders, tight hamstrings, and Anterior Pelvic Tilt.

* **🎬 Embedded YouTube Video Player (Anti-Error 153 HTTPS Relay):**

  * Tap any exercise row to expand an inline **16:9 embedded YouTube player** without leaving the app.

  * **Timestamped Cues (`⏱️ 00:15 — 00:50`):** Videos automatically start and end at the exact instructional demonstration window.

  * **HTTPS Relay Engine:** Routed through `cdn.embedly.com` HTTPS Relay so embedded videos play smoothly across local `file:///` HTML files, mobile WebViews, and GitHub Pages without triggering YouTube **Error 153**.

* **➕ Full Routine & Exercise Editor + 🌐 Auto-Translator:**

  * **`➕ New` / `✏️ Edit`:** Create custom workout programs, type or pick any emoji icon, add/rename/delete training days, and customize the **3 Fixed Scientific Sections** (*Program Purpose*, *Execution Methodology*, *Progression Protocol*).

  * **🌐 1-Click Free Translation (TR ↔ EN):** Translate routine descriptions and exercise form notes in place with the **`🌐 Translate`** button or automatically upon saving, while keeping exercise titles in canonical international English terminology.

### 3. 📏 Body Measurements, PR Manager & 4 Scientific Body Fat Formulas

* **PR & Lift Tracker:** Automatically populates exercises from all active routines plus a **`✍️ Type Custom Exercise...`** option, calculates estimated **1RM**, and supports full inline editing (`✏️`) and deletion (`✕`).

* **Manual Input OR 4 Scientific Body Fat Equations:**

  1. **U.S. Navy Circumference Formula:** Anthropometric gold standard using height, neck, waist, and hip measurements.

  2. **YMCA Equation:** Practical body fat estimation from weight and waist circumference.

  3. **CUN-BAE Clinical Equation:** Validated equation factoring BMI, age, and biological sex.

  4. **Deurenberg BMI Formula:** Classic clinical equation using BMI, age, and sex multipliers.

* **Profile Persistence & Live Metrics:** Remembers your height, age, and sex across sessions, calculates Body Fat %, Lean Body Mass (LBM kg), and archives waist/neck/hip, shoulder/chest, and left/right arm symmetry with full edit/delete support.

### 4. 📚 Completed Books Log (Bookworm Tracker)

* Tap **"📚 Book Done"** next to the daily Reading habit to log book title, author, page count, start & finish dates (auto-calculating reading duration in days), and key takeaways.

* Chronologically archived in the **📊 Analytics** tab and directly fuels the *Bookworm & Scholar* 7-tier badge.

### 5. ⏱️ Background-Safe Multi-Round Pomodoro & Daily Routines

* **Wall-Clock Synced Timer:** 25-minute focus sprints and 5-minute recovery breaks are anchored to `Date.now()`, ensuring accurate countdowns even when the browser tab is backgrounded or the phone screen is locked.

* **Customizable Life Routines:** Rename the 4 core daily routine tabs (*🌅 Morning Routine*, *⚡ Deep Work*, *🔋 Afternoon Reset*, *🌙 Evening Wind-Down*) and add, edit, or delete individual step cards.

### 6. 🏆 RPG Character Stat Balance & 7-Tier Ranked Badges

* **4 Core Attributes (STR, INT, WILL, VIT):** Dynamic radar chart displaying both daily balance percentages (`%`) and cumulative numeric stat points (`140 Pts`).

* **7-Tier Progression Hierarchy & Mini Bar Charts:**

  * 🥉 Bronze → 🥈 Silver → 🥇 Gold → 🏆 Platinum → 💎 Diamond → 🔥 Elite → 👑 Legendary

  * Every badge card features a 7-step visual bar chart tracking long-term milestones (`5 → 12 → 24 → 40 → 60 → 85 → 120`).

### 7. 🎨 8 Custom Themes & 100% Bilingual Support

* **Themes:** 🌑 AMOLED Dark, ☀️ Light Mode, 🌸 Cotton Candy (Pastel Pink), 🔮 Cyberpunk Neon, 🌲 Emerald Forest, 🌅 Sunset Mocha & Gold, 🌊 Deep Ocean & Coral, ❄️ Nordic Slate & Ice.

* **Bilingual:** Instant 1-click switch between 100% Turkish 🇹🇷 and English 🇬🇧 across all menus, workouts, form notes, and guides.

### 8. ☁️ Bidirectional Cloud Sync & Security

* **Google Drive Auto-Sync + 🔒 Secret Key Protection:** Automated webhook backup to your personal Google Drive (`LifeOS_AutoSync_Data.json`) protected by your custom passphrase.

* **GitHub Gist Sync:** Private cloud backup via GitHub Personal Access Tokens (`ghp_...`).

* **Offline JSON Export / Import & Granular Resets:** Export/import full `.json` backups anytime, or selectively restore default Habits, Programs, or Routines from Settings.

## 📱 PWA Installation & Mobile Setup

By browser security design (Chrome, Samsung Internet, and Safari), **PWA Add to Home Screen** requires a secure **HTTPS connection**.

Included PWA files:

* `index.html` / `LifeOS_Gamified_Habit_Gym_Tracker.html` (Main application)

* `manifest.json` (Web App Manifest with standalone display and theme settings)

* `sw.js` (Offline cache and Service Worker)

* `icon-192.png` & `icon-512.png` (High-resolution AMOLED dark and gold ⚡ app icons)

### 🚀 1-Minute GitHub Pages HTTPS Deployment:

1. Push this repository to your GitHub account.

2. Go to **Settings → Pages** in your repository.

3. Select **Branch:** `main` (or `master`) and `/ (root)`, then click **Save**.

4. Open `https://<your-username>.github.io/<repo-name>/` on your phone:

   * **Samsung Internet / Chrome:** Tap the install prompt in the address bar or tap **"Install App"** inside Settings.

   * **Safari (iOS):** Tap Share → Select **"Add to Home Screen"**.

## ☁️ Google Drive Auto-Sync Setup (6 Easy Steps)

1. Go to **script.google.com**, click **"+ New Project"**, and delete any default code.

2. Copy the Apps Script code from **Settings > Tab 2 (Cloud & Sync)** inside the app and paste it into the editor.

3. On line 2, set your secret password: `const SECRET_KEY = "123456";` and click **💾 Save (Ctrl+S)**.

4. Click **`▷ Run`** in the top toolbar and authorize Drive access: **Review Permissions → Select Account → Advanced → Go to project (unsafe) → Allow**.

5. Click **Deploy → New deployment** at the top right, select **Web App**, set **Execute as:** *Me* and **Who has access:** *Anyone*, then click **Deploy**.

6. Paste the generated `https://script.google.com/macros/s/.../exec` Web App URL and your `SECRET_KEY` into the app's sync settings.

> **💡 Note:** Whenever you modify the script or change your `SECRET_KEY`, publish a new version via **Deploy → Manage deployments → ✏️ Edit → Version: "New version" → Deploy**.

## 📄 License

This project is open-source under the [MIT License](https://www.google.com/search?q=LICENSE).

[Back to Top ⬆️](#-language--dil-seçimi)