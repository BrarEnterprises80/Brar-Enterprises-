<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Decor Haven</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow p-6 flex justify-between items-center">
    <h1 class="text-3xl font-bold tracking-tight">Decor Haven</h1>
    <nav class="space-x-6 text-lg">
      <a href="#products" class="hover:text-gray-500">Products</a>
      <a href="#about" class="hover:text-gray-500">About</a>
      <a href="#contact" class="hover:text-gray-500">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1505692794400-5e0a1f3d6d36');">
    <div class="bg-white bg-opacity-70 inline-block px-8 py-6 rounded-2xl shadow-xl">
      <h2 class="text-4xl font-bold mb-4">Beautiful Decor for Every Space</h2>
      <p class="text-lg mb-6">Elevate your home with curated, stylish pieces.</p>
      <a href="#products" class="px-6 py-3 bg-gray-900 text-white rounded-xl text-lg hover:bg-gray-700">Shop Now</a>
    </div>
  </section>

  <!-- Products Section -->
  <section id="products" class="py-20 px-6 max-w-6xl mx-auto">
    <h3 class="text-3xl font-bold text-center mb-12">Featured Decor Items</h3>

    <div class="grid md:grid-cols-3 gap-10">
      <!-- Product Card 1 -->
      <div class="bg-white rounded-2xl shadow-xl p-6">
        <img src="https://images.unsplash.com/photo-1582582428401-751a5b43d4d1" alt="Vase" class="rounded-xl mb-4" />
        <h4 class="text-xl font-semibold mb-1">Elegant Ceramic Vase</h4>
        <p class="mb-3">A minimalist vase perfect for modern spaces.</p>
        <button class="bg-gray-900 text-white px-4 py-2 rounded-xl hover:bg-gray-700">Buy Now</button>
      </div>

      <!-- Product Card 2 -->
      <div class="bg-white rounded-2xl shadow-xl p-6">
        <img src="https://images.unsplash.com/photo-1578898887932-dce23a5958e9" alt="Wall Art" class="rounded-xl mb-4" />
        <h4 class="text-xl font-semibold mb-1">Abstract Wall Art</h4>
        <p class="mb-3">Bring life to your walls with vibrant designs.</p>
        <button class="bg-gray-900 text-white px-4 py-2 rounded-xl hover:bg-gray-700">Buy Now</button>
      </div>

      <!-- Product Card 3 -->
      <div class="bg-white rounded-2xl shadow-xl p-6">
        <img src="https://images.unsplash.com/photo-1519710164239-da123dc03ef4" alt="Lamp" class="rounded-xl mb-4" />
        <h4 class="text-xl font-semibold mb-1">Warm Ambient Lamp</h4>
        <p class="mb-3">Soft lighting to enrich cozy environments.</p>
        <button class="bg-gray-900 text-white px-4 py-2 rounded-xl hover:bg-gray-700">Buy Now</button>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-6 bg-gray-100 text-center">
    <h3 class="text-3xl font-bold mb-6">About Us</h3>
    <p class="max-w-3xl mx-auto text-lg">At Decor Haven, we believe that every home deserves to feel warm, stylish, and personal. Our curated decor items are hand‑selected to bring beauty, comfort, and character to your space.</p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-6">Contact</h3>
    <p class="text-lg mb-4">Have questions? We'd love to hear from you.</p>
    <a href="mailto:info@decorhaven.com" class="text-xl underline">info@decorhaven.com</a>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-6 mt-10">
    <p>&copy; 2025 Decor Haven. All rights reserved.</p>
  </footer>
</body>
</html>

