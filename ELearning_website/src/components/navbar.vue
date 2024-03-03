<template>
    <nav>
        <div class="header">
            <span class="logo">Elearning website</span>
            <div class="nav-links">
                <a href="navbar.vue">Home</a>
                <a href="navbar.vue">Courses</a>
                <a href="navbar.vue">About</a>
            
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'navbar'
}
</script>

<style scoped>
.header {
    position: absolute;
    top: 10px;
    left: 20px;
    right: 20px; 
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    
}

.logo {
    font-weight: bold;
    color: blue;
    font-size: 24px;
}

.nav-links {
    display: flex;
}

.header a {
    margin-left: 20px; /* Add margin between navigation links */
}
</style>
