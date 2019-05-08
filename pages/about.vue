<template>
    <section class="recipes">
        <Recipe 
        thumbnail='http://stmedia.stimg.co/OC-FairStick_wide.00_00_37_18.Still016.jpg?h=630&w=1200&fit=crop&bg=999&crop=faces'
        title='Delicous Food'
        previewText='State Fair on a stick food'
        />

        <Recipe 
        thumbnail='https://farm1.staticflickr.com/712/20771425623_4888c3a045_b.jpg'
        title='Candy on stick'
        previewText='Its on a stick yo'
        />
    </section>

  
</template>

<script>
import Recipe from '@/components/Recipe'
export default {
  components: {
    Recipe
  }
}
</script>

<style scoped>
    .recipes {
        display: flex;
        flex-flow: row wrap;
        justify-content: center;
        align-items: center;
    }
</style>
