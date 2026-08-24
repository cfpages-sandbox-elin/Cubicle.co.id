---
article_id: CUB-11-A02
title: "Kamus Rating dan Istilah pada Nameplate Cubicle Listrik"
slug: "kamus-rating-nameplate-cubicle-listrik"
description: "Pembaca dapat mengenali rated voltage/current/frequency, short-circuit terms, IP/IK, insulation, standards, serial, and ambiguity yang harus diklarifikasi."
writing_contract_version: "native-id-v2"
status: draft
publication_date: "2026-01-07"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-11
primary_intent: "Memahami istilah nameplate"
reader_community: "Cubicle.co.id"
reader_address: "Sobat Cubicle.co.id"
final_route: "/artikel/kamus-rating-nameplate-cubicle-listrik.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021"
  - "https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf"
---

# Kamus Rating dan Istilah pada Nameplate Cubicle Listrik

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

Halo, Sobat Cubicle.co.id! Nameplate bukan sekadar label untuk difoto saat serah terima. Ia adalah indeks identitas dan batas penggunaan yang perlu dicocokkan dengan single-line diagram, spesifikasi pembelian, serta dokumen pengujian. Istilah seperti **rated voltage**, **rated current**, **frequency**, dan **short-circuit rating** membantu Anda tahu apa yang harus ditanyakan; istilah itu sendiri belum membuktikan bahwa rating tersebut cukup untuk sistem Anda.

Cara aman membacanya adalah memisahkan tiga hal: identitas unit, rating yang dinyatakan pabrikan, dan bukti bahwa konfigurasi yang dikirim memang memenuhi kebutuhan proyek. Kecukupan rating memerlukan studi sistem dan persetujuan profesional; hal itu berada di luar kamus ini. Jika angka, kode, atau arti singkatan pada pelat tidak cocok dengan dokumen vendor, tahan keputusan dan minta klarifikasi tertulis.

![Ilustrasi cubicle listrik 1](/wp-content/uploads/2023/01/cubicle-listrik-1.jpg)


*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*

## Jawaban singkat: angka nameplate belum sama dengan kecukupan sistem

Bagian ini membantu Anda menjawab pertanyaan paling sering muncul saat melihat pelat: informasi apa yang ada, dan apa yang belum bisa diputuskan dari sana. Dengan begitu, Anda tidak menganggap satu angka atau logo standar sebagai bukti bahwa cubicle sudah cocok.

Nameplate biasanya memuat nomor model, serial, tahun pembuatan, tegangan dan arus nominal, frekuensi, kemampuan menahan hubung singkat, kelas proteksi selubung, tingkat isolasi, serta standar acuan. Bacalah setiap istilah bersama satuannya, kondisi pengujiannya, dan komponen yang dicakup. “400 V” tanpa penjelasan apakah itu tegangan operasi atau batas isolasi belum cukup untuk memilih cubicle. Demikian pula “25 kA” harus ditanya: arus hubung singkat yang mana, untuk durasi berapa, pada titik mana, dan bagian mana yang terverifikasi.

Kawan Cubicle.co.id, jangan menyamakan merek atau bentuk pelat yang mirip dengan kesetaraan teknis. Serial number mengidentifikasi unit tertentu; ia bukan sertifikat performa. Standar yang tercetak menunjukkan rujukan, bukan otomatis bahwa semua persyaratan standar telah dipenuhi. Minta datasheet, gambar rangkaian, laporan uji yang relevan, dan daftar deviasi sebelum menyimpulkan.

## Definisi cubicle dan batas pembacaan nameplate

Sebelum membaca singkatan, pastikan dulu benda yang sedang diidentifikasi dan keputusan apa yang memang hendak dibuat. Jembatan ini mencegah kamus istilah dipakai sebagai pengganti perhitungan atau pemeriksaan teknis; bagian berikut membatasi objek dan hasil yang boleh Anda simpulkan.

**Cubicle** di sini berarti rakitan panel atau *switchgear* (peralatan pemutus dan penghubung listrik) yang identitasnya ditunjukkan oleh *nameplate* (pelat identitas). Kamus ini membahas cara mengenali istilah, bukan menghitung arus gangguan, koordinasi proteksi, atau menetapkan ukuran penghantar. Jangan gunakan artikel ini untuk mengesahkan instalasi, menentukan rating akhir, atau menggantikan inspeksi.

## Cara membaca kelompok rating pada nameplate

