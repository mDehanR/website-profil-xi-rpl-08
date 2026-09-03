# Website Profil XI RPL

Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.

## Anggota Tim

1. Dehan - Project Manager
2. Rafly - Developer
3. Regina - Developer
4. Andri - Developer

## I. Challenge 2: Clone Repository

**Pertanyaan:** Apa arti hasil `git status`?

**Jawaban:**
Perintah `git status` digunakan untuk melihat kondisi atau status terkini dari working directory dan staging area. Setelah repository baru di-clone, hasilnya biasanya menampilkan: On branch `main`: Menunjukkan bahwa kita sedang berada di branch `main`. Your branch is up to date with 'origin/main': Menandakan bahwa kode di lokal komputer kita sudah sama/sinkron dengan kode yang ada di GitHub. nothing to commit, working tree clean: Menunjukkan belum ada perubahan file baru atau modifikasi yang perlu di-commit.

## J. Challenge 3: Membuat Branch

**Pertanyaan Analisis:** Mengapa setiap developer tidak langsung bekerja pada main?

**Jawaban:** Agar kode utama `main` tetap stabil, aman, dan siap rilis. Dengan bekerja di branch terpisah, setiap developer dapat mengembangkan dan menguji fiturnya tanpa berisiko merusak sistem utama atau mengganggu pekerjaan anggota tim lainnya.

## N. Challenge 5: Commit

**Pertanyaan:** Apa perbedaan pesan commit git commit -m "update" dan git commit -m "Menambahkan halaman profil kelas"? Mana yang lebih baik?

**Jawaban:** Pesan "update" terlalu umum dan tidak memberikan penjelasan spesifik mengenai perubahan yang dibuat. Pesan "Menambahkan halaman profil kelas" rinci, informatif, dan jelas. Mana yang lebih baik: Pesan kedua jauh lebih baik karena memudahkan tim melacak riwayat perubahan kode di masa mendatang.

## U. Pertanyaan Analisis (Sinkronisasi)

1. Apa fungsi git pull?

**Jawaban:** Memperbarui kode di repository lokal dengan mengambil dan menggabungkan (merge) perubahan/commit terbaru dari repository remote di GitHub.

2. Apa yang terjadi jika programmer tidak melakukan git pull?

**Jawaban:** Kode di komputer lokal akan tertinggal (outdated), sehingga berisiko tinggi menimbulkan conflict saat hendak melakukan push atau penggabungan kode nantinya.

3. Mengapa main harus dijaga agar tetap stabil?

**Jawaban:** Karena branch `main` merupakan cerminan versi produk utama yang siap rilis (production). Jika main rusak, seluruh tim akan terhambat dan aplikasi tidak bisa digunakan.

## X. Pertanyaan Conflict

1. Mengapa conflict terjadi?

**Jawaban:** Karena dua atau lebih programmer mengubah baris kode yang sama pada file yang sama dengan isi yang berbeda secara bersamaan.

2. Apakah conflict berarti Git rusak?

**Jawaban:** Tidak. Conflict adalah fitur keamanan Git untuk mencegah kode milik seorang programmer tertimpa (overwrite) secara tidak sengaja.

3. Siapa yang harus menentukan versi kode yang benar?

**Jawaban:** Developer yang mengalami conflict bersama dengan developer penyusun perubahan terkait, atau mendiskusikannya bersama Project Manager / Lead Developer.

4. Mengapa komunikasi antar programmer penting?

**Jawaban:** Untuk menyelaraskan pembagian tugas, menghindari tumpang tindih pengerjaan file yang sama, serta mempermudah penyelesaian conflict dan code review.

## 2. AC. REFLEKSI INDIVIDU

**Apa perbedaan bekerja sendiri** dengan bekerja menggunakan Git dan GitHub? Bekerja sendiri membuat kita bebas mengubah file tanpa aturan, tetapi berisiko kehilangan histori perbaikan. Bekerja menggunakan Git dan GitHub membutuhkan alur kerja terstruktur (branching, PR, review), tetapi kolaborasi tim jadi jauh lebih aman, rapi, dan mudah dipantau bersama.

**Apa manfaat branch?** Mengisolasi pengerjaan fitur baru agar tidak langsung mengganggu atau merusak kode utama `main` yang sudah stabil.

**Mengapa Pull Request diperlukan?** Sebagai media resmi untuk mengajukan penggabungan kode dari branch fitur ke main, sekaligus tempat diskusi dan pengecekan kualitas kode sebelum di-merge.

**Apa manfaat Code Review?** Membantu menemukan bug atau kesalahan penulisan lebih awal, serta menjaga standar kualitas kode seluruh tim.

**Error apa yang paling sulit kalian selesaikan?** Menangani merge conflict pada file README.md saat ada perubahan di baris yang sama.

**Bagaimana kalian menemukan solusinya?** Membaca tanda penunjuk conflict (<<<<<<<, =======, >>>>>>>), berdiskusi dengan rekan tim untuk memilih teks yang tepat, menghapus tanda conflict, lalu commit dan push ulang.

**Apa kontribusi terbesar kalian dalam kelompok?** Mengerjakan fitur bagian saya sesuai aturan, membantu melakukan review pada Pull Request teman, dan aktif berdiskusi saat menyelesaikan conflict.

**Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?** Selalu bekerja melalui branch terpisah, menulis pesan commit yang informatif, melakukan code review dengan teliti, dan rutin melakukan git pull sebelum bekerja.

## 3. AE. REFLEKSI AKHIR

**Sebelum belajar GitHub, saya berpikir bahwa...** mengerjakan proyek kelompok dilakukan dengan saling berkirim file secara manual (lewat flashdisk atau aplikasi pesan) yang rawan tertimpa dan membingungkan.

**Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...** kolaborasi pengembangan perangkat lunak membutuhkan alur terstruktur (Git flow) seperti branching, push, Pull Request, dan code review agar proyek tim tetap rapi dan terintegrasi.

**Kesalahan/error yang saya alami mengajarkan saya bahwa...** error adalah bagian normal dari proses belajar yang memberikan petunjuk untuk diperbaiki, bukan tanda kegagalan.

**Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...** mengutamakan komunikasi yang jelas, mematuhi alur Git flow, rutin mensinkronkan kode (git pull), dan terbuka terhadap masukan saat code review.
