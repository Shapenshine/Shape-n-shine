# Shape-n-shine

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shape N Shine – Achieve Your Best Self</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #334155;
      line-height: 1.6;
    }
    .section-title {
      @apply text-3xl md:text-4xl font-bold text-gray-900 mb-8 text-center;
    }
    .card {
      @apply bg-white rounded-xl shadow-lg p-8 transform transition hover:-translate-y-1;
    }
    .whatsapp-btn {
      @apply inline-flex items-center justify-center bg-green-500 text-white font-semibold px-6 py-3 rounded-full shadow-lg transition transform hover:bg-green-600 active:shadow-md active:translate-y-0;
    }
    .quote-section {
      @apply bg-blue-50 border-l-8 border-teal-300 rounded-lg p-8 my-12 max-w-3xl mx-auto;
    }
  </style>
</head>
<body class="antialiased">

  <!-- Hero -->
  <header class="bg-gradient-to-r from-emerald-500 to-teal-600 text-white py-16 px-6 text-center rounded-b-3xl shadow-lg">
    <h1 class="text-5xl md:text-6xl font-bold mb-4">Shape N Shine</h1>
    <p class="text-xl md:text-2xl font-light mb-8">
      Unleash Your Potential. Transform Your Life.
    </p>
    <a
      href="https://wa.me/919111107790?text=Hello%2C%20I%20would%20like%20to%20know%20more%20about%20your%20services%21"
      target="_blank"
      rel="noopener"
      class="whatsapp-btn"
    >
      <svg class="h-6 w-6 mr-2" fill="currentColor" viewBox="0 0 24 24">
        <!-- WhatsApp icon path -->
        <path d="M12.0007 2C6.48622 2 ..."/>
      </svg>
      Chat with Us on WhatsApp
    </a>
  </header>

  <!-- Quote -->
  <section class="quote-section">
    <p class="text-2xl italic text-teal-800 text-center mb-4">
      "The only bad workout is the one that didn't happen.
      <br />
      Your body can stand almost anything. It's your mind that you have to convince."
    </p>
    <p class="text-lg font-semibold text-right text-teal-800">– Anita Gupta</p>
  </section>

  <!-- About -->
  <section class="container mx-auto px-6 py-16">
    <h2 class="section-title">About Shape N Shine</h2>
    <div class="card text-center">
      <p class="text-lg mb-4">
        At Shape N Shine, we believe that true well-being comes from a balanced approach to fitness, nutrition, and mental health. Our dedicated team is committed to guiding you on your journey to a healthier, happier, and more confident you.
      </p>
      <p class="text-lg">
        Whether your goal is weight loss, muscle gain, improved energy, or simply a more active lifestyle, we provide personalized plans and expert support to help you achieve lasting results.
      </p>
    </div>
  </section>

  <!-- Services -->
  <section class="bg-blue-50 py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title">Our Services</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Repeat this block for each service -->
        <div class="card text-center">
          <img src="https://placehold.co/150x150/FFDDC1/E57373?text=Active+Lifestyle" alt="Personalized Fitness Coaching" class="w-24 h-24 rounded-full mx-auto mb-4 object-cover">
          <h3 class="text-xl font-semibold mb-2">Personalized Fitness Coaching</h3>
          <p class="text-gray-700">Customized workout plans tailored to your goals, fitness level, and preferences, delivered by certified trainers.</p>
        </div>
        <!-- …other cards… -->
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="container mx-auto px-6 py-16">
    <h2 class="section-title">What Our Clients Say</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="card italic text-gray-700">
        "Shape N Shine has transformed my life! The personalized attention and supportive trainers made all the difference. I've never felt better."
        <span class="block font-semibold text-right mt-4">– Aarti Sharma</span>
      </div>
      <div class="card italic text-gray-700">
        "The nutrition guidance helped me understand healthy eating without restrictive diets. I've lost weight and gained so much energy. Highly recommend!"
        <span class="block font-semibold text-right mt-4">– Rahul Kumar</span>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="bg-blue-50 py-16">
    <div class="container mx-auto px-6 text-center">
      <h2 class="section-title">Get in Touch</h2>
      <p class="text-lg mb-8">Ready to start your transformation? Contact us today!</p>
      <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
        <a href="https://wa.me/919111107790?text=Hello%2C%20I%20would%20like%20to%20know%20more%20about%20your%20services%21" target="_blank" rel="noopener" class="whatsapp-btn">
          <svg class="h-6 w-6 mr-2" fill="currentColor" viewBox="0 0 24 24">
            <!-- icon -->
          </svg>
          Chat with Us on WhatsApp
        </a>
        <div class="text-gray-700 text-lg">
          <p>Email: <a href="mailto:info@shapenshine.com" class="underline">info@shapenshine.com</a></p>
          <p>Phone: +91 9111107790</p>
          <p>Address: Devendra Nagar, Raipur, India</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white text-center py-8">
    <p>&copy; 2025 Shape N Shine. All rights reserved.</p>
  </footer>

</body>
</html>

Initial commit for Shape N Shine website.
