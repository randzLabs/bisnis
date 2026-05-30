---
name: laporan-growth-randzlabs
version: 1.0.0
description: Membuat laporan growth mingguan RandzLabs — kompilasi riset, konten, pipeline lead, dan rekomendasi aksi minggu depan
triggers:
  - "buat laporan"
  - "laporan mingguan"
  - "laporan growth"
  - "rangkuman minggu ini"
  - "weekly report"
  - "evaluasi minggu"
tags:
  - reporting
  - growth
  - weekly
  - analytics
  - randzlabs
author: RandzLabs
---

# Skill: Laporan Growth Mingguan RandzLabs

## Tujuan
Menghasilkan laporan mingguan yang jujur, singkat, dan actionable — mencakup semua aktivitas growth yang terjadi minggu ini dan rekomendasi konkret untuk minggu depan.

## Prinsip Laporan
- Jujur > optimis. Jika ada yang tidak berjalan, nyatakan.
- Angka > opini. Semua klaim harus ada datanya.
- Actionable > informatif. Setiap temuan harus berujung rekomendasi.
- Maksimal 1 halaman A4 — jika lebih panjang, ringkas.

## Data yang Dikumpulkan

### Dari Sesi Manus Minggu Ini
Review semua task yang sudah dikerjakan dalam 7 hari terakhir:
- Riset yang dilakukan
- Konten yang dibuat
- Temuan kompetitor baru
- Update komunitas UMKM

### Dari Input Manual Founder (tanyakan jika tidak tersedia)
- Berapa lead yang masuk minggu ini?
- Berapa yang sudah dihubungi?
- Berapa yang sudah demo atau meeting?
- Ada feedback dari calon klien atau klien aktif?
- Konten mana yang paling banyak respons?

## Format Laporan Output

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
GROWTH REPORT — RandzLabs
Minggu: [tanggal mulai] – [tanggal akhir]
Dibuat oleh: Growth Agent (Manus)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. ANGKA MINGGU INI
   Leads masuk      : [angka] (sumber: [channel])
   Follow-up        : [angka]
   Demo/meeting     : [angka]
   Deal closed      : [angka]
   Konten tayang    : [angka]
   Respons terbaik  : [judul konten + metrik]

2. RISET & TEMUAN
   Kompetitor baru  : [nama jika ada, atau "tidak ada temuan baru"]
   Tren UMKM lokal  : [1-2 temuan dari berita/komunitas minggu ini]
   Peluang baru     : [jika ada]

3. APA YANG BERJALAN
   - [item 1 + data pendukung]
   - [item 2 + data pendukung]

4. APA YANG TIDAK BERJALAN
   - [item 1 + analisis singkat kenapa]
   - [item 2]

5. REKOMENDASI MINGGU DEPAN
   Prioritas 1: [aksi spesifik + alasan]
   Prioritas 2: [aksi spesifik + alasan]
   Prioritas 3: [aksi spesifik + alasan]
   
   Eksperimen yang disarankan:
   [1 ide eksperimen kecil yang bisa dicoba minggu depan]

6. CATATAN UNTUK CEO
   [Jika ada hal yang perlu keputusan founder — anggaran, pivot, 
   atau sesuatu yang di luar otoritas Growth Agent]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

## Cara Menggunakan Skill Ini

**Dengan data lengkap:**
Berikan input: "Minggu ini lead masuk 5, 3 sudah dihubungi, 1 demo, 0 close. Konten terbaik adalah post tentang kasir manual."
→ Manus langsung buat laporan penuh.

**Tanpa data (Manus yang tanya):**
Jika founder tidak memberikan data, Manus HARUS tanya dulu:
"Untuk laporan mingguan, saya butuh beberapa angka dari kamu:
1. Berapa lead masuk minggu ini?
2. Berapa yang sudah dihubungi?
3. Konten mana yang paling banyak respons?
Boleh jawab singkat saja."

**Mode ringkas (jika waktu terbatas):**
Ketik: "/laporan-growth ringkas"
→ Output hanya bagian 1 (Angka) + 5 (Rekomendasi), tanpa analisis panjang.
