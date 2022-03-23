<template>
  <select v-model="foo">
    <option value="a">test</option>
  </select>
</template>

<script>
export default {
  data() {
    return {
      foo: 'a'
    }
  }
}
</script>
