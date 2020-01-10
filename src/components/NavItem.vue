<template>
  <li>
    <a href="#" :title="tooltip" v-b-tooltip="{ trigger: tooltipTrigger }">
      <slot/>
    </a>
  </li>
</template>

<script>
export default {
  props: {
    tooltip: {
      type: String,
      default: ''
    },
    tooltipTrigger: {
      type: String,
      default: 'hover'
    }
  }
}
</script>