<template>
  <section class="py-20 px-8 md:px-20 bg-darker">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold mb-12 border-l-4 border-primary pl-4">Technical Skills</h2>

      <div class="grid md:grid-cols-2 gap-12">
        
        <!-- Left: Skill Bars -->
        <div class="space-y-8">
          <!-- Programming -->
          <div>
            <div class="flex justify-between mb-2">
              <span class="font-bold text-gray-200">Programming (Python, C++)</span>
              <span class="text-primary">85%</span>
            </div>
            <div class="h-3 w-full bg-gray-700 rounded-full overflow-hidden">
              <div class="h-full bg-primary rounded-full" style="width: 85%"></div>
            </div>
          </div>

          <!-- Networking -->
          <div>
            <div class="flex justify-between mb-2">
              <span class="font-bold text-gray-200">Networking & Hardware</span>
              <span class="text-primary">90%</span>
            </div>
            <div class="h-3 w-full bg-gray-700 rounded-full overflow-hidden">
              <div class="h-full bg-primary rounded-full" style="width: 90%"></div>
            </div>
          </div>

          <!-- Productivity -->
          <div>
            <div class="flex justify-between mb-2">
              <span class="font-bold text-gray-200">Productivity Tools (Office)</span>
              <span class="text-primary">95%</span>
            </div>
            <div class="h-3 w-full bg-gray-700 rounded-full overflow-hidden">
              <div class="h-full bg-primary rounded-full" style="width: 95%"></div>
            </div>
          </div>
        </div>

        <!-- Right: Summary Text -->
        <div class="text-gray-400 leading-relaxed">
          <p class="mb-4">
            I am a detail-oriented Computer Engineering student at <strong class="text-white">Cagayan State University - Carig Campus</strong>. 
          </p>
          <p class="mb-4">
            I have hands-on experience in programming, embedded systems, and circuit design. I am eager to gain an internship opportunity to further enhance my knowledge and skills while continuously improving technical proficiency.
          </p>
          <ul class="list-disc list-inside text-sm space-y-2 mt-6">
            <li>Proficient in Python (Pandas, NumPy) and C++</li>
            <li>Experience with Arduino-based systems</li>
            <li>Network configuration and maintenance</li>
          </ul>
        </div>

      </div>
    </div>
  </section>
</template>