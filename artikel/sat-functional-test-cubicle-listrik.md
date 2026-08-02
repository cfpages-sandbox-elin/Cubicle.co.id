---
article_id: CUB-14-A06
title: "SAT dan Functional Test Cubicle Listrik"
slug: "sat-functional-test-cubicle-listrik"
description: "Pembaca dapat menyusun prerequisites, isolation, inspection, wiring/control, interlock, protection, communication, alarms, trip paths, records, defects, and retest."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-04-03"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-14
primary_intent: "Menyiapkan site acceptance testing"
reader_community: "Cubicle.co.id"
reader_address: "Kawan Cubicle.co.id"
final_route: "/artikel/sat-functional-test-cubicle-listrik.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021"
  - "https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021"
---

# SAT dan Functional Test Cubicle Listrik

Halo, Kawan Cubicle.co.id! SAT (site acceptance test) dan functional test cubicle listrik bukan sekadar menyalakan panel lalu menandai “OK”. Hasil yang dapat dipertanggungjawabkan adalah bukti bahwa cubicle yang terpasang sesuai dokumen proyek, aman untuk diuji, setiap fungsi yang disepakati merespons pada kondisi yang benar, dan setiap defect memiliki keputusan tindak lanjut. Untuk menata dokumen pendukung dan konteks proyek, gunakan [beranda Cubicle.co.id](/) sebagai titik kembali, bukan sebagai bukti teknis.

Urutan praktisnya: tetapkan cakupan dan kewenangan, pastikan prerequisites serta isolation, cocokkan gambar dan konfigurasi, lakukan inspeksi, uji fungsi kontrol–interlock–proteksi–komunikasi secara terkendali, rekam hasil dan defect, lalu ulangi bagian yang gagal. Nilai setting, metode injection, dan keputusan energization tidak boleh ditebak dari artikel ini; semuanya harus berasal dari prosedur proyek yang disetujui dan ditangani personel berkompeten. **[NEEDS PROJECT-APPROVED TEST PROCEDURE AND SETTINGS]**

![Ilustrasi cubicle listrik](/wp-content/uploads/2023/01/cubicle-listrik.jpg)

