<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">ROMCA :-)</h1>
      <navigation-panel />
    </div>
  </div>
</template>

<script>
import NavigationPanel from '~/components/NavigationPanel'
export default {
  components: {
    NavigationPanel,
  },
  data() {
    return {
      count: "2323fff",  // ctr s a hovno
      foo: 'cus'
    }
  },
  methods: {
    test() {
      return "fsdfasdf"; // tady to samy
    },
  },
}
</script>

<style></style>