Setelah objeknya jelas, pembacaan paling aman dilakukan dari identitas ke rating lalu ke bukti pendukung. Urutan ini menjawab apa yang harus dicatat, bagaimana istilah bekerja dalam konteksnya, dan pertanyaan apa yang perlu dikirim ke vendor sebelum keputusan dibuat.

Mulailah dari identitas: pabrikan (*manufacturer*), tipe atau model, nomor seri (*serial number*), tanggal atau tahun produksi, dan diagram referensi. Catat tulisan persis, termasuk tanda hubung dan sufiks. Lalu kelompokkan rating berikut.

| Istilah pada nameplate | Cara membacanya | Pertanyaan klarifikasi |
|---|---|---|
| Rated voltage (Ue/Ur) | Tegangan nominal yang dinyatakan untuk fungsi tertentu; jangan tebak apakah operasi, isolasi, atau keduanya. | Untuk rangkaian mana dan pada kondisi apa? |
| Rated current (In/Ib) | Arus nominal yang terkait dengan konfigurasi tertentu. | Apakah berlaku untuk incoming, feeder, busbar, atau satu kompartemen? |
| Frequency (Hz) | Frekuensi sistem yang dirujuk. | Apakah 50/60 Hz, dan apakah ada batas operasi lain? |
| Short-circuit terms (Icw, Ipk, Icc/Icu) | Kode kemampuan hubung singkat; makna dan durasi harus mengikuti datasheet/standar yang dipakai. | Nilai RMS atau puncak? Berapa lama? Titik dan perangkat pembatasnya apa? |
| Insulation level / withstand | Istilah terkait kemampuan isolasi dan uji ketahanan. | Uji apa, pada konfigurasi apa, dan laporan mana yang membuktikannya? |
| IP / IK | Kode perlindungan selubung terhadap masuknya benda/air atau benturan mekanis. | Kode berlaku untuk selubung lengkap atau bagian tertentu? |
| Standard | Standar rujukan yang tercetak. | Edisi, ruang lingkup, dan sertifikat/laporan yang tersedia? |
| Serial / batch | Identitas unit atau kelompok produksi. | Apakah cocok dengan packing list, FAT, dan drawing revisi terakhir? |

Singkatan tidak boleh diperluas berdasarkan kebiasaan toko. Minta legend resmi pabrikan. Bila pelat memakai “Icw 25 kA/1 s”, perlakukan itu sebagai klaim yang perlu dicocokkan dengan laporan uji dan desain busbar, bukan sebagai izin untuk memasang pada sistem apa pun.

## Faktor yang mengubah arti angka nameplate

Angka yang sama dapat memberi keputusan berbeda ketika rakitan, lokasi, atau dokumen acuannya berubah. Bagian ini menunjukkan mekanisme perubahan itu agar Anda tahu kapan transkripsi nameplate cukup untuk pencocokan awal dan kapan harus berhenti untuk pemeriksaan lanjutan.

Angka nameplate berubah maknanya ketika konfigurasi berubah. Jumlah feeder, tipe breaker, busbar, sambungan kabel, ventilasi, segregasi, dan enclosure dapat memengaruhi jalur panas, isolasi, dan kemampuan menahan gaya elektromagnetik. Karena itu, serial yang benar tetap harus dicocokkan dengan BOM dan gambar as-built.

Lingkungan juga penting: suhu, kelembapan, debu, korosif, ketinggian, ruang kerja, serta akses pemeliharaan. Kode IP pada pintu tidak otomatis menggambarkan sambungan kabel atau bagian belakang. Istilah IK tidak boleh dipakai untuk menyimpulkan ketahanan seluruh ruangan. Untuk antarmuka bangunan, survei harus memeriksa struktur, void plafon, utilitas tersembunyi, sprinkler, jalur data, dan kapasitas substrat; panduan FEMA menekankan pentingnya interface dan pengikatan elemen nonstruktural ([FEMA E-74](https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf)).

Dokumen nasional dan standar yang disebut vendor juga perlu konteks. Peraturan seperti PP No. 16 Tahun 2021 bukan pengganti spesifikasi teknis atau verifikasi produk ([BPK](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021)). Jangan menyimpulkan kepatuhan hanya karena nama peraturan tercetak di penawaran.

## Contoh keputusan praktis dari empat angka

