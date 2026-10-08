# Paugeran Sriwedari — Transliterasi Aksara Jawa Interaktif

> **Aplikasi web resmi untuk transliterasi aksara Latin ke Aksara Jawa berbasis kaidah baku Paugeran Sriwedari (1926) dilengkapi modul Paramasastra (Morfologi Jawa) dan Tembung Dwipurwa.**

---

## 📌 Ringkasan Platform

**Paugeran Sriwedari** adalah aplikasi web edukatif dan alat bantu linguistik interaktif yang dirancang untuk melakukan transliterasi teks Latin ke Aksara Jawa secara otomatis, akurat, dan sesuai dengan hukum ejaan baku klasik (*Paugeran Sriwedari 1926*). 

Selain fungsi transliterasi utama, platform ini dilengkapi dengan dua modul pendukung penting untuk tata bahasa Jawa:
1. **Aplikasi Paramasastra (Morfologi Jawa):** Pembentukan kata berimbuhan (*Tembung Andhahan*) yang tunduk pada hukum peluluhan konsonan, *sandi*, serta *panyigeging wanda*.
2. **Pembentukan Tembung Dwipurwa:** Modul otomatisasi pengulangan suku kata awal (*dwipurwa*) yang disesuaikan dengan ejaan Latin baku dan penulisan aksara legena.

---

## 🚀 Fitur Utama

### 1. Mesin Transliterasi Otomatis
- **Real-Time Processing:** Transliterasi langsung saat pengguna mengetik teks Latin pada kolom input.
- **Dukungan Aksara Lengkap:**
  - **Aksara Legena & Pasangan** (termasuk penanganan otomatis pasangan ganda/tumpuk tiga).
  - **Aksara Murda** (diakses melalui konsonan kapital: `N, K, T, S, P, G, B, C, NY, J, DH`).
  - **Aksara Swara** (diakses melalui vokal kapital: `A, I, U, E, O`).
  - **Aksara Rekan** (khusus serapan: `kh`, `dz`, `gh`, `z`, `f/v`).
  - **Sandhangan Swara, Panyigeg Wanda, & Wyanjana** (pengkal, cakra, keret, cecak, wignyan, layar, pangkon).
- **Aturan Baku Sriwedari:** Otomatisasi pembacaan vokal *o/a* miring, pengubahan pasangan *Da Mahaprana* (`꧀ꦣ`) menjadi *Da Murda* (`꧀ꦝ`), dan pencegahan pasangan ganda antarkata.

### 2. Modul Paramasastra (Morfologi Jawa)
- Pembentukan kata dasar (*tembung lingga*) dengan penggabungan *ater-ater* (awalan) dan *panambang* (akhiran).
- Pilihan awalan lengkap: *Anuswara* (`N-`, `m-`, `n-`, `ng-`, `ny-`), *dak-*, *ko-*, *di-*, *sa-*, *pa-*, *pi-*, *pra-* *pri-*, *ka-*, *kuma-*, *kami-*, *kapi-*, *pating pa-N*, dan seselan *-in-*.
- Pilihan akhiran lengkap: *-a*, *-i*, *-e/-é*, *-en*, *-an*, *-ana*, *-na*, *-aké*, *-aken*, *-ipun*, serta kombinasi kompleks.
- Validasi otomatis (*Paugeran Warning*) apabila kombinasi awalan/akhiran tidak sesuai kaidah morfologi Jawa.

### 3. Modul Tembung Dwipurwa
- Generator kata ulang dwipurwa otomatis dari kata dasar.
- Otomatisasi peluluhan konsonan awal dan penyesuaian vokal pepet (`e`) pada ejaan Latin baku serta penulisan aksara *legena*.

### 4. Kustomisasi Tampilan & Ekspor Teks
- **Pilihan Font Aksara Jawa:** Mendukung font *Ngayogyann* (default) dan *Noto Sans Javanese*.
- **Pengaturan Tipografi Interaktif:** Slider penyesuaian ukuran font dan jarak antarbaris (*line-height*).
- **Penyalinan Cepat (One-Click Copy):** Fitur salin teks Latin maupun salin hasil Aksara Jawa ke papan klip (*clipboard*) dalam sekali klik.

---

## 📖 Panduan Penulisan Latin (Aturan Transliterasi)

Untuk menghasilkan transliterasi Aksara Jawa yang presisi, gunakan petunjuk penulisan berikut pada kolom teks Latin:

| Unsur Teks | Cara Penulisan Latin | Hasil Transliterasi Aksara Jawa |
| :--- | :--- | :--- |
| **Vokal Taling (`é`/`è`)** | Ketik `é`, `è`, atau `e'` | ꦺ (Sandhangan Taling) |
| **Vokal Pepet (`e`)** | Ketik `e` biasa | ꦼ (Sandhangan Pepet) |
| **Panambang (Akhiran)** | Tambahkan tanda hubung `-` (misal: `omah-e`) | Memisahkan pembentukan suku kata terbuka/tertutup |
| **Aksara Rekan** | `kh`, `dz`, `gh`, `z`, `f`, `v` | ꦏ꦳, ꦢ꦳, ꦒ꦳, ꦗ꦳, ꦥ꦳ |
| **Aksara Swara** | Huruf vokal kapital (`A, I, U, E, O`) | ꦄ, ꦆ, ꦈ, ꦌ, ꦎ |
| **Aksara Murda** | Huruf konsonan kapital (`N, K, T, S, P, G, B, J, NY`) | ꦟ, ꦑ, ꦡ, ꦯ, ꦦ, ꦓ, ꦨ, ꦙ, ꦘ |
| **Paksaan Cakra/Pengkal** | Tambahkan `x` setelah konsonan (misal: `rxya`, `ngxra`, `hxre`) | Memaksa huruf `r`, `ng`, atau `h` menerima sandhangan wyanjana |

---

## 💻 Spesifikasi Teknis

Aplikasi ini dibangun menggunakan arsitektur web murni (*vanilla client-side*) tanpa *framework* berat, sehingga sangat ringan dan cepat diakses:

- **Bahasa Pemrograman:** JavaScript (ES6+ Native Engine Transliteration)
- **Markup & Styling:** HTML5, CSS3 Custom Variables (Design System Responsive & Clean UI)
- **Tipografi:** Google Fonts (*Noto Sans Javanese*, *PT Serif*) & Custom Webfont (`Ngayogyann.ttf`)
- **Compatibility:** Responsif di desktop, tablet, dan perangkat seluler (Mobile Friendly).

---

## 🔗 Ekosistem & Tautan Terkait

- **Katalog Game & Aplikasi Aksara Jawa Lainnya:** [Kandangjago Jawa Portal](https://kandangjagojawa.github.io/)

---

© **Paugeran Sriwedari** — Tim Pengembang & Pegiat Pelestarian Aksara Jawa.