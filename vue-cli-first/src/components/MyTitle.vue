<template>
    <div>
        <h1>{{ titolo }}</h1>
    </div>
</template>
<script>
export default {
  name: 'MyTitle',
  props: {
    titolo: String
  }
}
</script>