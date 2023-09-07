<template>
  <div>
    <p>Here it is: {{ dbname }}</p>
  </div>
</template>

<script setup>
  const dbname = useRuntimeConfig().public.dbHost;
</script>
