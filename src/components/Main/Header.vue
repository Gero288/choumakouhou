<template>
  <div class="flex flex-row max-h-2 bg-black">
      <div class="w-6">
          Wallet
      </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
