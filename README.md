# ⚡ Claudia Prompt Optimizer (CPO)

> **Framework Pengoptimal Prompt AI Presisi Tinggi untuk Rekayasa Perangkat Lunak & Arsitektur Sistem.**

Repositori ini berisi framework terstruktur untuk mengubah instruksi percakapan informal menjadi prompt teknis berdensitas tinggi (*high-density architectural directives*) bagi Model Bahasa Besar (LLM). Framework ini memaksa LLM untuk berhenti "menebak" dan bertindak sebagai arsitek sistem deterministik dengan akurasi maksimal.

---

## 🎯 Mengapa Membutuhkan Framework Ini?

Sebagian besar model AI canggih dilatih terutama pada korpus dataset teknis berbahasa Inggris. Mengirimkan tugas logika yang rumit menggunakan bahasa percakapan informal sering kali memicu:
1. **Context Decay**: Hilangnya batasan teknis atau aturan ketat di tengah percakapan panjang.
2. **Halusinasi & Asumsi Liar**: AI menambahkan fitur, kode spekulatif, atau pustaka baru yang tidak diminta.
3. **Fluff & Basa-Basi**: Output dipenuhi kalimat pembuka dan penutup tidak penting yang menghabiskan token.

**Claudia Prompt Optimizer (CPO)** bertindak sebagai cetak biru sistem. Saat diinjeksikan ke dalam *System Prompt* atau instruksi rekayasa, model AI dipaksa menghasilkan solusi kode yang presisi, ringkas (*zero-fluff*), dan berbasis fakta empiris.

---

## 🚀 Cara Penggunaan

1. Buka file [`optimizer_system_prompt.md`](./optimizer_system_prompt.md).
2. Salin seluruh konten ke dalam kolom **System Prompt** di platform AI pilihan Anda (Claude, ChatGPT, Gemini, Antigravity, OpenClaw, Cursor, dll).
3. Anda dapat langsung memberikan instruksi dalam Bahasa Indonesia sehari-hari, dan sistem secara otomatis mensintesisnya ke dalam arahan teknis berpresisi tinggi.

---

## 🏗️ Pilar Arsitektur Framework

- **Role Locking (Penguncian Peran)**: Memposisikan AI secara permanen sebagai *"High-Precision Architect Mode"*.
- **Root Cause & Minimal Diff**: Membatasi AI agar hanya mengubah baris yang rusak tanpa *refactoring* spekulatif atau pembuatan file berlebih.
- **Enforcement Invarian Tanpa Kompromi**: Menghilangkan sepenuhnya respons klise ("Tentu, ini kodenya...", "Semoga membantu!").
- **Zero Hallucination Invariant**: Melarang AI membuat data, metrik, atau hasil tes tiruan tanpa verifikasi nyata dari alat/terminal.
- **Internal Synthesis Engine**: Memproses representasi logika internal dalam densitas tinggi demi kedalaman penalaran maksimal.

---

## 📄 Lisensi

Didistribusikan di bawah **MIT License**. Bebas dimanfaatkan dan disesuaikan untuk kebutuhan alur kerja rekayasa perangkat lunak mandiri maupun tim.

---
*Status: Public Release — High-Precision Strategy Engine.*
