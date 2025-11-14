<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ristoire | Home</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root {
      --beige-dark: #c3a687;
      --beige-light: #fffef8;
      --text-dark: #3b3b3b;
    }
  </style>
</head>
<body class="bg-[--beige-light] text-[--text-dark] font-sans scroll-smooth">
  <!-- Header -->
  <header class="bg-[--beige-light] shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <a href="#home"><img src="https://i.postimg.cc/8C9XmrGN/temp-Imagehbvx-Wd.avif" alt="Ristoire Logo" class="h-10"></a>
      <nav class="space-x-6 text-sm hidden md:flex">
  <a href="#about" class="hover:text-[--beige-dark]" id="nav-about">About</a>
  <a href="#products" class="hover:text-[--beige-dark]" id="nav-products">Products</a>
  <a href="#portfolio" class="hover:text-[--beige-dark]" id="nav-portfolio">Portfolio</a>
  <a href="#contact" class="hover:text-[--beige-dark]" id="nav-contact">Contact</a>
</nav>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    const navLinks = document.querySelectorAll('nav a');

    function updateActiveLink() {
      const scrollY = window.scrollY;
      const sections = ['about', 'products', 'portfolio', 'contact'];
      let activeId = '';
      for (let id of sections) {
        const section = document.getElementById(id);
        if (section && section.offsetTop - 80 <= scrollY) {
          activeId = id;
        }
      }
      navLinks.forEach(link => link.classList.remove('font-semibold'));
      if (activeId) {
        const activeLink = document.querySelector(`#nav-${activeId}`);
        if (activeLink) activeLink.classList.add('font-semibold');
      }
    }

    updateActiveLink();
    window.addEventListener('scroll', updateActiveLink);
  });
</script>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative h-[500px] bg-cover bg-center flex items-center justify-center text-center text-white" style="background-image: url('https://i.postimg.cc/brM0fJfz/temp-Imaged2pz1q.avif');">
    <div class="bg-black bg-opacity-40 w-full h-full absolute top-0 left-0 z-0"></div>
    <div class="relative z-10 px-6">
      <h1 class="text-4xl md:text-5xl font-bold mb-4">Transform Your Home into a Safe, Serene Sanctuary</h1>
      <p class="text-lg max-w-2xl mx-auto mb-6">Elegant window mesh and blackout solutions designed for comfort and protection</p>
      <div class="flex flex-col md:flex-row justify-center gap-4">
        <a href="https://api.whatsapp.com/send/?phone=%2B6588784383&text=Hello%20Ristoire!"
   target="_blank" rel="noopener"
   class="bg-[#c3a687] hover:bg-[#b49572] text-white px-6 py-2 rounded shadow-md transition">
  Request a Site Visit
</a>
        <a href="#products" class="bg-[#fdfaf6] text-[#a07c54] px-6 py-2 rounded border border-[#d8c5ad] hover:bg-[#f4e8dc] shadow-md transition">Explore Our Products</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-4">Our Story</h2>
      <p class="text-lg leading-relaxed">At Ristoire, our story began with a simple but important mission: to create safer, more comfortable homes for families in Singapore. Inspired by a personal need—my partner’s fear of lizards—we discovered a gap in the market. A trip to Korea revealed innovative retractable window meshes, and later, dual-function mesh-blind systems that allow airflow and blackout control. We brought these high-quality, bespoke solutions to Singapore to elevate urban family living.</p>
    </div>
  </section>

<!-- Why Choose Ristoire Section -->
<section class="bg-[#f8f3ec] py-16">
  <div class="max-w-6xl mx-auto px-4 text-center">
    <h2 class="text-2xl font-bold mb-12">Why Choose Ristoire?</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-2 text-sm text-[--text-dark]">
      
      <!-- Custom Fit Installations -->
<div class="flex flex-col items-center space-y-2">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" class="h-8 w-8" fill="currentColor">
    <path d="M27.313 21.677l-6.531-6.531c.146-.708.219-1.438.219-2.188 0-5.188-4.219-9.406-9.406-9.406-1.146 0-2.25.208-3.281.563l5.031 5.031-4.188 4.188-5.031-5.031c-.355 1.031-.563 2.135-.563 3.281 0 5.188 4.219 9.406 9.406 9.406.75 0 1.479-.073 2.188-.219l6.531 6.531 5.625-5.625z"/>
  </svg>
  <p>Custom Fit<br>Installations</p>
</div>


      <!-- Stylish & Minimalist Design -->
