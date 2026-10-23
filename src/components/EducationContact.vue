<template>
  <!-- Education Section -->
  <section id="education" class="py-20 px-8 md:px-20 bg-darker">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-4xl font-bold mb-12 border-l-4 border-primary pl-4 text-white">Education</h2>
      
      <div class="space-y-8 relative before:absolute before:inset-0 before:ml-5 before:-translate-x-px md:before:mx-auto md:before:translate-x-0 before:h-full before:w-0.5 before:bg-gradient-to-b before:from-transparent before:via-gray-700 before:to-transparent">
        
        <!-- Item 1: College -->
        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
          <div class="flex items-center justify-center w-10 h-10 rounded-full border border-primary bg-dark text-primary shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
            <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24"><path d="M12 2L1 21h22L12 2zm0 4.5l7.5 13h-15L12 6.5z"/></svg>
          </div>
          <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] p-6 rounded border border-gray-700 bg-dark shadow-lg">
            <div class="flex flex-col md:flex-row md:items-center justify-between mb-1">
              <div class="font-bold text-primary text-lg">Cagayan State University</div>
              <time class="text-gray-500 font-mono text-sm">2023 - Present</time>
            </div>
            <div class="text-white font-semibold mb-2">BS Computer Engineering</div>
            <p class="text-gray-400 text-sm">Tuguegarao City, Cagayan</p>
          </div>
        </div>

        <!-- Item 2: SHS -->
        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
          <div class="flex items-center justify-center w-10 h-10 rounded-full border border-gray-600 bg-dark text-gray-500 shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
            <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24"><path d="M12 2L1 21h22L12 2zm0 4.5l7.5 13h-15L12 6.5z"/></svg>
          </div>
          <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] p-6 rounded border border-gray-700 bg-dark shadow-lg">
            <div class="flex flex-col md:flex-row md:items-center justify-between mb-1">
              <div class="font-bold text-gray-200 text-lg">Cagayan National High School</div>
              <time class="text-gray-500 font-mono text-sm">2021 - 2023</time>
            </div>
            <div class="text-gray-400 text-sm">Science, Technology, Engineering, and Mathematics (SHS)</div>
          </div>
        </div>

        <!-- Item 3: JHS -->
        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
          <div class="flex items-center justify-center w-10 h-10 rounded-full border border-gray-600 bg-dark text-gray-500 shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
            <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24"><path d="M12 2L1 21h22L12 2zm0 4.5l7.5 13h-15L12 6.5z"/></svg>
          </div>
          <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] p-6 rounded border border-gray-700 bg-dark shadow-lg">
            <div class="flex flex-col md:flex-row md:items-center justify-between mb-1">
              <div class="font-bold text-gray-200 text-lg">Cagayan National High School</div>
              <time class="text-gray-500 font-mono text-sm">2017 - 2021</time>
            </div>
            <div class="text-gray-400 text-sm">Junior High School (JHS)</div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Footer / Contact -->
  <footer id="contact" class="bg-dark py-20 px-8 text-center border-t border-gray-800">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-4xl font-bold mb-4 text-white">Let's Build Something</h2>
      <p class="text-gray-400 mb-10 text-lg">Currently looking for internship opportunities.</p>
      
      <!-- Contact Links -->
      <div class="flex flex-col md:flex-row justify-center items-center gap-6 text-lg">
        
        <!-- Email -->
        <a href="mailto:baggav_geraldibert@email.com" class="flex items-center gap-3 hover:text-primary transition-colors text-white">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>
          Email Me
        </a>
        
        <span class="hidden md:block text-gray-600">|</span>
        
        <!-- Phone -->
        <a href="tel:09058187046" class="flex items-center gap-3 hover:text-primary transition-colors text-white">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
          </svg>
          Call Me
        </a>

        <span class="hidden md:block text-gray-600">|</span>

        <!-- Facebook -->
        <!-- UPDATE THE HREF BELOW WITH YOUR FACEBOOK LINK -->
        <a href="https://www.facebook.com/Filing.Baggay" target="_blank" rel="noopener noreferrer" class="flex items-center gap-3 hover:text-primary transition-colors text-white">
          <!-- Facebook SVG Icon -->
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary" fill="currentColor" viewBox="0 0 24 24">
            <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.469h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.469h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
          </svg>
          Facebook
        </a>

      </div>
      
      <p class="mt-16 text-sm text-gray-600">© 2023 Gerald Gilbert U. Baggay. All rights reserved.</p>
    </div>
  </footer>
</template>