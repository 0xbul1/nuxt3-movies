<template>
  pages/index.vue
  <NuxtLayout>
    <NuxtLayout name="custom">
     <div>
      <NuxtLink to="/testlink1">
        <button style="width:100%;height:500px;">testlink1</button>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/testlink2">
        <button  style="width:100%;height:500px;">testlink2</button>
      </NuxtLink>
    </div>
  </NuxtLayout>
</NuxtLayout>
</template>
<script>
export default {
  layout: false
}
</script>