<div class="flex flex-col items-center space-y-2">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" class="h-8 w-8" fill="black">
    <g transform="translate(1.4065934065934016 1.4065934065934016) scale(2.81 2.81)">
      <path d="M 30.648 90 h -4.666 c -0.276 0 -0.54 -0.114 -0.729 -0.315 c -0.189 -0.202 -0.287 -0.473 -0.269 -0.748 c 1.473 -23.129 7.78 -37.706 23.516 -52.984 c -11.987 6.803 -23.657 18.781 -25.661 35.247 c -0.051 0.42 -0.361 0.763 -0.774 0.854 c -0.414 0.094 -0.84 -0.086 -1.065 -0.443 c -8.808 -14.02 -8.505 -26.712 0.952 -39.944 c 5.454 -7.272 13.28 -11.279 20.185 -14.815 c 8.346 -4.273 15.554 -7.964 17.098 -16.04 c 0.078 -0.407 0.398 -0.723 0.807 -0.796 c 0.407 -0.073 0.818 0.113 1.032 0.467 c 10.854 17.977 19.798 35.828 10.159 56.542 c -7.694 13.752 -20.459 20.112 -37.994 18.96 c -1.01 4.324 -1.531 8.595 -1.59 13.028 C 31.641 89.561 31.195 90 30.648 90 z M 27.052 88 h 2.617 c 0.129 -4.515 0.728 -8.881 1.825 -13.313 c 0.118 -0.475 0.554 -0.793 1.049 -0.757 c 17.367 1.366 29.437 -4.464 36.911 -17.814 c 8.859 -19.047 1.472 -35.189 -8.879 -52.575 c -2.563 7.429 -9.851 11.161 -17.526 15.091 c -7.04 3.604 -14.319 7.332 -19.483 14.216 c -8.376 11.72 -9.128 23.011 -2.278 35.324 c 3.534 -18.634 18.924 -31.329 32.625 -37.12 c 0.452 -0.192 0.977 -0.027 1.237 0.39 c 0.261 0.416 0.181 0.959 -0.188 1.283 C 36.16 49.192 28.777 63.753 27.052 88 z"/>
    </g>
  </svg>
  <p>Stylish &<br>Minimalist Design</p>
</div>


      <!-- Bird & Pest Protection -->
<div class="flex flex-col items-center space-y-2">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" class="h-8 w-8" fill="black">
    <g transform="translate(1.4065934065934016 1.4065934065934016) scale(2.81 2.81)">
      <path d="M 30.318 79.749 c -9.466 0 -18.684 -2.702 -26.659 -7.812 L 0 69.591 L 4.317 70.1 c 1.291 0.152 2.62 0.23 3.947 0.23 c 6.65 0 12.969 -1.91 18.428 -5.548 c -6.56 -1.122 -12.061 -5.799 -14.136 -12.275 l -0.515 -1.605 l 1.656 0.318 c 1.046 0.2 2.109 0.305 3.146 0.289 c -6.164 -2.93 -10.31 -9.231 -10.31 -16.302 c 0 -0.094 0 -0.183 0.005 -0.272 l 0.087 -1.598 l 1.398 0.778 c 1.218 0.678 2.524 1.193 3.873 1.532 C 8.577 32.3 6.672 27.756 6.672 22.936 c 0 -3.184 0.845 -6.32 2.443 -9.067 l 0.727 -1.25 l 0.913 1.121 c 8.213 10.075 20.223 16.353 33.117 17.353 c -0.142 -0.918 -0.214 -1.857 -0.214 -2.804 c 0 -9.946 8.094 -18.038 18.042 -18.038 c 4.778 0 9.402 1.923 12.773 5.293 c 3.512 -0.751 6.865 -2.064 9.973 -3.906 l 2.266 -1.343 l -0.803 2.509 c -0.903 2.823 -2.487 5.36 -4.59 7.408 c 1.898 -0.464 3.745 -1.093 5.524 -1.884 L 90 16.926 l -1.917 2.872 c -2.26 3.384 -5.055 6.329 -8.312 8.759 c 0.019 0.568 0.027 1.139 0.027 1.711 C 79.798 54.591 61.29 79.749 30.318 79.749 z M 8.317 72.331 c 6.775 3.554 14.303 5.416 22.002 5.416 c 29.719 0 47.479 -24.141 47.479 -47.48 c 0 -0.723 -0.015 -1.442 -0.047 -2.158 l -0.024 -0.54 l 0.438 -0.317 c 2.329 -1.683 4.414 -3.639 6.228 -5.84 c -2.202 0.722 -4.48 1.226 -6.808 1.505 l -4.647 0.555 l 4.013 -2.407 c 2.569 -1.541 4.638 -3.743 5.999 -6.348 c -2.736 1.337 -5.624 2.309 -8.618 2.898 l -0.543 0.107 l -0.38 -0.404 c -3.023 -3.221 -7.291 -5.068 -11.707 -5.068 c -8.845 0 -16.041 7.194 -16.041 16.037 c 0 1.25 0.14 2.48 0.415 3.657 l 0.303 1.294 l -1.327 -0.067 c -13.439 -0.675 -26.065 -6.854 -34.876 -17.015 c -0.985 2.115 -1.501 4.431 -1.501 6.778 c 0 5.377 2.668 10.368 7.137 13.351 l 2.906 1.94 l -3.492 -0.107 c -2.276 -0.07 -4.536 -0.582 -6.627 -1.493 c 0.624 7.005 5.816 12.902 12.803 14.301 l 4.156 0.833 l -4.089 1.114 c -2.081 0.566 -4.249 0.76 -6.425 0.556 c 2.488 5.693 8.088 9.488 14.404 9.605 l 2.814 0.053 l -2.215 1.735 C 23.789 69.725 16.277 72.319 8.317 72.331 z"/>
    </g>
  </svg>
  <p>Bird & Pest<br>Protection</p>
