<template>
  <div>
    <h1 class="authTitle">Forgot Password</h1>
  </div>
</template>

<script>
export default {
  name: 'SignupPage',

  layout: 'user',
  head() {
    const title = 'Forgot password'
    return {
      title,
    }
  },
}
</script>
