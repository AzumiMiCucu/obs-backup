# 🌊 Mekanika Fluida — Fluida Statis

> **Mata Kuliah:** Fisika Dasar | **Topik:** FD-9 Fluida Diam **Sumber:** Serway Physics 5ed, Fundamentals of Physics 7th & 8th ed

---

## 📌 Deskripsi Umum

> **Fluida** → suatu zat yang memiliki kerapatan **renggang** serta **bergerak** dan **memenuhi ruang**.

**Contoh Fluida:** Zat cair dan gas **Berat** = Gaya

> 💡 _"Kalau kamu tidak bisa menjelaskan/menggambarkan sesuatu, kamu belum memahaminya."_

---

## 📚 Capaian Pembelajaran

- Dapat mendeskripsikan besaran fisis **Fluida Diam** mengacu pada **Hukum dan Prinsip Pascal**
- Dapat mendeskripsikan besaran fisis **Fluida Diam** mengacu pada **Prinsip Archimedes**

---

## 1️⃣ Besaran Fisis: Massa & Massa Jenis

### 1.1 Massa

- Satuan: **kg** atau **gram**
- _"Sifat" massa:_ semakin kecil ukuran, semakin kecil nilai massanya
- Dapat diukur **secara langsung**

### 1.2 Massa Jenis (Densitas)

$$\rho = \frac{m}{V} = \frac{\Delta m}{\Delta V} = \frac{dm}{dV}$$

|Simbol|Arti|Satuan|
|---|---|---|
|$\rho$|Massa jenis|kg/m³ atau g/cm³|
|$m$|Massa|kg atau gram|
|$V$|Volume|m³ atau cm³|

**Konversi penting:** $$1 \text{ g/cm}^3 = 1000 \text{ kg/m}^3$$

> 💡 _"Sifat" massa jenis:_ berapapun ukuran (wadah) cairannya, **nilai massa jenis selalu tetap**

**Cara mengetahui massa jenis:** diketahui dengan mengukur massa dan volume cairan

---

### 1.3 Specific Gravity (Berat Jenis Relatif)

> Diciptakan untuk keperluan pengukuran praktis sebagai **pengganti besaran massa jenis**

$$SG = \frac{\text{density of the object}}{\text{density of water}} = \frac{\rho_{object}}{\rho_{H_2O}}$$

- Rasio massa jenis cairan (selain air) terhadap massa jenis **air murni pada suhu 4°C**
- Tidak memiliki satuan (dimensionless)

**Alat ukur Specific Gravity:** **HYDROMETER** (alat pengukur specific gravity sebuah cairan)

---

## 2️⃣ Besaran Fisis: Tekanan

### 2.1 Definisi Tekanan

$$P = \frac{F}{A} = \frac{ma}{A} = \frac{m\frac{dv}{dt}}{A}$$

|Simbol|Arti|
|---|---|
|$P$|Tekanan (Pascal, Pa = N/m²)|
|$F$|Gaya tegak lurus (N)|
|$A$|Luas permukaan (m²)|

> **Beda Pengertian Gaya & Tekanan:**
> 
> - **Gaya F** selama waktu kontak $\Delta t$ pada benda $m$ → menyebabkan benda bergerak (perubahan momentum)
> - **Tekanan p** = Gaya F yang bekerja sepanjang luas permukaan A fluida secara **tegak lurus**

---

### 2.2 Tekanan Hidrostatis (Ruang Terbuka)

> Tekanan yang dihasilkan dari **bobot (gaya berat) fluida itu sendiri**

$$P = \frac{F}{A} = \frac{m \cdot g}{A} = \frac{\rho V g}{A} = \frac{\rho A h g}{A} = \rho g h$$

$$\boxed{P = \rho g h}$$

**Untuk fluida dalam wadah (bejana):** $$p = p_0 + \rho g h$$

**Untuk fluida skala besar (danau/waduk):** $$P = P_a + \rho g h$$

---

### 2.3 Selisih Tekanan pada Cairan Diam

Sampel cairan diam dalam sebuah wadah → total gaya yang bekerja di tiap "permukaan" cairan (luasan A) = **NOL**

$$\sum F = 0$$ $$F_2 - F_1 - mg = 0$$ $$P_2 A - P_1 A = mg$$ $$\Delta P = \rho g h$$

$$\boxed{\Delta P = \rho g h}$$

---

### 2.4 Sifat Tekanan pada Fluida Statis

> Sembarang titik dalam fluida statis mengalami **tekanan sama ke segala arah**

- Keadaan/sifat STATIS fluida dijamin dengan cara nilai tekanan **p** bernilai **SAMA** di semua arah pada tiap titik
- Benda di dalam cairan mengalami tekanan **serbasama** di semua sisi secara tegak lurus

---

## 3️⃣ Hukum Pascal (Ruang Tertutup)

