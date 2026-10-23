<template>
  <section class="min-h-screen flex flex-col md:flex-row relative">
    
    <!-- Left Side: Text Content -->
    <div class="w-full md:w-3/5 p-8 md:p-20 flex flex-col justify-center relative z-10 bg-dark">
      <div class="mb-4">
        <span class="text-primary font-semibold tracking-widest uppercase text-sm">Hello Everyone.</span>
      </div>
      
      <h1 class="text-5xl md:text-7xl font-bold leading-tight mb-6 text-white">
        I'M GERALD <br/>
        <span class="text-primary">BAGGAY</span>
      </h1>
      
      <p class="text-gray-400 text-lg mb-8 max-w-lg">
        A motivated Computer Engineering student specializing in embedded systems, networking, and software development. Eager to gain an internship opportunity to enhance my technical proficiency.
      </p>
      
      <!-- CTA Buttons -->
      <div class="flex flex-wrap gap-4">
        <a href="#contact" class="bg-primary text-darker font-bold py-3 px-8 rounded-sm hover:bg-white transition-colors duration-300 flex items-center gap-2">
          Contact Me
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
          </svg>
        </a>
        <a href="#projects" class="border border-primary text-primary font-bold py-3 px-8 rounded-sm hover:bg-primary hover:text-darker transition-colors duration-300">
          View Projects
        </a>
      </div>
    </div>

    <!-- Right Side: Accent Block & Photo -->
    <div class="w-full md:w-2/5 bg-primary/10 relative overflow-hidden hidden md:flex items-center justify-center min-h-[50vh]">
        <!-- Decorative Grid Pattern -->
        <div class="absolute inset-0 opacity-20" style="background-image: radial-gradient(#06b6d4 1px, transparent 1px); background-size: 30px 30px;"></div>
        
        <!-- Photo Container -->
        <div class="relative z-20 w-64 h-64 md:w-80 md:h-80 lg:w-96 lg:h-96 rounded-full border-4 border-primary overflow-hidden shadow-2xl bg-darker flex items-center justify-center">
             <!-- Placeholder for now. We will add your photo next. -->
             <img src="/profile.jpeg" alt="Gerald Baggay" class="object-cover w-full h-full" />
        </div>
    </div>
  </section>
</template>