<template>
    <div>
        <section class="courses">
            
            <h1>COURSES</h1>
            <div class="box-container">
                
                <div class="box">
                    <div class="tutor">
                        <img src="G:\JS\ELearning_website\src\images1\pic-1.jpg" alt="">
                        <div class="info">
                            <h3>john deo</h3>
                            
                        </div>
                    </div>
                    <div class="thumb">
                        <img src="G:\JS\ELearning_website\src\images1\post-1-1.png" alt="">
                        <span>new videos</span>
                        
                    </div>
                    <h3 class="title">complete HTML tutorial</h3>
                    
                </div>
                <div class="box">
                    <div class="tutor">
                        <img src="G:\JS\ELearning_website\src\images1\pic-2.jpg" alt="">
                        <div class="info">
                            <h3>mark</h3>
                            
                        </div>
                    </div>
                    <div class="thumb">
                        <img src="G:\JS\ELearning_website\src\images1\post-3-1.png" alt="">
                        <span>new videos</span>
                    </div>
                    <h3 class="title">complete HTML tutorial</h3>
                    
                </div>
                <div class="box">
                    <div class="tutor">
                        <img src="G:\JS\ELearning_website\src\images1\pic-3.jpg" alt="">
                        <div class="info">
                            <h3>john deo</h3>
                            
                        </div>
                    </div>
                    <div class="thumb">
                        <img src="G:\JS\ELearning_website\src\images1\post-2-1.png" alt="">
                        <span>new videos</span>
                    </div>
                    <h3 class="title">complete HTML tutorial</h3>
                    
                </div>
               
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        name: 'courses'
        
    }
</script>

<style scoped>
.courses .box-container {
    margin-top: 50px; 
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 1.5rem;
    justify-content: center;
    align-items: flex-start;
}
.courses .h1 {
    margin-bottom: 100px; /* Add margin to create space between heading and boxes */
}


.courses .box {
    border-radius: .5rem;
    background-color: var(--black);
    padding: 2rem;
}

.courses .box-container .box .tutor{
   display: flex;
   align-items: center;
   gap: 1.5rem;
   margin-bottom: 2.5rem;
}

.courses .box-container .box .tutor img{
   height: 5rem;
   width: 5rem;
   border-radius: 50%;
   object-fit: cover;
}

.courses .box-container .box .tutor h3{
   font-size: 1.8rem;
   color: var(--black);
   margin-bottom: .2rem;
}

.courses .box-container .box .tutor span{
   font-size: 1.3rem;
   color:var(--light-color);
}

.courses .box-container .box .thumb{
   position: relative;
}

.courses .box-container .box .thumb span{
   position: absolute;
   top:1rem; left: 1rem;
   border-radius: .5rem;
   padding: .5rem 1.5rem;
   background-color: rgba(0,0,0,.3);
   color: #fff;
   font-size: 1.5rem;
}

.courses .box-container .box .thumb img{
   width: 100%;
   height: 20rem;
   object-fit: cover;
   border-radius: .5rem;
}





</style>
