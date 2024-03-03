<template>
    <div class="image-container">
        <img class="partial-image" src="G:\JS\ELearning_website\src\images1\carousel-1.jpg" alt="">
        <p>Courses</p>
    </div>
</template>

<script>
export default {
    name: 'bodyy'
}
</script>

<style scoped>
.image-container {
    position: relative;
    margin-top: 50px;
    width: 100%;
    height: 300px; 
    margin-bottom: 0px; 
}

.partial-image {
    width: 100%;
    height: 100%; 
    object-fit: cover;
    filter: blur(1px); 
}

p {
    position: absolute;
    top: 30%; 
    left: 50%; 
    transform: translate(-50%, -50%); 
    color: white; 
    font-size: 50px;
    font-weight: bold; 
    text-align: center; 
    z-index: 1; 
}
</style>

