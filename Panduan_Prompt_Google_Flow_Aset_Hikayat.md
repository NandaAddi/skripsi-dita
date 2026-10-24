# PANDUAN MASTER PROMPT GOOGLE FLOW: ASET E-MODUL HIKAYAT SA-IJAAN
## Pedoman Konsistensi Visual: Gaya "Fun Whimsical 2D Storybook Cartoon"
**Platform Target**: Google Flow (Creative Studio Labs: Imagen 3 & Veo)  
**Tema Estetika**: *Fun Whimsical 2D Animated Storybook Cartoon* (Perpaduan Dongeng Cerita Rakyat Nusantara dengan Sentuhan Animasi Layar Lebar 2D ala *Klaus*, Keajaiban Visual *Cartoon Saloon*, dan Kehangatan Kartun Klasik Disney 2D)  
**Karakter Visual**: Sangat ekspresif, ceria, dinamis, bersahabat, memikat bagi siswa SMA (Fase E), bebas dari rasa takut/seram (*zero menace, zero gore*), dan bebas dari kekakuan 3D CGI (*zero 3D uncanny valley*).  
**Palet Dominan**: Ocean Deep Indigo (`#2A4D69`), Electric Turquoise (`#06D6A0`), Sunny Honey Amber (`#E9C46A`), Warm Peach-Tan (`#F4B382`), dan Soft Cloud Cream (`#FDFBF7`).

---

## 1. SISTEM KONSISTENSI GOOGLE FLOW (STYLE & CHARACTER ANCHORS)

Agar seluruh 12 aset yang dihasilkan di Google Flow memiliki **keseragaman visual 100%**, gunakan formula baku di bawah ini pada setiap pembuatan prompt:

### 1.1 Formula Baku Gaya Seni (Master Style Capsule)
Setiap prompt gambar di Google Flow **WAJIB** menyertakan blok formula baku ini di bagian akhir deskripsi:

> `[STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON]: Vibrant fun 2D whimsical storybook cartoon animation style, inspired by Klaus, Cartoon Saloon, and classic 2D hand-drawn feature animation, highly expressive and lively character design, playful fluid shapes and dynamic curved silhouettes, charming facial expressions bursting with personality and warmth, clean stylized line art with beautiful soft painterly lighting, rich cheerful oceanic color palette with bright cerulean blue, sparkling turquoise, sunny golden amber, and soft warm cream, delightfully heartwarming, family-friendly, full of visual joy, zero 3d cgi render, zero uncanny photorealism, zero corporate flat vector, zero grimdark or scary grotesque monster elements.`

### 1.1b Aturan Negatif Baku (Universal Negative Anchors)
Wajib disalin ke kolom **Negative Prompt** di Google Flow / Midjourney / Flux untuk mengeliminasi kesan dewa Yunani dan 3D CGI:
> `[UNIVERSAL NEGATIVE ANCHORS]: greek god, zeus, poseidon, roman philosopher, greek toga, chiton, himation, draped greek cloth, bare chest, shirtless, caucasian, western face, blonde hair, greek mythology, laurel wreath, marble statue, roman drapery, photorealistic, 3d cgi render, plastic shiny skin, octane render, uncanny valley, dull muted colors, dark grimdark fantasy, horror, scary, fierce angry monster, sharp terrifying teeth, bleeding wounds, mutilated, grotesque, distorted anatomy, extra limbs, extra fingers, flat boring clip-art.`

---

