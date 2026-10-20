- Analisis Komparatif Platform: Web, Desktop, dan Mobile
| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa utama** | Menggunakan HTML (HyperText Markup Language) untuk struktur, CSS (Cascading Style Sheets) untuk styling, dan JavaScript (serta TypeScript atau WebAssembly) untuk fungsionalitas dan interaksi. | Menggunakan bahasa pemrograman yang mendukung performa sistem tinggi seperti C++, C#, Java, Python, Swift, atau Rust. | Menggunakan bahasa spesifik seperti Swift untuk iOS, Kotlin/Java untuk Android, atau kerangka kerja cross-platform seperti Dart (Flutter) dan JavaScript/TypeScript (React Native). |
| **Arsitektur** | Menggunakan arsitektur Klien-Server (Client-Server), Single Page Application (SPA), atau PWA (Progressive Web App) di mana sebagian besar pemrosesan atau pemuatan data diakses melalui jaringan internet atau browser. | Menggunakan arsitektur monolitik atau client-server lokal yang terintegrasi langsung dengan sistem operasi komputer (menggunakan pola desain seperti MVVM atau MVC native). | Berbasis komponen seluler dengan penerapan pola arsitektur seperti MVVM (Model-View-ViewModel), MVP, atau Clean Architecture. |
| **Cara distribusi** | Didistribusikan melalui jaringan internet menggunakan URL. Pengguna dapat mengaksesnya secara langsung melalui peramban (web browser) tanpa perlu proses instalasi yang rumit. | Didistribusikan melalui paket installer mandiri (seperti .exe, .msi, .dmg, .pkg) atau melalui manajemen paket (package manager / app store khusus desktop). | Didistribusikan secara resmi melalui toko aplikasi digital seperti Google Play Store (Android) dan Apple App Store (iOS), atau melalui sideloading (.apk/.ipa). |
| **Keunggulan** | Sangat fleksibel karena dapat diakses dari berbagai perangkat yang memiliki peramban, tidak memerlukan ruang penyimpanan lokal yang besar, serta pembaruan aplikasi dapat dilakukan secara terpusat di sisi server tanpa perlu update manual oleh pengguna. | Menawarkan performa komputasi yang sangat tinggi, memiliki akses penuh ke perangkat keras (GPU, CPU, file system), serta dapat berjalan secara optimal tanpa memerlukan koneksi internet (offline). | Bersifat sangat portabel, terintegrasi secara mendalam dengan sensor perangkat keras (kamera, GPS, gyroscope, akselerometer), serta memberikan pengalaman pengguna yang sangat personal dan responsif. |
| **Keterbatasan** | Sangat bergantung pada kestabilan koneksi internet dan memiliki keterbatasan akses langsung terhadap perangkat keras (hardware) mendalam pada perangkat pengguna. | Memerlukan proses instalasi manual, ukuran file instalasi yang relatif besar, dan pembaruan aplikasi harus diunduh serta diinstal secara manual oleh pengguna. | Memiliki keterbatasan ukuran layar, tingkat fragmentasi perangkat yang tinggi (bervariasinya ukuran layar dan versi OS), serta terikat oleh aturan dan biaya publikasi yang ketat dari toko aplikasi. |
| **Contoh aplikasi** | Google Workspace, Netflix Web, Trello, dan GitHub. | Microsoft Office (Word/Excel), Visual Studio Code, Adobe Photoshop, dan VLC Media Player. | WhatsApp, Instagram, Google Maps, dan Mobile Legends. |

- Sumber Referensi

Johnson, T., & Seeling, P. (2014). Desktop and mobile web page comparison: characteristics, trends, and implications. IEEE Communications Magazine, 52(6), 144-151.

Fransisca, M., & Saputri, R. P. (2024). Comparative Study Of Android-Based Learning Media With Web-Based Learning Media. The Indonesian Journal of Computer Science, 13(4).

Sommerville, I. (2015). Software Engineering (10th ed.). Pearson.

- Refleksi

Dari ketiga platform yang dianalisis, platform Desktop adalah yang paling menarik bagi saya untuk dipelajari lebih mendalam. Alasan utamanya adalah ketertarikan saya dalam membuat mod untuk game Minecraft. Pembuatan mod Minecraft berbasis Java membutuhkan pemahaman mendalam mengenai arsitektur aplikasi Desktop, manajemen memori, serta interaksi langsung dengan sistem berkas dan pustaka perangkat lunak lokal.

Tantangan terbesar yang saya hadapi saat melakukan setup environment adalah mengonfigurasi Java JDK dan environment variables agar sesuai dengan kebutuhan IDE, serta mengatasi kendala eksekusi skrip (execution policy) pada terminal PowerShell saat menjalankan perintah CLI. Selain itu, ukuran unduhan beberapa tools pendukung juga membutuhkan waktu pengunduhan yang cukup lama.

Rencana saya untuk mengatasi tantangan tersebut adalah dengan mempelajari dokumentasi resmi Java dan skrip konfigurasi terminal, serta membiasakan diri membaca log kesalahan (error message). Saya juga akan memanfaatkan komunitas pengembang mod dan forum seperti Stack Overflow untuk berdiskusi ketika menemukan kendala teknis dalam pengembangan aplikasi maupun modding.