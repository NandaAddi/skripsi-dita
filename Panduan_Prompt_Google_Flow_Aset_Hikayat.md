# PANDUAN MASTER PROMPT GOOGLE FLOW: ASET E-MODUL HIKAYAT SA-IJAAN
## Pedoman Konsistensi Visual Karakter, Latar, Gaya Seni, dan Video Veo
**Platform Target**: Google Flow (Creative Studio Labs: Imagen 3 & Veo)  
**Tema Estetika**: *Semi-Realistic Classical Nusantara Folklore Oil Painting*  
**Palet Dominan**: Deep Ocean Teal (`#0F2C4C`), Antique Royal Gold (`#C89B3C`), Warm Ivory Parchment (`#F8F4EB`), dan Terracotta/Sepia Ink (`#2A2421`)  
**Tujuan Modul**: Ilustrasi Halaman & Media Interaktif Flipbook Heyzine (Portrait A4 & Video Embed)

---

## 1. SISTEM KONSISTENSI GOOGLE FLOW (STYLE & CHARACTER ANCHORS)

Agar seluruh aset yang dihasilkan di Google Flow memiliki **gaya visual yang seragam 100%** (tidak belang-belang antara satu bab dengan bab lain), gunakan **formula baku** di bawah ini:

### 1.1 Formula Baku Gaya Seni (Master Style Capsule)
Setiap prompt gambar di Google Flow **WAJIB** menyertakan blok style capsule berikut di bagian akhir kalimat:

> `[STYLE ANCHOR]: Semi-realistic classical Nusantara folklore oil painting on aged warm ivory parchment texture, fine expressive impasto brushstrokes, masterpiece maritime epic illustration, dignified Indonesian mythology aesthetic, chiaroscuro lighting, warm golden hour rays contrasting with deep oceanic teal (#0F2C4C) and burnished antique gold (#C89B3C) accents, atmospheric sea mist, fine art archival quality, 8k resolution, no modern elements, no anime style, no cartoon flat 2D.`

---

### 1.2 Token Karakter Baku (Character Sheet Tokens)
Jangan mengubah deskripsi fisik tokoh saat berpindah bab. Gunakan deskripsi baku berikut agar wajah, pakaian, dan proporsi tokoh konsisten:

#### A. Token Karakter: DATU MABRUR
> `[CHARACTER: DATU MABRUR]: An elderly, dignified Indonesian ascetic hermit sage named Datu Mabrur, weathered noble Javanese-Banjar facial features with calm wise gentle eyes, long flowing silver-white beard and moustache, silver-white long hair tied in a neat traditional ascetic topknot, wearing a simple unadorned dark indigo-brown handwoven ascetic linen cloth draped across his shoulder and wrapped at waist, barefoot, serene meditative demeanor radiating quiet inner spiritual aura.`

#### B. Token Karakter: RAJA IKAN TODAK
> `[CHARACTER: RAJA IKAN TODAK]: A colossal mythical Indo-Pacific sawfish-swordfish sovereign named Raja Ikan Todak, iridescent shimmering turquoise and deep cobalt-blue scales with pearl-silver belly, magnificent elongated sword-like snout lined with razor-sharp translucent saw teeth, glowing majestic amber-gold eyes filled with royal intelligence, proud spiny dorsal fin rimmed with bioluminescent golden light, powerful muscular marine sovereign silhouette.`

---

### 1.3 Panduan Mengunci Karakter Menggunakan Fitur "Ingredients" di Google Flow

Google Flow memiliki fitur canggih bernama **"Ingredients" (Asset / Reference Locker)**:
1. **Langkah 1 (Hasilkan Gambar Induk / Anchor Reference)**:
   * Buat adegan pertama (misalnya **ASET 01: Cover Datu Mabrur** atau **ASET 03: Raja Ikan Todak Menyerang**).
   * Pilih hasil generasi terbaik yang paling sesuai dengan imajinasimu.
