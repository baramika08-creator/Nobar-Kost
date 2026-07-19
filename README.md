 
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nobar Kost - Kost Putri ITERA</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <nav class="bg-[#023E3F] text-white py-4 px-6 md:px-12 flex justify-between items-center sticky top-0 z-50 shadow-md">
        <div class="flex items-center space-x-2">
            <i class="fa-solid fa-house-chimney text-2xl text-[#00A896]"></i>
            <span class="font-bold text-xl tracking-wide">NOBAR <span class="text-xs block text-[#00A896] font-normal -mt-1">KOST</span></span>
        </div>
        <div class="hidden md:flex space-x-6 text-sm font-medium">
            <a href="#" class="hover:text-[#00A896] transition">Beranda</a>
            <a href="#fasilitas" class="hover:text-[#00A896] transition">Fasilitas</a>
            <a href="#kamar" class="hover:text-[#00A896] transition">Kamar</a>
            <a href="#galeri" class="hover:text-[#00A896] transition">Galeri</a>
            <a href="#lokasi" class="hover:text-[#00A896] transition">Lokasi</a>
            <a href="#kontak" class="hover:text-[#00A896] transition">Kontak</a>
        </div>
        <a href="https://wa.me/6285379953940" target="_blank" class="bg-[#00A896] hover:bg-[#028074] text-white px-4 py-2 rounded-full text-sm font-semibold flex items-center space-x-2 transition shadow">
            <i class="fa-brands fa-whatsapp text-lg"></i>
            <span>Hubungi Kami</span>
        </a>
    </nav>

    <section class="relative bg-gradient-to-r from-[#023E3F] via-[#023E3F]/90 to-transparent min-h-[85vh] flex items-center px-6 md:px-20 text-white overflow-hidden">
        <div class="absolute inset-0 z-0 bg-cover bg-center opacity-40 md:opacity-100 md:left-1/3" style="background-image: url('https://images.unsplash.com/photo-1522771739844-6a9f6d5f14af?auto=format&fit=crop&w=1200&q=80');"></div>
        
        <div class="relative z-10 max-w-xl space-y-6">
            <span class="bg-[#00A896]/20 text-[#00A896] border border-[#00A896] px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider">Kost Putri</span>
            <h1 class="text-4xl md:text-5xl font-extrabold leading-tight">
                Terima Kost <br><span class="text-[#00A896]">Putri ITERA</span>
            </h1>
            <p class="text-gray-300 text-base md:text-lg">
                Hunian nyaman, aman, bersih dan strategis untuk mahasiswa Putri ITERA.
            </p>
            
            <div class="bg-[#012A2B]/80 backdrop-blur border border-teal-800 p-4 rounded-xl max-w-xs shadow-lg">
                <span class="text-xs text-gray-400 block">Mulai dari</span>
                <span class="text-2xl font-bold text-[#00A896]">Rp. 6.500.000 / tahun</span>
                <span class="text-xs text-gray-300 block mt-1"><i class="fa-solid fa-circle-check text-emerald-400 mr-1"></i> Sudah termasuk free air & parkir luas!</span>
            </div>

            <div class="flex flex-wrap gap-4 pt-2">
                <a href="https://wa.me/6285379953940" target="_blank" class="bg-[#00A896] hover:bg-[#028074] px-6 py-3 rounded-xl font-bold flex items-center space-x-2 transition shadow-lg">
                    <i class="fa-brands fa-whatsapp"></i>
                    <span>Hubungi Kami</span>
                </a>
                <a href="#lokasi" class="bg-transparent border border-white/50 hover:bg-white/10 px-6 py-3 rounded-xl font-bold flex items-center space-x-2 transition">
                    <i class="fa-solid fa-location-dot"></i>
                    <span>Lihat Lokasi</span>
                </a>
            </div>
        </div>
    </section>

    <section id="fasilitas" class="max-w-6xl mx-auto -mt-10 relative z-20 px-4">
        <div class="bg-white rounded-2xl shadow-xl p-6 grid grid-cols-2 sm:grid-cols-4 md:grid-cols-8 gap-6 text-center border border-gray-100">
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-bed"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Kamar Standar</h4>
                <p class="text-[10px] text-gray-500">3x2,8 m</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-mattress-pillow"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Bed Cover</h4>
                <p class="text-[10px] text-gray-500">Siap Pakai</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-box-archive"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Lemari</h4>
                <p class="text-[10px] text-gray-500">Penyimpanan</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-table-columns"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Meja Belajar</h4>
                <p class="text-[10px] text-gray-500">Nyaman</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-shower"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Kamar Mandi</h4>
                <p class="text-[10px] text-gray-500">Dalam Kamar</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-faucet-drip"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Free Air</h4>
                <p class="text-[10px] text-gray-500">Tanpa Biaya</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-kitchen-set"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Dapur Umum</h4>
                <p class="text-[10px] text-gray-500">Bersih & Rapi</p>
            </div>
            <div class="space-y-2 flex flex-col items-center">
                <div class="text-[#00A896] text-2xl"><i class="fa-solid fa-square-parking"></i></div>
                <h4 class="font-bold text-xs text-gray-900">Parkir Luas</h4>
                <p class="text-[10px] text-gray-500">Aman & Nyaman</p>
            </div>
        </div>
    </section>

    <section class="max-w-6xl mx-auto py-16 px-6 grid md:grid-cols-2 gap-10 items-center">
        <div class="grid grid-cols-2 gap-4">
            <div class="space-y-4">
                <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=400&q=80" alt="Dapur" class="rounded-xl w-full h-40 object-cover shadow">
                <img src="https://images.unsplash.com/photo-1598928506311-c55ded91a20c?auto=format&fit=crop&w=400&q=80" alt="Kamar" class="rounded-xl w-full h-40 object-cover shadow">
            </div>
            <div>
                <img src="https://images.unsplash.com/photo-1582268611958-ebfd161ef9cf?auto=format&fit=crop&w=400&q=85" alt="Gedung" class="rounded-xl w-full h-[21rem] object-cover shadow">
            </div>
        </div>
        <div class="space-y-6">
            <div>
                <span class="text-xs font-bold text-[#00A896] uppercase tracking-wider block mb-1">Tentang Nobar Kost</span>
                <h2 class="text-3xl font-extrabold text-[#023E3F]">Kost Putri Nyaman <br><span class="text-[#00A896]">Dekat ITERA</span></h2>
            </div>
            <p class="text-gray-600 leading-relaxed text-sm">
                NOBAR KOST hadir untuk memberikan kenyamanan tinggal bagi mahasiswa putri ITERA dengan lingkungan yang aman, bersih, dan fasilitas lengkap.
            </p>
            <ul class="space-y-3 text-sm font-medium text-gray-700">
                <li class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-[#00A896]"></i> <span>Akses tangga 2 lantai</span></li>
                <li class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-[#00A896]"></i> <span>± 3-5 menit dari ITERA</span></li>
                <li class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-[#00A896]"></i> <span>Lingkungan aman & nyaman</span></li>
                <li class="flex items-center space-x-3"><i class="fa-solid fa-circle-check text-[#00A896]"></i> <span>Khusus untuk putri</span></li>
            </ul>
        </div>
    </section>

    <section id="kamar" class="bg-gray-100 py-16 px-6">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-10">
                <span class="text-xs font-bold text-[#00A896] uppercase tracking-wider block mb-1">Kamar</span>
                <h2 class="text-3xl font-extrabold text-[#023E3F]">Kamar Standar</h2>
                <div class="w-12 h-1 bg-[#00A896] mx-auto mt-2 rounded"></div>
            </div>

            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 flex flex-col justify-between">
                    <img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=300&q=80" alt="Kamar Bersih" class="w-full h-40 object-cover">
                    <div class="p-4 flex items-start space-x-3">
                        <div class="bg-teal-50 text-[#00A896] p-2 rounded-lg mt-1"><i class="fa-solid fa-bed"></i></div>
                        <div>
                            <h4 class="font-bold text-sm text-gray-900">Kamar Bersih & Nyaman</h4>
                            <p class="text-xs text-gray-500 mt-1">Ukuran 3x2,8 meter dengan ventilasi udara yang baik.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 flex flex-col justify-between">
                    <img src="https://images.unsplash.com/photo-1595515106969-1ce29566ff1c?auto=format&fit=crop&w=300&q=80" alt="Fasilitas" class="w-full h-40 object-cover">
                    <div class="p-4 flex items-start space-x-3">
                        <div class="bg-teal-50 text-[#00A896] p-2 rounded-lg mt-1"><i class="fa-solid fa-couch"></i></div>
                        <div>
                            <h4 class="font-bold text-sm text-gray-900">Fasilitas Lengkap</h4>
                            <p class="text-xs text-gray-500 mt-1">Lemari pakaian dan meja belajar untuk kenyamanan Anda.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 flex flex-col justify-between">
                    <img src="https://images.unsplash.com/photo-1620626011160-9928f1b9b630?auto=format&fit=crop&w=300&q=80" alt="Kamar Mandi" class="w-full h-40 object-cover">
                    <div class="p-4 flex items-start space-x-3">
                        <div class="bg-teal-50 text-[#00A896] p-2 rounded-lg mt-1"><i class="fa-solid fa-toilet"></i></div>
                        <div>
                            <h4 class="font-bold text-sm text-gray-900">Kamar Mandi Dalam</h4>
                            <p class="text-xs text-gray-500 mt-1">Lebih privasi dan praktis setiap saat tanpa perlu antre.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 flex flex-col justify-between">
                    <img src="https://images.unsplash.com/photo-1582268611958-ebfd161ef9cf?auto=format&fit=crop&w=300&q=80" alt="Suasana" class="w-full h-40 object-cover">
                    <div class="p-4 flex items-start space-x-3">
                        <div class="bg-teal-50 text-[#00A896] p-2 rounded-lg mt-1"><i class="fa-solid fa-building-user"></i></div>
                        <div>
                            <h4 class="font-bold text-sm text-gray-900">Suasana Kost</h4>
                            <p class="text-xs text-gray-500 mt-1">Lingkungan kost yang rapi, tenang, aman dan bersih.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="galeri" class="max-w-6xl mx-auto py-16 px-6 relative">
        <div class="text-center mb-10">
            <span class="text-xs font-bold text-[#00A896] uppercase tracking-wider block mb-1">Galeri</span>
            <h2 class="text-3xl font-extrabold text-[#023E3F]">Galeri Kost</h2>
            <div class="w-12 h-1 bg-[#00A896] mx-auto mt-2 rounded"></div>
        </div>

        <div class="flex items-center space-x-4">
            <button class="bg-white border text-gray-600 p-3 rounded-full shadow hover:bg-gray-100 transition"><i class="fa-solid fa-chevron-left"></i></button>
            
            <div class="grid grid-cols-2 md:grid-cols-5 gap-4 w-full overflow-hidden">
                <img src="https://images.unsplash.com/photo-1582268611958-ebfd161ef9cf?auto=format&fit=crop&w=250&q=80" alt="Galeri 1" class="rounded-xl w-full h-48 object-cover shadow-sm">
                <img src="https://images.unsplash.com/photo-1598928506311-c55ded91a20c?auto=format&fit=crop&w=250&q=80" alt="Galeri 2" class="rounded-xl w-full h-48 object-cover shadow-sm">
                <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=250&q=80" alt="Galeri 3" class="rounded-xl w-full h-48 object-cover shadow-sm">
                <img src="https://images.unsplash.com/photo-1595515106969-1ce29566ff1c?auto=format&fit=crop&w=250&q=80" alt="Galeri 4" class="rounded-xl w-full h-48 object-cover shadow-sm">
                <img src="https://images.unsplash.com/photo-1620626011160-9928f1b9b630?auto=format&fit=crop&w=250&q=80" alt="Galeri 5" class="rounded-xl w-full h-48 object-cover shadow-sm">
            </div>

            <button class="bg-white border text-gray-600 p-3 rounded-full shadow hover:bg-gray-100 transition"><i class="fa-solid fa-chevron-right"></i></button>
        </div>
    </section>

    <footer id="kontak" class="bg-[#023E3F] text-white py-10 px-6 md:px-12 border-t-4 border-[#00A896]">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-start md:items-center gap-8">
            
            <div class="flex items-center space-x-4">
                <div class="bg-[#00A896] p-4 rounded-full text-2xl text-white">
                    <i class="fa-brands fa-whatsapp"></i>
                </div>
                <div>
                    <h4 class="font-bold text-base">Hubungi Kami</h4>
                    <p class="text-xs text-gray-300">Booking kamar sekarang juga sebelum penuh!</p>
                </div>
            </div>

            <div class="flex flex-col sm:flex-row gap-4 sm:gap-8">
                <div class="flex items-center space-x-3">
                    <i class="fa-solid fa-phone text-[#00A896] text-lg"></i>
                    <div class="text-sm">
                        <p class="font-bold">0853 7995 3940</p>
                        <p class="text-[11px] text-gray-400">(Ambar)</p>
                    </div>
                </div>
                <div class="flex items-center space-x-3">
                    <i class="fa-solid fa-phone text-[#00A896] text-lg"></i>
                    <div class="text-sm">
                        <p class="font-bold">0853 7995 3930</p>
                        <p class="text-[11px] text-gray-400">(Yudi)</p>
                    </div>
                </div>
            </div>

            <div id="lokasi" class="flex items-center space-x-3 max-w-xs">
                <i class="fa-solid fa-location-dot text-[#00A896] text-xl"></i>
                <div class="text-xs">
                    <h5 class="font-bold mb-0.5">Lokasi Kost</h5>
                    <p class="text-gray-300 leading-tight">Mamikos, Kec. Labuhan Maringgai, Kabupaten Lampung Timur, Lampung</p>
                </div>
            </div>

        </div>
        <div class="text-center text-xs text-gray-400 mt-10 pt-4 border-t border-teal-900">
            &copy; 2026 Nobar Kost. All rights reserved.
        </div>
    </footer>

</body>
</html>
