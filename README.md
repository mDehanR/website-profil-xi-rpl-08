# Website Profil XI RPL

Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.

## Anggota Tim

1. Dehan - Project Manager
2. Rafly - Developer
3. Regina - Developer
4. Andri - Developer

## Challenge 2: Clone Repository

**Pertanyaan:** Apa arti hasil `git status`?

**Jawaban:** Hasil `git status` menampilkan kondisi terkini dari working directory dan staging area. Informasi yang ditampilkan meliputi branch aktif, status sinkronisasi dengan remote repository, file yang baru diubah atau ditambahkan, serta file yang siap di-commit.

## Analisis Challenge 3: Membuat Branch

**Pertanyaan:** Mengapa setiap developer tidak langsung bekerja pada `main`?

**Jawaban:** Developer tidak boleh bekerja langsung di `main` agar branch tersebut tetap bersih, stabil, dan bebas dari bug atau error. Dengan membuat branch terpisah untuk setiap fitur, beberapa developer dapat bekerja bersamaan tanpa merusak kode utama.

## Challenge 5: Commit

**Pertanyaan:** Apa perbedaan pesan commit `git commit -m "update"` dan `git commit -m "Menambahkan halaman profil kelas"`? Mana yang lebih baik?

**Jawaban:** Pesan `update` terlalu umum dan ambigu. Pesan `Menambahkan halaman profil kelas` lebih baik karena spesifik, deskriptif, dan memudahkan tim membaca riwayat pengembangan.

## Analisis: Sinkronisasi

1. **Apa fungsi `git pull`?** `git pull` berfungsi mengambil dan menggabungkan perubahan terbaru dari remote repository ke local repository.
2. **Apa yang terjadi jika programmer tidak melakukan `git pull`?** Kode lokal akan tertinggal dari kode di GitHub dan dapat menimbulkan penolakan push atau merge conflict.
3. **Mengapa `main` harus dijaga agar tetap stabil?** Branch `main` merupakan fondasi utama atau produk siap pakai. Jika rusak, seluruh proyek dapat terganggu.

## Analisis Conflict

1. **Mengapa conflict terjadi?** Conflict terjadi ketika beberapa developer mengubah baris kode yang sama pada branch berbeda dan mencoba menggabungkannya.
2. **Apakah conflict berarti Git rusak?** Tidak. Conflict merupakan hal yang normal dan menunjukkan bahwa Git mencegah kode hilang secara tidak sengaja.
3. **Siapa yang menentukan versi kode yang benar?** Developer yang mengalami conflict bersama tim atau Project Manager.
4. **Mengapa komunikasi antarprogrammer penting?** Komunikasi membantu menyelaraskan tugas, mencegah perubahan bersamaan, dan mempercepat penyelesaian conflict.

## Refleksi Individu

1. **Apa perbedaan bekerja sendiri dengan menggunakan Git dan GitHub?** Git dan GitHub memungkinkan kerja paralel, pencatatan riwayat perubahan, dan integrasi fitur yang lebih aman.
2. **Apa manfaat branch?** Branch menyediakan ruang kerja terpisah untuk membuat fitur, memperbaiki error, atau bereksperimen tanpa merusak `main`.
3. **Mengapa Pull Request diperlukan?** Pull Request memungkinkan anggota tim memeriksa dan mendiskusikan perubahan sebelum digabungkan ke `main`.
4. **Apa manfaat Code Review?** Code Review membantu menjaga kualitas kode, menemukan bug, dan menjadi sarana belajar bersama.
5. **Error apa yang paling sulit diselesaikan?** Penolakan push akibat non-fast-forward dan merge conflict pada `README.md`.
6. **Bagaimana solusi ditemukan?** Dengan membaca pesan error, berdiskusi, menjalankan `git pull origin main`, dan menyelesaikan conflict secara manual.
7. **Apa kontribusi terbesar dalam kelompok?** Membuat fitur halaman HTML, merapikan struktur tag, dan aktif dalam code review.
8. **Kebiasaan apa yang akan dipertahankan?** Membuat branch untuk setiap fitur, menulis pesan commit yang jelas, dan melakukan `git pull` sebelum mulai bekerja.

## Refleksi Akhir

Sebelum belajar GitHub, saya berpikir bahwa pekerjaan tim dilakukan dengan saling mengirim file secara manual. Setelah berkolaborasi menggunakan GitHub, saya memahami bahwa branching, Pull Request, Code Review, dan merge membuat kerja tim lebih cepat, aman, serta terorganisir. Pengalaman ini mengajarkan bahwa error merupakan petunjuk teknis yang membantu menemukan hal yang perlu diperbaiki. Sebagai programmer, saya akan mematuhi workflow Git, disiplin membuat branch, aktif berkomunikasi, dan menghargai masukan saat code review.