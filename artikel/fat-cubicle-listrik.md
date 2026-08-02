---
article_id: CUB-14-A02
title: "Menyusun FAT Cubicle Listrik yang Bisa Ditelusuri"
slug: "fat-cubicle-listrik"
description: "Pembaca dapat menyusun ruang lingkup, prosedur yang disetujui, instrumen dan kalibrasi, identitas unit, verifikasi rutin, uji fungsi, titik saksian atau penahanan, hasil, cacat, dan pelepasan."
status: draft
publication_date: "2026-03-20"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-14
primary_intent: "Menyiapkan factory acceptance test"
reader_community: "Cubicle.co.id"
reader_address: "Sobat Cubicle.co.id"
final_route: "/artikel/fat-cubicle-listrik.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021"
  - "https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021"
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
---

# Menyusun FAT Cubicle Listrik yang Bisa Ditelusuri

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-008`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi cubicle listrik 1](/wp-content/uploads/2023/01/cubicle-listrik-1.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `cubicle listrik 1` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-008]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

Halo, Sobat Cubicle.co.id!

FAT (factory acceptance test) cubicle listrik yang bisa ditelusuri bukan sekadar lembar “lulus”. Yang dicari owner, witness, EPC, dan manufacturer adalah rantai bukti: cakupan yang disepakati, prosedur yang disetujui, alat ukur dan kalibrasinya, identitas unit, hasil tiap pemeriksaan, keputusan atas deviasi, sampai dokumen persetujuan lanjut. Jika satu mata rantai hilang, hasil sulit dibedakan dari klaim visual.

Jawaban singkatnya: bekukan cakupan dan acceptance criteria lebih dulu, cocokkan setiap langkah dengan dokumen desain serta serial unit, lalu catat siapa melakukan apa, dengan instrumen mana, kapan, dan terhadap kriteria apa. Nilai atau metode pengujian listrik yang spesifik tetap harus berasal dari desain yang disetujui dan personel kompeten; artikel ini tidak menetapkan test voltage/current atau mengarahkan pembaca membuka equipment. [NEEDS PROJECT TEST CRITERIA: CUB-12-A07]

![Ilustrasi cubicle listrik 1](/wp-content/uploads/2023/01/cubicle-listrik-1.jpg)


*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*

## Hasil akhir dan prasyarat

Hasil FAT adalah paket yang dapat dibaca ulang tanpa menghadirkan orang yang sama: agenda dan attendance, approved procedure, drawing/BOM yang menjadi kondisi acuan, daftar instrumen, sertifikat kalibrasi, serial number, checklist, lembar hasil, daftar punch atau defect, serta berita acara persetujuan lanjut atau conditional persetujuan lanjut. Tetapkan sejak awal siapa yang berwenang menyetujui prosedur, menyaksikan titik tahan, menerima deviasi, dan menandatangani penutupan. Bila perlu menyamakan istilah dokumen dengan konteks situs, gunakan [beranda Cubicle.co.id](/) sebagai titik rujuk umum, bukan sebagai bukti teknis.

Prasyaratnya bukan hanya cubicle selesai dirakit. Siapkan revisi desain yang berlaku, konfigurasi aktual, data nameplate, metode keselamatan, status alat ukur, dan akses ke rekaman inspeksi internal. Kerangka bangunan nasional mengingatkan bahwa keputusan pada elemen bangunan berhubungan dengan keselamatan, kesehatan, kenyamanan, fungsi, dokumentasi, dan penggunaan; label produk saja tidak membuktikan kepatuhan ([PP No. 16 Tahun 2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021)). Prinsip yang sama membantu menahan godaan menganggap label “tested” sebagai bukti lengkap.

## Langkah 1 — tetapkan ruang lingkup

Tulis cakupan sebagai batas yang bisa dicentang. Identifikasi unit atau lineup, jumlah panel, konfigurasi, aksesori, antarmuka kontrol, dan dokumen rujukan. Nyatakan pula yang tidak termasuk: misalnya penetapan rating desain, perubahan wiring tanpa approval, atau pengujian site yang memang baru mungkin setelah instalasi. Untuk setiap item, tentukan apakah diperiksa dokumen, visual, fungsi, atau pengukuran oleh personel yang ditunjuk.

Buat matriks requirement-to-test: requirement atau drawing di kolom kiri, metode verifikasi di tengah, dan bukti yang harus dilampirkan di kanan. Jangan menyalin toleransi dari produk lain. Pada sistem cubicle, konfigurasi panel, support, pengikat, bukaan, dan urutan pemasangan dapat mengubah stabilitas serta akses pemeliharaan; instruksi manufacturer harus dicocokkan dengan sistem yang benar ([petunjuk instalasi Bobrick](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf)). Jika kondisi acuan belum disetujui, cakupan FAT belum siap dibekukan.

## Langkah 2 — kumpulkan dan cocokkan bukti

Gunakan satu register dokumen dengan nomor revisi. Cocokkan drawing, BOM, datasheet, wiring diagram, I/O list, procedure, dan inspection record terhadap serial unit. Bila nama material atau konfigurasi berubah, tandai sebagai substitution/deviation dan minta disposition tertulis; jangan mengubah checklist diam-diam. Bukti untuk bagian yang akan tertutup harus diperoleh sebelum penutupan, karena kondisi tersembunyi tidak dapat diverifikasi andal setelah ditutup ([Permen PUPR No. 10 Tahun 2021](https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021)).

Register instrumen minimal memuat identitas alat, rentang yang relevan, status kalibrasi, tanggal berlaku, dan operator. Di lembar hasil, sisakan ruang untuk kondisi awal, langkah aktual, unit, kriteria penerimaan, hasil, tanda tangan, dan lampiran. Catatan “OK” tanpa referensi instrumen atau serial tidak cukup untuk penelusuran. Sobat Cubicle.co.id, lakukan spot-check: pilih satu hasil secara acak dan pastikan Anda bisa kembali ke unit, revisi prosedur, sertifikat alat, serta foto atau record pendukungnya.

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman adalah: briefing dan verifikasi keselamatan; pemeriksaan identitas serta kelengkapan; tinjauan dokumen dan konfigurasi; inspeksi visual/rutin sesuai prosedur; functional test pada fungsi yang disepakati; pencatatan hasil; lalu tinjauan bersama dan disposition. Pengujian fungsi harus membuktikan intended function, bukan hanya tampilan selesai. Jangan mengarang angka uji: metode, batas, dan koneksi harus diisi dari approved procedure proyek dan dilakukan personel kompeten. [NEEDS APPROVED PROCEDURE AND TEST VALUES]

Setiap langkah memiliki status: witness (pihak tertentu hadir), hold (pekerjaan berhenti sampai rilis), tinjauan, atau record. Cantumkan kondisi setup dan reset setelah uji agar hasil dapat diulang. Bila fungsi bergantung pada antarmuka eksternal yang belum tersedia, nyatakan simulasi dan batas kesimpulannya; jangan menulis seolah-olah site performance sudah terbukti.

## Titik tahan dan kondisi berhenti

Hentikan FAT ketika serial tidak cocok, revisi drawing tidak jelas, segel atau komponen hilang, alat ukur kedaluwarsa kalibrasinya, procedure belum disetujui, atau witness wajib tidak hadir. Hentikan pula saat ada deviasi yang memengaruhi keselamatan, fungsi, integritas enclosure, atau dokumentasi. Kawan Cubicle.co.id, “lanjut dulu, rapikan berita acara nanti” justru memutus jejak keputusan dan berisiko membuat hasil yang tidak comparable.

Beri setiap defect nomor, deskripsi faktual, lokasi/unit, referensi requirement, pengusul tindakan, pemilik, dan status. Klasifikasikan apakah perlu re-test, engineering tinjauan, concession, atau penggantian. Tidak ada status “closed” sebelum bukti koreksi dan verifikasi ulang dilampirkan. Jika keputusan menyentuh compliance, garansi, atau perubahan desain, naikkan ke designer/QA/HSE dan pihak kontrak yang berwenang. [NEEDS PROFESSIONAL/PROJECT APPROVAL FOR G-01–G-14]

## Verifikasi hasil dan serah terima

Sebelum persetujuan lanjut, lakukan rekonsiliasi: semua item cakupan punya hasil; semua hasil punya kriteria dan instrumen; semua defect punya disposition; semua titik tahan punya tanda rilis; dan daftar deviasi tersalin ke berita acara. Paket serah terima sebaiknya memuat index dokumen, approved procedure dan revisinya, checklist bertanda tangan, raw record, sertifikat kalibrasi, serial register, daftar spare atau as-built yang memang diwajibkan kontrak, serta status open item.

Bedakan persetujuan lanjut penuh, persetujuan lanjut bersyarat, dan gagal. persetujuan lanjut bersyarat harus menyebut item terbuka, batas penggunaannya, pemilik tindakan, dan tenggat yang disetujui—bukan sekadar paraf. Permintaan komersial juga perlu dibandingkan pada cakupan yang sama: konfigurasi, material, support, testing, exclusions, garansi, spares, dan serah terima; luas atau lump sum terendah tidak otomatis setara. Jangan jadikan contoh spesifikasi vendor sebagai kontrak atau kewajiban hukum.

## Jalan pintas yang sering menggoda

Jalan pintas paling umum adalah memakai checklist lama lalu mengganti nomor proyek. Itu gagal ketika konfigurasi, revisi, antarmuka, atau acceptance criteria berbeda. Jalan yang lebih dapat dipertanggungjawabkan ialah memulai dari kondisi acuan yang disetujui, membuat matriks requirement-to-test, dan menandai setiap baris yang belum memiliki bukti. Dokumen yang lebih pendek tetapi lengkap jejaknya lebih berguna daripada formulir panjang yang tidak menunjukkan dasar keputusan.

## Kesimpulan

Menyusun FAT cubicle listrik yang bisa ditelusuri berarti menghubungkan cakupan, procedure, instrumen, serial, langkah verifikasi, witness/titik tahan, hasil, defect, dan persetujuan lanjut dalam satu paket yang konsisten. Teman Cubicle.co.id, tindakan berikutnya adalah meminta approved procedure dan kondisi acuan desain, lalu menguji satu sampel record dari awal hingga tanda rilis. Jangan menetapkan angka pengujian, menyatakan kepatuhan, atau menutup deviasi tanpa bukti proyek dan tinjauan personel kompeten.
