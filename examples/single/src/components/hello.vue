<template>
  <div>
    <p>hello component.</p>
    <zi-button>zi btn</zi-button>
  </div>
</template>

<script>
import Vue from 'vue'
import '@zeit-ui/vue/lib/button.css'
import Button from '@zeit-ui/vue/lib/button.common'

Button.install(Vue)
export default {}
</script>
