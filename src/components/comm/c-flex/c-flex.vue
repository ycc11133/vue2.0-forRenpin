<template>
  <div :class="['c-flex', class, align]">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'c-flex',
  props: {
    class: {
      type: String,
      default: ''
    },
    align: {
      type: String,
      default: ''
    }
  }
}
</script>

<style src="./flex"></style>