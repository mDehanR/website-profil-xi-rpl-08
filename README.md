# Website Profil XI RPL
Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.
## Anggota Tim
1. Dehan - Project Manager
2. Rafly - Developer Profil
3. Regina - Developer Anggota
4. Andri - Developer Kontak

## Pertanyaan & Refleksi
Challenge 2 - Pertanyaan
​1. Apa arti hasil git status?
​Jawaban: git status adalah perintah untuk mengecek kondisi repository lokal saat ini, seperti melihat branch mana yang sedang aktif, file apa saja yang telah diubah (modified), file baru yang belum dilacak (untracked), serta file yang sudah siap di-commit (staged).

Challenge 3 - Pertanyaan Analisis
​2. Mengapa setiap developer tidak langsung bekerja pada main?
​Jawaban: Agar branch main tetap aman, bersih, dan stabil (bebas dari error/bug). Jika semua developer langsung bekerja di main, kode yang belum selesai atau masih penuh bug dapat merusak aplikasi utama dan mengganggu pekerjaan anggota tim lainnya.

Challenge 5 - Pertanyaan
​3. Apa perbedaan pesan commit berikut?
git commit -m "update" dan 
git commit -m "Menambahkan halaman profil kelas"
mana yang lebih baik?
​Jawaban: Pesan "update" terlalu ambigu dan tidak menjelaskan perubahan apa yang dilakukan. Pesan "Menambahkan halaman profil kelas" sangat spesifik dan informatif. Pesan yang kedua jauh lebih baik karena memudahkan tim dalam melacak histori perubahan di masa mendatang.

Challenge 11 - Pertanyaan Analisis
​4. Apa fungsi git pull?
​Jawaban: git pull berfungsi untuk mengambil (fetch) dan menggabungkan (merge) perubahan kode terbaru dari repository remote (GitHub) ke repository lokal di komputer kita agar file lokal selalu ter-update.

​5. Apa yang terjadi jika programmer tidak melakukan git pull?
​Jawaban: Kode di komputer lokal akan tertinggal dari versi terbaru di GitHub. Hal ini dapat menyebabkan terjadinya merge conflict saat programmer tersebut mencoba mengunggah (push) kodenya nanti.

​6. Mengapa main harus dijaga agar tetap stabil?
​Jawaban: Karena branch main merepresentasikan versi produk/aplikasi utama yang siap digunakan atau dirilis. Jika main rusak, maka seluruh sistem atau produk akhir aplikasi akan ikut terganggu/down.

## Pertanyaan Conflict
​7. Mengapa conflict terjadi?
​Jawaban: Conflict terjadi ketika dua atau lebih developer mengubah baris kode yang sama pada file yang sama secara bersamaan, sehingga Git tidak dapat menentukan secara otomatis perubahan mana yang harus dipakai.

​8. Apakah conflict berarti Git rusak?
​Jawaban: Tidak. Conflict adalah hal yang normal dan merupakan fitur keselamatan dari Git agar tidak ada kode milik salah satu developer yang terhapus secara tidak sengaja tanpa konfirmasi.

​9. Siapa yang harus menentukan versi kode yang benar?
​Jawaban: Seluruh developer yang terlibat dalam konflik tersebut, yang biasanya didampingi atau disetujui oleh Project Manager / Lead Developer.

​10. Mengapa komunikasi antar programmer penting?
​Jawaban: Komunikasi penting untuk membagi tugas secara jelas, menghindari pengerjaan fitur yang sama secara tidak sengaja, mempermudah penyelesaian conflict, dan menjaga agar alur integrasi proyek berjalan lancar.

## Refleksi Individu
​11. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?
​Jawaban: Bekerja sendiri biasanya hanya menyimpan file secara manual (lokal) dan berisiko kehilangan data jika lupa back-up. Bekerja dengan Git & GitHub memungkinkan kolaborasi banyak orang secara terstruktur, pelacakan histori perubahan file, serta kemudahan menggabungkan karya banyak orang tanpa saling menimpa secara berantakan.

​12. Apa manfaat branch?
​Jawaban: Manfaat branch adalah memberikan ruang kerja terisolasi (branching) sehingga developer bisa fokus membuat fitur baru atau memperbaiki bug tanpa merusak kode utama di branch main.

​13. Mengapa Pull Request diperlukan?
​Jawaban: Pull Request (PR) diperlukan sebagai wadah untuk mengajukan, mendiskusikan, dan meninjau perubahan kode dari sebuah branch fitur sebelum akhirnya digabungkan ke branch utama (main).

​14. Apa manfaat Code Review?
​Jawaban: Code Review bermanfaat untuk meningkatkan kualitas kode, menemukan kesalahan/bug lebih awal, memastikan standar penulisan kode ditaati, serta membagikan pengetahuan antar anggota tim.

​15. Error apa yang paling sulit kalian selesaikan?
​Jawaban: Error merge conflict saat melakukan git pull atau git push, serta kesalahan path/lokasi folder saat menjalankan perintah di Git Bash.

​16. Bagaimana kalian menemukan solusinya?
​Jawaban: Dengan membaca pesan error dengan teliti, berdiskusi dan meminta bantuan teman sekelompok/Project Manager, serta mencari panduan penyelesaian masalah secara mandiri di internet/AI.

​17. Apa kontribusi terbesar kalian dalam kelompok?
​Jawaban: Membuat branch fitur anggota, menyusun file anggota.html dengan benar, serta berhasil melakukan commit, push, dan Pull Request tanpa merusak branch utama proyek.

​18. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?
​Jawaban: Kebiasaan selalu bekerja di branch terpisah, menulis pesan commit yang jelas dan bermakna, rajin melakukan git pull sebelum mulai bekerja, serta selalu melakukan periksa ulang (review) kode sebelum digabungkan.

## Refleksi Akhir
​19. Sebelum belajar GitHub, saya berpikir bahwa...
​Jawaban: membuat proyek koding secara berkelompok dilakukan dengan cara saling mengirimkan file program secara manual melalui aplikasi pesan, yang sangat merepotkan dan rawan tertukar.

​20. Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...
​Jawaban: pengembangan software secara tim dapat dilakukan dengan sangat rapi, sistematis, dan aman melalui penggunaan fitur branching, commit, dan Pull Request.

​21. Kesalahan/error yang saya alami mengajarkan saya bahwa...
​Jawaban: pesan error di terminal bukanlah masalah besar melainkan petunjuk teknis yang harus dibaca dengan teliti, dan ketelitian serta komunikasi tim adalah kunci utama dalam koding.

​22. Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...
​Jawaban: disiplin menerapkan standar alur kerja Git (Git Workflow), rajin berkomunikasi dengan rekan tim, serta selalu menjaga agar branch utama proyek tetap stabil dan bersih dari bug.