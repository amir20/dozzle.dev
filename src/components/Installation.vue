<template>
  <div mx-auto container space-y-20 text="gray-700 dark:gray-200" p="x-4">
    <section grid="~ lg:cols-3" gap="y-10 x-6">
      <h2 text="2xl" tracking-tight>
        Installation
      </h2>
      <div grid="lg:col-span-2" prose text-lg>
        <p>
          Dozzle can be install using the Docker command line. Dozzle needs access to <code>docker.sock</code> file to access the logs of other containers. This file is usually located at <code>/var/run/docker.sock</code>. You can mount this file using the <code>-v</code> flag.
        </p>

        <code-block>
          docker run -v /var/run/docker.sock:/var/run/docker.sock -p 8080:8080 amir20/dozzle
        </code-block>
      </div>
    </section>
  </div>
</template>
