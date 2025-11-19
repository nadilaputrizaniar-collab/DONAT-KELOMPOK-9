# DONAT-KELOMPOK-9
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kentato - Donat Kentang Paling Hits!</title>
    
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter & Pacifico -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&family=Pacifico&display=swap" rel="stylesheet">
    
    <style>
        /* Custom styles for the page */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #FFF7ED; /* A warm, creamy background color */
        }
        .font-pacifico {
            font-family: 'Pacifico', cursive;
        }
        .brand-text {
            color: #D66A2A; /* A warm, donut-like color */
        }
        .brand-bg {
            background-color: #D66A2A;
        }
        .brand-bg-light {
            background-color: #FDE68A; /* A light, friendly yellow */
        }
        .card-shadow {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.05), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .btn-whatsapp {
            background-color: #25D366;
            transition: background-color 0.3s ease;
        }
        .btn-whatsapp:hover {
            background-color: #1DAE52;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Header -->
    <header class="p-4 text-center">
        <h1 class="font-pacifico text-5xl brand-text">Kentato</h1>
        <p class="text-gray-500 mt-1">oleh Kelompok 9 (XII-H)</p>
        <p class="text-sm text-gray-400">Ghizzelya Dzulaikha • M. Fasya Alhady • Nadila Putri Zaniar</p>
    </header>

    <main class="container mx-auto p-4 md:p-8 max-w-6xl">

        <!-- Hero Section -->
        <section id="home" class="text-center bg-white rounded-2xl p-8 md:p-12 card-shadow" style="background-image: url('https://images.unsplash.com/photo-1551024601-bec78d8d5d36?q=80&w=2070&auto=format&fit=crop'); background-size: cover; background-position: center;">
            <div class="bg-white/80 backdrop-blur-sm p-6 rounded-xl">
                <h2 class="text-3xl md:text-4xl font-extrabold brand-text">Donat Kentang Paling Hits di SMAN 1 Dramaga!</h2>
                <p class="mt-4 max-w-2xl mx-auto text-gray-700">
                    Cobain Kentato sekarang! Donat kentang dengan tekstur super empuk, rasa manis yang pas, dan harga yang dijamin terjangkau. Bikin harimu jadi lebih manis!
                </p>
            </div>
        </section>

        <!-- Varian Donat Section -->
        <section id="varian" class="mt-12">
            <h3 class="text-3xl font-bold text-center mb-8">Pilih Varian Favoritmu</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Donat Gula Halus -->
                <div class="bg-white rounded-2xl overflow-hidden card-shadow transform hover:scale-105 transition-transform duration-300">
                    <img src="https://dekopin.or.id/wp-content/uploads/2024/11/032875800_1604118231-shutterstock_1729999204.webp" alt="Donat Gula Halus" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold">🍩 Donat Gula Halus</h4>
                        <p class="mt-2 text-gray-600">Donat klasik dengan taburan gula halus yang lembut di setiap gigitan. Manisnya pas, bikin nagih!</p>
                        <p class="mt-4 text-2xl font-bold brand-text">Rp 5.000</p>
                    </div>
                </div>
                <!-- Donat Topping Coklat -->
                <div class="bg-white rounded-2xl overflow-hidden card-shadow transform hover:scale-105 transition-transform duration-300">
                    <img src="https://media.istockphoto.com/id/182420116/id/foto/donat-berlapis-cokelat.jpg?s=612x612&w=0&k=20&c=-mcWr0atVmmMPR58gIng7m1T-wHgXIOCgDAvmRvbf-Q=" alt="Donat Topping Coklat" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold">🍫 Donat Topping Coklat</h4>
                        <p class="mt-2 text-gray-600">Donat super fluffy dengan lelehan coklat premium di atasnya. Pilihan tepat buat para pecinta coklat!</p>
                        <p class="mt-4 text-2xl font-bold brand-text">Rp 5.000</p>
                    </div>
                </div>
                <!-- Donat Strawberry -->
                <div class="bg-white rounded-2xl overflow-hidden card-shadow transform hover:scale-105 transition-transform duration-300">
                    <img src="https://hypeabis.id/assets/content/20230716061419000000Bomboloni.jpg" alt="Donat Strawberry" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold">🍓 Donat Strawberry</h4>
                        <p class="mt-2 text-gray-600">Manis dan segarnya selai stroberi bertemu dengan lembutnya donat kentang. Kombinasi yang sempurna!</p>
                        <p class="mt-4 text-2xl font-bold brand-text">Rp 5.000</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Alasan Kenapa Harus Coba Section -->
        <section id="why" class="mt-12 text-center bg-amber-100/50 rounded-2xl p-8 md:p-12">
            <h3 class="text-3xl font-bold mb-6">Kenapa Harus Coba Kentato?</h3>
            <div class="grid md:grid-cols-2 gap-6 text-left">
                <div class="bg-white p-6 rounded-lg">
                    <h4 class="font-bold text-lg">🎉 Cocok Untuk Semua Situasi</h4>
                    <p class="text-gray-600 mt-1">Pas buat ngemil santai pas istirahat, kumpul bareng teman, atau jadi oleh-oleh buat orang tersayang.</p>
                </div>
                 <div class="bg-white p-6 rounded-lg">
                    <h4 class="font-bold text-lg">💰 Harga Ramah di Kantong</h4>
                    <p class="text-gray-600 mt-1">Nikmati cita rasa premium dengan harga yang bersahabat. Kualitas top, kantong tetap aman!</p>
                </div>
            </div>
        </section>

        <!-- Form Pemesanan Section -->
        <section id="order" class="mt-12">
            <div class="bg-white rounded-2xl p-8 md:p-12 card-shadow">
                <h3 class="text-3xl font-bold text-center mb-8">Form Pemesanan</h3>
                <form id="orderForm" class="max-w-lg mx-auto">
                    <div class="mb-4">
                        <label for="nama" class="block text-gray-700 font-bold mb-2">Nama Lengkap</label>
                        <input type="text" id="nama" name="nama" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-amber-400" placeholder="Masukkan nama kamu" required>
                    </div>
                    <div class="mb-4">
                        <label for="kelas" class="block text-gray-700 font-bold mb-2">Kelas</label>
                        <input type="text" id="kelas" name="kelas" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-amber-400" placeholder="Contoh: XII-H" required>
                    </div>
                    <div class="mb-4">
                        <label for="varian" class="block text-gray-700 font-bold mb-2">Pilih Varian Donat</label>
                        <select id="varian" name="varian" class="w-full px-4 py-3 border border-gray-300 rounded-lg bg-white focus:outline-none focus:ring-2 focus:ring-amber-400" required>
                            <option value="">-- Pilih Varian --</option>
                            <option value="Gula Halus">Donat Gula Halus</option>
                            <option value="Topping Coklat">Donat Topping Coklat</option>
                            <option value="Strawberry">Donat Strawberry</option>
                        </select>
                    </div>
                    <div class="mb-6">
                        <label for="jumlah" class="block text-gray-700 font-bold mb-2">Jumlah Pesanan</label>
                        <input type="number" id="jumlah" name="jumlah" min="1" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-amber-400" placeholder="Minimal 1" required>
                    </div>
                    <button type="submit" class="w-full btn-whatsapp text-white font-bold py-4 px-4 rounded-lg flex items-center justify-center text-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
                        Kirim Pesanan via WhatsApp
                    </button>
                </form>
            </div>
        </section>
        
        <!-- Pembayaran Section -->
        <section id="payment" class="mt-12">
            <div class="bg-blue-50 border-l-4 border-blue-500 text-blue-800 p-6 rounded-lg">
                 <h3 class="text-2xl font-bold">Langkah Pembayaran</h3>
                 <p class="mt-4">Setelah mengirim pesanan via WhatsApp, kamu bisa langsung melakukan pembayaran melalui DANA:</p>
                 <div class="mt-4 bg-white p-4 rounded-lg text-center">
                    <p class="font-mono text-lg font-bold">081283737028</p>
                    <p class="text-sm">a.n. Kentato (contoh)</p>
                 </div>
                 <p class="mt-4 font-semibold">Setelah pembayaran berhasil, pesananmu akan langsung kami proses. Terima kasih!</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="text-center p-6 mt-8">
        <p class="text-gray-600">&copy; 2025 Kentato - Kelompok 9, SMAN 1 Dramaga. All Rights Reserved.</p>
    </footer>

    <script>
        // JavaScript to handle form submission and redirect to WhatsApp
        document.getElementById('orderForm').addEventListener('submit', function(event) {
            event.preventDefault();

            // Get form values
            const nama = document.getElementById('nama').value;
            const kelas = document.getElementById('kelas').value;
            const varian = document.getElementById('varian').value;
            const jumlah = document.getElementById('jumlah').value;
            const harga = 5000;
            const total = jumlah * harga;

            // Format number to Indonesian Rupiah
            const formattedTotal = new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', minimumFractionDigits: 0 }).format(total);

            // Construct the WhatsApp message
            const message = `Halo Kentato, saya mau pesan donat! 🍩
---
*Nama:* ${nama}
*Kelas:* ${kelas}
*Varian:* ${varian}
*Jumlah:* ${jumlah} buah
*Total Harga:* ${formattedTotal}
---
Terima kasih! 🙏`;

            // WhatsApp phone number
            const phoneNumber = '6281283737028'; // Indonesian country code + phone number without leading 0

            // Create the WhatsApp URL
            const whatsappURL = `https://wa.me/${phoneNumber}?text=${encodeURIComponent(message)}`;

            // Open WhatsApp
            window.open(whatsappURL, '_blank');
        });
    </script>

</body>
</html>
