<template>
  <main>
    <section v-if="posts" class="w-full max-w-5xl mx-auto">
      <h1 class="title">Projects</h1>
      <posts post-type="sitename" />
    </section>
  </main>
</template>

