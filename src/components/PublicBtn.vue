<script>
export default {
  props:{
    content:{
      type: String,
    },
    link:{
      type: String,
      default:'/',
    },
    style:{
      type: String,
      default:'back',
    },
  },

}
</script>

<template>
    <RouterLink :to="link">
        <button class="p-2 rounded-lg text-white" :class="style">{{ content }}</button>
    </RouterLink>
</template>