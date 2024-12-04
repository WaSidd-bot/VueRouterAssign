<script setup>
import { ref } from "vue";
</script>

<template>
    <h2>Featured Movies</h2>
    <div>
        <div class="movie">
            <img src="https://i.pinimg.com/736x/56/44/e8/5644e8ba9bcbd40cc541b0df9e47c1e7.jpg" alt="Frozen 2" width= "368" height="552">
            <p>Frozen 2</p>
        </div>
        <div class="movie">
            <img src="https://www.vintagemovieposters.co.uk/wp-content/uploads/2019/11/IMG_2167-2.jpeg" alt="The Joker" width="250.9" height="378.3">
            <p>The Joker</p>
        </div>
        <div class="movie">
            <img src="https://posterspy.com/wp-content/uploads/2020/02/DIE_HARD_poster_main.jpg" alt="Die Hard" width="250" height="375">
            <p>Die Hard</p>
        </div>
        <div class="movie">
            <img src="https://picfiles.alphacoders.com/348/thumb-1920-348097.jpg" alt="Terminator 2" width="233.3" height="350">
            <p>Terminator 2</p>
        </div>
    </div>
</template>

<style scoped>
img {
    position: relative;
    margin-top: 20px;
    margin-left: 0;
    padding: 0;
    left: 0px;
}
</style>