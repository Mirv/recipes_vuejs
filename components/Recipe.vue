<template>
  <artitle class="recipe">
      <div class="thumbnail" :style="{backgroundImage: 'url(' + thumbnail + ')}'></div>
      <h1> {{ title }}</h1>
      <p> {{ previewText }} </p>
  </artitle>
</template>

<script>
export default {
  props: ['thumbnail', 'title', 'previewText']
}
</script>
