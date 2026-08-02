---
article_id: CUB-15-A07
title: "Spare Part dan Obsolescence Register Cubicle Listrik"
slug: "spare-part-obsolescence-cubicle-listrik"
description: "Pembaca dapat mencatat model/serial, firmware/software, interchangeable limits, shelf life, preservation, failure criticality, vendor support, last-buy, and contingency."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-05-05"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-15
primary_intent: "Mengelola supportability"
reader_community: "Cubicle.co.id"
reader_address: "Sobat Cubicle.co.id"
final_route: "/artikel/spare-part-obsolescence-cubicle-listrik.html"
technical_review: required
sources:
  - "https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0"
---

# Spare Part dan Obsolescence Register Cubicle Listrik
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

Spare part register bukan daftar belanja yang baru dibuka ketika cubicle listrik gagal. Ia adalah catatan identitas, kecocokan, kondisi penyimpanan, dan pilihan pemulihan untuk setiap komponen yang terpasang. Obsolescence register menambahkan pertanyaan waktu: kapan vendor berhenti mendukung, kapan firmware tidak lagi dipelihara, dan kapan keputusan last-buy atau penggantian harus dibuat.

Jawaban singkatnya: bangun satu register yang mengikat aset terpasang dengan bukti OEM dan keputusan risiko. Jangan menyatakan part pengganti aman hanya karena bentuk atau nomor katalog tampak sama. Batas interchangeable, rating, firmware, konfigurasi proteksi, dan persetujuan engineer harus diverifikasi untuk proyek ini. **[NEEDS OEM/ENGINEER VERIFICATION: kompatibilitas dan substitusi setiap part]**

![Ilustrasi cubicle listrik 1](/wp-content/uploads/2023/01/cubicle-listrik-1.jpg)


*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

Spare-part register menjawab “apa yang harus tersedia agar fungsi dapat dipulihkan?” Untuk cubicle listrik, objeknya dapat mencakup pemutus, relay proteksi, meter, modul komunikasi, kipas, heater, power supply, interlock, fuse, terminal, konektor, dan perangkat lunak konfigurasi—tetapi hanya jika benar-benar ada pada instalasi yang dicatat. Satu baris harus menunjuk ke satu part number dan satu posisi atau fungsi yang jelas.

Obsolescence register menjawab “apa yang akan membuat dukungan berhenti?” Tandai status produk, revisi perangkat keras, versi firmware/software, tanggal notifikasi end-of-sale atau end-of-support bila tersedia, serta pengganti resmi. Catatan ini tidak menetapkan kewajiban vendor atau umur pakai universal. Kontrak, manual OEM, dan kondisi proyek tetap menjadi sumber keputusan. **[NEEDS OEM/CONTRACT EVIDENCE: status dukungan dan tanggal last-buy]**

Di luar cakupan register ini adalah persetujuan pengadaan dan keputusan modifikasi instalasi. Bukti procurement berada di proses terpisah; register hanya menyediakan data teknis dan konsekuensi risiko agar permintaan tersebut dapat diperiksa.

## Cara kerjanya

Mulai dari as-built, nameplate, foto identitas, daftar I/O, dan backup konfigurasi. Buat kunci aset yang tidak berubah-ubah: lokasi cubicle, feeder atau fungsi, manufacturer, model, serial number, part number, hardware revision, firmware/software version, dan tanggal verifikasi. Jika sebuah nilai belum terbaca, tulis “belum diverifikasi”, bukan menebak dari seri yang mirip.

Tambahkan kolom interchangeable limits. Bedakan “pengganti resmi dengan prosedur OEM” dari “serupa secara fisik”. Catat syarat seperti revisi panel, soket, protokol komunikasi, CT/VT interface, setting proteksi, dimensi, dan kebutuhan commissioning. Selama bukti belum lengkap, statusnya *hold* dan tidak boleh dipasang sebagai substitusi.

Untuk stok, pisahkan shelf life dari preservation. Shelf life adalah batas yang ditentukan produsen untuk komponen tertentu; preservation adalah tindakan menjaga kondisi selama disimpan—kemasan, kelembapan, suhu, baterai, konektor, dan pemeriksaan berkala. Isi tanggal masuk, kondisi kemasan, lokasi, pemilik, dan bukti inspeksi. Nilai interval dan kondisi numerik harus berasal dari OEM atau prosedur site. **[NEEDS OEM/PROJECT PROCEDURE: shelf life, interval, dan batas lingkungan]**

Terakhir, beri failure criticality dan contingency. Criticality bukan label “mahal”, melainkan dampak kehilangan fungsi, waktu pemulihan, alternatif operasi yang disetujui, dan kebutuhan personel berwenang. Hubungkan setiap item kritis dengan rencana: stok lokal, repair exchange, vendor escalation, konfigurasi cadangan, atau strategi penggantian yang telah direkayasa.

## Faktor yang mengubah hasil

Installed base yang terlihat seragam sering menyimpan revisi berbeda. Dua relay dengan nama model sama dapat memiliki firmware, konektor, atau setting yang berbeda. Karena itu, model tanpa serial dan revision tidak cukup untuk menjamin kecocokan.