Ilustrasi umum dari aset lokal Cubicle.co.id; bukan dokumentasi proyek tertentu.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-009`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi cubicle listrik](/wp-content/uploads/2023/01/cubicle-listrik.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `cubicle listrik` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-009]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Hasil akhir dan prasyarat

Sebelum tanggal witness, sepakati apa yang diterima: identitas cubicle, feeder atau fungsi yang diuji, batas antarmuka, daftar skenario, saksi, serta kriteria pass/fail. Otoritas pengujian harus jelas—misalnya commissioning lead, pemilik sistem, vendor, dan HSE/QA—beserta siapa yang boleh memberi izin isolasi dan menutup punch list. Jangan memulai hanya karena cubicle sudah tampak rapi.

Siapkan single-line diagram, schematic kontrol, wiring list, terminal schedule, datasheet, nameplate, approved method statement, risk assessment, permit, formulir hasil, dan daftar alat ukur dengan status kalibrasi. Cocokkan revisi dokumen dengan cubicle yang berada di lapangan. Jika gambar, label, atau konfigurasi tidak cocok, tahan pengujian pada bagian tersebut dan minta klarifikasi tertulis.

Dalam kerangka bangunan nasional, keputusan instalasi dan serah-terima berkaitan dengan keselamatan, kesehatan, kenyamanan, fungsi, serta dokumentasi penggunaan bangunan; label produk saja tidak membuktikan kepatuhan ([PP No. 16 Tahun 2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021)). Untuk rangkaian listrik, detail kriteria penerimaan tetap harus berasal dari basis desain dan persetujuan proyek.

## Langkah 1 — tetapkan ruang lingkup

Tuliskan boundary: cubicle mana, incoming atau outgoing mana, sumber kontrol apa, sinyal ke sistem mana, dan kondisi operasi yang disimulasikan. Pisahkan pemeriksaan instalasi dari uji fungsi. Pastikan antarmuka upstream, downstream, CT/VT, relay, PLC/SCADA, battery/UPS, dan jaringan komunikasi sudah memiliki owner dan status siap.

SAT bukan pengganti uji pabrikan atau pemeriksaan instalasi yang belum selesai. Jangan memasukkan test injection, perubahan setting relay, pembukaan enclosure bertegangan, atau energization gate ke langkah generik ini. **[NEEDS PROFESSIONAL REVIEW: TEST BOUNDARY, HAZARD CONTROLS, AND ENERGIZATION AUTHORITY]**

Buat matriks skenario sederhana: kondisi awal, aksi operator atau simulasi input, respons yang diharapkan, indikasi lokal/remote, trip atau permissive, dan bukti yang harus disimpan. Matriks ini menghindari satu fungsi diuji dua kali sementara fungsi lain terlupakan.

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dari identitas: tag cubicle, feeder, serial number, drawing revision, relay type, firmware, auxiliary supply, dan terminal yang dipakai. Lanjutkan dengan inspeksi visual tanpa menganggap “tidak terlihat masalah” sebagai bukti fungsi. Periksa penandaan, akses, kebersihan, enclosure, gland, bonding/earthing yang ditentukan desain, serta kondisi komponen dan interlock mekanis.

Untuk wiring dan kontrol, cocokkan nomor terminal, polaritas yang ditentukan desain, kontak NO/NC, sumber DC/AC kontrol, dan jalur ke annunciator atau SCADA dengan schematic. Gunakan continuity atau simulasi hanya dalam metode yang disetujui. Jangan menyalin toleransi, beban, atau dimensi dari manual produk lain; konfigurasi, support, fixing, dan urutan pemasangan memengaruhi bukti sistem dan harus diverifikasi terhadap dokumen vendor/proyek ([Permen PUPR No. 10 Tahun 2021](https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021)).

Minta bukti kesiapan yang dapat diaudit: checklist pre-commissioning bertanda tangan, sertifikat kalibrasi, daftar deviasi, approved redline, dan izin isolasi. Jika item tersembunyi akan tertutup atau sulit diakses, simpan foto, checklist, dan as-built sebelum penutupan; bukti yang hilang tidak dapat diganti dengan asumsi.

## Langkah 3 — jalankan urutan kerja

1. **Briefing dan isolasi.** Konfirmasi permit, batas area, sumber energi, status zero-energy sesuai prosedur keselamatan setempat, serta komunikasi dengan semua pihak. Pasang pengamanan dan identifikasi titik isolasi; hanya petugas berwenang yang boleh mengubah statusnya.
2. **Inspeksi awal.** Catat kondisi sebelum alat uji dipasang. Hentikan langkah berikutnya bila identitas, wiring, atau protective cover tidak sesuai dokumen.
3. **Wiring dan kontrol.** Dengan kondisi aman dan metode disetujui, beri input simulasi yang ditentukan matriks. Pastikan perintah open/close, indikasi posisi, local/remote, permissive, dan feedback mengikuti desain—bukan sekadar lampu menyala.
4. **Interlock dan trip path.** Uji setiap prasyarat dan larangan operasi secara berurutan. Verifikasi bahwa perintah yang tidak diizinkan ditolak dan jalur trip menghasilkan indikasi yang benar. Jangan mem-bypass interlock untuk “mempercepat” witness kecuali bypass itu sendiri disahkan, dikendalikan, dan dipulihkan.
5. **Proteksi, alarm, dan komunikasi.** Konfirmasi status relay, alarm, event, time stamp, dan komunikasi lokal/remote terhadap skenario yang disepakati. Nilai pickup, kurva, dan setting adalah data proyek; jangan mengarang atau mengubahnya di lapangan. **[NEEDS RELAY COORDINATION STUDY AND APPROVED SETTING SHEET]**
6. **Reset dan pemulihan.** Kembalikan setiap simulasi, selector, latch, test switch, dan alarm ke kondisi normal. Rekonsiliasi status fisik dengan HMI/SCADA dan minta saksi mengonfirmasi akhir pengujian.

## Titik tahan dan kondisi berhenti

titik tahan berlaku bila permit atau isolasi tidak jelas, dokumen berbeda revisi, label tidak terbaca, alat ukur kedaluwarsa kalibrasinya, ada kerusakan, protective earth atau cover belum siap, input simulasi tidak dapat dikendalikan, atau respons sistem berbeda dari matriks. Temuan keselamatan selalu mengalahkan target jadwal.

Kawan Cubicle.co.id, defect yang tampak kecil dapat mengubah makna hasil: satu kontak auxiliary tertukar bisa membuat interlock seolah-olah lulus, sementara sinyal remote salah alamat. Catat kondisi aktual, hentikan skenario terdampak, dan minta keputusan engineer/vendor. Jangan menghapus jejak dengan mengedit lembar hasil setelah witness.

## Verifikasi hasil dan serah terima

Lembar SAT sebaiknya memuat tanggal, lokasi, tag, revisi dokumen, prasyarat, skenario, input, respons aktual, pass/fail, instrumen, saksi, dan referensi bukti. Untuk alarm atau trip, simpan event log, tangkapan layar yang diizinkan, dan catatan reset. Setiap fail mendapat nomor defect, deskripsi faktual, owner, klasifikasi dampak, tindakan koreksi, dan status retest.

Retest tidak berarti mengulang semua hal secara membabi buta. Tentukan fungsi yang terdampak oleh koreksi, prasyarat yang harus diulang, dan bukti bahwa kondisi normal sudah dipulihkan. Tanda tangan penutupan hanya diberikan setelah hasil retest cocok dengan kriteria yang disetujui. Paket serah terima minimal berisi SAT yang disahkan, punch/defect register, as-built dan redline, setting sheet, sertifikat alat, daftar spare yang disepakati, serta catatan pengecualian. **[NEEDS PROJECT serah terima INDEX AND ACCEPTANCE CRITERIA]**

## Jalan pintas yang sering menggoda

“Panel sudah dites di pabrik, jadi di site cukup cek lampu.” jalan pintas ini gagal karena instalasi site menambahkan kabel, sumber kontrol, antarmuka komunikasi, interlock antarperalatan, kondisi mekanis, dan revisi dokumen yang tidak hadir pada konteks pabrik. Alternatif yang lebih aman adalah memakai FAT sebagai bukti pendukung, lalu membuktikan ulang fungsi yang bergantung pada instalasi dan konfigurasi site melalui matriks SAT.

Sebelum witness, susun daftar kesiapan yang dapat dicentang. Periksa bahwa tag dan label cocok, gambar serta setting sheet berada pada revisi yang disetujui, alat ukur masih berlaku, area aman, dan saksi memahami skenario. Tautkan setiap skenario pada input yang diberikan, respons yang diharapkan, batas lulus, serta bukti yang akan disimpan. Jika satu prasyarat belum terpenuhi, tandai statusnya terbuka dan jelaskan dampaknya pada jadwal. Daftar ini membantu tim membedakan pengujian tertunda dari pengujian gagal.

Selama pelaksanaan, seorang pencatat sebaiknya menjaga urutan waktu dan perubahan kondisi. Catat siapa yang mengubah selector atau simulasi, kapan alarm muncul, dan kapan sistem dikembalikan normal. Jangan menyalin hasil dari unit lain atau menggabungkan rekaman dari revisi berbeda. Setelah sesi, commissioning lead meninjau anomali, menentukan retest, dan mengesahkan paket bukti. Dengan disiplin ini, SAT memberi dasar keputusan yang dapat ditelusuri tanpa memperluas artikel menjadi prosedur energisasi.

## Kesimpulan

SAT dan functional test cubicle listrik yang baik menghasilkan keputusan berbasis bukti: cakupan jelas, isolasi sah, dokumen cocok, fungsi diuji berurutan, defect ditahan atau ditutup dengan retest, dan serah terima dapat ditelusuri. Langkah berikutnya adalah meminta commissioning lead mengesahkan matriks skenario, permit/isolation plan, setting sheet, serta acceptance criteria sebelum jadwal witness.

Teman Cubicle.co.id, bila satu saja dari dokumen atau pengaman itu belum tersedia, tandai **[NEEDS TECHNICAL REVIEW]** dan tahan fungsi terkait. Artikel ini membantu menyiapkan percakapan dan rekaman; keputusan setting, keselamatan, dan energization tetap berada pada prosedur proyek serta tenaga profesional yang berwenang.
