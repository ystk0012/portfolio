<template>
  <div id="book">
    <feed />
  </div>
</template>

<script>
  export default {
    name: 'Book',
    components: {
      Feed: () => import('@/components/Feed')
    }
  }
</script>
