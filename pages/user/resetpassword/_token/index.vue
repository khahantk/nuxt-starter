<template>
  <div><h1 class="authTitle">Password recover</h1></div>
</template>

<script>
export default {
  name: 'ResetPasswordPage',
  layout: 'user',
  async asyncData(context) {},
  data() {},
  head() {
    const title = 'Reset password'
    return {
      title,
    }
  },
}
</script>
