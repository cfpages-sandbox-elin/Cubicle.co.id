---
article_id: CUB-11-A01
title: "Panelboard, MDB, Switchboard, MCC, Switchgear, atau RMU?"
slug: "panelboard-mdb-switchboard-mcc-switchgear-rmu"
description: "Pembaca dapat membedakan fungsi, voltage range, switching/protection role, construction, maintenance, and typical application sebelum meminta produk."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-04"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-11
primary_intent: "Mengklasifikasikan electrical assembly"
reader_community: "Cubicle.co.id"
reader_address: "Sobat Cubicle.co.id"
final_route: "/artikel/panelboard-mdb-switchboard-mcc-switchgear-rmu.html"
technical_review: required
sources: []
---

# Panelboard, MDB, Switchboard, MCC, Switchgear, atau RMU?

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-005`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi bg cubicle](/wp-content/uploads/2023/01/bg-cubicle.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `bg cubicle` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-005]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

Halo, Sobat Cubicle.co.id! Keenam istilah ini bukan enam nama yang bisa dipertukarkan. Perbedaan utamanya ada pada fungsi rangkaian, tingkat tegangan, cara pemutusan dan proteksi, konstruksi, serta lokasi pemakaian. Panelboard biasanya melayani distribusi akhir bertegangan rendah; MDB (main distribution board) menjadi papan distribusi utama tegangan rendah; switchboard adalah rakitan distribusi dan switching yang dapat lebih luas; MCC (motor control centre) mengelompokkan kendali motor; switchgear menekankan switching, isolasi, dan proteksi; sedangkan RMU (ring main unit) adalah rakitan jaringan distribusi yang lazim dipakai pada sisi tegangan menengah.

Namun label itu belum cukup untuk membeli barang. Rating, arus hubung singkat, skema proteksi, koordinasi jaringan, ruang kerja, dan aturan proyek harus ditetapkan engineer. Karena paket ini tidak memuat lembar data atau standar listrik proyek, batas aman artikel ini adalah klasifikasi awal. **[NEEDS ELECTRICAL DESIGN BASIS AND CURRENT PRODUCT/PROJECT EVIDENCE]**

![Ilustrasi bg cubicle](/wp-content/uploads/2023/01/bg-cubicle.jpg)


*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*

## Jawaban singkat dan salah paham utama

“Panel” adalah istilah payung untuk enclosure yang menampung penghantar, perangkat switching, proteksi, pengukuran, atau kontrol. Panelboard dan MDB sama-sama bisa tampak seperti kabinet berdiri, tetapi nama tidak otomatis menyatakan kelas tegangan atau kemampuan menahan gangguan. MDB menunjuk peran di hulu sistem tegangan rendah; panelboard lebih sering menunjuk distribusi cabang atau beban akhir. Batas aktualnya harus dibaca dari single-line diagram dan nameplate yang disetujui, bukan dari ukuran pintu.

Switchboard juga bukan sinonim universal MDB. Ia dapat berisi beberapa incoming, outgoing, busbar, meter, dan pemutus dengan konstruksi tertentu. Sebuah MDB mungkin diwujudkan sebagai switchboard, tetapi tidak setiap switchboard adalah MDB. Switchgear lebih menonjolkan fungsi switching, isolasi, interlock, dan proteksi—terutama ketika konsekuensi gangguan dan kebutuhan pemeliharaan menuntut pengaturan akses yang lebih ketat. **[NEEDS APPLICABLE SWITCHGEAR STANDARD, VOLTAGE CLASS, AND TYPE-TEST DOCUMENTS]**

MCC memiliki fokus berbeda: mengoperasikan dan melindungi motor melalui starter, contactor, overload, variable-speed drive, atau kombinasi yang ditentukan desain. Jadi, MCC bukan sekadar MDB yang diberi label baru. RMU biasanya merupakan unit ring pada distribusi tegangan menengah, dengan fungsi load-break switching, pembumian, dan proteksi sesuai konfigurasi jaringan. Apakah unit memakai gas, udara, atau teknologi lain adalah pertanyaan produk spesifik, bukan definisi yang boleh ditebak.

## Definisi dan batas objek

Klasifikasi ini menjelaskan peran assembly dalam sistem, bukan merekomendasikan merek, ukuran, atau rating. Satu proyek dapat memiliki panelboard di hilir, MDB di titik utama, MCC untuk motor, dan switchgear atau RMU di sisi tegangan menengah. Istilah yang sama dapat dipakai berbeda oleh vendor, sehingga dokumen kontrak harus mendefinisikan fungsi dan batas pasoknya.

Jangan menyamakan enclosure dengan sistem lengkap. Busbar, pemutus, relay, meter, terminal, kabel, pembumian, fondasi, ventilasi, dan interlock ikut menentukan hasil. **[NEEDS APPROVED cakupan-OF-SUPPLY AND INTERFACE DRAWINGS]**

## Cara kerjanya

Mulailah dari aliran energi. Sumber masuk ke perangkat incoming, melewati busbar atau kompartemen, lalu dibagi ke feeder. Perangkat switching memutus atau menghubungkan rangkaian; perangkat proteksi mendeteksi kondisi abnormal dan memerintahkan trip; metering memberi informasi operasi; interlock mencegah urutan tindakan yang berbahaya. Pada MCC, cabang-cabang itu berakhir pada motor dan rangkaian kontrol. Pada RMU, beberapa feeder membentuk titik jaringan yang dapat diisolasi untuk manuver distribusi.

Urutan ini menjelaskan mengapa konstruksi penting. Kompartemen, barrier, shutter, terminal, dan akses kabel menentukan siapa yang dapat bekerja, bagian mana yang tetap bertegangan, serta bagaimana inspeksi dilakukan. Pendinginan, derajat perlindungan enclosure, ruang tekuk kabel, dan posisi busbar memengaruhi desain fisik. Tidak ada angka universal untuk semua merek atau lokasi. **[NEEDS MANUFACTURER DRAWING, HEAT/SHORT-CIRCUIT DATA, AND INSTALLATION METHOD]**

Tanggung jawab pun berlapis: perancang menetapkan skema dan koordinasi; pemasok menyatakan konfigurasi yang dibuat; installer mengikuti instruksi dan memeriksa terminasi; operator menjalankan prosedur yang disahkan. Dokumen serah-terima semestinya menghubungkan nomor sirkuit, label, setting, hasil pengujian, dan revisi gambar.

## Faktor yang mengubah hasil

Pertama, tentukan kelas jaringan: tegangan rendah atau menengah, sistem tiga fasa atau konfigurasi lain, titik netral dan pembumian, serta karakter beban. Kedua, tentukan fungsi: distribusi umum, beban motor, pemindahan sumber, atau manuver jaringan ring. Ketiga, periksa lingkungan: dalam atau luar ruang, kelembapan, debu, korosi, ketinggian, suhu, dan akses publik. Keempat, lihat antarmuka bangunan: jalur kabel, fondasi, ventilasi, clearance, pintu, dan jalur evakuasi.

Kawan Cubicle.co.id, jangan menerima klaim “heavy duty”, “anti-busur”, atau “siap outdoor” tanpa definisi dan bukti yang tepat untuk konfigurasi yang ditawarkan. Brosur menjelaskan keluarga produk, tetapi tidak membuktikan bahwa susunan pemutus, busbar, dan enclosure tertentu memenuhi kebutuhan proyek. **[NEEDS COMPLETE TEST REPORTS, ROUTINE-TEST RECORDS, AND PROJECT ACCEPTANCE CRITERIA]**

Maintenance juga mengubah pilihan. Panel dengan akses depan saja memiliki kebutuhan ruang berbeda dari unit yang memerlukan akses belakang. Spare part, kemampuan isolasi, pengujian relay, pembersihan, dan kompetensi personel perlu direncanakan sebelum pembelian. Untuk RMU atau switchgear tegangan menengah, prosedur switching, pembumian, dan penguncian harus berasal dari desain serta aturan operasi yang disahkan.

## Contoh keputusan praktis

| Kebutuhan awal | Istilah yang mungkin relevan | Pertanyaan pengunci |
|---|---|---|
| Membagi daya tegangan rendah ke banyak sirkuit bangunan | Panelboard atau MDB | Apakah ini distribusi akhir atau titik utama? |
| Menggabungkan incoming, busbar, feeder, dan metering utama | MDB yang diwujudkan sebagai switchboard | Berapa sumber, feeder, dan skema transfernya? |
| Menjalankan banyak motor dengan kendali terpusat | MCC | Jenis starter, kontrol, dan filosofi operasi apa yang disetujui? |
| Switching serta proteksi dengan kebutuhan isolasi dan interlock | Switchgear | Kelas tegangan, arus gangguan, dan akses kerja apa yang ditetapkan? |
| Titik jaringan ring tegangan menengah | RMU | Topologi ring, titik pembumian, dan metode manuvernya bagaimana? |

Gunakan tabel ini untuk menyusun pertanyaan, bukan untuk memilih rating. Jika beban utama ternyata kumpulan pompa dan fan, label “MDB” tidak menjawab kebutuhan kendali motor. Sebaliknya, jika fungsi hanya feeder tegangan rendah, menyebut “switchgear” dapat membingungkan lingkup dan biaya. Engineer harus mengonfirmasi arus desain, fault level, selektivitas, dan koordinasi proteksi. **[NEEDS APPROVED SINGLE-LINE DIAGRAM AND PROTECTION STUDY]**

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memilih berdasarkan nama dagang atau foto kabinet. Minta datasheet, GA drawing, diagram satu garis, daftar komponen, kelas enclosure, dan matriks pengujian untuk konfigurasi aktual. Kesalahan kedua adalah menganggap tegangan cukup dijawab oleh satu angka pada brosur; kelas isolasi, impulse withstand, clearances, dan metode terminasi harus cocok dengan sistem.

Kesalahan ketiga adalah menyalin rating pemutus dari proyek lain. Rating harus mengikuti beban, kabel, prospective fault current, derating, dan koordinasi. Kesalahan keempat adalah melupakan pekerjaan setelah energisasi: ruang tarik kabel, akses relay, termografi, pengencangan, pembersihan, serta ketersediaan komponen pengganti. Buat daftar verifikasi dan minta setiap jawaban ditautkan ke revisi dokumen yang dapat diaudit.

## Saat vendor menawarkan jalan pintas

jalan pintas yang sering menarik adalah meminta vendor “tentukan saja panel yang paling aman”. Vendor dapat menawarkan konfigurasi, tetapi keputusan keselamatan dan rating tidak boleh dipindahkan tanpa basis desain dan persetujuan engineer. Cara yang lebih andal: berikan single-line diagram, data sumber dan beban, kondisi lokasi, filosofi operasi, serta batas ruang; lalu minta penawaran yang menyebut asumsi, pengecualian, dan dokumen pembuktiannya.

## Langkah berikutnya

Panelboard, MDB, switchboard, MCC, switchgear, dan RMU dibedakan terutama oleh fungsi dalam sistem dan cara switching/proteksinya, bukan oleh bentuk kabinet atau istilah pemasaran. Teman Cubicle.co.id, sebelum meminta harga, siapkan diagram satu garis, data beban dan sumber, kondisi lokasi, kebutuhan maintenance, serta kriteria pengujian. Minta engineer menetapkan kelas tegangan, fault level, koordinasi, rating, dan konfigurasi; kemudian cocokkan penawaran dengan dokumen itu. Anda dapat memulai daftar dokumen dari [beranda Cubicle.co.id](/), lalu kembali ke spesifikasi proyek yang disahkan. Jika bukti desain atau produk belum tersedia, tandai **[NEEDS ENGINEER REVIEW]** dan jangan mengubah klasifikasi awal menjadi keputusan pembelian.