2. **Langkah 2 (Jadikan Ingredient)**:
   * Klik ikon **"Add to Ingredients"** (atau simpan ke panel *Asset Library* proyekmu di Google Flow).
   * Beri label: `@DatuMabrur` untuk tokoh Datu Mabrur, dan `@RajaTodak` untuk Raja Ikan Todak.
3. **Langkah 3 (Generasi Adegan Berikutnya)**:
   * Pada saat mem-prompt adegan bab selanjutnya, panggil tag `@DatuMabrur` dan `@RajaTodak` di dalam kotak prompt Google Flow.
   * Google Flow secara otomatis akan mempertahankan kontur wajah, jenggot putih, pakaian bertapa, dan anatomi ikan todak persis seperti gambar acuan pertama.

---

## 2. MASTER PROMPT 8 ILUSTRASI ADEGAN NARATIF (IMAGEN 3)

Seluruh prompt di bawah ini telah disesuaikan dengan rasio vertikal buku A4 Portrait (`--ar 3:4` atau mode *Portrait* di Google Flow).

---

### ASET 01: COVER UTAMA (SAMPUL DEPAN MODUL)
* **Penempatan**: Halaman 1 (Cover Luar Modul)
* **Subjek**: Datu Mabrur duduk bersila bermeditasi di atas batu karang runcing di tengah samudra berbadai dahsyat, menatap ke arah berkas cahaya ilahi yang menyinari siluet pulau mistis di cakrawala.
* **Prompt Google Flow**:
```text
A majestic epic composition of [CHARACTER: DATU MABRUR] sitting serenely in deep cross-legged meditation upon a sharp jagged coral reef rock in the middle of a tempestuous ocean, huge foaming ocean waves crashing harmlessly around the rock, atmospheric sea spray, a sacred golden divine ray of sunlight piercing through dark dramatic storm clouds onto the distant horizon revealing the faint silhouette of a promised fertile island, wide dramatic eye-level perspective, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 02: BAB 1 – AWAL PERJALANAN (PERTAPAAN DI ANTARA DUA SELAT)
* **Penempatan**: Halaman 6 (Pembuka Chapter 1)
* **Subjek**: Datu Mabrur bermeditasi khusyuk dalam keheningan saat senja temaram di Selat Laut dan Selat Makassar. Suasana hening dan mistis.
* **Prompt Google Flow**:
```text
Atmospheric contemplative scene of [CHARACTER: DATU MABRUR] meditating in silence on a wide flat ocean reef stone, set between the calm waters of Strait of Laut and Strait of Makassar during a peaceful dusk, glowing crimson and amber sunset reflections ripples across the ocean surface, gentle sea breeze swaying his white beard, a subtle golden aura enveloping his body, tranquility and unshakable determination, medium-wide cinematic shot, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 03: BAB 2 – SERANGAN IKAN TODAK (AMUKAN PRAJURIT SAMUDRA)
* **Penempatan**: Halaman 10 (Pembuka Chapter 2)
* **Subjek**: Pertarungan laut dinamis; Raja Ikan Todak melompat tinggi dari dalam gelombang ombak gelap, moncong pedang bergeriginya mengarah tajam ke Datu Mabrur yang tetap bersila tenang menangkisnya dengan perisai batin.
* **Prompt Google Flow**:
```text
High dynamic action scene, [CHARACTER: RAJA IKAN TODAK] leaping violently out of a dark roaring sea wave into the air, its serrated snout aimed directly at [CHARACTER: DATU MABRUR] sitting impassively on the coral rock, Datu Mabrur calmly raises one bare palm without opening his eyes creating a shimmering translucent golden spiritual barrier that repels the ferocious sea creature, water droplets frozen mid-air, dynamic diagonal composition, dramatic low-angle shot, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 04: BAB 2 (ADEGAN 2) – TAKLUKNYA RAJA IKAN TODAK
* **Penempatan**: Halaman 11 (Ilustrasi Naskah Cerita Bab 2)
* **Subjek**: Raja Ikan Todak tergeletak lemah terjepit di sela-sela batu karang tajam yang basah, megap-megap kehabisan napas, menatap memelas kepada Datu Mabrur yang berdiri di depannya. Di kejauhan, ribuan moncong ikan todak menyembul dari air laut mengelilingi karang.
* **Prompt Google Flow**:
```text
A poignant dramatic scene, [CHARACTER: RAJA IKAN TODAK] lying exhausted and wounded, trapped tightly between jagged dark coral rocks above water line, gills gasping for air, looking up with humbled pleading amber eyes, [CHARACTER: DATU MABRUR] stands before the fish looking down with deep calm compassion, in the ocean background thousands of smaller sawfish snouts poke out of the foaming water anxiously watching their king, emotional tension, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 05: BAB 3 – MUKJIZAT KASIH SAYANG & PENYEMBUHAN
* **Penempatan**: Halaman 14 (Pembuka Chapter 3)
* **Subjek**: Datu Mabrur berlutut lembut dengan kedua tangan menyentuh kulit Raja Ikan Todak. Cahaya hangat keemasan memancar menyembuhkan luka-luka di tubuh ikan hingga sisiknya kembali berkilau indah.
* **Prompt Google Flow**:
```text
A deeply moving spiritual scene of divine compassion, [CHARACTER: DATU MABRUR] kneeling gently beside [CHARACTER: RAJA IKAN TODAK] on the coral ledge, placing his warm weathered hands upon the fish's wounded body, brilliant warm healing emerald and golden light radiating from his touch, closing all wounds and restoring the glistening smooth texture of the fish scales, peaceful serene sunset over the ocean, intimate sacred bond between human sage and sea creature, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 06: BAB 3 (ADEGAN 2) – PERJANJIAN SUCI "SA-IJAAN"
* **Penempatan**: Halaman 15 (Ilustrasi Naskah Cerita Bab 3)
* **Subjek**: Datu Mabrur melepaskan Raja Ikan Todak kembali ke dalam laut. Ikan Todak melompat gembira berputar di atas permukaan air laut yang tenang, diiringi ribuan ikan laut yang bersorak riang merayakan perjanjian Sa-Ijaan.
* **Prompt Google Flow**:
```text
Joyous celebratory maritime scene, [CHARACTER: DATU MABRUR] standing on the edge of the coral rock smiling warmly with open hands, watching [CHARACTER: RAJA IKAN TODAK] leaping high into the air joyfully re-entering the turquoise ocean water, surrounded by thousands of silvery fish jumping in unison creating ripples and sparkling foam under golden morning light, symbolizing the sacred eternal pact of mutual help, uplifting atmosphere, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 07: BAB 4 – JANJI MENJADI KENYATAAN (PENGANGKATAN PULAU DARI DASAR SAMUDRA)
* **Penempatan**: Halaman 18 (Pembuka Chapter 4)
* **Subjek**: Sudut pandang bawah laut menakjubkan (*underwater panoramic*); jutaan makhluk samudra (paus raksasa, lumba-lumba, penyu, kawanan ikan todak) bersatu padu menyangga dan mendorong dasar daratan tanah berbatu ke atas permukaan laut, disinari berkas cahaya matahari yang menembus kedalaman air.
* **Prompt Google Flow**:
```text
An awe-inspiring epic underwater perspective looking upward, millions of diverse sea creatures including giant blue whales, sea turtles, manta rays, and thousands of sawfish led by [CHARACTER: RAJA IKAN TODAK], swimming in synchronized harmony pushing and hoisting a colossal ancient landmass from the abyssal sea floor up toward the sunlit water surface, bubbles, turbulent currents, glowing god-rays filtering through the ocean depths, magnificent collective solidarity, epic scale, [STYLE ANCHOR] --ar 3:4
```

