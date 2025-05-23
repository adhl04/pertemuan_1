<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
    <h1>Biodata Pribadi</h1>
    <div>
      <p><strong>NAMA:</strong> MUHAMMAD AIDHIL </p>
      <p><strong>NPM:</strong> 233510373 </p>
      <p><strong>KELAS:</strong> 4D </p>
      <p><strong>PROGRAM STUDI:</strong> TEKNIK INFORMATIKA </p>
      <p><strong>FAKULTAS:</strong> FAKULTAS TEKNIK </p>
      <p><strong>UNIVERSITAS:</strong> UNIVERSITAS ISLAM RIAU</p>
      <p><strong>SEMESTER:</strong> 4 </p>
      <p><strong>EMAIL:</strong> maidhil0110@gmail.com</p>
    </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
