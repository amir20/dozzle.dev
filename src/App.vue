<template>
  <div p="x-4 y-10" text="gray-700 dark:gray-200" min-h-screen>
    <div grid="~ lg:cols-3 lg:gap-8" h-full mx-auto>
      <div flex="~ col" text="center" p="x-4">
        <h1 text-4xl my-auto font-extralight>
          <span font-playfair>Dozzle</span> is a modern log viewer
          for Docker providing efficient and intuitive ways to
          view and search logs from containers
        </h1>
      </div>
      <div grid="lg:col-span-2" flex>
        <div my-auto>
          <browser-window>
            <video muted loop autoplay playsinline>
              <source src="./media/dozzle.webm" type="video/webm">
              <source src="./media/dozzle.mp4" type="video/mp4">
            </video>
          </browser-window>
        </div>
      </div>
    </div>
  </div>

  <div mx-auto container space-y-20 text="gray-700 dark:gray-200">
    <section grid="~ lg:cols-3" gap="y-10 x-6" min-h-screen>
      <h2 text="2xl" font-light tracking-tight>
        What's included
      </h2>
      <div grid="lg:col-span-2" prose text-lg font-light>
        <div>
          <p>Pocket is a beautiful mobile app marketing template built with Tailwind CSS and Next.js, designed and built by the Tailwind CSS team. It's production-ready and easy to customize, making it the perfect starting point for your new mobile app website.</p>
          <p>We've taken just as much care with the code as we have with the design, so it's also an invaluable resource if you want to study how experts build a website with Tailwind CSS and React.</p>
        </div>

        <p><strong>Built by experts</strong> — you can trust that all of the code is written following Tailwind CSS best practices, because it’s written by the same team who created and maintain the framework.</p>

        <p><strong>Built by experts</strong> — you can trust that all of the code is written following Tailwind CSS best practices, because it’s written by the same team who created and maintain the framework.</p>
      </div>
    </section>
  </div>
</template>