Lingkungan juga mengubah risiko. Debu, kondensasi, panas, getaran, korosi, dan siklus operasi dapat mempercepat kegagalan atau merusak stok sebelum dipakai. Prinsip pengendalian kelembapan bangunan dapat dipakai sebagai rujukan umum untuk mencari sumber air dan mencegah kerusakan berulang, tetapi bukan standar khusus panel listrik ([panduan EPA](https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0)). Catat kondisi aktual dan gejala, tetapi jangan mengubah gejala menjadi diagnosis tanpa pemeriksaan. Bila ada jejak air, panas berlebih, atau bau terbakar, hentikan asumsi “cukup ganti modul” dan minta penilaian teknis.

Ketergantungan software sering luput. Simpan file setting, checksum atau versi, lisensi, kabel/adapter, dan instruksi pemulihan sesuai aturan keamanan setempat. Backup tidak sama dengan bukti bahwa firmware baru kompatibel; perubahan versi memerlukan tinjauan dan uji yang ditetapkan OEM/proyek. **[NEEDS ENGINEER/COMMISSIONING EVIDENCE: dampak perubahan firmware atau setting]**

Kawan Cubicle.co.id, pisahkan fakta dari keputusan. “Vendor masih menjual” adalah fakta bertanggal; “kita aman menunda pembelian” adalah keputusan risiko yang harus memiliki pemilik, tanggal tinjau, dan pemicu eskalasi.

## Contoh keputusan praktis

Gunakan tabel sederhana berikut sebagai titik mulai, bukan sebagai persetujuan otomatis.

| Temuan register | Keputusan sementara | Bukti yang harus diminta |
|---|---|---|
| Part number, serial, revisi, dan firmware lengkap; dukungan aktif | Simpan stok sesuai criticality dan lead time yang disetujui | Datasheet/manual OEM dan catatan vendor bertanggal |
| Model sama, tetapi revisi atau konektor berbeda | Karantina sebagai kandidat; jangan pasang silang | Pernyataan interchangeability OEM dan tinjauan engineer |
| Vendor mengumumkan last-buy | Hitung kebutuhan installed base, stok, repair, dan rencana transisi | Notifikasi resmi, forecast kebutuhan, dan rencana teknis |
| Shelf life terlewati atau kemasan rusak | Tahan penggunaan dan lakukan inspeksi yang ditentukan OEM | Prosedur preservation, hasil inspeksi, keputusan teknis |
| Tidak ada backup firmware/setting | Perlakukan sebagai risiko pemulihan tinggi | Salinan resmi, lisensi, alat pemrograman, dan uji pemulihan |

Contoh ini sengaja tidak memberi angka stok atau umur simpan. Angka tersebut bergantung pada failure history, waktu kirim, redundansi, operasi, dan kontrak. **[NEEDS SITE DATA: criticality, lead time, failure history, dan target pemulihan]**

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menyalin daftar BOM lama tanpa mencocokkannya dengan serial yang terpasang. Pemeriksaan silang harus menunjukkan siapa yang memverifikasi, kapan, dari dokumen apa, dan apa yang berbeda.

Kesalahan kedua adalah menyamakan “pin-to-pin” dengan interchangeable. Tanyakan: apakah rating, setting, firmware, protokol, isolasi, interlock, dan metode pengujian tetap berlaku? Jika satu jawaban belum terbukti, status tetap *hold*.

Kesalahan ketiga adalah menyimpan part tanpa preservation log. Tempelkan identitas stok, segel, tanggal inspeksi, kondisi, dan tindakan berikutnya. Jangan menghapus riwayat hanya karena kemasan tampak baik.

Kesalahan keempat adalah menganggap obsolescence selesai setelah membeli last-buy. Register harus memuat rencana setelah stok habis: repair, redesign, retrofit, atau penggantian sistem. Opsi tersebut memerlukan studi dan persetujuan tersendiri.

Periksa register pada setiap perubahan cubicle, shutdown, penggantian modul, pembaruan firmware, dan pemberitahuan vendor. Teman Cubicle.co.id, tetapkan pemilik data dan tanggal tinjauan; register tanpa pemilik cepat berubah menjadi arsip yang tidak dapat dipakai saat gangguan.

## Jalan pintas yang perlu ditolak

Jalan pintas yang paling menggoda adalah membeli part dengan label “compatible” dari pemasok lalu memasangnya untuk mengejar waktu. Risiko utamanya bukan hanya part gagal menyala, tetapi setting proteksi, komunikasi, interlock, atau dokumentasi konfigurasi berubah tanpa jejak. Alternatif yang lebih aman adalah mengunci identitas part, meminta bukti OEM, menilai dampak engineering, dan mencatat keputusan *use*, *hold*, atau *reject* sebelum pemasangan.

## Penutup

Spare-part dan obsolescence register yang baik menghubungkan identitas aset, status dukungan, kondisi stok, criticality, dan rencana kontingensi. Langkah berikutnya adalah mengambil satu sampel cubicle, melengkapi kolom model/serial–firmware–revision, lalu minta OEM atau engineer mengesahkan batas interchangeable dan strategi last-buy. Untuk dokumentasi umum situs, Anda dapat kembali ke [beranda Cubicle.co.id](/). Jangan mengubah baris register menjadi izin substitusi; izin itu tetap menunggu bukti teknis dan persetujuan proyek.
