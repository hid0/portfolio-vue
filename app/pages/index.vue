<template>
  <UContainer class="py-12 space-y-24">
    <!-- Hero Section -->
    <section class="flex flex-col items-center text-center gap-6 py-12">
      <UBadge
        color="primary"
        variant="subtle"
        size="lg"
        class="rounded-full"
      >
        Available for Backend & Fullstack Projects
      </UBadge>

      <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight">
        High-Performance <br>
        <span class="text-primary">System Architect</span>
      </h1>

      <p class="max-w-2xl text-lg text-gray-500 dark:text-gray-400">
        Membangun aplikasi web modern yang cepat dan terukur. Menggabungkan fleksibilitas <strong>Laravel & Vue</strong> dengan kecepatan eksekusi <strong>Golang</strong>.
      </p>

      <div class="flex gap-4">
        <UButton
          size="xl"
          icon="i-heroicons-envelope"
        >
          Hubungi Saya
        </UButton>
        <UButton
          size="xl"
          variant="ghost"
          icon="i-heroicons-code-bracket"
        >
          Lihat Proyek
        </UButton>
      </div>
    </section>

    <!-- Tech Stack Grid -->
    <section class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <UCard>
        <template #header>
          <div class="flex items-center gap-3">
            <UIcon
              name="i-simple-icons-go"
              class="w-8 h-8 text-blue-500"
            />
            <h3 class="font-bold">
              Golang
            </h3>
          </div>
        </template>
        <p class="text-sm text-gray-500">
          Fokus pada Microservices, performa tinggi, dan sistem konkurensi menggunakan debugging Delve.
        </p>
      </UCard>

      <UCard>
        <template #header>
          <div class="flex items-center gap-3">
            <UIcon
              name="i-simple-icons-laravel"
              class="w-8 h-8 text-red-500"
            />
            <h3 class="font-bold">
              Laravel
            </h3>
          </div>
        </template>
        <p class="text-sm text-gray-500">
          Manajemen database kompleks, integrasi Excel masif, dan optimasi query SQL.
        </p>
      </UCard>

      <UCard>
        <template #header>
          <div class="flex items-center gap-3">
            <UIcon
              name="i-simple-icons-vuedotjs"
              class="w-8 h-8 text-green-500"
            />
            <h3 class="font-bold">
              Vue / Nuxt
            </h3>
          </div>
        </template>
        <p class="text-sm text-gray-500">
          Frontend interaktif dengan Nuxt UI, ApexCharts untuk visualisasi data, dan state management yang bersih.
        </p>
      </UCard>
    </section>

    <!-- Featured Project (Student Management System) -->
    <section class="space-y-8">
      <div class="flex justify-between items-end">
        <h2 class="text-3xl font-bold italic">
          Featured Work
        </h2>
        <UButton
          variant="link"
          trailing-icon="i-heroicons-arrow-right"
        >
          Semua Proyek
        </UButton>
      </div>

      <UCard overflow-hidden>
        <div class="grid md:grid-cols-2 gap-0">
          <div class="bg-gray-100 dark:bg-gray-800 flex items-center justify-center p-12">
            <!-- Kamu bisa taruh screenshot dashboard ApexCharts kamu di sini -->
            <UIcon
              name="i-heroicons-chart-bar-square"
              class="w-24 h-24 text-gray-400"
            />
          </div>
          <div class="p-8 space-y-4">
            <UBadge
              color="primary"
              variant="solid"
            >
              Case Study
            </UBadge>
            <h3 class="text-2xl font-bold">
              Student Management & Analytics
            </h3>
            <p class="text-gray-500">
              Sistem manajemen siswa berskala besar dengan dashboard visitor menggunakan <strong>ApexCharts</strong> dan optimasi caching Laravel untuk menangani ribuan data.
            </p>
            <div class="flex gap-2 pt-4">
              <UKbd>Laravel</UKbd>
              <UKbd>Vue 3</UKbd>
              <UKbd>MySQL</UKbd>
            </div>
          </div>
        </div>
      </UCard>
    </section>
  </UContainer>
</template>