</div>


      <!-- UV & Sunlight Control -->
      <div class="flex flex-col items-center space-y-2">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <circle cx="12" cy="12" r="4" stroke="currentColor" stroke-width="2" fill="none" />
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2v2m0 16v2m10-10h-2M4 12H2m15.54 6.46l-1.42-1.42M6.88 6.88l-1.42-1.42m12.02 0l-1.42 1.42M6.88 17.12l-1.42 1.42" />
        </svg>
        <p>UV & Sunlight<br>Control</p>
      </div>

    </div>
  </div>
</section>
  
  <!-- Products Section -->
<section id="products" class="py-20 px-6 bg-[--beige-light] text-[--text-dark]">
  <div class="max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Our Core Products</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-[#3b3b3b] rounded-lg shadow-md overflow-hidden hover:scale-105 hover:shadow-lg transition-transform duration-300">
        <img src="https://i.postimg.cc/yN24rhkx/temp-Imagez1dfx9.avif" alt="Retractable Window Mesh" class="w-full h-48 object-cover">
        <div class="p-4 bg-white bg-opacity-10 backdrop-blur-md">
          <h3 class="text-lg font-bold text-white mb-1">Retractable Window Mesh</h3>
          <p class="text-sm text-gray-200 h-20">Elegant protection when you need it, seamless views when you don’t.</p>
          <a href="#retractable-details" class="inline-block text-[--beige-dark] text-sm font-semibold hover:underline">Learn More</a>
        </div>
      </div>
      <div class="bg-[#3b3b3b] rounded-lg shadow-md overflow-hidden hover:scale-105 hover:shadow-lg transition-transform duration-300">
        <img src="https://i.postimg.cc/JhXRN7Q9/IMG-2134.avif" alt="Dual-function Meshblind" class="w-full h-48 object-cover">
        <div class="p-4 bg-white bg-opacity-10 backdrop-blur-md">
          <h3 class="text-lg font-bold text-white mb-1">Dual-function Meshblind</h3>
          <p class="text-sm text-gray-200 h-20">The best of both worlds—mesh and blackout in one sleek system.</p>
          <a href="#meshblind-details" class="inline-block text-[--beige-dark] text-sm font-semibold hover:underline">Learn More</a>
        </div>
      </div>
      <div class="bg-[#3b3b3b] rounded-lg shadow-md overflow-hidden hover:scale-105 hover:shadow-lg transition-transform duration-300">
        <img src="https://i.postimg.cc/s24NdtfM/temp-Image-M1g9-WV.avif" alt="Lux Model Removable Mesh" class="w-full h-48 object-cover">
        <div class="p-4 bg-white bg-opacity-10 backdrop-blur-md">
          <h3 class="text-lg font-bold text-white mb-1">Lux Model: Mesh</h3>
          <p class="text-sm text-gray-200 h-20">Premium mesh system with locking feature for added flexibility and safety.</p>
          <a href="#luxmodel-details" class="inline-block text-[--beige-dark] text-sm font-semibold hover:underline">Learn More</a>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- Retractable Mesh Detail Section -->
