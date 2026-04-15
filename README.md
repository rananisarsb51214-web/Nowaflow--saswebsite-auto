# Nowaflow--saswebsite-auto
Nowaflow -saswebsite-auto you can use to generate full websites, SaaS pages, or client projects with AI.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NovaFlow - Smart SaaS Platform</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-950 text-white scroll-smooth">

<!-- NAVBAR -->
<header class="fixed w-full top-0 z-50 bg-gray-950/80 backdrop-blur border-b border-gray-800">
  <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
    <h1 class="text-xl font-bold">NovaFlow</h1>
    <nav class="hidden md:flex gap-6">
      <a href="#about" class="hover:text-blue-400">About</a>
      <a href="#services" class="hover:text-blue-400">Features</a>
      <a href="#pricing" class="hover:text-blue-400">Pricing</a>
      <a href="#contact" class="hover:text-blue-400">Contact</a>
    </nav>
    <button id="menuBtn" class="md:hidden">☰</button>
  </div>

  <div id="mobileMenu" class="hidden flex-col px-4 pb-4 md:hidden">
    <a href="#about" class="py-2">About</a>
    <a href="#services" class="py-2">Features</a>
    <a href="#pricing" class="py-2">Pricing</a>
    <a href="#contact" class="py-2">Contact</a>
  </div>
</header>

<!-- HERO -->
<section class="pt-28 pb-20 px-6 text-center bg-gradient-to-b from-gray-900 to-gray-950">
  <h2 class="text-4xl md:text-6xl font-bold mb-6">
    Build Faster. Grow Smarter.
  </h2>
  <p class="text-gray-400 max-w-2xl mx-auto mb-8">
    NovaFlow helps creators and businesses launch, automate, and scale without complexity.
  </p>
  <a href="#contact" class="bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-2xl shadow-lg">
    Get Started
  </a>
</section>

<!-- ABOUT -->
<section id="about" class="py-20 px-6 max-w-6xl mx-auto text-center">
  <h3 class="text-3xl font-bold mb-6">Why NovaFlow?</h3>
  <p class="text-gray-400 max-w-3xl mx-auto">
    Most tools are complicated and slow you down. NovaFlow simplifies everything into one powerful platform
    that lets you launch faster, automate workflows, and scale without technical headaches.
  </p>
</section>

<!-- SERVICES -->
<section id="services" class="py-20 px-6 bg-gray-900">
  <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-8">

    <div class="p-6 bg-gray-800 rounded-2xl shadow hover:scale-105 transition">
      <h4 class="text-xl font-semibold mb-2">Automation</h4>
      <p class="text-gray-400">Automate repetitive tasks and focus on growth.</p>
    </div>

    <div class="p-6 bg-gray-800 rounded-2xl shadow hover:scale-105 transition">
      <h4 class="text-xl font-semibold mb-2">Analytics</h4>
      <p class="text-gray-400">Real-time insights to make better decisions.</p>
    </div>

    <div class="p-6 bg-gray-800 rounded-2xl shadow hover:scale-105 transition">
      <h4 class="text-xl font-semibold mb-2">Scalability</h4>
      <p class="text-gray-400">Grow without limits using powerful infrastructure.</p>
    </div>

  </div>
</section>

<!-- TESTIMONIALS -->
<section class="py-20 px-6 text-center">
  <h3 class="text-3xl font-bold mb-10">What Users Say</h3>

  <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

    <div class="bg-gray-800 p-6 rounded-2xl">
      <p class="text-gray-400">"This platform changed how we run our business."</p>
      <h4 class="mt-4 font-semibold">Ali Khan</h4>
      <span class="text-sm text-gray-500">Startup Founder</span>
    </div>

    <div class="bg-gray-800 p-6 rounded-2xl">
      <p class="text-gray-400">"Clean, fast, and incredibly powerful."</p>
      <h4 class="mt-4 font-semibold">Sara Ahmed</h4>
      <span class="text-sm text-gray-500">Marketing Expert</span>
    </div>

    <div class="bg-gray-800 p-6 rounded-2xl">
      <p class="text-gray-400">"We scaled 3x using NovaFlow."</p>
      <h4 class="mt-4 font-semibold">Usman Tariq</h4>
      <span class="text-sm text-gray-500">Agency Owner</span>
    </div>

  </div>
</section>

<!-- PRICING -->
<section id="pricing" class="py-20 px-6 bg-gray-900 text-center">
  <h3 class="text-3xl font-bold mb-10">Pricing</h3>

  <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

    <div class="bg-gray-800 p-6 rounded-2xl">
      <h4 class="text-xl font-semibold mb-2">Starter</h4>
      <p class="text-3xl font-bold mb-4">$9/mo</p>
      <p class="text-gray-400 mb-4">Basic features to get started</p>
      <button class="bg-blue-600 px-4 py-2 rounded-xl">Choose</button>
    </div>

    <div class="bg-blue-600 p-6 rounded-2xl scale-105">
      <h4 class="text-xl font-semibold mb-2">Pro</h4>
      <p class="text-3xl font-bold mb-4">$29/mo</p>
      <p class="mb-4">Best for growing businesses</p>
      <button class="bg-black px-4 py-2 rounded-xl">Choose</button>
    </div>

    <div class="bg-gray-800 p-6 rounded-2xl">
      <h4 class="text-xl font-semibold mb-2">Enterprise</h4>
      <p class="text-3xl font-bold mb-4">$99/mo</p>
      <p class="text-gray-400 mb-4">Full power & support</p>
      <button class="bg-blue-600 px-4 py-2 rounded-xl">Choose</button>
    </div>

  </div>
</section>

<!-- CTA -->
<section class="py-20 text-center">
  <h3 class="text-3xl font-bold mb-4">Ready to Scale?</h3>
  <p class="text-gray-400 mb-6">Start building your future today.</p>
  <a href="#contact" class="bg-blue-600 px-6 py-3 rounded-2xl">
    Get Started Now
  </a>
</section>

<!-- CONTACT -->
<section id="contact" class="py-20 px-6 bg-gray-900">
  <div class="max-w-xl mx-auto">
    <h3 class="text-3xl font-bold mb-6 text-center">Contact Us</h3>

    <form class="flex flex-col gap-4">
      <input type="text" placeholder="Name" class="p-3 rounded-xl bg-gray-800"/>
      <input type="email" placeholder="Email" class="p-3 rounded-xl bg-gray-800"/>
      <textarea placeholder="Message" class="p-3 rounded-xl bg-gray-800"></textarea>
      <button class="bg-blue-600 py-3 rounded-xl">Send Message</button>
    </form>

  </div>
</section>

<!-- FOOTER -->
<footer class="py-6 text-center text-gray-500 border-t border-gray-800">
  <p>© 2026 NovaFlow. All rights reserved.</p>
</footer>

<script>
document.getElementById('menuBtn').onclick = function () {
  document.getElementById('mobileMenu').classList.toggle('hidden');
};
</script>

</body>
</html>
