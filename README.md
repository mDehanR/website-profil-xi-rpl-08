# Website Profil XI RPL

Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.

## Anggota Tim

1. Dehan - Project Manager
2. Rafly - Developer Profil
3. Regina - Developer Anggota
4. Andri - Developer Kontak

## I. PERTANYAAN CHALLENGE 2 (CLONE REPOSITORY)

**Pertanyaan:** Apa arti hasil `git status`?

**Jawaban:**

Perintah `git status` digunakan untuk menampilkan kondisi working directory dan staging area saat ini. Perintah ini memberikan informasi mengenai:

- Branch yang sedang aktif.
- Status sinkronisasi dengan repositori remote di GitHub.
- Berkas yang mengalami perubahan tetapi belum masuk ke staging area (`untracked` atau `unstaged`).
- Berkas yang sudah masuk ke staging area (`staged`) dan siap di-commit.

## II. PERTANYAAN ANALISIS CHALLENGE 3 (MEMBUAT BRANCH)

**Pertanyaan:** Mengapa setiap developer tidak langsung bekerja pada `main`?

**Jawaban:**

- **Menjaga stabilitas kode utama (`main`):** Branch `main` difungsikan sebagai versi kode stabil yang siap digunakan. Bekerja langsung di `main` berisiko merusak sistem jika terdapat error.
- **Isolasi fitur:** Pembuatan branch terpisah memungkinkan pengerjaan fitur baru dilakukan secara independen tanpa mengganggu anggota tim lain.
- **Memudahkan code review:** Perubahan dapat diperiksa dan diuji terlebih dahulu melalui Pull Request sebelum digabungkan ke kode utama.
- **Pengelolaan perubahan:** Jika suatu fitur dibatalkan, branch fitur tersebut cukup dihapus tanpa merusak kode di `main`.

## III. PERTANYAAN CHALLENGE 5 (COMMIT)

**Pertanyaan:** Apa perbedaan pesan commit berikut, dan mana yang lebih baik?

```bash
git commit -m "update"
git commit -m "Menambahkan halaman profil kelas"
```

**Jawaban:**

Pesan `git commit -m "update"` terlalu umum dan tidak menjelaskan perubahan yang dilakukan. Sebaliknya, pesan `git commit -m "Menambahkan halaman profil kelas"` menjelaskan aksi dan hasil perubahan secara spesifik.

**Pilihan terbaik:** `git commit -m "Menambahkan halaman profil kelas"` karena memudahkan pelacakan riwayat pengembangan dan proses code review.

## IV. PERTANYAAN ANALISIS U (SINKRONISASI & GIT PULL)

**Pertanyaan:**

1. Apa fungsi `git pull`?
2. Apa yang terjadi jika programmer tidak melakukan `git pull`?
3. Mengapa `main` harus dijaga agar tetap stabil?

**Jawaban:**

- **Fungsi `git pull`:** Mengambil perubahan terbaru dari repositori remote (GitHub) dan menggabungkannya ke branch lokal yang aktif.
- **Dampak tanpa `git pull`:** Kode lokal menjadi tertinggal (`outdated`), berisiko mengalami merge conflict saat melakukan push, dan tidak terintegrasi dengan pekerjaan tim lain.
- **Alasan branch `main` harus stabil:** `main` merupakan acuan utama seluruh tim dan mencerminkan versi aplikasi yang siap dirilis.

## V. PERTANYAAN X (KONFLIK KODE / CONFLICT)

**Pertanyaan:**

1. Mengapa conflict terjadi?
2. Apakah conflict berarti Git rusak?
3. Siapa yang harus menentukan versi kode yang benar?
4. Mengapa komunikasi antarprogrammer penting?

**Jawaban:**

- **Penyebab konflik:** Terjadi ketika dua atau lebih developer mengubah baris kode yang sama pada file yang sama dengan isi berbeda, lalu mencoba menggabungkannya.
- **Status Git:** Git tidak rusak. Konflik menandakan Git bekerja secara aman dengan menyerahkan keputusan penimpaan kode kepada developer.
- **Pihak penentu:** Developer yang terlibat dalam perubahan tersebut melalui diskusi bersama Project Manager atau Lead Developer.
- **Pentingnya komunikasi:** Mencegah bentrokan pengerjaan fitur, mempercepat penyelesaian konflik, dan menjaga konsistensi kode.

## VI. REFLEKSI INDIVIDU (BAGIAN AC)

**Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?**

**Jawab:** Bekerja sendiri tidak memerlukan koordinasi penggabungan kode, sedangkan bekerja dengan Git dan GitHub membutuhkan alur pembagian branch, code review, dan integrasi kode bersama tim.

**Apa manfaat branch?**

**Jawab:** Memungkinkan pengerjaan fitur baru atau perbaikan kode dilakukan secara terpisah tanpa mengganggu branch utama (`main`).

**Mengapa Pull Request diperlukan?**

**Jawab:** Untuk menyediakan ruang pemeriksaan dan diskusi kode sebelum perubahan digabungkan ke branch utama.

**Apa manfaat Code Review?**

**Jawab:** Membantu menemukan bug lebih awal, menjaga standar penulisan kode, dan memastikan fitur sesuai dengan spesifikasi proyek.

**Error apa yang paling sulit kalian selesaikan?**

**Jawab:** Merge conflict saat penggabungan branch atau kendala push rejected karena repositori lokal belum di-pull.

**Bagaimana kalian menemukan solusinya?**

**Jawab:** Membaca pesan error, berdiskusi dengan tim, memeriksa dokumentasi, dan menyelesaikan konflik pada file terkait.

**Apa kontribusi terbesar kalian dalam kelompok?**

**Jawab:** Membuat dan mengintegrasikan file fitur sesuai tugas, melakukan review pada Pull Request tim, serta membantu penyelesaian konflik kode.

**Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?**

**Jawab:** Selalu membuat branch baru untuk setiap fitur, menulis pesan commit yang informatif, serta melakukan code review sebelum penggabungan kode.

## VII. REFLEKSI AKHIR (BAGIAN AE)

**Sebelum belajar GitHub, saya berpikir bahwa...** pengerjaan proyek tim dilakukan dengan menggabungkan file secara manual yang berisiko tertimpa atau hilang.

**Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...** kolaborasi terstruktur menggunakan branch, Pull Request, dan Merge sangat penting untuk menjaga keutuhan kode proyek.

**Kesalahan/error yang saya alami mengajarkan saya bahwa...** error merupakan informasi petunjuk yang membantu memahami alur kerja dan penanganan masalah pada sistem.

**Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...** disiplin mengikuti alur kerja Git, berkomunikasi aktif dengan tim, dan selalu memastikan stabilitas kode utama.
