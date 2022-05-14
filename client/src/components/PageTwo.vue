<template>
    <div>
      {{ msg }}
    </div>
</template>

<script>
export default {
  name: 'PageOne',
  props: {
    msg: String
  }
}
</script>