<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sigma Mobile - Connect Without Limits</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap">
  <style>
    body { font-family: 'Inter', sans-serif; }
  </style>
</head>
<body class="bg-white text-gray-800">

  <!-- Homepage -->
  <!-- Hero Section -->
  <section class="bg-red-600 text-white py-20">
    <div class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between">
      <div class="md:w-1/2">
        <h1 class="text-4xl font-bold mb-4">Stay Connected Without Limits</h1>
        <p class="mb-6 text-lg">Affordable mobile data, voice & eSIM plans tailored for you.</p>
        <div class="space-x-4">
          <a href="/plans" class="bg-white text-red-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-100 transition">Shop Plans</a>
          <a href="/activate-sim" class="border border-white px-6 py-3 rounded-full font-semibold hover:bg-white hover:text-red-600 transition">Activate eSIM</a>
        </div>
      </div>
      <div class="md:w-1/2 mt-10 md:mt-0">
        <img src="https://via.placeholder.com/500x300" alt="Hero Image" class="rounded-xl shadow-lg">
      </div>
    </div>
  </section>

  <!-- Plans Page -->
  <section class="py-16 bg-gray-50" id="plans">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">Choose Your Plan</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white border p-6 rounded-lg shadow text-center">
          <h3 class="text-xl font-semibold mb-2">Starter Plan</h3>
          <p class="mb-4">1GB Data · 100 Minutes</p>
          <p class="text-2xl font-bold mb-4">UGX 5,000</p>
          <button class="bg-red-600 text-white px-6 py-2 rounded-full">Buy Now</button>
        </div>
        <div class="bg-white border p-6 rounded-lg shadow text-center">
          <h3 class="text-xl font-semibold mb-2">Pro Plan</h3>
          <p class="mb-4">5GB Data · 300 Minutes</p>
          <p class="text-2xl font-bold mb-4">UGX 15,000</p>
          <button class="bg-red-600 text-white px-6 py-2 rounded-full">Buy Now</button>
        </div>
        <div class="bg-white border p-6 rounded-lg shadow text-center">
          <h3 class="text-xl font-semibold mb-2">Unlimited Plan</h3>
          <p class="mb-4">Unlimited Data & Calls</p>
          <p class="text-2xl font-bold mb-4">UGX 50,000</p>
          <button class="bg-red-600 text-white px-6 py-2 rounded-full">Buy Now</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Activate eSIM Page -->
  <section class="py-16" id="activate-sim">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-6">Activate Your eSIM</h2>
      <p class="mb-8">Scan the QR code below or upload your eSIM profile to get started.</p>
      <img src="https://via.placeholder.com/200x200" alt="QR Code" class="mx-auto mb-6">
      <form class="max-w-md mx-auto">
        <input type="file" class="block w-full mb-4 border rounded px-4 py-2">
        <button type="submit" class="bg-red-600 text-white px-6 py-2 rounded-full">Upload eSIM Profile</button>
      </form>
    </div>
  </section>

  <!-- Dashboard Page -->
  <section class="py-16 bg-gray-50" id="dashboard">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">My Dashboard</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold mb-2">Current Plan</h4>
          <p>Pro Plan - 5GB Data · 300 Minutes</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold mb-2">Data Usage</h4>
          <p>2.3GB used of 5GB</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold mb-2">Account Balance</h4>
          <p>UGX 3,500</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-10">
    <div class="container mx-auto px-4 text-center">
      <p>&copy; 2025 Sigma Mobile. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