### 3.1 Pernyataan Hukum Pascal

> _"Tekanan yang diberikan pada zat cair dalam ruang tertutup diteruskan ke segala arah dengan sama besar"_

### 3.2 Prinsip Pascal (Matematis)

$$p_1 = p_2 \implies \frac{F_1}{A_1} = \frac{F_2}{A_2}$$

$$\boxed{F_2 = \frac{A_2}{A_1} \times F_1}$$

**Penurunan dari kesetaraan tekanan:** $$\frac{F_1}{A_1} = \frac{F_2}{A_2}$$ $$= \frac{m_1 g}{A_1} = \frac{m_2 g}{A_2}$$ $$= \frac{\rho_1 V_1 g}{A_1} = \frac{\rho_2 V_2 g}{A_2}$$ $$= \frac{\rho_1 A_1 h_1 g}{A_1} = \frac{\rho_2 A_2 h_2 g}{A_2}$$ $$\rho_1 h_1 g = \rho_2 h_2 g$$

### 3.3 Contoh Penerapan Prinsip Pascal

|Aplikasi|Penjelasan|
|---|---|
|🚲 Pompa ban sepeda|Tekanan kecil di ujung pompa menghantarkan udara ke dalam ban|
|🪥 Memencet pasta gigi|Tekanan kecil di ujung mengeluarkan isi pasta gigi|
|🔧 Dongkrak hidrolik|Gaya kecil → gaya besar (pengali gaya)|
|💧 Botol kaca|Ujung botol ditekan → alas botol pecah karena tekanan diteruskan merata|

---

## 4️⃣ Kesetimbangan Gaya pada Fluida Statis

### 4.1 Kondisi Kesetimbangan

Pada cairan diam (fluida statis), **"kolom" cairan mengalami kesetimbangan** karena:

1. Bobot cairan itu sendiri ($mg$)
2. Gaya angkat cairan / gaya apung ($\rho_2 A$)
3. Gaya tekan cairan ($\rho_1 A$)

$$\sum F_y = 0$$ $$P_2 A - P_1 A - mg = 0$$ $$P_2 A = P_1 A + mg \quad (m = V\rho, ; V = Ah)$$ $$P_2 A = P_1 A + \rho V g$$ $$P_2 A = P_1 A + \rho A h g$$

$$\boxed{P_2 = P_1 + \rho h g}$$

---

## 5️⃣ Hukum Archimedes (Prinsip Archimedes)

### 5.1 Gaya Apung (Buoyant Force)

$$F_B = P_2 A - P_1 A = (P_2 - P_1) A$$

Karena $P_2 - P_1 = \rho g h$ dan $V = hA$:

$$F_B = \rho g h A = \rho V g$$

$$\boxed{F_B = \rho V g}$$

> 💡 **Arti Fisis:** Besarnya gaya apung $F_B$ adalah **sejumlah volume $V$ cairan $\rho$ yang dipindahkan**

> _"Buoyancy is a measure of the upward force a fluid exerts on an object that is submerged."_

### 5.2 Kondisi Benda dalam Fluida

|Kondisi|Persamaan|Keterangan|
|---|---|---|
|**Tenggelam**|$F_B < mg$|$\rho_{benda} > \rho_{fluida}$|
|**Melayang**|$F_B = mg$|$\rho_{benda} = \rho_{fluida}$|
|**Terapung**|$F_B \geq mg$|$\rho_{benda} < \rho_{fluida}$|

### 5.3 Benda Terapung (Floating)

Jika benda terapung: $W_{benda} = F_B$

$$W_{benda} = \rho_{fluida} \cdot V_{tercelup} \cdot g$$

**Fraksi volume yang tercelup:** $$\frac{\rho_{benda}}{\rho_{fluida}} = \frac{V_{tercelup}}{V_{total}}$$

### 5.4 Contoh Penting — Hiu

> _"A shark's body is not neutrally buoyant, so a shark must swim continuously or it will sink deeper."_ $$F_{bouy} \neq mg$$ → Setimbang dengan cara **TETAP/SELALU BERGERAK**

---

## 6️⃣ Tegangan Permukaan (Surface Tension)

### 6.1 Konsep Dasar

- Dua molekul cairan cenderung **berdekatan** satu sama lain (energi gain)
- Molekul di **permukaan** mengalami gaya kohesif lebih kuat karena ketidakseimbangan gaya (ditarik lebih kuat ke dalam bulk)
- Molekul di **dalam bulk**: setiap partikel mengalami gaya tarik ke semua arah → lebih lemah

### 6.2 Persamaan Tegangan Permukaan

$$F_s = \gamma L$$

|Simbol|Arti|Satuan|
|---|---|---|
|$F_s$|Gaya tegangan permukaan|N|
|$\gamma$|Koefisien tegangan permukaan|N/m = J/m²|
|$L$|Panjang garis kontak|m|

