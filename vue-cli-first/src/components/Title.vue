<template>
    <div>
        <h1>{{ msg }}</h1>
    </div>
</template>
<script>
export default {
  name: 'La mia prima app con Vue CLI!',
  props: {
    msg: String
  }
}
</script>