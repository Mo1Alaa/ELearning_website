<template>
    <div>
        <section class="playlist-details">

<h1 class="heading">playlist details</h1>

<div class="row">

   <div class="column">
      

      <div class="thumb">
         <img src="G:\JS\ELearning_website\src\images1\post-2-1.png" alt="">
         <span>10 videos</span>
      </div>
   </div>
   
</div>

</section>
<section class="playlist-videos">

<h1 class="heading">playlist videos</h1>

<div class="box-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/jIB1bE57JQg?si=FNIdhe537eqqDJiG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/te-lFidcrcM?si=27H4jYKcWxxyMY0F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/gmgmRx6KsWA?si=ibp3QFQaf1rxcwZF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/x8cWpwsHa8A?si=auZygjKaG2Gcso-s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <!-- Add more video links similarly -->
</div>


</section>
    </div>
</template>

<script>
    export default {
        name:'videos'
    }
</script>

<style scoped>

.playlist-details .row .column .thumb img{
   height: 30rem;
   width: 100%;
   object-fit: cover;
   border-radius: .5rem;
}


.playlist-videos .box-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
   gap:1.5rem;
   justify-content: center;
   align-items: flex-start;
}


</style>