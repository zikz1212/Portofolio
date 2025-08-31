<html lang="id">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>Portofolio Rafi Mahya Zikri</title>
  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet"/>
  <!-- AOS Animate On Scroll -->
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet"/>
  <style>
   body {
      font-family: "Poppins", Arial, sans-serif;
      background-color: #0a0a0a;
      color: #eee;
      scroll-behavior: smooth;
    }
    /* Scrollbar styling */
    ::-webkit-scrollbar { width: 8px; height: 8px; }
    ::-webkit-scrollbar-track { background: #121212; }
    ::-webkit-scrollbar-thumb { background-color: #d4af37; border-radius: 10px; border: 2px solid #121212; }
  </style>
 </head>
 <body class="min-h-screen flex flex-col">
  <!-- Header -->
  <header class="relative bg-gradient-to-b from-yellow-600 via-yellow-500 to-yellow-400 text-center py-20 px-6 overflow-hidden">
   <div class="absolute inset-0 -z-10 opacity-20">
    <img alt="Golden abstract background" class="w-full h-full object-cover" src="https://storage.googleapis.com/a1aa/image/3acfd26b-04a6-4b77-5948-20711c0c3f6f.jpg"/>
   </div>
   <div class="max-w-3xl mx-auto">
    <!-- FOTO PROFIL LEBIH BESAR (w-48 h-48) -->
    <img alt="Foto Profil Rafi Mahya Zikri" 
         class="mx-auto rounded-full border-8 border-white shadow-2xl w-48 h-48 object-cover" 
         src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtK9nxzZlPd9G851SnEnRm2zXMorh0wWwHOg&s"/>
    
    <h1 class="mt-8 text-white text-5xl font-extrabold tracking-tight drop-shadow-lg" data-aos="fade-up">
     Rafi Mahya Zikri
    </h1>
    <p class="mt-3 text-yellow-100 text-xl font-semibold tracking-wide drop-shadow-md" data-aos="fade-up" data-aos-delay="200">
     Web Developer | Designer | Freelancer
    </p>
    <div class="mt-8 flex justify-center space-x-6 text-yellow-100 text-3xl drop-shadow-md">
     <a href="https://github.com/rafimahyaz" target="_blank" class="hover:text-white transition">
      <i class="fab fa-github"></i>
     </a>
     <a href="https://linkedin.com/in/rafimahyaz" target="_blank" class="hover:text-white transition">
      <i class="fab fa-linkedin"></i>
     </a>
     <a href="https://twitter.com/rafimahyaz" target="_blank" class="hover:text-white transition">
      <i class="fab fa-twitter"></i>
     </a>
    </div>
   </div>
  </header>
  
  <!-- Main -->
  <main class="flex-grow max-w-7xl mx-auto px-6 sm:px-12 py-16 space-y-20">
   <!-- Tentang -->
   <section class="bg-gradient-to-r from-yellow-600 via-yellow-500 to-yellow-400 rounded-3xl shadow-2xl p-12 max-w-4xl mx-auto" data-aos="fade-right">
    <h2 class="text-white text-4xl font-extrabold mb-6 tracking-wide drop-shadow-lg">Tentang Saya</h2>
    <p class="text-yellow-50 text-lg leading-relaxed tracking-wide drop-shadow-md">
     Halo! Saya adalah seorang developer yang berfokus pada pembuatan website modern, responsif, dan user-friendly. 
     Saya senang mengubah ide menjadi produk digital yang bermanfaat. 
     Dengan pengalaman dalam berbagai teknologi web, saya selalu berusaha memberikan hasil terbaik.
    </p>
   </section>

   <!-- Keahlian -->
   <section class="bg-gradient-to-l from-yellow-600 via-yellow-500 to-yellow-400 rounded-3xl shadow-2xl p-12 max-w-5xl mx-auto" data-aos="fade-left">
    <h2 class="text-white text-4xl font-extrabold mb-8 tracking-wide drop-shadow-lg">Keahlian</h2>
    <div class="flex flex-wrap justify-center gap-6">
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">HTML</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">CSS</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">JavaScript</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">React</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">UI/UX</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">Tailwind CSS</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">Node.js</span>
     <span class="bg-white text-yellow-600 font-bold px-7 py-3 rounded-full shadow-xl">Git</span>
    </div>
   </section>

   <!-- Proyek -->
   <section class="max-w-7xl mx-auto" data-aos="fade-up">
    <h2 class="text-yellow-500 text-5xl font-extrabold mb-12 text-center tracking-wide drop-shadow-lg">Proyek</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-12">
     <!-- Card 1 -->
     <div class="bg-gradient-to-tr from-yellow-600 via-yellow-500 to-yellow-400 rounded-3xl shadow-2xl overflow-hidden transform hover:scale-105 transition-transform">
      <img class="w-full h-48 object-cover" src="https://storage.googleapis.com/a1aa/image/e3dd4f1e-44ea-405b-8619-acec2900ea88.jpg"/>
      <div class="p-8 bg-black bg-opacity-70">
       <h3 class="text-white text-2xl font-extrabold mb-3">Website Portofolio</h3>
       <p class="text-yellow-100 text-base mb-6">Portofolio pribadi dengan desain responsif dan elegan.</p>
      </div>
     </div>
     <!-- Card 2 -->
     <div class="bg-gradient-to-tr from-yellow-600 via-yellow-500 to-yellow-400 rounded-3xl shadow-2xl overflow-hidden transform hover:scale-105 transition-transform">
      <img class="w-full h-48 object-cover" src="https://storage.googleapis.com/a1aa/image/3e16674a-73fd-4186-1031-ef891255fb4e.jpg"/>
      <div class="p-8 bg-black bg-opacity-70">
       <h3 class="text-white text-2xl font-extrabold mb-3">Aplikasi To-Do List</h3>
       <p class="text-yellow-100 text-base mb-6">Aplikasi sederhana untuk mencatat daftar tugas harian.</p>
      </div>
     </div>
     <!-- Card 3 -->
     <div class="bg-gradient-to-tr from-yellow-600 via-yellow-500 to-yellow-400 rounded-3xl shadow-2xl overflow-hidden transform hover:scale-105 transition-transform">
      <img class="w-full h-48 object-cover" src="https://storage.googleapis.com/a1aa/image/1514ffb8-457b-4f19-de23-49a5bdea0841.jpg"/>
      <div class="p-8 bg-black bg-opacity-70">
       <h3 class="text-white text-2xl font-extrabold mb-3">Landing Page Produk</h3>
       <p class="text-yellow-100 text-base mb-6">Halaman promosi produk dengan desain modern.</p>
      </div>
     </div>
    </div>
   </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gradient-to-t from-yellow-600 via-yellow-500 to-yellow-400 text-black text-center py-10 px-6 mt-20 shadow-inner">
   <p class="mb-4 text-lg font-semibold">Hubungi saya di: 
    <a class="underline font-extrabold" href="mailto:rafimahyaz@gmail.com">rafimahyaz@gmail.com</a>
   </p>
   <div class="flex justify-center space-x-10 text-black text-3xl">
    <a href="https://github.com/rafimahyaz" target="_blank"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/rafimahyaz" target="_blank"><i class="fab fa-linkedin"></i></a>
    <a href="https://twitter.com/rafimahyaz" target="_blank"><i class="fab fa-twitter"></i></a>
   </div>
   <p class="mt-6 text-black text-sm">© 2024 Rafi Mahya Zikri. All rights reserved.</p>
  </footer>

  <!-- AOS JS -->
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
   AOS.init({ duration: 1200, once: true, easing: 'ease-in-out' });
  </script>
 </body>
</html>