### 1.2 Token Karakter Baku (Character Sheet Tokens)
> [!NOTE]
> Spesifikasi lengkap anatomi, palet HEX, lembar ekspresi, dan turnaround model sheet multi-sudut untuk setiap karakter dapat dilihat pada dokumen induk: [Sistem Desain Karakter Resmi: Fun 2D Whimsical Storybook Cartoon](file:///d:/DYTA%20JOKI/Sistem_Desain_Karakter_2D_Oil_Painting.md).

#### A. Token Karakter: DATU MABRUR (Otentik Indonesia Banjar - Fun 2D Cartoon)
> `[CHARACTER: DATU MABRUR]: An adorable, wise, and lovable Indonesian elder sage named Datu Mabrur from South Kalimantan folklore, fun 2D animated storybook cartoon style, warm Southeast Asian golden-tan complexion with rosy cheeks, merry twinkling eyes with happy smile crinkles, neat silver-white mustache and beard, wearing a traditional South Kalimantan Banjar headdress (Laung Banjar / destar) with subtle golden Sasirangan motifs, dressed in a modest indigo-blue traditional Banjar tunic shirt (baju kurung teluk belanga) and a vibrant honey-amber Sasirangan sarung wrap around his waist, barefoot, radiating an inviting joyful golden aura, zero greek toga, zero bare chest, zero caucasian features.`


#### B. Token Karakter: RAJA IKAN TODAK (Fun 2D Cartoon Style)
> `[CHARACTER: RAJA IKAN TODAK]: A charismatic and agile mythical sawfish king named Raja Ikan Todak, fun 2D animated cartoon design with sleek hydrodynamic acrobatic curves, vibrant electric turquoise and deep royal cobalt scales with a soft vanilla-cream underbelly, an elegant sculpted jade-and-pearl saw rostrum with smooth glowing rounded teeth (charming and heroic, not menacing), large expressive intelligent golden eyes, royal fin crest lined with sunny gold bioluminescent shimmer.`

#### C. Token Karakter: KAWANAN PRAJURIT TODAK KECIL (Mini Sawfish Squad)
> `[CHARACTER: MINI TODAK SQUAD]: A school of charming and humorous small seafoam-teal sawfish companions with big round curious cartoon eyes and cute rounded snouts, swimming and leaping playfully in synchronized arcs.`

#### D. Token Karakter: BIOTA LAUT RAKSASA (Guardian Sea Giants)
> `[CHARACTER: SEA GIANTS]: A gigantic, chubby smiling blue whale with squinting happy eyes and a playful water spout, accompanied by a wise friendly ancient mossy sea turtle and cheerful gliding manta rays working together joyfully.`

---

### 1.3 Cara Mengunci Karakter via Fitur "Ingredients" di Google Flow
1. **Buat Gambar Acuan Pertama Menggunakan Model Sheet**:
   * Generate gambar acuan menggunakan prompt model sheet dari [Sistem Desain Karakter](file:///d:/DYTA%20JOKI/Sistem_Desain_Karakter_2D_Oil_Painting.md) (Bab 2.6 untuk Datu Mabrur dan Bab 3.5 untuk Raja Todak).
   * Pilih hasil generasi multi-angle terbaik yang paling Anda sukai.
2. **Kunci Karakter sebagai Ingredient**:
   * Klik menu **"Add to Ingredients"** pada gambar terpilih.
   * Beri nama tag: `@DatuMabrurCartoon2D` dan `@RajaTodakCartoon2D`.
3. **Gunakan pada Generasi Berikutnya**:
   * Saat mem-prompt bab-bab selanjutnya (ASET 01 s.d. ASET 08), sertakan tag `@DatuMabrurCartoon2D` atau `@RajaTodakCartoon2D`. Google Flow akan mengunci proporsi wajah ramah sang Datu dan sisik toska ceria Raja Todak secara konsisten di semua adegan!

---

## 2. MASTER PROMPT 5 COVER BAB (CHAPTER DIVIDERS - RASIO 3:4)

Setiap Cover Bab dirancang sebagai halaman poster vertikal penuh bergaya *2D Whimsical Storybook Animation* berpadu estetika sastra klasik Banjar. Setiap karya menyisakan **ruang kosong di bagian atas (*negative space*)** untuk tipografi nomor dan judul bab beraksen emas (*Royal Gold* `#C89B3C`), berbingkai ornamen Sasirangan halus di tepinya.

---

### CVR 01: COVER BAB 1 – TAPA DI KARANG SAMUDRA
* **Penempatan**: Halaman 6 (Cover Bab 1)
* **Subjek**: Datu Mabrur bersila tenang di atas bongkahan batu karang hitam di tengah lautan luas nan damai saat fajar menyingsing. Di belakangnya terbentang langit fajar jingga keemasan bertabur partikel cahaya berkilau, dengan riak ombak toska lembut melingkar. Area atas lapang untuk judul "BAB 1: PERTAPAAN DI SELAT LAUT".
* **Prompt Google Flow (Imagen 3)**:
```text
A majestic, serene full-page book chapter cover illustration in fun 2D storybook cartoon animation style, featuring [CHARACTER: DATU MABRUR] sitting cross-legged in deep noble meditation atop a smooth dark ocean reef stone at glorious golden sunrise, peaceful turquoise sea ripples reflecting honey-amber dawn light, soft glowing spiritual aura around the sage, thoughtful composition with spacious airy pastel sky at the top creating ample clean negative space for golden chapter title typography, framed by subtle traditional Banjar Sasirangan motifs along the borders, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### CVR 02: COVER BAB 2 – AMUKAN PRAJURIT SAMUDRA
* **Penempatan**: Halaman 11 (Cover Bab 2)
* **Subjek**: Kemunculan akrobatik Raja Ikan Todak dari deburan ombak raksasa berputar (*dramatic tidal crest*). Moncong gergaji zamrud menyala keemasan beradu dengan pendaran perisai pelindung Datu Mabrur. Suasana dramatis namun bersahabat, dengan langit toska keunguan di bagian atas yang menyisakan ruang tipografi judul "BAB 2: AMUKAN PRAJURIT SAMUDRA".
* **Prompt Google Flow (Imagen 3)**:
```text
A thrilling, majestic full-page chapter cover illustration in fun 2D storybook cartoon animation style, featuring [CHARACTER: RAJA IKAN TODAK] leaping dynamically in an acrobatic upward spiral from a colossal curling turquoise sea wave, its bioluminescent jade rostrum glowing brilliantly, met by a shimmering golden arc of protective energy from [CHARACTER: DATU MABRUR], sparkling water droplets suspended like stars, dramatic royal indigo and turquoise ocean atmosphere with clean spacious upper sky left as negative space for bold chapter headline text, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### CVR 03: COVER BAB 3 – IKRAR DUA PENGUASA
* **Penempatan**: Halaman 16 (Cover Bab 3)
* **Subjek**: Momen sakral pengikatan janji suci dan penyembuhan di atas batu karang berlumut. Datu Mabrur mengusap lembut Raja Ikan Todak dengan pancaran cahaya bintang-bintang emas kesembuhan diiringi lambaian kawanan ikan todak cilik. Langit senja temaram bernuansa peach-amber hangat di area atas untuk judul "BAB 3: PERJANJIAN DUA PENGUASA".
* **Prompt Google Flow (Imagen 3)**:
```text
A heartwarming, sacred full-page chapter cover illustration in fun 2D storybook cartoon animation style, depicting the holy pact of unity between land and sea, [CHARACTER: DATU MABRUR] gently touching [CHARACTER: RAJA IKAN TODAK] on the coral ledge, radiant healing golden starbursts flowing between them, surrounded by a peaceful calm ocean with [CHARACTER: MINI TODAK SQUAD] surfacing joyfully, glowing warm peach and amber sunset sky with thoughtful negative space at the upper half for chapter title typography, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### CVR 04: COVER BAB 4 – TERBITNYA PULAU HALIMUN
* **Penempatan**: Halaman 21 (Cover Bab 4)
* **Subjek**: Keajaiban kolosal saat pulau hijau berundak terangkat dari samudra raya! Jutaan biota laut dan paus biru raksasa memikul daratan baru dengan semburan busa putih toska. Sinar matahari pagi menembus kabut halimun, dengan latar langit cerah bersih di bagian atas untuk judul "BAB 4: KEAJAIBAN PULAU HALIMUN".
* **Prompt Google Flow (Imagen 3)**:
```text
An awe-inspiring, wondrous full-page chapter cover illustration in fun 2D storybook cartoon animation style, showcasing the birth of a promised land, a lush vibrant green island mass emerging triumphantly from the sparkling cerulean sea supported by [CHARACTER: SEA GIANTS] and millions of cheerful sea creatures pushing upward, frothy white foam crests and sparkling waterfalls cascading down cliffs, radiant morning sunbeams breaking through soft mist, generous airy sky in the top area designed as clean negative space for book title typography, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### CVR 05: COVER BAB 5 – WARISAN KEARIFAN KOTABARU
* **Penempatan**: Halaman 26 (Cover Bab 5)
* **Subjek**: Datu Mabrur berdiri gagah di puncak bukit hijau Pulau Laut yang makmur, memandang teluk Kotabaru nan permai di mana perahu nelayan tradisional berlayar berdampingan dengan todak yang melompat di laut toska. Langit biru keemasan cemerlang di bagian atas untuk judul "BAB 5: WARISAN KEARIFAN KOTABARU".
* **Prompt Google Flow (Imagen 3)**:
```text
A noble, inspiring full-page chapter cover illustration in fun 2D storybook cartoon animation style, [CHARACTER: DATU MABRUR] standing serenely on a scenic grassy hilltop overlooking the breathtaking expanse of Pulau Laut (Kotabaru), lush rounded hills, tranquil coastal bay with traditional colorful Indonesian sailing boats, cheerful sawfishes leaping in distant waves, radiant morning sky with glorious sunbursts, spacious clean upper sky composition leaving perfect negative space for chapter typography, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

## 3. MASTER PROMPT 8 ILUSTRASI ADEGAN NARATIF (IMAGEN 3)

Seluruh prompt di bawah ini diformat untuk rasio vertikal buku A4 Portrait (`--ar 3:4` di Google Flow) untuk halaman isi cerita.

---

### ASET 01: COVER UTAMA (SAMPUL DEPAN MODUL)
* **Penempatan**: Halaman 1 (Cover Luar Modul)
* **Subjek**: Datu Mabrur duduk bersila dengan senyum teduh ceria di atas batu karang bundar di tengah lautan berombak melengkung lincah (*curled whimsical waves*), memandang seberkas pilar cahaya matahari keemasan yang menembus awan senja pastel ke arah siluet pulau impian di kejauhan.
* **Prompt Google Flow**:
```text
A breathtaking cover illustration in fun whimsical 2D animated storybook style, featuring [CHARACTER: DATU MABRUR] sitting peacefully cross-legged in zen joyful meditation atop a smooth rounded ocean reef stone in the middle of a playful swirling sea, dynamic animated waves with frothy cartoon foam curls, a glorious warm golden ray of divine sunlight breaking through dreamy soft-edged twilight clouds onto the horizon revealing the lush green silhouette of a promised island, wide eye-level perspective, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 01B: HALAMAN 4 – PETA PENJELAJAHAN MANUSKRIP (ROADMAP DAFTAR ISI)
* **Penempatan**: Halaman 4 (Latar Belakang Peta Petualangan Daftar Isi Interaktif di Canva/Figma)
* **Subjek**: Peta bahari fantasi bertema petualangan ekspedisi (*nautical adventure roadmap / treasure map*) dalam gaya kartun 2D whimsical yang memikat dan bersahabat bagi siswa SMA. Berlatar naskah perkamen kuno gading krem dengan vignette tepi keemasan lembut, memperlihatkan lautan toska cerah berombak melengkung lincah, rute pelayaran garis putus-putus emas melengkung anggun menghubungkan pulau-pulau karang mini dari kiri bawah (titik awal pertapaan Datu Mabrur) menuju pulau surga hijau di kejauhan (Pulau Halimun). Dipercantik perahu pinisi tradisional kartun mungil berlayar santai, todak cilik melompat ceria, serta **area tengah-atas yang lapang, bersih, dan bergradasi lembut (*subtle airy negative space*)** agar teks babak daftar isi di Canva dapat terbaca dengan kontras sempurna dan ergonomis.
* **Prompt Google Flow (Imagen 3)**:
```text
A whimsical fantasy nautical adventure treasure map background in fun 2D storybook cartoon animation style, designed for an interactive book roadmap page. An ancient warm cream parchment scroll canvas with subtle antique textures and soft golden edge vignettes, a playful winding dotted gold adventure trail curving smoothly across a shimmering turquoise sea, connecting stylized miniature island waypoints from a small hermit reef stone to a lush emerald tropical island in the distance. Charming tiny details including a cute mini traditional Indonesian wooden sailing boat, cheerful jumping cartoon sawfishes splashing tiny crystal water droplets, soft gentle clouds, with a clean and airy low-contrast central reading area thoughtfully composed to leave ample negative space for text overlay, delightful Klaus and Cartoon Saloon fairy tale aesthetic, highly polished, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 02: BAB 1 – AWAL PERJALANAN (PERTAPAAN DI ANTARA DUA SELAT)
* **Penempatan**: Halaman 7 (Pembuka Chapter 1 & Pemantik)
* **Subjek**: Datu Mabrur bermeditasi santai dalam suasana senja yang hangat dan ceria di antara Selat Laut dan Selat Makassar. Air laut jernih berkilau toska, ikan-ikan kecil berwarna-warni berenang ceria mengitari batu karangnya, memancarkan kedamaian batin dan kebahagiaan.
* **Prompt Google Flow**:
```text
A heartwarming, lively peaceful scene of [CHARACTER: DATU MABRUR] meditating in tranquil stillness upon a flat sea stone, set between the calm shimmering turquoise waters of Strait of Laut and Strait of Makassar at golden sunset, warm pastel coral and honey-amber skies reflecting on gentle ripples, schools of colorful friendly little tropical fishes swimming playfully in the crystal clear water around his rock, soft radiant golden aura glowing around the sage, serene atmosphere of patience and hope, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 03: BAB 2 – SERANGAN IKAN TODAK (AKROBATIK SAMUDRA YANG DINAMIS & SERU)
* **Penempatan**: Halaman 12 (Pembuka Chapter 2 & Pemantik)
* **Subjek**: Aksi akrobatik laut yang seru, lincah, dan menghibur; Raja Ikan Todak meluncur lincah melompat dari lengkungan ombak samudra, moncong gergaji permata menyala keemasan, tertahan santai oleh gelembung perisai bulat cahaya keemasan lembut yang dipancarkan telapak tangan Datu Mabrur dengan senyum tenang tanpa rasa takut. Percikan tetesan air memantul lucu seperti kelereng kristal di udara.
* **Prompt Google Flow**:
```text
A thrilling dynamic action scene in fun 2D animated cartoon style, [CHARACTER: RAJA IKAN TODAK] leaping acrobatically high out of a dramatic swirling turquoise wave in a playful corkscrew curve, its glowing jade snout bouncing harmlessly against a translucent magical golden bubble shield conjured gently by [CHARACTER: DATU MABRUR] who calmly sits with one open hand and a reassuring gentle smile, glistening water droplets frozen mid-air like sparkling cartoon jewels, vibrant deep blue and emerald ocean colors, thrilling yet friendly family-friendly action, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 04: BAB 2 (ADEGAN 2) – TAKLUKNYA RAJA IKAN TODAK (LUCU & MENGHARUKAN)
* **Penempatan**: Halaman 13 (Ilustrasi Naskah Cerita Bab 2)
* **Subjek**: Raja Ikan Todak bersandar lelah dan cemberut lucu di sela karang basah di tepi air, matanya memelas bulat penuh harap seperti anak kucing laut, sisiknya tampak meredup lembut (tanpa luka darah sama sekali). Datu Mabrur berdiri menunduk menatapnya dengan senyum belas kasih yang hangat. Di belakangnya, kawanan ikan todak kecil menyembul dari air laut dengan mata bulat cemas yang ekspresif.
* **Prompt Google Flow**:
```text
A touching and humorous storybook cartoon scene, [CHARACTER: RAJA IKAN TODAK] resting wearily on a smooth tidal rock ledge, its shimmering scales temporarily dimmed and tired, looking up with large expressive pleading golden cartoon eyes, [CHARACTER: DATU MABRUR] standing kindly over the fish with a comforting compassionate smile, in the background gentle turquoise sea waves where [CHARACTER: MINI TODAK SQUAD] poke their heads above water watching anxiously, warm cozy lighting, zero gore, charming visual storytelling, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 05: BAB 3 – MUKJIZAT KASIH SAYANG & PENYEMBUHAN
* **Penempatan**: Halaman 17 (Pembuka Chapter 3 & Pemantik)
* **Subjek**: Datu Mabrur berlutut lembut mengusap punggung Raja Ikan Todak. Sentuhan tangannya memancarkan cahaya keemasan dan pirus berkilau (*magical sparkling stars*), membuat sisik ikan kembali menyala cerah cemerlang. Keduanya saling bertukar senyum hangat penuh persahabatan sejati.
* **Prompt Google Flow**:
```text
A heartwarming magical healing scene in vibrant 2D cartoon style, [CHARACTER: DATU MABRUR] kneeling gently beside [CHARACTER: RAJA IKAN TODAK] on the coral ledge, gently stroking the fish with warm open hands, dazzling sparkles of soft golden and teal magical healing starbursts flowing from his fingers, instantly restoring the fish's brilliant turquoise shimmering scales and vitality, the sea king smiles up at the sage with profound gratitude and friendship, beautiful warm sunset glow over calm gentle waves, pure heartwarming fairy tale moment, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 06: BAB 3 (ADEGAN 2) – IKRAR SUCI "SA-IJAAN" (SELEBRASI CERIA)
* **Penempatan**: Halaman 18 (Ilustrasi Naskah Cerita Bab 3)
* **Subjek**: Perayaan gembira ikrar Sa-Ijaan! Datu Mabrur tersenyum lebar melambaikan tangan dari karang, sementara Raja Ikan Todak melompat tinggi berputar ceria di atas air laut mengibaskan siripnya seolah tos gembira, dikelilingi ribuan ikan laut berbagai warna yang melompat bersama menciptakan busa ombak berbentuk sulur artistik di bawah sinar mentari pagi.
* **Prompt Google Flow**:
```text
A joyful celebratory maritime scene in lively 2D animation style, [CHARACTER: DATU MABRUR] standing at the water's edge on the coral rock cheerfully waving both hands, watching [CHARACTER: RAJA IKAN TODAK] leap high in a triumphant joyful arch back into the sparkling sea waving a fin in greeting, surrounded by [CHARACTER: MINI TODAK SQUAD] and thousands of colorful happy sea creatures leaping in unison creating playful swirling ripples and glistening sea spray under bright cheerful morning sunlight, uplifting mood, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 07: BAB 4 – JANJI MENJADI KENYATAAN (GOTONG ROYONG MENGANGKAT DARATAN)
* **Penempatan**: Halaman 22 (Pembuka Chapter 4 & Pemantik)
* **Subjek**: Pemandangan bawah laut yang spektakuler, penuh canda tawa dan kehangatan gotong royong! Paus biru gemuk tersenyum lebar, penyu bijak yang lucu, pari manta gemulai, serta ribuan todak cilik bahu-membahu menyangga bongkahan daratan pulau hijau dari dasar laut, berenang beriringan ke atas menuju permukaan air laut yang ditembus pilar-pilar cahaya matahari keemasan.
* **Prompt Google Flow**:
```text
An enchanting, wondrous underwater scene full of joy and cooperation in fun 2D storybook cartoon style, [CHARACTER: SEA GIANTS] including a gigantic chubby blue whale with a beaming smile, wise friendly sea turtles, and thousands of joyful sawfishes led by [CHARACTER: RAJA IKAN TODAK], all working together cheerfully hoisting a magnificent lush green landmass from the sandy seabed up toward the sunlit turquoise water surface, playful streams of magical underwater bubbles, radiant golden sunbeams piercing through the depths, vibrant teamwork, whimsical cartoon grandeur, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

### ASET 08: BAB 5 – PULAU HALIMUN NAN SUBUR MAKMUR (PULAU LAUT)
* **Penempatan**: Halaman 27 (Pembuka Chapter 5 & Pemantik)
* **Subjek**: Panorama mempesona Pulau Halimun nan asri dan makmur; perbukitan hijau bulat berundak yang ramah, air terjun jernih, pantai berpasir emas, diselimuti kabut putih lembut (*fluffy white halimun mist*), dikelilingi laut toska tenang. Datu Mabrur berdiri di atas bukit melompat kecil bersorak gembira memandang pulau ciptaan Tuhan dengan tangan terangkat penuh rasa syukur.
* **Prompt Google Flow**:
```text
A breathtaking aerial panoramic 2D cartoon painting of the newly emerged island of Pulau Halimun (Pulau Laut), a fertile tropical paradise with rounded vibrant emerald green hills, sparkling waterfalls, golden sandy shores, and gentle fluffy white morning mist (halimun) dancing around the lush valleys, surrounded by calm crystal turquoise sea waters under a radiant golden sunrise sky, [CHARACTER: DATU MABRUR] seen on a high viewpoint cheerfully raising his arms in joyous thanksgiving prayer, idyllic enchanted island, peaceful wonderland, [STYLE ANCHOR - FUN WHIMSICAL 2D STORYBOOK CARTOON] --ar 3:4
```

---

## 4. MASTER PROMPT 2 VIDEO VEO (GOOGLE FLOW ANIMATION)

Prompt video ini dirancang untuk mode **Text-to-Video** atau **Ingredients-to-Video** di Google Flow dengan model Veo (Format 16:9 Landscape untuk disematkan di widget Heyzine).

---

### ASET 09: VIDEO VEO 01 – ANIMASI AKROBATIK SERANGAN IKAN TODAK
* **Penempatan**: Halaman 12 (Widget Video Heyzine Bab 2)
* **Durasi Target**: 5 – 8 detik (Looping mulus)
* **Prompt Video Veo**:
```text
Delightful 2D animated cartoon sequence in Klaus and Disney style. A charismatic turquoise sawfish leaps playfully and acrobatically out of a curling wave in a fluid corkscrew motion toward a smiling, lovable elderly Indonesian sage wearing a traditional Banjar headdress (Laung) and indigo tunic sitting cross-legged on a rounded sea stone. The sage gently raises a hand and an elastic glowing golden bubble shield pulses outward, softly bouncing the sawfish back into the sea with a comical splash of sparkling crystal water droplets in slow motion. Friendly Indonesian maritime folklore aesthetic, vibrant turquoise and golden colors, bouncy fluid 2D animation, zero greek toga, zero bare chest --ar 16:9
```

---

### ASET 10: VIDEO VEO 02 – TIMBULNYA DARATAN PULAU DARI SAMUDRA
* **Penempatan**: Halaman 22 (Widget Video Heyzine Bab 4)
* **Durasi Target**: 5 – 8 detik (Looping mulus)
* **Prompt Video Veo**:
```text
Enchanting 2D storybook cartoon animation panning smoothly over a sunlit sparkling turquoise ocean at dawn. Joyful streams of sea bubbles rise as a magnificent, lush green tropical island emerges gracefully from beneath the ocean surface, with waterfalls playfully cascading into the sea. Friendly colorful fish jump along the shore in joyous celebration, soft fluffy white morning mist rolls over the new paradise island under glowing sunrise rays, heartwarming magical cartoon fantasy --ar 16:9
```

---

## 5. MASTER PROMPT 5 ELEMEN ORNAMEN GRAFIS BANJAR (PNG TRANSPARAN)

---

### ASET 11: BORDER SUDUT UKIRAN BANJAR (FUN CARTOON GOLD)
* **Penempatan**: Halaman 1 s.d. 34 (Sudut Kanvas Canva A4)
* **Prompt Google Flow**:
```text
An intricate traditional South Kalimantan Banjar corner border ornament featuring stylized Tali Bapintal spiral braid and Pucuk Rebung floral patterns, rendered in a charming whimsical 2D storybook cartoon style with warm glowing burnished gold and sunny amber tones, crisp clean contours, isolated on clean transparent background, clean symmetrical decorative book corner decoration --ar 1:1
```

---

### ASET 12: SEGEL CAP KERAJAAN SA-IJAAN (STORYBOOK MEDALLION)
* **Penempatan**: Halaman 3, 4, 28, & 34 (Cap Segel Modul)
* **Prompt Google Flow**:
```text
A charming royal seal medallion in whimsical 2D cartoon storybook style, circular vintage emblem in warm embossed gold and rich ocean teal, featuring two symmetrical friendly stylized sawfishes leaping gracefully facing each other over playful cartoon waves, banner beneath engraved with the clean inscription 'SA-IJAAN', decorative Banjar filigree border, isolated on transparent background, regal yet friendly folk emblem --ar 1:1
```

---

### ASET 13: KOMPAS MAWAR ANGIN BAHARI (NAUTICAL COMPASS ROSE)
* **Penempatan**: Halaman 4 (Pojok Peta Penjelajahan Manuskrip di Canva)
* **Subjek**: Kompas mawar angin penjelajah bahari kuno (*nautical windrose compass*) bergaya kartun 2D whimsical yang ramah dan artistik. Terbuat dari kuningan emas berukir ornamen Banjar dan aksen biru laut toska, dengan jarum kompas berbentuk bintang matahari tersenyum cerah, lingkaran cincin tali temali bahari tradisional, dan huruf mata angin dekoratif, berlatar transparan bersih (*isolated on transparent background*).
* **Prompt Google Flow**:
```text
A charming antique nautical windrose compass rose in whimsical 2D storybook cartoon style, circular brass and burnished gold compass with vibrant turquoise blue enamel inlays, an artistic radiating sunburst needle pointing gracefully, stylized nautical rope ring border and delicate traditional filigree stars, playful curved contours, isolated on clean transparent background, high resolution, clean vector-like crisp edges, warm welcoming fairy tale navigation instrument --ar 1:1
```

---

### ASET 14: PITA GULUNGAN NASKAH PETUALANGAN (VINTAGE SCROLL BANNER)
* **Penempatan**: Halaman 4 (Header Plakat Judul: "PETA PENJELAJAHAN MODUL" di Canva)
* **Subjek**: Pita gulungan naskah perkamen bahari kuno (*whimsical nautical parchment scroll banner*) yang melengkung anggun dengan ujung terlipat rapi. Berwarna krem gading dengan bingkai garis emas berpendar hangat, dihiasi simpul tali bahari di kedua sisinya, dirancang khusus sebagai wadah teks judul yang lapang dan bersih, berlatar transparan (*isolated on transparent background*).
* **Prompt Google Flow**:
```text
An elegant whimsical 2D storybook cartoon parchment ribbon scroll banner, curved flowing parchment banner in warm ivory cream with ornate glowing gold edges, curled paper tails at both ends decorated with tiny subtle nautical sailor rope knots and friendly golden laurels, spacious clean flat horizontal banner surface designed for headline typography, isolated on clean transparent background, crisp clean outlines, Klaus and Disney 2D animation style --ar 16:9
```

---

### ASET 15: PIN CHECKPOINT BABAK PETUALANGAN (WAYPOINT MEDALLIONS)
* **Penempatan**: Halaman 4 (Penanda Titik Pos Bab 1 s.d. Bab 5 pada Rute Peta di Canva)
* **Subjek**: Pin penanda peta petualangan (*adventure map waypoint pin*) berbentuk stempel lilin segel kerajaan merah marun berbingkai medali emas berpendar dengan ikon jangkar kecil atau siluet todak kartun ceria, memberikan kesan interaktif seperti tombol checkpoint dalam game petualangan, berlatar transparan (*isolated on transparent background*).
* **Prompt Google Flow**:
```text
A set of 5 charming adventure map waypoint checkpoint pins in whimsical 2D storybook cartoon style, circular embossed ruby-red wax seal medallions encased in chunky polished golden frames with cute nautical motifs, numbered medallions 1 through 5, glossy cartoon finish with soft warm highlights, game UI element aesthetic for an interactive storybook map, isolated on clean transparent background --ar 1:1
```

---

## 6. TABEL PANDUAN EKSPOR DAN PENEMPATAN LENGKAP ASET (34 HALAMAN)

| Kode | Nama File | Format | Rasio | Penempatan di Modul | Kesan Visual & Fungsi |
|---|---|---|---|---|---|
| **IMG-01** | `IMG_Cover_DatuMabrur.png` | PNG | 3:4 | Halaman 1 (Cover Luar Modul) | Sampul depan megah, ramah, dan memikat siswa SMA |
| **IMG-01B** | `IMG_Halaman4_Peta_Penjelajahan.png` | PNG | 3:4 | Halaman 4 (Peta Daftar Isi) | Peta petualangan bahari dongeng cerah & lapang untuk teks |
| **CVR-01** | `CVR_Bab1_Pertapaan_Datu.png` | PNG | 3:4 | **Halaman 6 (Cover Bab 1)** | Poster pembatas Bab 1: Datu Mabrur khusyuk di fajar kencana |
| **IMG-02** | `IMG_Bab1_Pertapaan_Selat.png` | PNG | 3:4 | Halaman 7 (Pembuka Bab 1 & Pemantik) | Senja damai nan santai di antara dua selat |
| **CVR-02** | `CVR_Bab2_Serangan_Todak.png` | PNG | 3:4 | **Halaman 11 (Cover Bab 2)** | Poster pembatas Bab 2: Kemunculan dramatis Raja Todak |
| **IMG-03** | `IMG_Bab2_Serangan_Todak.png` | PNG | 3:4 | Halaman 12 (Pembuka Bab 2 & Pemantik) | Akrobatik seru, perisai gelembung emas membal |
| **VID-01** | `VID_Veo_Serangan_Todak.mp4` | MP4 | 16:9 | Halaman 12 (Widget Video Heyzine) | Animasi 2D lentur & akrobatik yang menghibur |
| **IMG-04** | `IMG_Bab2_Todak_Takluk.png` | PNG | 4:3 | Halaman 13 (Teks Cerita Bab 2) | Mengharukan, ekspresif, tanpa darah (cemberut lucu) |
| **CVR-03** | `CVR_Bab3_Ikrar_Sahabat.png` | PNG | 3:4 | **Halaman 16 (Cover Bab 3)** | Poster pembatas Bab 3: Sentuhan suci & cahaya kesembuhan |
| **IMG-05** | `IMG_Bab3_Penyembuhan_Luka.png` | PNG | 3:4 | Halaman 17 (Pembuka Bab 3 & Pemantik) | Cahaya penyembuhan bertabur bintang magis |
| **IMG-06** | `IMG_Bab3_Ikrar_SaIjaan.png` | PNG | 4:3 | Halaman 18 (Teks Cerita Bab 3) | Ceria, perayaan persahabatan laut yang meriah |
| **CVR-04** | `CVR_Bab4_Terbit_Halimun.png` | PNG | 3:4 | **Halaman 21 (Cover Bab 4)** | Poster pembatas Bab 4: Pulau hijau terangkat dari laut |
| **IMG-07** | `IMG_Bab4_Angkat_Pulau.png` | PNG | 3:4 | Halaman 22 (Pembuka Bab 4 & Pemantik) | Gotong royong jutaan hewan laut lucu & paus gembira |
| **VID-02** | `VID_Veo_Bangkitnya_Pulau.mp4` | MP4 | 16:9 | Halaman 22 (Widget Video Heyzine) | Timbulnya pulau surga dengan kabut halimun ceria |
| **IMG-08** | `IMG_Bab5_Pulau_Halimun.png` | PNG | 3:4 | Halaman 27 (Pembuka Bab 5 & Pemantik) | Panorama pulau surga hijau berselimut kabut halimun |
| **CVR-05** | `CVR_Bab5_Warisan_Kotabaru.png` | PNG | 3:4 | **Halaman 26 (Cover Bab 5)** | Poster pembatas Bab 5: Pemandangan Kotabaru masa depan |
| **ORN-01** | `ORN_Border_Sudut_Banjar.png` | PNG | 1:1 | Sudut Halaman Canva A4 (1-34) | Ornamen ukiran Banjar emas bergaya kartun hangat |
| **ORN-02** | `ORN_Segel_SaIjaan.png` | PNG | 1:1 | Halaman 3, 4, 28, 34 | Cap segel ramah bergambar sepasang todak ceria |
| **ORN-03** | `ORN_Kompas_Mawar_Angin.png` | PNG | 1:1 | Halaman 4 (Sudut Peta) | Kompas bahari antik emas-toska bergaya kartun |
| **ORN-04** | `ORN_Pita_Banner_Naskah.png` | PNG | 16:9 | Halaman 4 (Header Plakat Judul) | Gulungan perkamen naskah bahari untuk plakat judul |
| **ORN-05** | `ORN_Pin_Checkpoint_Bab.png` | PNG | 1:1 | Halaman 4 (Pos Bab 1 s.d. 5) | Medali stempel lilin checkpoint nomor bab 1 s.d. 5 |