<section id="retractable-details" class="py-16 bg-[#3b3b3b] bg-opacity-80 text-white hidden">
  <div class="max-w-6xl mx-auto px-4">
    
    <!-- Title -->
    <h2 class="text-2xl font-bold mb-4">Retractable Window Mesh</h2>
    
    <!-- Description -->
    <p class="text-sm mb-10">
      Discreet and functional, our retractable mesh system enhances your window’s usability without sacrificing design. 
      When not in use, it smoothly retracts into the side casing, giving you an unobstructed view. Designed to fit modern 
      living spaces, this solution offers convenience, airflow, and elegance—all in one.
    </p>
    
    <!-- How It Works -->
    <div class="mb-10">
      <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">How It Works</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
        
        <!-- Step 1 -->
        <div>
          <img src="https://via.placeholder.com/300x200" alt="How it works - Step 1" 
               class="w-full h-32 object-cover rounded mb-3">
          <p class="text-sm"><strong>Step 1:</strong> Mesh is neatly stored in the side casing (closed).</p>
        </div>
        
        <!-- Step 2 -->
        <div>
          <img src="https://via.placeholder.com/300x200" alt="How it works - Step 2" 
               class="w-full h-32 object-cover rounded mb-3">
          <p class="text-sm"><strong>Step 2:</strong> Mesh is halfway opened across the window.</p>
        </div>
        
        <!-- Step 3 -->
        <div>
          <img src="https://via.placeholder.com/300x200" alt="How it works - Step 3" 
               class="w-full h-32 object-cover rounded mb-3">
          <p class="text-sm"><strong>Step 3:</strong> Mesh is fully closed, covering the window completely.</p>
        </div>
        
      </div>
    </div>
    
    <!-- Meshes Available -->
    <div class="mb-10">
      <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Meshes Available</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        
        <!-- Highest Density -->
        <div class="text-center">
          <img src="https://i.postimg.cc/5t9hp4pt/temp-Imageh-HWWTX.avif" alt="Highest Density Mesh" 
               class="w-full h-72 object-cover rounded mb-3">
          <p class="text-sm"><strong>Highest Density</strong><br>Seamless view with maximum protection.<br>Hole size: 0.5mm</p>
        </div>
        
        <!-- Medium Density -->
        <div class="text-center">
          <img src="https://i.postimg.cc/mgLpWd9X/temp-Image-Aug-Uga.avif" alt="Medium Density Mesh" 
               class="w-full h-72 object-cover rounded mb-3">
          <p class="text-sm"><strong>Medium Density</strong><br>Clear view with balanced airflow.<br>Hole size: 1.0mm</p>
        </div>
        
        <!-- Low Density -->
        <div class="text-center">
          <img src="https://i.postimg.cc/4yGbbdbL/temp-Imagetn-CMRo.avif" alt="Low Density Mesh" 
               class="w-full h-72 object-cover rounded mb-3">
          <p class="text-sm"><strong>Low Density</strong><br>Maximum airflow, keeps insects out.<br>Hole size: 1.5mm</p>
        </div>
        
      </div>
    </div>
    
    <!-- Frame Colours Available -->
    <div>
      <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Colors Available for Frames</h3>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center">
        <div class="w-full h-20 bg-black rounded flex items-center justify-center text-xs 
                    transform transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-white/30">
          Black
        </div>
        <div class="w-full h-20 bg-gray-500 rounded flex items-center justify-center text-xs 
                    transform transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-white/30">
          Grey
        </div>
        <div class="w-full h-20 bg-white text-black border rounded flex items-center justify-center text-xs 
                    transform transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-gray-400/50">
          White
        </div>
        <div class="w-full h-20 rounded flex items-center justify-center text-xs" 
             style="background-color:#4B3621; transition:all 0.3s; transform:translateZ(0);"
             onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 4px 15px rgba(255,255,255,0.3)';"
             onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
          Coffee Brown
        </div>
      </div>
    </div>

  </div>
</section>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelector("a[href='#retractable-details']").addEventListener('click', function (e) {
      e.preventDefault();
      const section = document.getElementById('retractable-details');
      const other = document.getElementById('meshblind-details');
      section.classList.toggle('hidden');
      other.classList.add('hidden');
      section.scrollIntoView({ behavior: 'smooth' });
    });
  });
</script>