Contoh berikut menerjemahkan istilah menjadi tindakan yang bisa dilakukan pembaca, bukan persetujuan desain. Ikuti urutannya untuk melihat bagaimana satu ketidakjelasan mengubah keputusan dari “sesuai” menjadi “perlu klarifikasi”.

Misalkan pelat menyebut “11 kV, 630 A, 50 Hz, 25 kA”. Langkah pembaca bukan langsung menyetujui pembelian. Buat empat kolom pemeriksaan:

1. Cocokkan 11 kV dengan tegangan sistem pada SLD dan dokumen utilitas.
2. Tanyakan apakah 630 A berlaku pada incoming lengkap atau hanya rating busbar/feeder tertentu.
3. Minta definisi 25 kA, durasi, titik penerapan, serta laporan uji untuk konfigurasi yang sama.
4. Cocokkan serial, model breaker, CT/VT, dan revisi gambar dengan unit yang akan dikirim.

Jika satu jawaban belum tersedia, statusnya “perlu klarifikasi”, bukan “diasumsikan sesuai”. Teman Cubicle.co.id, catat juga siapa yang harus menjawab—vendor, engineer proteksi, atau inspector—agar pertanyaan tidak berhenti sebagai catatan pembelian.

## Kesalahan umum saat menyalin dan menafsirkan pelat

Kesalahan pembacaan sering tampak kecil—satu sufiks terlewat atau satu kode dianggap universal—tetapi akibatnya bisa menjalar ke dokumen pembelian. Bagian ini memberi tanda yang dapat diperiksa sebelum Anda membubuhkan paraf.

Kesalahan pertama adalah menyalin angka dari brosur ke semua cubicle. Periksa nomor model dan suffix. Kedua, menganggap standar adalah hasil uji; minta laporan dan ruang lingkupnya. Ketiga, menyamakan IP dengan kedap total; periksa titik masuk kabel, gasket, dan kondisi pemasangan. Keempat, mengabaikan frekuensi dan kondisi lingkungan. Kelima, memakai serial sebagai bukti bahwa isi internal tidak berubah; cocokkan segel, BOM, dan FAT.

Gunakan checklist singkat sebelum paraf: foto pelat terbaca, transkripsi diverifikasi dua orang, satuan lengkap, istilah ambigu diberi tanda, dokumen rujukan tercantum, dan deviasi memiliki pemilik tindak lanjut.

## Jalan pintas yang perlu dihindari saat menyamakan rating

Ketika dikejar waktu, menyamakan angka dengan proyek lama terasa efisien. Bagian ini menjelaskan mengapa intuisi itu bisa gagal dan aturan pengganti yang membuat keputusan tetap dapat ditelusuri.

Jalan pintas yang sering dipilih adalah, “Angkanya sama dengan proyek lama, jadi pasti aman.” Itu gagal ketika arus gangguan, konfigurasi busbar, lingkungan, atau perangkat pembatas berbeda. Alternatif yang lebih andal: jadikan pelat sebagai titik awal penelusuran, lalu minta datasheet, gambar, laporan uji, dan tinjauan studi sistem untuk proyek ini. Bila dokumen tidak tersedia, tandai `[NEEDS TECHNICAL REVIEW: kecukupan rating dan arti kode short-circuit belum terverifikasi]` dan jangan mengisi kekosongan dengan angka perkiraan.

## Langkah penutup: ubah pembacaan menjadi daftar klarifikasi

Penutup ini merangkum tindakan yang bisa Anda lakukan setelah meninggalkan nameplate, sehingga artikel tidak berhenti pada hafalan istilah. Gunakan aturan terakhir untuk menentukan kapan dokumen siap diteruskan dan kapan keputusan harus ditahan.

Kamus nameplate membantu Anda mengenali identitas, rated voltage/current/frequency, istilah short-circuit, insulation, IP/IK, standar, dan serial. Ia tidak menjawab apakah cubicle cukup untuk sistem tertentu. Setelah membaca pelat, simpan transkripsi dan fotonya, cocokkan dengan SLD serta dokumen vendor, lalu kirim daftar pertanyaan yang belum terjawab kepada engineer atau pemeriksa berwenang. Untuk bacaan umum tentang situs ini, Anda dapat kembali ke [beranda Cubicle.co.id](/).

Aturan operasionalnya sederhana: tidak ada angka nameplate yang boleh berdiri sendiri. Setiap rating harus memiliki konteks konfigurasi dan bukti yang dapat diaudit; keputusan akhir tetap memerlukan tinjauan teknis.
