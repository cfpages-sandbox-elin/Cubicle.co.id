---
article_id: CUB-16-A02
title: "Menyusun BoQ dan Basis Kuantitas Cubicle"
slug: "boq-dan-basis-kuantitas-cubicle"
description: "Panduan menentukan unit dan baris pekerjaan, pengukuran dari gambar, pengecualian, susut, aksesori, pengujian, dokumen, serta dasar revisi tiap sistem."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-05-16"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUB-16
primary_intent: "Menghitung scope quantity yang dapat dibandingkan"
reader_community: "Cubicle.co.id"
reader_address: "Sobat Cubicle.co.id"
final_route: "/artikel/boq-dan-basis-kuantitas-cubicle.html"
technical_review: required
sources:
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
  - "https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende"
  - "https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzN2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi"
  - "https://peraturan.bpk.go.id/Details/37637/uu"
  - "https://peraturan.bpk.go.id/Details/161844/pp-no-14-tahun-2021"
  - "https://www.bobrick.com/resource-center-2/guide-specifications/"
  - "https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true"
  - "https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf"
  - "https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0"
  - "https://www.gypsum.org/wp-content/uploads/2011/11/GA-238-03.pdf"
  - "https://www.formica.com/zh-cn/-/media/project/formica/asia/documents/products-documents/compact/farbiration-guide_compact_2023.pdf?rev=692c868288044704aac2458e42c2bb23"
---

# Menyusun BoQ dan Basis Kuantitas Cubicle

Halo, Sobat Cubicle.co.id! Ketika beberapa vendor diminta menawar cubicle dari denah yang sama, perbedaan angka sering terlihat seperti perbedaan harga—padahal bisa berasal dari jumlah pintu, hardware, support, aksesori, atau pekerjaan yang tidak ditulis. BoQ (Bill of Quantities) membantu Anda melihat perbedaan cakupan itu sebelum memilih penawaran.

BoQ cubicle yang dapat dibandingkan bukan sekadar luas panel dikalikan harga. Basisnya adalah daftar line item (baris pekerjaan atau komponen) yang menyatakan sistem apa yang dihitung, satuannya, sumber dimensinya, pekerjaan yang termasuk, exclusions (pekerjaan yang dikecualikan), allowance susut (kelonggaran kuantitas), aksesori, pengujian, dokumen serah terima, dan revisi gambar yang berlaku.

Jawaban singkatnya: tetapkan basis pengukuran sebelum meminta penawaran. Ambil kuantitas dari gambar revisi yang disebutkan, pecah tiap sistem menjadi komponen yang bisa diverifikasi, lalu tulis asumsi dan exclusions di baris yang sama. Jika kondisi lapangan, detail sambungan, atau spesifikasi produk belum tersedia, jangan mengubahnya menjadi angka pasti; tandai sebagai `[NEEDS PROJECT SURVEY]` untuk ditutup oleh tim desain, kontraktor, dan QA. Dengan cara ini, artikel ini membantu Anda membandingkan cakupan—bukan berpura-pura menggantikan survei atau keputusan engineering.

![Ilustrasi cubicle](/wp-content/uploads/2023/01/cubicle.jpg)

