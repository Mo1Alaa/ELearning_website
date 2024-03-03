<template>
    <div>
        
<footer class="footer">

    <span>footer</span> | @gmail.com

</footer>

    </div>
</template>

<script>
    export default {
        name: 'footerr'
    }
</script>

<style  scoped>
.footer{
   background-color: var(--white);
   border-top: var(--border);
   position:fixed;
   bottom: 0; left: 0; right: 0;
   text-align: center;
   font-size: 2rem;
   padding:2.5rem 2rem;
   color:var(--black);
   margin-top: 1rem;
   z-index: 1000;
   
}

.footer span{
   color:var(--main-color);
}



</style>