---

### ASET 08: BAB 5 – PULAU HALIMUN NAN SUBUR MAKMUR (PULAU LAUT)
* **Penempatan**: Halaman 22 (Pembuka Chapter 5)
* **Subjek**: Panorama lanskap megah Pulau Halimun (Pulau Laut Kotabaru) yang baru timbul di tengah laut jernih membiru, perbukitan hijau subur, ngarai dan lembah nan permai, diselimuti kabut putih tipis (halimun) di bawah siraman cahaya fajar keemasan.
* **Prompt Google Flow**:
```text
Breathtaking panoramic aerial landscape painting of the newly emerged island of Pulau Halimun (Pulau Laut), a fertile paradise island rising gracefully out of the turquoise and ultramarine South Kalimantan sea, lush emerald tropical hills, cascading waterfalls, mist-shrouded green valleys wrapped in gentle morning white mist, radiant golden dawn sunlight illuminating the pristine shores, Datu Mabrur seen as a tiny reverent figure kneeling in gratitude on the highest mountain peak, paradise on earth, [STYLE ANCHOR] --ar 3:4
```

---

## 3. MASTER PROMPT 2 VIDEO SINEMATIK VEO (GOOGLE FLOW VIDEO)

Gunakan prompt ini pada mode **Text-to-Video** atau **Frame-to-Video (Ingredients-to-Video)** di Google Flow menggunakan model Google Veo. Rasio format video disarankan **16:9** agar proporsional di dalam bingkai pemutar video flipbook Heyzine.