Ilustrasi umum dari aset lokal Cubicle.co.id; bukan dokumentasi proyek tertentu.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-004`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi cubicle](/wp-content/uploads/2023/01/cubicle.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `cubicle` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-004]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Definisi BoQ cubicle dan batas objek yang dihitung

Sebelum menyusun tabel, kita perlu menyamakan apa yang dimaksud dengan objek hitungan. Bagian ini mencegah luas panel atau jumlah bilik dianggap sudah mewakili seluruh pekerjaan; kita akan membedakan isi BoQ dari keputusan engineering, harga, dan tanggung jawab proyek.

Dalam artikel ini, “cubicle” berarti sistem partisi atau enclosure yang akan dihitung untuk pengadaan dan pelaksanaan—misalnya panel, rangka, pintu, hardware, seal, trim, dan interface pendukung. BoQ menjawab “berapa dan apa yang diserahkan”; ia tidak menetapkan peringkat teknis, kapasitas struktur, atau harga yang benar untuk semua proyek. Cakupan teknis tetap perlu dirujukkan ke dokumen desain yang disetujui.

Pisahkan tiga lapisan informasi berikut.

1. **Basis kuantitas:** gambar, detail, schedule, dan tanggal/revisi yang menjadi sumber takeoff (pengukuran dari gambar).
2. **Basis sistem:** tipe panel, rangka atau support (penyangga), ukuran modul, pintu, hardware, finish, sealant, dan aksesori yang termasuk.
3. **Basis komersial-pelaksanaan:** pekerjaan persiapan, proteksi, akses/logistik, testing, dokumentasi, garansi, spare (suku cadang cadangan), exclusions, dan aturan perubahan.

Kerangka ini sejalan dengan kebutuhan dokumen konstruksi dan pengadaan yang harus membedakan lingkup, spesifikasi, serta bukti serah terima. Status dan ruang lingkup umum jasa konstruksi dapat dilihat pada [UU No. 2 Tahun 2017](https://peraturan.bpk.go.id/Details/37637/uu) dan [PP No. 14 Tahun 2021](https://peraturan.bpk.go.id/Details/161844/pp-no-14-tahun-2021), tetapi keduanya bukan template kontrak atau pengganti tinjauan hukum proyek.

## Cara menyusun basis kuantitas dari gambar revisi hingga bukti serah terima

Setelah objek dan tiga lapisan basis dipisahkan, pertanyaan praktisnya adalah bagaimana mengubahnya menjadi baris yang dapat diperiksa. Urutan ini membantu mencegah angka dari satu denah, asumsi lapangan, dan komponen sistem tercampur dalam satu total.

Di sini, drawing register berarti daftar kendali gambar; reflected ceiling plan adalah denah plafon; dan substrate berarti lapisan dasar atau permukaan penyangga. Istilah ini membantu Anda membaca sumber ukuran dan titik tumpu sebelum menghitung.

Mulai dengan **drawing register**: nomor gambar, judul, revisi, tanggal, dan siapa yang menerbitkan. Tandai denah, elevasi, detail sambungan, reflected ceiling plan, serta schedule pintu atau hardware yang dipakai. Takeoff dari denah saja berisiko melewatkan tinggi aktual, transisi, dan pertemuan dengan elemen lain. Panduan nonstruktural FEMA juga mengingatkan bahwa layout tidak otomatis mengungkap lokasi struktur, sambungan gerak, utilitas tersembunyi, sprinkler, detektor, atau kapasitas substrate; kondisi ini harus diverifikasi melalui survei dan koordinasi proyek ([FEMA E-74](https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf)).

Setelah sumber beku, buat satu baris per unit yang bisa dihitung dan diperiksa. Contoh struktur kolomnya:

Pada tahap serah terima, as-built berarti gambar kondisi terpasang, sedangkan commissioning berarti uji fungsi dan pengoperasian sesuai tujuan sistem.

| Kolom | Isi yang harus terlihat |
|---|---|
| ID/area | Ruang, grid, elevasi, atau zona pemasangan |
| Sistem dan konfigurasi | Tipe panel/rangka, tinggi, tebal, modul, pintu, arah bukaan |
| Unit dan kuantitas | m, m², set, unit, titik, atau lot; tulis rumus takeoff |
| Include/exclude | Pekerjaan yang masuk dan yang sengaja dikeluarkan |
| Allowance | Sambungan, potongan, wastage, spare; nilai harus disetujui, bukan ditebak |
| Bukti | Gambar/revisi, submittal (dokumen pengajuan produk), checklist inspeksi, foto, hasil test |

Hitung panel, rangka, pintu, hardware, trim, sealant, dan penetrasi secara terpisah sebelum membuat total sistem. Instruksi pemasangan partisi HPL Bobrick memperlihatkan mengapa detail fastener, support, dan urutan pemasangan tidak boleh diringkas menjadi “1 set”; gunakan dokumen pabrikan sistem yang benar, bukan menyalin toleransi atau langkahnya ke produk lain ([instruksi Bobrick](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf)). Untuk sistem stud metal, hub sistem Knauf menunjukkan bahwa konfigurasi lapisan dan komponen pembentuk dinding harus disebut, bukan hanya luas permukaannya ([Knauf W11](https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende)).

Tutup siklus dengan **inspection and test plan (ITP)**. Tetapkan titik tahan sebelum elemen tersembunyi ditutup, pemeriksaan dimensi dan alignment, verifikasi hardware, fungsi buka-tutup, serta daftar dokumen as-built dan manual. Sistem lipat/geser, misalnya, perlu commissioning atas fungsi yang dimaksud; manual operasi dormakaba menekankan penggunaan dan pengoperasian sistem tertentu, bukan bukti bahwa sistem lain telah lulus ([manual dormakaba](https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzN2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi).

## Faktor lapangan, material, dan perubahan yang mengubah hasil BoQ

Satu baris BoQ dapat benar menurut gambar tetapi berubah ketika bertemu bangunan dan produk yang nyata. Bagian ini menjelaskan tiga sumber perubahan—lapangan, material, dan revisi—agar Anda tahu mana yang perlu diukur ulang, dimintakan data, atau disetujui.

**Kondisi lapangan.** Tinggi lantai-ke-plafon, plumb/level, balok, kolom, movement joint, utilitas, skirting, drainase, akses angkut, dan ruang stacking dapat mengubah panjang, jumlah trim, support, atau urutan kerja. Karena itu, kuantitas dari gambar harus punya kolom “terverifikasi lapangan” dan tanggal pengukuran.

**Lingkungan dan material.** “Moisture resistant” bukan berarti rakitan kedap air. EPA menjelaskan bahwa kebocoran, kondensasi, drainase, ventilasi, sambungan, dan kemampuan mengering memengaruhi pengendalian kelembapan ([EPA Moisture Control Guidance](https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0)). Pedoman Gypsum Association dan panduan fabrikasi Formica juga menempatkan penyimpanan, tepi, lubang fastener, substrate, dan detail area basah sebagai hal yang perlu dikendalikan ([GA-238-03](https://www.gypsum.org/wp-content/uploads/2011/11/GA-238-03.pdf); [Formica Compact](https://www.formica.com/zh-cn/-/media/project/formica/asia/documents/products-documents/compact/farbiration-guide_compact_2023.pdf?rev=692c868288044704aac2458e42c2bb23)). Maka, tulis kelas paparan dan detail perlindungan sebagai asumsi terbuka, bukan klaim performa.

**Perubahan dan bukti.** Substitusi material, perubahan modul, atau deviasi support dapat memengaruhi struktur, akustik, api, kelembapan, tampilan, dan garansi. Setiap revisi perlu nomor perubahan, alasan, dampak kuantitas, dan persetujuan. Dokumen guide-specification Bobrick dan contoh technical specification Modernfold berguna sebagai pola kelengkapan submittal, bukan spesifikasi otomatis untuk proyek Anda ([Bobrick guide specifications](https://www.bobrick.com/resource-center-2/guide-specifications/); [Modernfold specification](https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true)).

## Keputusan praktis saat denah cubicle belum lengkap

Sampai di sini, prinsipnya perlu diuji pada situasi yang sering terjadi: estimator menerima denah dengan jumlah bilik, tetapi belum menerima detail plafon, schedule hardware, atau status area basah. Contoh ini menunjukkan kapan angka boleh dihitung, kapan harus dipisahkan sebagai allowance, dan kapan perlu ditahan.

Bayangkan estimator menerima denah dengan 24 bilik, tetapi tidak menerima detail plafon, schedule hardware, atau status area basah. Jangan masukkan “24 set lengkap” sebagai angka final. Buat tiga status:

| Status | Tindakan BoQ |
|---|---|
| Terukur | Hitung unit yang jelas dari gambar revisi; simpan rumus dan referensi grid. |
| Allowance | Pisahkan trim, seal, sambungan, atau spare yang kebutuhannya bergantung detail; minta dasar persetujuan. |
| Belum terbukti | Tandai `[NEEDS PROJECT SURVEY]` untuk support, penetrasi, plafon, utilitas, atau kondisi lembap yang belum disurvei. |

Jika dua vendor menawarkan luas panel yang sama, bandingkan juga pintu dan hardware, framing/support, hasil akhir, proteksi, akses/logistik, bongkar-buang, testing, jadwal, garansi, spare, dan serah terima. Equal area atau lump sum terendah belum berarti equal cakupan. Untuk isu yang melampaui basis kuantitas, mulai dari [halaman utama Cubicle.co.id](/) dan arahkan pertanyaan teknis ke dokumen desain serta reviewer proyek.

## Kesalahan umum dalam BoQ cubicle dan cara memeriksanya

Sebelum angka dipakai untuk quotation atau fabrikasi, periksa kesalahan yang paling mudah membuat tabel tampak rapi tetapi tidak dapat dibandingkan. Daftar ini menyoroti sumber selisih yang perlu dilacak kembali ke gambar, line item, atau bukti.

- **Mengukur dari satu denah.** Cocokkan setiap segmen dengan elevasi, detail, dan register revisi.
- **Menggabungkan semua aksesori ke “set”.** Tampilkan engsel, kunci, kaki, trim, seal, dan penetrasi sebagai line item atau sub-item yang dapat dihitung.
- **Menyembunyikan wastage.** Nyatakan basis potongan, sambungan, dan persetujuan allowance; jangan memakai persentase generik tanpa data proyek.
- **Menganggap visual selesai sebagai commissioning.** Uji fungsi yang dimaksud dan lampirkan checklist, hasil pengujian, serta punch list.
- **Mengabaikan exclusions.** Tulis siapa yang menangani substrate, plafon, listrik/data, sprinkler, proteksi, pembongkaran, pembersihan, dan disposal.
- **Menyalin spesifikasi pabrikan lain.** Gunakan instruksi produk yang benar dan minta persetujuan bila ada substitusi.

Kawan Cubicle.co.id, pemeriksaan terakhir seharusnya bisa menjawab: “Untuk angka ini, saya menunjuk gambar revisi mana, mengukur dengan unit apa, dan bukti apa yang akan saya terima?” Jika salah satu jawabannya tidak ada, baris tersebut belum siap dibandingkan.

## Mengapa harga total per bilik dapat menyamarkan cakupan pekerjaan

Sebelum menutup keputusan komersial, kita perlu melihat godaan yang paling umum: meminta satu harga total per bilik agar proses cepat. Bagian ini menjelaskan mengapa format ringkas itu bisa menyembunyikan perbedaan dan apa yang perlu diminta sebagai pembanding.

Jalan pintas yang sering dipilih buyer adalah meminta satu harga total per bilik agar proses cepat. Cara ini memang mengurangi jumlah baris, tetapi menyamarkan perbedaan konfigurasi, exclusions, support, aksesori, dan dokumen serah terima. Akibatnya, variasi baru muncul ketika kondisi lapangan atau detail pintu dibuka.

Alternatif yang lebih aman adalah memakai template line item yang sama untuk semua vendor, membekukan gambar dan revisi, lalu meminta mereka mengisi kolom “termasuk”, “tidak termasuk”, allowance, lead time, testing, garansi, spare, dan deliverables. Itu membuat perbedaan terlihat sebelum komitmen komersial—tanpa mengubah BoQ menjadi keputusan engineering atau legal.

## Keputusan akhir BoQ cubicle berdasarkan cakupan dan bukti

BoQ cubicle yang dapat dibandingkan dibangun dari sistem dan basis bukti, bukan dari luas atau jumlah bilik saja. Bekukan drawing takeoff, pecah unit/line item, nyatakan exclusions dan allowance, masukkan aksesori serta testing, dan kendalikan setiap revisi dengan dokumen.

Langkah berikutnya: minta drawing register dan survei antarmuka, isi satu contoh baris lengkap untuk tiap sistem, lalu lakukan tinjauan teknis sebelum angka dipakai untuk evaluasi penawaran. Sobat Cubicle.co.id, jangan mengubah `[NEEDS PROJECT SURVEY]` menjadi angka tebakan; selesaikan gate lapangan, produk, dan profesional yang masih terbuka terlebih dahulu. BoQ membantu membandingkan cakupan—ia tidak menggantikan persetujuan desain, verifikasi kondisi, atau tinjauan hukum proyek.
