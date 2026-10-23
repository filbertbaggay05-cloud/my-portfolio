<template>
  <section id="projects" class="py-20 px-8 md:px-20 bg-dark">
    <div class="max-w-6xl mx-auto">
      
      <h2 class="text-4xl font-bold mb-12 text-center text-white">
        Academic <span class="text-primary">Projects</span>
      </h2>

      <div class="grid md:grid-cols-2 gap-8">
        
        <!-- Project 1 -->
        <div class="group bg-darker rounded-lg overflow-hidden border border-gray-700 hover:border-primary transition-all duration-300 shadow-lg">
          
          <!-- Top Image Area -->
          <div class="h-56 relative overflow-hidden">
             <!-- The Image -->
             <img src="/LIS.jpeg" alt="LISIS Project" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" />
             <!-- Hover Color Overlay -->
             <div class="absolute inset-0 bg-primary/20 opacity-0 group-hover:opacity-100 transition-all duration-300"></div>
          </div>
          
          <!-- Content Area -->
          <div class="p-8">
            <h3 class="text-2xl font-bold mb-3 text-white group-hover:text-primary transition-colors">
              Libag Integrated School Information System
            </h3>
            <p class="text-gray-400 mb-6 text-sm leading-relaxed">
              Led a team in developing a centralized platform for managing student, faculty, and administrative records. Coordinated team collaboration and oversaw testing to ensure system reliability.
            </p>
            <div class="flex flex-wrap gap-2">
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Project Lead</span>
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Web Dev</span>
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Quality Assurance</span>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="group bg-darker rounded-lg overflow-hidden border border-gray-700 hover:border-primary transition-all duration-300 shadow-lg">
          
          <!-- Top Image Area -->
          <div class="h-56 relative overflow-hidden">
             <!-- The Image -->
             <img src="/eco.png" alt="Eco-Charge Project" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" />
             <!-- Hover Color Overlay -->
             <div class="absolute inset-0 bg-primary/20 opacity-0 group-hover:opacity-100 transition-all duration-300"></div>
          </div>
          
          <!-- Content Area -->
          <div class="p-8">
            <h3 class="text-2xl font-bold mb-3 text-white group-hover:text-primary transition-colors">
              Sustainable Plastic Bottle Charging System
            </h3>
            <p class="text-gray-400 mb-6 text-sm leading-relaxed">
              Collaborating in the development of an automated system that detects bottles and activates a charging mechanism using Arduino. Contributed to system flow design.
            </p>
            <div class="flex flex-wrap gap-2">
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Arduino</span>
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Embedded Systems</span>
              <span class="text-xs font-semibold bg-gray-800 text-primary px-3 py-1 rounded-full border border-gray-700">Hardware Design</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>