---

### ASET 09: VIDEO VEO 01 – DETIK-DETIK SERANGAN IKAN TODAK
* **Penempatan**: Halaman 10 (Frame Pemutar Video Bab 2 Heyzine)
* **Durasi Target**: 5 – 10 detik (Seamless Loop)
* **Prompt Video Google Veo**:
```text
Cinematic slow-motion shot, dramatic turbulent ocean waves churning violently around a dark jagged coral rock. Suddenly, a giant mythical sawfish with shimmering turquoise scales and razor-sharp snout leaps explosively out of the white foam toward an ascetic sage sitting peacefully in meditation. A luminous golden spiritual shockwave pulses outward from the sage, deflecting the fish mid-air into a spectacular cascade of glistening water droplets, camera slowly orbits the sage, hyper-realistic fluid physics, fantasy maritime legend aesthetic, 4k resolution --ar 16:9
```

---

### ASET 10: VIDEO VEO 02 – TIMBULNYA DARATAN DARI DASAR SAMUDRA
* **Penempatan**: Halaman 18 (Frame Pemutar Video Bab 4 Heyzine)
* **Durasi Target**: 5 – 10 detik (Seamless Loop)
* **Prompt Video Google Veo**:
```text
Epic cinematic drone shot moving over a churning ocean at sunrise. The deep sea rumbles as a massive lush green landmass rises steadily from beneath the ocean surface, cascading water torrents pouring down fresh rocky cliffs into the sea. Thousands of silver and blue fish leap along the newly formed shores in celebration, revealing pristine tropical hills emerging into warm golden morning rays, atmospheric white mist rolling over the new island, photorealistic cinematic VFX --ar 16:9
```

---

## 4. MASTER PROMPT 2 ELEMEN ORNAMEN GRAFIS BANJAR (PNG TRANSPARAN)

Gunakan prompt ini untuk menghasilkan elemen grafis dekorasi layout Canva/Figma (Background Transparan / Isolated on White).

---

### ASET 11: BORDER SUDUT UKIRAN TRADISIONAL BANJAR
* **Penempatan**: Halaman 1 s.d. 30 (Keempat Sudut Bingkai Manuskrip Canva)
* **Deskripsi**: Ornamen sudut khas rumah adat Banjar (motif Tali Bapintal berpadu Pucuk Rebung) bersepuh emas kuno antik dengan sentuhan patina.
* **Prompt Google Flow**:
```text
An intricate corner border decorative ornament, traditional South Kalimantan Banjar wood carving pattern featuring Tali Bapintal spiral braid and Pucuk Rebung floral motifs, crafted in antique burnished royal gold with subtle dark bronze patina highlights, filigree craftsmanship, isolated on pure white background, flat lay vector-style clean silhouette, symmetrical corner design, master artisan quality --ar 1:1
```

