<template>
  <div id="work">
    <feed />
  </div>
</template>

<script>
  export default {
    name: 'Work',
    components: {
      Feed: () => import('@/components/Feed')
    }
  }
</script>
