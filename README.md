# IndoLanner 🗺️🤖

> **Status:** Prototype / In Development - Dikembangkan untuk UI/UX Protothon 2026.

IndoLanner adalah aplikasi perencanaan wisata dan kuliner cerdas yang dirancang dengan estetika *Neo-Brutalism* yang tegas. Aplikasi ini mendobrak desain konvensional dengan menghadirkan pengalaman pengguna yang interaktif, kontras tinggi, dan dipandu oleh asisten Chatbot AI untuk memberikan rekomendasi destinasi personal.

## 🎨 Fokus UI/UX: Neo-Brutalism Styling
Seluruh komponen dalam aplikasi ini menerapkan aturan *Neo-Brutalism* yang ketat untuk memberikan kesan *bold* dan *stand-out*:
- **Border & Shadow:** Garis batas hitam solid 4px dengan bayangan solid (offset 4px) tanpa efek gradasi atau *blur*.
- **Tipografi:** Penggunaan *font* serif yang tebal dan agresif.
- **Warna Kontras:** Memanfaatkan warna-warna primer dengan kontras tinggi (merah, kuning, biru) untuk elemen interaktif.

## ✨ Fitur Interaktif Unggulan
* **Intelligent Chatbot FAB:** Tombol aksi melayang (z-index: 50) yang membuka antarmuka obrolan cerdas berukuran 384px x 500px dengan animasi *slide-in* yang mulus.
* **Rich Destination Cards:** Saat AI memberikan rekomendasi, pengguna disajikan kartu destinasi visual yang mencakup:
  - Indikator kepadatan area *real-time* (Ramai/Sedang/Sepi) dengan *color-coding*.
  - Tombol "Tambah ke Rencana" yang langsung memberikan umpan balik kontekstual dari AI.
* **Peta Dinamis:** Integrasi Leaflet untuk pemetaan interaktif destinasi di Indonesia.

## 🛠️ Tech Stack
Proyek ini dibangun menggunakan teknologi *frontend* terkini untuk mendukung *rendering* UI yang kompleks:
- **Framework:** Next.js 16.2.0
- **Styling:** Tailwind CSS v4 & berbagai komponen UI Radix (shadcn/ui)
- **Maps:** React Leaflet
- **Prototyping Tools:** Diakselerasi dengan bantuan v0.ai

## 🚀 Cara Menjalankan Aplikasi

```bash
# Clone repositori
git clone [URL-REPOSITORI]
cd indolanner

# Install dependensi
npm install

# Jalankan development server
npm run dev
