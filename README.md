# anisalupitasaritug195410048.github.io
Responsi Teknologi Cloud
Untuk menampilkan semua Docker image yang ada di dalam sistem. Jika ingin menampilkan informasi tambahan, tambahkan command berikut ini ke baris command sudo docker images --help. Setelah menjalankan command di atas, informasi yang ditampilkan adalah saat ini tidak ada Docker Image di sistem kami. Kemudian akan pull image terlebih dulu. Pertama-tama, masuk ke Docker Hub. Kemudian docker menemukan ratusan Docker Image. Klik dan buka masing-masing halaman Image untuk mengetahui informasinya lebih lengkap. Dengan command ini, kami akan pull image docker pull <image name>. Untuk <image name>, bisa mengubah atau menggantinya dengan ratusan image yang ada di Docker Hub. Setelah tahu cara pull dan menempatkan image untuk membuat container Docker, sudah bisa mulai bekerja. Menjalankan Image berarti membuat container dari image tersebut. Selanjutnya, kami akan membuat image ubuntu. Gunakan command ini untuk membuat container Docker. Sekarang container sudah dibuat, tapi belum berfungsi. Untuk mengaktifkan container, jalankan command ini. -name MyContainer untuk memberi nama proses yang sedang berjalan, sedangkan -it ubuntu bash menamai container yang sedang dijalankan. Buka jendela terminal lainnya, koneksikan SSH ke server, dan jalankan command ini sudo docker ps -a. Hasilnya, kita bisa lihat kalau container yang diberi nama MyContainer sedang berjalan dan selesai. 
