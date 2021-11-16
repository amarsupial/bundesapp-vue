<template>
    <span class="inline-flex rounded-md shadow">

      <a v-if="size === 's'" :href="target" class="inline-flex items-center px-4 py-2 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-gray-50 hover:text-indigo-500">
        {{ content }}
      </a>

      <a v-else-if="size === 'l'" :href="target" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-gray-50 md:py-4 md:text-lg md:px-10">
        {{ content }}
      </a>

    </span>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// console.log(size)

export default {
  name: 'SecondaryButton',
  props: {
    target: String,
    content: String,
    size: {
      default: 's',
      type: String
    }
  }
}
</script>