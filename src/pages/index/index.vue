<template>
  <div></div>
</template>

<script>
import { is } from '../../caring-js'
export default {
  created() {

    let e = '123465798@gmail.com'

    console.log(is.email(e))
  }
}
</script>

<style lang="scss" scoped></style>
