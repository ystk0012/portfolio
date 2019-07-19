<template>
  <div id="hobby">
    <feed />
  </div>
</template>

<script>
  export default {
    name: 'Hobby',
    components: {
      Feed: () => import('@/components/Feed')
    }
  }
</script>
