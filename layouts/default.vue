<template>
  <div>
    
    <ParallaxHero>
      <template v-slot:navbar>
        <nav class="bg-gray-800 opacity-75">
          <ContentNavigation v-slot="{ navigation }">
            <ul class="flex space-x-4">
              <li v-for="link of navigation" :key="link._path" class="hover:bg-gray-700 text-white px-3 py-2 text-sm font-medium">
                <NuxtLink :to="link._path" >{{ link.title }}</NuxtLink>
              </li>
            </ul>
          </ContentNavigation>
        </nav>
      </template>
    </ParallaxHero>
    <slot />
  </div>
</template>

<script lang="ts" setup>
</script>

<style>

</style>