<!-- Meshblind Detail Section -->
<section id="meshblind-details" class="py-16 bg-[#3b3b3b] bg-opacity-80 text-white hidden">
  <div class="max-w-6xl mx-auto px-4">
    <!-- Title -->
    <h2 class="text-2xl font-bold mb-4">Dual-function Meshblind</h2>

    <!-- Description -->
    <p class="text-sm mb-10">
      Experience both ventilation and privacy with our dual-function meshblind system—perfect for Singapore’s modern homes.
      Use mesh for airflow, blinds for light control & privacy, or both together to suit the moment.
    </p>

    <!-- Orientations (replaces Step 1/2/3) -->
    <div class="mb-10">
      <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Orientations</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
        <div>
          <img src="https://i.postimg.cc/pLwG722v/temp-Imagesi-X9-CS.avif" alt="Blinds fully opened"
               class="w-full h-44 object-cover rounded mb-3">
          <p class="text-sm"><strong>Orientation 1:</strong> Blinds fully opened.</p>
        </div>
        <div>
          <img src="https://i.postimg.cc/hPbthG5y/temp-Image-B5mr-Un.avif" alt="Mesh fully opened"
               class="w-full h-44 object-cover rounded mb-3">
          <p class="text-sm"><strong>Orientation 2:</strong> Mesh fully opened.</p>
        </div>
        <div>
          <img src="https://i.postimg.cc/CMRvFBz0/temp-Imager-GUcov.avif" alt="Blinds/Mesh half opened"
               class="w-full h-44 object-cover rounded mb-3">
          <p class="text-sm"><strong>Orientation 3:</strong> Blinds/Mesh half opened.</p>
        </div>
      </div>
    </div>

<!-- Meshes Available -->
<div class="mb-10">
  <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Meshes Available</h3>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">

    <!-- Single Fold - Black -->
    <div class="text-center">
      <img src="https://i.postimg.cc/gk0vHfbK/temp-Image-Cg5-Ya-W.avif" alt="Single Fold - Black"
           class="w-full h-32 object-cover rounded mb-3">
      <p class="text-sm">
        <strong>Single Fold – Black</strong><br>
        Durable netting material with a single layer, ensuring that the chosen layer does not affect airflow.
      </p>
    </div>

    <!-- Single Fold - White -->
    <div class="text-center">
      <img src="https://i.postimg.cc/T2Nyf1Br/temp-Image6-VBJLs.avif" alt="Single Fold - White"
           class="w-full h-32 object-cover rounded mb-3">
      <p class="text-sm">
        <strong>Single Fold – White</strong><br>
        Durable netting material with a single layer, ensuring that the chosen layer does not affect airflow.
      </p>
    </div>

    <!-- Double Fold - White -->
    <div class="text-center">
      <img src="https://i.postimg.cc/sgYDQgHH/temp-Image-W2-PGPh.avif" alt="Double Fold - White"
           class="w-full h-32 object-cover rounded mb-3">
      <p class="text-sm">
        <strong>Double Fold – White</strong><br>
        The double-layer netting offers a sleek and elegant design, though it may slightly reduce airflow.
      </p>
    </div>

  </div>
</div>


<!-- Blinds Available -->
<div class="mb-10">
  <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Blinds Available</h3>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<!-- LEFT: Fully Blackout -->
<div>
  <h4 class="text-base font-semibold mb-3">Fully Blackout — popular choices (9)</h4>
  <div class="inline-grid w-fit grid-cols-3 gap-x-3 gap-y-3">
    <!-- Row 1 -->
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#dcdcdc;">White-grey</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#f5f5dc;">Beige</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#a67b5b;">Light Brown</div>
    <!-- Row 2 -->
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#4b3621;">Dark Brown</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#add8e6;">Light Blue</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#90ee90;">Light Green</div>
    <!-- Row 3 -->
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#d3d3d3;">Light Grey</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#555555;">Dark Grey</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#000000;">Black</div>
  </div>
</div>

<!-- RIGHT: Partial Blackout -->
<div>
  <h4 class="text-base font-semibold mb-3">Partial Blackout — popular choices (3)</h4>
  <div class="inline-grid w-fit grid-cols-3 gap-x-3 gap-y-3">
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#ffffff; color:black;">White</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#f5f5dc;">Beige</div>
    <div class="w-20 h-20 rounded flex items-center justify-center text-[10px] border border-white/10
                transition duration-200 hover:scale-105 hover:shadow-md hover:shadow-white/20"
         style="background-color:#d3d3d3;">Light Grey</div>
  </div>
</div>




