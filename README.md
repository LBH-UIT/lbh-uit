## Selamat Datang di LBH-UIT 👋

<!--
**LBH-UIT/lbh-uit** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
git clone https://github.com/LBH‑UIT/lbh‑uit‑website.git
cd lbh‑uit‑website
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LBH-UIT Makassar</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 font-sans">
  <!-- Header -->
  <header class="bg-red-800 text-white py-6 shadow">
    <div class="container mx-auto px-6">
      <h1 class="text-3xl font-bold">Lembaga Bantuan Hukum Universitas Indonesia Timur (LBH-UIT)</h1>
      <p class="text-sm">Makassar</p>
    </div>
  </header>

  <!-- Navigasi -->
  <nav class="bg-red-700 text-white">
    <div class="container mx-auto px-6 py-2 flex space-x-4">
      <a href="#beranda" class="hover:underline">Beranda</a>
      <a href="#tentang" class="hover:underline">Tentang Kami</a>
      <a href="#layanan" class="hover:underline">Layanan</a>
      <a href="#kontak" class="hover:underline">Kontak</a>
    </div>
  </nav>

  <!-- Beranda -->
  <section id="beranda" class="py-12 text-center bg-white">
    <h2 class="text-2xl font-semibold mb-2">Mewujudkan Keadilan, Mengabdi untuk Rakyat</h2>
    <p class="text-gray-700">LBH-UIT hadir untuk membantu masyarakat yang membutuhkan keadilan dan perlindungan hukum.</p>
  </section>

  <!-- Tentang Kami -->
  <section id="tentang" class="py-12 bg-gray-50 px-6">
    <h2 class="text-xl font-semibold text-red-800 mb-4">Visi</h2>
    <p class="mb-6">Menjadi cahaya keadilan di tengah kabut ketimpangan, memperjuangkan hak setiap insan untuk hidup bermartabat dalam naungan hukum yang adil.</p>

    <h2 class="text-xl font-semibold text-red-800 mb-4">Misi</h2>
    <ol class="list-decimal ml-6 text-gray-800 space-y-2">
      <li>Menyediakan layanan bantuan hukum yang profesional dan berpihak pada masyarakat miskin, marjinal, dan kelompok rentan.</li>
      <li>Mendorong reformasi hukum melalui advokasi dan pendidikan hukum.</li>
      <li>Membangun sinergi dengan lembaga nasional dan internasional dalam memperkuat sistem hukum yang demokratis dan akuntabel.</li>
      <li>Menjunjung tinggi prinsip keadilan restoratif sebagai sarana pemulihan dan pemberdayaan masyarakat.</li>
    </ol>
  </section>

  <!-- Layanan -->
  <section id="layanan" class="py-12 bg-white px-6">
    <h2 class="text-xl font-semibold text-red-800 mb-4">Pelayanan LBH-UIT</h2>
    <ul class="list-disc ml-6 text-gray-800 space-y-2">
      <li>Membantu masyarakat yang memerlukan bantuan hukum.</li>
      <li>Membantu masyarakat yang membutuhkan pendidikan dan pelatihan paralegal.</li>
      <li>Membantu masyarakat dalam memantau dan melaporkan pelanggaran hukum oleh penegak hukum atau pemerintah.</li>
      <li>Menyediakan tempat magang bagi mahasiswa hukum, calon advokat, asisten advokat, pembela umum, paralegal, dan sarjana hukum.</li>
    </ul>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="py-12 bg-gray-50 px-6">
    <h2 class="text-xl font-semibold text-red-800 mb-4">Kontak Kami</h2>
    <p>Email: <a href="mailto:gintamaleo12@gmail.com" class="text-blue-600 underline">gintamaleo12@gmail.com</a></p>
  </section>

  <!-- Footer -->
  <footer class="bg-red-800 text-white text-center py-4">
    <p>&copy; 2025 LBH-UIT. Semua Hak Dilindungi.</p>
  </footer>
</body>
</html>
git add index.html
git commit -m "Initial LBH‑UIT website"
git push origin main
