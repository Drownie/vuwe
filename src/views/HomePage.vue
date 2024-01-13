<script setup lang="ts">
  import DataTable from '@/components/'
  function toggleModal() {
    console.log('hello word');
  }
</script>

<template>
  <section class="bg-gray-50 p-3 antialiased dark:bg-gray-900 sm:p-5">
    <div class="mx-auto max-w-screen-xl px-4 lg:px-12">
      HELLO
    </div>
    <div class="relative overflow-hidden bg-white shadow-md dark:bg-gray-800 sm:rounded-lg">
      <nav
          class="flex flex-col items-start justify-content space-y-3 p-4 md:flex-row md:items-center md:space-y-0"
          aria-label="Table Navigation"
      >
        <h2 class="mb-4 text-3xl font-extrabold leading-none tracking-tight text-gray-900 dark:text-white md:text-4xl">
          TODO-CRUD
        </h2>
      </nav>

      <div class="flex flex-col items-center justify-between space-y-3 p-4 md:flex-row md:space-x-4 md:space-y-0">
        <button
            type="button"
            id="createProductionModalButton"
            data-modal-target="createProductionModal"
            class="flex items-center justify-center rounded-lg bg-green-700 px-4 py-2 text-sm
                font-medium text-white hover:bg-green-800 focus:outline-none focus:ring-4 focus:ring-green-300
                dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
            @click="toggleModal"
        >
          Add Task
        </button>
      </div>
    </div>
    <div class="overflow-x-auto">
      Data
    </div>
  </section>
</template>

<style scoped>

</style>