<!-- Colors Available for Frames (3 colours only) -->
<div class="w-full">
  <h3 class="text-lg font-semibold mb-6 text-[--beige-dark]">Colors Available for Frames</h3>

  <div class="grid grid-cols-3 gap-6 w-full justify-items-stretch text-center">
    <div class="h-20 bg-gray-500 rounded flex items-center justify-center text-xs
                transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-white/30">
      Grey
    </div>

    <div class="h-20 bg-white text-black border rounded flex items-center justify-center text-xs
                transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-gray-400/50">
      White
    </div>

    <div class="h-20 rounded flex items-center justify-center text-xs
                transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-white/30"
         style="background-color:#4B3621;">
      Coffee Brown
    </div>
  </div>
</div>
</section>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelector("a[href='#retractable-details']").addEventListener('click', function (e) {
      e.preventDefault();
      const section = document.getElementById('retractable-details');
      const other = document.getElementById('meshblind-details');
      section.classList.toggle('hidden');
      other.classList.add('hidden');
      section.scrollIntoView({ behavior: 'smooth' });
    });
  });
</script>

<!-- Lux Model Detail Section -->
<section id="luxmodel-details" class="py-16 bg-[#3b3b3b] bg-opacity-80 text-white hidden">
  <div class="max-w-6xl mx-auto px-4">
    <h2 class="text-2xl font-bold mb-4">Lux Model: Mesh</h2>
    <p class="text-sm mb-6">Our premium removable mesh model with a locking feature that enhances both safety and flexibility. Perfect for households looking for a clean aesthetic while maintaining full control of indoor ventilation.</p>
    <div class="grid md:grid-cols-2 gap-6">
      <div>
        <h3 class="text-lg font-semibold mb-2 text-[--beige-dark]">Features</h3>
        <ul class="text-sm list-disc pl-4 space-y-2">
          <li><strong>Removable Design:</strong> Easily detach when not needed for maximum view and flexibility.</li>
          <li><strong>Locking Mechanism:</strong> Secure your mesh in place—added safety for children and pets.</li>
          <li><strong>Elegant Finishing:</strong> Sleek and premium build, blending perfectly with modern interiors.</li>
        </ul>
      </div>
      <div>
        <h3 class="text-lg font-semibold mb-2 text-[--beige-dark]">Mesh Variation</h3>
        <div class="w-full h-16 bg-gray-500 rounded text-xs flex items-center justify-center">1.0mm Mesh (Single Option)</div>
      </div>
    </div>
  </div>
</section>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    const retractable = document.getElementById('retractable-details');
    const meshblind = document.getElementById('meshblind-details');
    const luxmodel = document.getElementById('luxmodel-details');

    const retractableLink = document.querySelector("a[href='#retractable-details']");
    const meshblindLink = document.querySelector("a[href='#meshblind-details']");
    const luxmodelLink = document.querySelector("a[href='#luxmodel-details']");

    if (retractableLink) {
      retractableLink.addEventListener('click', function (e) {
        e.preventDefault();
        retractable.classList.toggle('hidden');
        meshblind.classList.add('hidden');
        luxmodel.classList.add('hidden');
        retractable.scrollIntoView({ behavior: 'smooth' });
      });
    }

    if (meshblindLink) {
      meshblindLink.addEventListener('click', function (e) {
        e.preventDefault();
        meshblind.classList.toggle('hidden');
        retractable.classList.add('hidden');
        luxmodel.classList.add('hidden');
        meshblind.scrollIntoView({ behavior: 'smooth' });
      });
    }

    if (luxmodelLink) {
      luxmodelLink.addEventListener('click', function (e) {
        e.preventDefault();
        luxmodel.classList.toggle('hidden');
        retractable.classList.add('hidden');
        meshblind.classList.add('hidden');
        luxmodel.scrollIntoView({ behavior: 'smooth' });
      });
    }
  });
