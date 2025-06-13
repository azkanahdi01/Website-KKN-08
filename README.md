# Website-azka-nahdi
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jasa Pendamping Sertifikasi Halal - Azka Nahdi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .section-title {
            @apply text-3xl font-bold text-gray-800 text-center mb-2;
        }
        .section-subtitle {
            @apply text-lg text-gray-500 text-center mb-12 max-w-2xl mx-auto;
        }
        .cta-button {
            @apply inline-block bg-emerald-600 text-white px-8 py-3 rounded-lg font-bold text-lg hover:bg-emerald-700 transition-transform hover:scale-105 shadow-lg;
        }
        .card {
            @apply bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header & Navbar -->
    <header class="bg-white/90 backdrop-blur-lg shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <a href="#" class="text-xl font-bold text-emerald-600">
                    Azka Nahdi
                </a>
                <div class="hidden md:flex space-x-8">
                    <a href="#layanan" class="text-gray-600 hover:text-emerald-600 font-medium">Layanan</a>
                    <a href="#portofolio" class="text-gray-600 hover:text-emerald-600 font-medium">Portofolio</a>
                    <a href="#proses" class="text-gray-600 hover:text-emerald-600 font-medium">Proses</a>
                    <a href="#kontak" class="text-gray-600 hover:text-emerald-600 font-medium">Kontak</a>
                </div>
                <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="hidden md:flex items-center gap-2 bg-green-500 text-white px-4 py-2 rounded-md hover:bg-green-600 transition-colors">
                    <i class="fab fa-whatsapp"></i>
                    <span>Hubungi Saya</span>
                </a>
                <button id="menu-btn" class="md:hidden focus:outline-none">
                    <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
            <!-- Mobile Menu -->
            <div id="mobile-menu" class="hidden md:hidden mt-4">
                <a href="#layanan" class="block py-2 text-gray-600 hover:text-emerald-600">Layanan</a>
                <a href="#portofolio" class="block py-2 text-gray-600 hover:text-emerald-600">Portofolio</a>
                <a href="#proses" class="block py-2 text-gray-600 hover:text-emerald-600">Proses</a>
                <a href="#kontak" class="block py-2 text-gray-600 hover:text-emerald-600">Kontak</a>
                <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="block mt-2 w-full text-center bg-green-500 text-white px-4 py-2 rounded-md hover:bg-green-600 transition-colors">Hubungi Saya</a>
            </div>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="beranda" class="py-20 md:py-28 bg-emerald-50">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-5xl font-extrabold text-emerald-800 mb-4 leading-tight">Bingung Urus Sertifikat Halal Gratis?</h1>
                <p class="text-lg md:text-xl text-emerald-700 max-w-3xl mx-auto mb-8">Saya siap dampingi Anda sampai tuntas! Sebagai Pendamping Proses Produk Halal (P3H) resmi, saya akan memandu Anda di setiap langkah program SEHATI.</p>
                <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="cta-button">
                    <i class="fab fa-whatsapp"></i> Konsultasi Gratis Sekarang
                </a>
            </div>
        </section>
        
        <!-- Perkenalan Section -->
        <section id="perkenalan" class="py-20">
            <div class="container mx-auto px-6">
                <div class="flex flex-col md:flex-row items-center gap-12">
                    <div class="md:w-1/3 text-center">
                        <img src="https://placehold.co/400x400/10B981/FFFFFF?text=AN" alt="Foto Azka Nahdi" class="rounded-full w-64 h-64 mx-auto shadow-xl border-4 border-white">
                    </div>
                    <div class="md:w-2/3">
                        <h2 class="text-3xl font-bold text-gray-800 mb-3">Perkenalkan, Saya Azka Nahdi</h2>
                        <p class="text-xl text-emerald-600 font-semibold mb-4">Pendamping Proses Produk Halal (P3H) Terverifikasi</p>
                        <p class="text-gray-600 leading-relaxed">Misi saya adalah membantu para pelaku Usaha Mikro dan Kecil (UMK) untuk mendapatkan Sertifikat Halal dengan mudah dan tanpa biaya. Dengan pengalaman menghalalkan seluruh kantin di lingkungan Universitas Diponegoro dan mendampingi puluhan UMKM lainnya, saya paham betul seluk-beluk proses sertifikasi dan siap memastikan Anda tidak salah langkah.</p>
                        <div class="mt-6 flex gap-4">
                            <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="bg-gray-800 text-white px-5 py-3 rounded-lg font-semibold hover:bg-black transition-colors flex items-center gap-2">
                                <i class="fab fa-whatsapp"></i> 0877-7711-1904
                            </a>
                            <a href="https://instagram.com/nahdi.azka" target="_blank" class="bg-gray-800 text-white px-5 py-3 rounded-lg font-semibold hover:bg-black transition-colors flex items-center gap-2">
                                <i class="fab fa-instagram"></i> @nahdi.azka
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logo Halal Visualization Section -->
        <section id="logo-halal" class="py-20 bg-gray-100">
            <div class="container mx-auto px-6 text-center">
                <svg class="w-32 h-32 mx-auto mb-6" viewBox="0 0 1024 1024" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M512 1024C229.23 1024 0 794.77 0 512C0 229.23 229.23 0 512 0C794.77 0 1024 229.23 1024 512C1024 794.77 794.77 1024 512 1024ZM512 64C264.58 64 64 264.58 64 512C64 759.42 264.58 960 512 960C759.42 960 960 759.42 960 512C960 264.58 759.42 64 512 64Z" fill="#03A04A"/>
                    <path d="M512 896C321.94 896 156.42 751.29 128 565.17C99.58 379.05 204.18 192 394.24 192H629.76C819.82 192 924.42 379.05 896 565.17C867.58 751.29 702.06 896 512 896ZM512 256C308.28 256 193.58 402.13 214.83 543.83C236.08 685.52 366.41 768 512 768C657.59 768 787.92 685.52 809.17 543.83C830.42 402.13 715.72 256 512 256Z" fill="#03A04A"/>
                    <path d="M799.38 522.2C804.5 448.97 748.24 384 669.58 384H354.42C275.76 384 219.5 448.97 224.62 522.2L249.2 560H298.43L284.14 534.86C275.86 519.29 288.71 500.57 306.42 500.57H411.85V480H391.14C353.43 480 322.28 511.14 322.28 548.86C322.28 586.57 353.43 617.71 391.14 617.71H411.85V682.28H460.68V617.71H563.32V682.28H612.15V617.71H632.86C670.57 617.71 701.71 586.57 701.71 548.86C701.71 511.14 670.57 480 632.86 480H612.15V500.57H632.86C649.43 500.57 662.28 513.43 662.28 530C662.28 546.57 649.43 559.43 632.86 559.43H563.32V500.57H460.68V559.43H411.85C395.28 559.43 382.43 546.57 382.43 530C382.43 513.43 395.28 500.57 411.85 500.57H460.68V480H411.85C401.71 480 392.57 477.71 384.85 473.71L405.28 433.14H618.71L639.14 473.71C631.43 477.71 622.28 480 612.15 480H563.32V416H460.68V480H354.42C344.28 480 335.14 477.71 327.43 473.71L347.85 433.14H460.68V416H342.85C334.57 416 327.43 421.71 324.57 429.14L301.57 479.43C298.28 487.43 303.71 496 312.28 496H322.28V500.57H312.28C291.71 500.57 277.43 518.71 282.85 538.28L297.14 563.43H726.86L741.14 538.28C746.57 518.71 732.28 500.57 711.71 500.57H701.71V496C720.57 496 726.85 482.28 722.28 471.43L699.43 429.14C696.57 421.71 689.43 416 681.14 416H612.15V433.14H676.14L696.57 473.71C688.85 477.71 679.71 480 669.57 480H612.15V500.57H669.57C686.14 500.57 699 513.43 699 530C699 546.57 686.14 559.43 669.57 559.43H612.15V617.71H563.32V559.43H460.68V617.71H411.85V559.43H354.42C337.85 559.43 325 546.57 325 530C325 513.43 337.85 500.57 354.42 500.57H411.85V416H502.28L476.57 368H434.85L424.57 388.57H387.43L440 288H584L636.57 388.57H599.43L589.14 368H547.43L521.71 416H612.15V384H507.71L512 375.43L516.28 384H563.32L512 288L360.57 559.43H298.43L273.8 522.2C268.68 448.97 324.94 384 403.6 384H620.4C699.06 384 755.32 448.97 750.2 522.2L725.6 560H799.38Z" fill="#03A04A"/>
                </svg>
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Jaminan Produk Halal, Ketenangan untuk Umat</h2>
                <p class="text-gray-600 max-w-xl mx-auto">Sertifikat Halal bukan hanya selembar kertas, tetapi sebuah komitmen terhadap kebersihan, kualitas, dan keyakinan konsumen. Tingkatkan nilai jual produk Anda dan raih pasar yang lebih luas dengan jaminan halal yang diakui.</p>
            </div>
        </section>

        <!-- Portofolio Section -->
        <section id="portofolio" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Portofolio & Rekam Jejak</h2>
                <p class="section-subtitle">Pengalaman yang menjadi jaminan kualitas pendampingan untuk usaha Anda.</p>
                <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
                    <div class="card flex items-start gap-6">
                        <div class="flex-shrink-0 flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20">
                           <i class="fa-solid fa-school text-4xl text-emerald-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Kantin Universitas Diponegoro</h3>
                            <p class="text-gray-600">Berhasil memimpin dan menyelesaikan proyek sertifikasi halal untuk seluruh kantin di lingkungan Universitas Diponegoro.</p>
                        </div>
                    </div>
                    <div class="card flex items-start gap-6">
                         <div class="flex-shrink-0 flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20">
                            <i class="fa-solid fa-store text-4xl text-emerald-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Puluhan UMKM Berhasil</h3>
                            <p class="text-gray-600">Telah mendampingi puluhan pelaku UMKM dari berbagai sektor (makanan, minuman, dll) hingga berhasil mendapatkan sertifikat halal.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Layanan Saya Section -->
        <section id="layanan" class="py-20 bg-gray-100">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Bagaimana Saya Dapat Membantu Anda?</h2>
                <p class="section-subtitle">Fokus saja pada pengembangan bisnis Anda, biar saya yang bantu urusan administrasi dan teknis sertifikasi halal.</p>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="card text-center">
                        <div class="flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20 mb-4 mx-auto">
                           <i class="fa-solid fa-file-circle-check text-4xl text-emerald-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Konsultasi & Cek Syarat</h3>
                        <p class="text-gray-600">Membantu Anda memahami semua persyaratan dan memastikan dokumen Anda lengkap.</p>
                    </div>
                    <div class="card text-center">
                        <div class="flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20 mb-4 mx-auto">
                             <i class="fa-solid fa-desktop text-4xl text-emerald-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Pendampingan di SIHALAL</h3>
                        <p class="text-gray-600">Memandu Anda saat mengisi data dan mengunggah dokumen di portal resmi SIHALAL.</p>
                    </div>
                    <div class="card text-center">
                         <div class="flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20 mb-4 mx-auto">
                            <i class="fa-solid fa-shield-halved text-4xl text-emerald-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Verifikasi Proses Produk</h3>
                        <p class="text-gray-600">Melakukan verifikasi bahan dan proses produksi untuk memastikan sesuai standar halal.</p>
                    </div>
                    <div class="card text-center">
                         <div class="flex items-center justify-center bg-emerald-100 rounded-full w-20 h-20 mb-4 mx-auto">
                           <i class="fa-solid fa-certificate text-4xl text-emerald-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Pengawalan Hingga Terbit</h3>
                        <p class="text-gray-600">Mengawal proses dari awal hingga sertifikat halal Anda diterbitkan oleh BPJPH.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Proses Pendampingan Section -->
        <section id="proses" class="py-20">
            <div class="container mx-auto px-6">
                <h2 class="section-title">Proses Mudah Bersama Saya</h2>
                <p class="section-subtitle">Saya akan memandu Anda melewati setiap tahapan ini. Anda tidak akan bingung atau salah langkah.</p>
                 <div class="max-w-3xl mx-auto">
                    <div class="space-y-8">
                        <!-- Step 1 -->
                        <div class="flex items-center gap-6">
                            <div class="flex-shrink-0 flex items-center justify-center w-12 h-12 bg-emerald-600 text-white font-bold text-xl rounded-full shadow-lg">1</div>
                            <div class="w-full card p-5">
                                <h4 class="text-xl font-bold mb-1">Hubungi & Konsultasi Awal</h4>
                                <p class="text-gray-600">Hubungi saya via WhatsApp untuk konsultasi awal, lalu siapkan data dasar seperti NIB (jika ada), KTP, dan info produk Anda.</p>
                            </div>
                        </div>
                        <!-- Step 2 -->
                        <div class="flex items-center gap-6">
                            <div class="flex-shrink-0 flex items-center justify-center w-12 h-12 bg-emerald-600 text-white font-bold text-xl rounded-full shadow-lg">2</div>
                            <div class="w-full card p-5">
                                <h4 class="text-xl font-bold mb-1">Pendaftaran Akun SIHALAL</h4>
                                <p class="text-gray-600">Saya akan bantu Anda membuat akun dan mengajukan pendaftaran di portal resmi SIHALAL dengan tepat.</p>
                            </div>
                        </div>
                        <!-- Step 3 -->
                        <div class="flex items-center gap-6">
                            <div class="flex-shrink-0 flex items-center justify-center w-12 h-12 bg-emerald-600 text-white font-bold text-xl rounded-full shadow-lg">3</div>
                            <div class="w-full card p-5">
                                <h4 class="text-xl font-bold mb-1">Verifikasi & Validasi</h4>
                                <p class="text-gray-600">Saya akan melakukan kunjungan untuk memverifikasi bahan dan alur produksi usaha Anda sesuai standar.</p>
                            </div>
                        </div>
                        <!-- Step 4 -->
                        <div class="flex items-center gap-6">
                            <div class="flex-shrink-0 flex items-center justify-center w-12 h-12 bg-emerald-600 text-white font-bold text-xl rounded-full shadow-lg">4</div>
                            <div class="w-full card p-5">
                                <h4 class="text-xl font-bold mb-1">Sertifikat Halal Terbit!</h4>
                                <p class="text-gray-600">Setelah semua proses disetujui, sertifikat halal Anda akan terbit dan siap digunakan untuk meningkatkan nilai jual produk.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- CTA Section -->
        <section id="kontak" class="py-20 bg-emerald-700 text-white">
            <div class="container mx-auto px-6 text-center">
                 <h2 class="text-3xl font-bold mb-4">Siap Memajukan Bisnis Anda?</h2>
                 <p class="text-lg text-emerald-200 max-w-2xl mx-auto mb-8">Jangan tunda lagi kesempatan mendapatkan Sertifikat Halal Gratis. Hubungi saya untuk konsultasi, saya siap membantu Anda sepenuhnya.</p>
                 <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="inline-block bg-white text-emerald-700 px-8 py-3 rounded-lg font-bold text-lg hover:bg-gray-100 transition-transform hover:scale-105 shadow-lg">
                    <i class="fab fa-whatsapp"></i> Chat Saya di WhatsApp
                </a>
            </div>
        </section>

        <!-- FAQ Section -->
        <section id="faq" class="py-20 bg-gray-100">
            <div class="container mx-auto px-6 max-w-3xl">
                <h2 class="section-title">Tanya Jawab (FAQ)</h2>
                <p class="section-subtitle">Temukan jawaban atas pertanyaan yang sering diajukan.</p>
                <div class="space-y-4">
                    <div class="bg-white rounded-lg shadow-sm">
                        <button class="faq-toggle w-full flex justify-between items-center text-left p-5 font-semibold text-gray-800">
                            <span>Berapa biaya jasa pendampingan ini?</span>
                            <svg class="w-5 h-5 transform transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </button>
                        <div class="faq-content hidden p-5 pt-0 text-gray-600">
                            <p>Untuk program SEHATI (Sertifikasi Halal Gratis), jasa pendampingan saya sebagai P3H sepenuhnya GRATIS untuk Anda.</p>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm">
                        <button class="faq-toggle w-full flex justify-between items-center text-left p-5 font-semibold text-gray-800">
                            <span>Usaha seperti apa yang bisa didampingi?</span>
                             <svg class="w-5 h-5 transform transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </button>
                        <div class="faq-content hidden p-5 pt-0 text-gray-600">
                           <p>Saya mendampingi Usaha Mikro dan Kecil (UMK) yang memenuhi kriteria program SEHATI, yaitu memiliki NIB, produknya tidak berisiko tinggi (bukan sembelihan, dll), dan menggunakan bahan serta proses yang sederhana dan sudah terjamin kehalalannya.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-8 text-center">
            <a href="#" class="text-2xl font-bold text-white mb-4 inline-block">Azka Nahdi</a>
            <p class="text-gray-400 mb-4">Pendamping Proses Produk Halal (P3H)</p>
            <div class="flex justify-center space-x-6 mb-6">
                <a href="https://wa.me/6287777111904?text=Halo Kak Azka, saya tertarik untuk program sertifikasi halal gratis. Mohon informasinya." target="_blank" class="text-gray-300 hover:text-white text-3xl"><i class="fab fa-whatsapp"></i></a>
                <a href="https://instagram.com/nahdi.azka" target="_blank" class="text-gray-300 hover:text-white text-3xl"><i class="fab fa-instagram"></i></a>
            </div>
            <p class="text-gray-500 text-sm">
                &copy; 2024 Azka Nahdi. All rights reserved.
            </p>
        </div>
    </footer>
    
    <script>
        // Mobile menu toggle
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // FAQ Accordion
        const faqToggles = document.querySelectorAll('.faq-toggle');

        faqToggles.forEach(toggle => {
            toggle.addEventListener('click', () => {
                const content = toggle.nextElementSibling;
                const icon = toggle.querySelector('svg');
                
                // Close other open FAQs
                faqToggles.forEach(otherToggle => {
                    if (otherToggle !== toggle) {
                        otherToggle.nextElementSibling.classList.add('hidden');
                        otherToggle.querySelector('svg').classList.remove('rotate-180');
                    }
                });

                // Toggle current FAQ
                content.classList.toggle('hidden');
                icon.classList.toggle('rotate-180');
            });
        });
    </script>

</body>
</html>