---

### ASET 12: STEMPEL SEGAL KERAJAAN SA-IJAAN KOTABARU
* **Penempatan**: Halaman 3 (Daftar Isi), Halaman 23, dan Halaman 30
* **Deskripsi**: Medali segel lilin/logam kuno berbentuk lingkaran berukir sepasang ikan todak melengkung berhadapan di atas gelombang ombak samudra, dengan tulisan kaligrafi klasik "SA-IJAAN".
* **Prompt Google Flow**:
```text
An ancient royal wax seal medallion, circular vintage stamp crafted in embossed antique gold and deep crimson sealing wax, featuring two symmetrical mythical sawfish leaping gracefully facing each other over stylized swirling ocean waves, banner beneath engraved with the classic inscription 'SA-IJAAN', intricate Banjar ornamental filigree rim, isolated on pure white background, macro detail, regal historical emblem --ar 1:1
```

---

## 5. REKAPITULASI CHECKLIST PENAMAAN FILE UNTUK CANVA & HEYZINE

| No | Kode Aset | Nama File Target | Format | Dimensi / Rasio | Penempatan di Modul |
|---|---|---|---|---|---|
| 1 | IMG-01 | `IMG_Cover_DatuMabrur.png` | PNG | 2480 x 3508 px (3:4) | Halaman 1 (Cover Utama) |
| 2 | IMG-02 | `IMG_Bab1_Pertapaan_Selat.png` | PNG | 2480 x 3300 px (3:4) | Halaman 6 (Pembuka Bab 1) |
| 3 | IMG-03 | `IMG_Bab2_Serangan_Todak.png` | PNG | 2480 x 3300 px (3:4) | Halaman 10 (Pembuka Bab 2) |
| 4 | IMG-04 | `IMG_Bab2_Todak_Takluk.png` | PNG | 2000 x 1500 px (4:3) | Halaman 11 (Teks Cerita Bab 2) |
| 5 | IMG-05 | `IMG_Bab3_Penyembuhan_Luka.png` | PNG | 2480 x 3300 px (3:4) | Halaman 14 (Pembuka Bab 3) |
| 6 | IMG-06 | `IMG_Bab3_Ikrar_SaIjaan.png` | PNG | 2000 x 1500 px (4:3) | Halaman 15 (Teks Cerita Bab 3) |
| 7 | IMG-07 | `IMG_Bab4_Angkat_Pulau.png` | PNG | 2480 x 3300 px (3:4) | Halaman 18 (Pembuka Bab 4) |
| 8 | IMG-08 | `IMG_Bab5_Pulau_Halimun.png` | PNG | 2480 x 3300 px (3:4) | Halaman 22 (Pembuka Bab 5) |
| 9 | VID-01 | `VID_Veo_Serangan_Todak.mp4` | MP4 | 1920 x 1080 px (16:9) | Halaman 10 (Widget Video Heyzine) |
| 10 | VID-02 | `VID_Veo_Bangkitnya_Pulau.mp4` | MP4 | 1920 x 1080 px (16:9) | Halaman 18 (Widget Video Heyzine) |
| 11 | ORN-01 | `ORN_Border_Sudut_Banjar.png` | PNG (Transparan) | 1000 x 1000 px (1:1) | Semua Sudut Halaman (Canva) |
| 12 | ORN-02 | `ORN_Segel_SaIjaan.png` | PNG (Transparan) | 1000 x 1000 px (1:1) | Hal 3, 23, & 30 (Cap Modul) |

---
*Dokumen ini dirancang khusus untuk memandu pembuatan aset terpadu di Google Flow Studio agar menjamin keseragaman visual 100% pada E-Modul Heyzine.*