</script>
<!-- Benefits Section -->
<section class="bg-[#f8f3ec] py-16">
  <div class="max-w-6xl mx-auto px-4">
    <h3 class="text-2xl font-bold text-center mb-12">Benefits of Ristoire Products</h3>
    <div class="space-y-16">

      <!-- Benefit 1 -->
      <div class="grid md:grid-cols-2 gap-8 items-center">
        <img src="https://i.postimg.cc/hGgRF8nt/temp-Image-TB2-EMj.avif" alt="Airflow" class="rounded shadow">
        <div>
          <h4 class="text-xl font-semibold text-[--beige-dark] mb-2">Enhanced Airflow</h4>
          <p class="text-sm">Let fresh air flow freely through your home while keeping out unwanted bugs and dust. Perfect for creating breezy, comfortable interiors in Singapore’s tropical climate.</p>
        </div>
      </div>

      <!-- Benefit 2 -->
      <div class="grid md:grid-cols-2 gap-8 items-center">
        <div class="order-2 md:order-1">
          <h4 class="text-xl font-semibold text-[--beige-dark] mb-2">Keeping Insects Out</h4>
          <p class="text-sm">Our high-density mesh effectively blocks insects from entering your home while allowing airflow, ensuring a safe and comfortable living environment.</p>
        </div>
        <img src="https://i.postimg.cc/XvtTJ5GT/temp-Imagen-TOd-ID.avif" alt="Child and Pet Safety" class="rounded shadow order-1 md:order-2">
      </div>

      <!-- Benefit 3 -->
      <div class="grid md:grid-cols-2 gap-8 items-center">
        <img src="https://i.postimg.cc/FH8SnFJ9/temp-Imageb4-VTk2.avif" alt="Design Harmony" class="rounded shadow">
        <div>
          <h4 class="text-xl font-semibold text-[--beige-dark] mb-2">Elegant Minimalism</h4>
          <p class="text-sm">Ristoire’s mesh systems are crafted to complement contemporary interiors with subtlety. Available in customizable tones to match any window frame, they add polish to your living space.</p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- Portfolio Section -->
  <section id="portfolio" class="py-20 px-6">
  <div class="max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Customer Portfolio</h2>

    <h3 class="text-xl font-semibold mb-4 mt-8">Retractable Window Mesh</h3>
    <div class="grid md:grid-cols-3 gap-6 mb-10">
      <img src="https://i.postimg.cc/d0c1yhyT/temp-Image-CIJiv2.avif" alt="Retractable Example 1" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/7PtZNsz4/temp-Imageb-Cy-Ye-J.avif" alt="Retractable Example 2" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/nL1H90x6/temp-Imagei6-R5f5.avif" alt="Retractable Example 3" class="rounded-lg shadow-md">
    </div>

    <h3 class="text-xl font-semibold mb-4 mt-8">Dual-function Meshblind</h3>
    <div class="grid md:grid-cols-3 gap-6 mb-10">
      <img src="https://i.postimg.cc/mgfRd02v/temp-Imagek-Dx-OXf.avif" alt="Meshblind Example 1" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/9XsrhgQp/temp-Image-Jdy7q5.avif" alt="Meshblind Example 2" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/rphwYQH5/temp-Imager-Ddtw-O.avif" alt="Meshblind Example 3" class="rounded-lg shadow-md">
    </div>

    <h3 class="text-xl font-semibold mb-4 mt-8">Lux Model: Mesh</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <img src="https://i.postimg.cc/s24NdtfM/temp-Image-M1g9-WV.avif" alt="Lux Model Example 1" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/s24NdtfM/temp-Image-M1g9-WV.avif" alt="Lux Model Example 2" class="rounded-lg shadow-md">
      <img src="https://i.postimg.cc/s24NdtfM/temp-Image-M1g9-WV.avif" alt="Lux Model Example 3" class="rounded-lg shadow-md">
    </div>
  </div>
</section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-6">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-8 items-center min-h-[60vh]">
      <div class="text-left pr-16 flex flex-col items-center">
        <h1 class="text-center">
  <img src="https://i.postimg.cc/8C9XmrGN/temp-Imagehbvx-Wd.avif" alt="Ristoire Logo" class="mx-auto h-20">
</h1>
        <p class="text-base text-[--text-dark] leading-snug max-w-xs text-left">Creating safer, more elegant<br>homes in Singapore.</p>
      </div>
      <div class="pl-8 border-l border-[--beige-dark]">
        <div class="space-y-4 text-left">
          <h2 class="text-2xl font-semibold mb-4">[ CONTACT US ]</h2>
          <p><strong>Phone:</strong> <a href="https://api.whatsapp.com/send/?phone=%2B6588784383&text&type=phone_number&app_absent=0" target="_blank" class="text-[--beige-dark] font-medium">+65 8878 4383</a></p>
          <p><strong>TikTok:</strong> <span class="text-[--beige-dark]">@ristoirecollections</span></p>
          <p><strong>Instagram:</strong> <span class="text-[--beige-dark]">@ristoirecollections</span></p>
          <div>
            <a href="https://api.whatsapp.com/send/?phone=%2B6588784383&text&type=phone_number&app_absent=0" target="_blank" class="inline-block mt-4 px-6 py-2 bg-[--beige-dark] text-white rounded-sm hover:bg-opacity-90 transition">Contact Now</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