> Gaya bekerja **paralel** terhadap permukaan air

**Kesetimbangan:** $$\gamma = \frac{m_{needle} \cdot g}{2L \sin\alpha}$$

### 6.3 Aksi Kapiler (Capillary Action)

$$F_{STvertical} = \gamma 2\pi r \cos\varphi$$ $$w = Mg = \rho \pi r^2 g h$$

Cairan berhenti naik ketika: $F_{STvertical} = w$

$$\boxed{h = \frac{2\gamma \cos\varphi}{\rho g r}}$$

> ⚠️ **Jika r sangat besar → h sangat kecil!**

---

## 📊 Ringkasan Formula Kunci

|No|Konsep|Formula|Satuan|
|---|---|---|---|
|1|Massa Jenis|$\rho = m/V$|kg/m³|
|2|Tekanan|$P = F/A$|Pa (N/m²)|
|3|Tekanan Hidrostatis|$P = \rho g h$|Pa|
|4|Tekanan Total|$P = P_0 + \rho g h$|Pa|
|5|Selisih Tekanan|$\Delta P = \rho g \Delta h$|Pa|
|6|Prinsip Pascal|$F_1/A_1 = F_2/A_2$|—|
|7|Gaya Apung|$F_B = \rho V g$|N|
|8|Tegangan Permukaan|$F_s = \gamma L$|N|
|9|Tinggi Kapiler|$h = 2\gamma\cos\varphi/(\rho g r)$|m|

---

## 🧪 Contoh Soal Penting

### Soal 1 — Massa Jenis Darah

> Tubuh manusia (berat 690 N) mengandung ±5,2×10⁻³ m³ darah. Tentukan:
> 
> - (a) Berat darah
> - (b) Persentase terhadap berat tubuh

**Penyelesaian:** $$m = V\rho = (5{,}2 \times 10^{-3})(1060) = 5{,}5 \text{ kg}$$ $$W = mg = (5{,}5)(9{,}80) = 54 \text{ N}$$ $$% = \frac{54}{690} \times 100% = 7{,}8%$$

---

### Soal 2 — Kedalaman Snorkel

> Paru-paru manusia mampu menahan perbedaan tekanan hingga 1/20 atm. Berapa kedalaman maksimal berenang dengan snorkel? (1 atm = 1,013×10⁵ Pa)

**Penyelesaian:** $$\Delta P_{maks} = \frac{1}{20}(1{,}013 \times 10^5) = 5{,}065 \times 10^4 \text{ Pa}$$ $$L_{maks} = \frac{\Delta P_{maks}}{\rho g} = \frac{5{,}065 \times 10^4}{1000 \times 9{,}8} \approx 52 \text{ cm}$$

---

### Soal 3 — Tekanan Total pada Kedalaman Bertingkat

> Tekanan total pada kedalaman $h_1$ adalah $P_1$, pada $h_2$ adalah $P_2$, tekanan atmosfer $P_0$. Tekanan pada kedalaman $h_1 + h_2$?

$$\boxed{P_{tot} = P_1 + P_2 - P_0}$$

---

### Soal 4 — Papan Terapung (Archimedes)

> Lembar papan pinewood (4m×4m×0,30m), $\rho_{pine}$ = 550 kg/m³, terapung di air. Berapa tinggi $h$ yang masuk ke air?

$$V_{raft} = 4 \times 4 \times 0{,}30 = 4{,}8 \text{ m}^3$$ $$W_{raft} = (550)(4{,}8)(9{,}80) = 26000 \text{ N}$$ $$h = \frac{26000}{(1000)(4{,}0)(4{,}0)(9{,}80)} = 0{,}17 \text{ m}$$

---

## 🔗 Peta Konsep

```
Mekanika Fluida (Fluida Statis)
│
├── Besaran Fisis
│   ├── Massa (kg/gr)
│   ├── Massa Jenis ρ = m/V (kg/m³)
│   └── Specific Gravity (SG = ρ/ρ_air)
│
├── Tekanan P = F/A
│   ├── Tekanan Hidrostatis P = ρgh
│   ├── Selisih Tekanan ΔP = ρgΔh
│   └── Sifat: sama ke segala arah
│
├── Hukum Pascal (Ruang Tertutup)
│   └── F₁/A₁ = F₂/A₂
│
├── Kesetimbangan Gaya
│   └── P₂ = P₁ + ρhg
│
├── Prinsip Archimedes (Gaya Apung)
│   └── F_B = ρVg
│
└── Tegangan Permukaan
    ├── F_s = γL
    └── Aksi Kapiler: h = 2γcosφ/(ρgr)
```

---

## 🏷️ Tags

`#fisika-dasar` `#mekanika-fluida` `#fluida-statis` `#tekanan` `#pascal` `#archimedes` `#tegangan-permukaan` `#unsoed`