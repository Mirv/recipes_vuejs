<template>
    <section class="recipes">
        <artitle class="recipe">
            <div class="thumbnail" style="background-image: url('http://stmedia.stimg.co/OC-FairStick_wide.00_00_37_18.Still016.jpg?h=630&w=1200&fit=crop&bg=999&crop=faces')"></div>
                <h1>Title</h1>
                <p>Some nice preview text</p>
        </artitle>
    </section>

  
</template>

<style scoped>
    .recipes {
        display: flex;
        flex-flow: row wrap;
        justify-content: center;
        align-items: center;
    }
</style>

<style scoped>
.recipe {
    box-sizing: border-box;
    width: 280px;
    padding: 8px;
    border: 1px solid #ccc;
    box-shadow: 0 2px 2px #eee;
}

.thumbnail {
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 200px;
}
</style>