<footer class="bg-[#f5f1ea] text-[#4a4a4a] text-sm py-6">
  <div class="max-w-7xl mx-auto px-4 text-center">
    <p>Copyright © 2025 Ristoire</p>
  </div>
</footer>

  <!-- Floating Instagram Button (Square) -->
<a href="https://www.instagram.com/ristoirecollections" target="_blank"
   class="fixed bottom-44 right-6 bg-pink-500 hover:bg-pink-600 text-white w-12 h-12 flex items-center justify-center shadow-lg z-50 transition duration-300 ease-in-out">
  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
    <path d="M7 2C4.243 2 2 4.243 2 7v10c0 2.757 2.243 5 5 5h10c2.757 0 5-2.243 5-5V7c0-2.757-2.243-5-5-5H7zm10 2c1.654 0 3 1.346 3 3v10c0 1.654-1.346 3-3 3H7c-1.654 0-3-1.346-3-3V7c0-1.654 1.346-3 3-3h10zm-5 3a5 5 0 100 10 5 5 0 000-10zm0 2a3 3 0 110 6 3 3 0 010-6zm4.5-2a1.5 1.5 0 100 3 1.5 1.5 0 000-3z"/>
  </svg>
</a>

<a href="https://api.whatsapp.com/send?phone=6588784383&text=Hello%20Ristoire%21"
   target="_blank" rel="noopener"
   class="fixed bottom-28 right-6 bg-green-500 hover:bg-green-600 text-white w-12 h-12 flex items-center justify-center shadow-lg z-50 transition duration-300 ease-in-out"
   aria-label="Chat with Ristoire on WhatsApp">
  <svg viewBox="0 0 32 32" class="w-7 h-7" fill="currentColor" aria-hidden="true">
    <path d="M19.11 17.205c-.372 0-1.088 1.39-1.518 1.39a.63.63 0 0 1-.315-.1c-.802-.402-1.504-.817-2.163-1.447-.545-.516-1.146-1.29-1.46-1.963a.426.426 0 0 1-.073-.215c0-.33.99-.945.99-1.49 0-.143-.73-2.09-.832-2.335-.143-.372-.214-.487-.6-.487-.187 0-.36-.043-.53-.043-.302 0-.53.115-.746.315-.688.645-1.032 1.318-1.06 2.264v.114c-.015.99.472 1.977 1.017 2.78 1.23 1.82 2.506 3.41 4.554 4.34.616.287 2.035.888 2.722.888.817 0 2.15-.515 2.478-1.318.13-.33.244-.73.244-1.088 0-.058 0-.144-.03-.215-.1-.172-2.434-1.39-2.678-1.39zm-2.908 7.593c-1.747 0-3.48-.53-4.942-1.49L7.793 24.41l1.132-3.337a8.955 8.955 0 0 1-1.72-5.272c0-4.955 4.04-8.995 8.997-8.995S25.2 10.845 25.2 15.8c0 4.958-4.04 8.998-8.998 8.998zm0-19.798c-5.96 0-10.8 4.842-10.8 10.8 0 1.964.53 3.898 1.546 5.574L5 27.176l5.974-1.92a10.807 10.807 0 0 0 16.03-9.455c0-5.958-4.842-10.8-10.802-10.8z" fill-rule="evenodd"/>
  </svg>
</a>


<!-- Floating TikTok Button (Square, Black Background with Updated White Logo) -->
<a href="https://www.tiktok.com/@ristoirecollections" target="_blank"
   class="fixed bottom-60 right-6 bg-black hover:bg-gray-800 w-12 h-12 flex items-center justify-center shadow-lg z-50 transition duration-300 ease-in-out">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Iconoir_tiktok_white.svg/1024px-Iconoir_tiktok_white.svg.png" alt="TikTok" class="h-6 w-6">
</a>

<!-- Floating Back to Top Button -->
<a href="#top"
   class="fixed bottom-4 right-6 bg-gray-800 hover:bg-gray-700 text-white w-12 h-12 flex items-center justify-center shadow-lg z-50 transition duration-300 ease-in-out">
  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 15l7-7 7 7" />
  </svg>
</a>


</a>

<body id="top" class="bg-[--beige-light] text-[--text-dark] font-sans scroll-smooth">  
</body>
</html>
