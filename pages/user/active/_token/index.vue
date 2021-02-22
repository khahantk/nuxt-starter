<template>
  <div>
    <h1 class="authTitle">Account activation</h1>
  </div>
</template>

<script>
export default {
  name: 'ActiveAccountPage',
  layout: 'user',
  async asyncData(context) {},
  data() {
    return {
      message: {
        message: '',
        type: '',
      },
      token: '',
      verify: false,
      valid: false,
      loading: false,
    }
  },
  head() {
    const title = 'Account activation'
    return {
      title,
    }
  },
}
</script>
