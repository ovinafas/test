<template>
    <div>
    <nav class="navbar navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Vue App</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <!-- Navbar content -->
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">

            <router-link :to="{ name: 'home' }"  class="nav-item nav-link">Home</router-link>

            <router-link :to="{ name: 'hello' }"  class="nav-item nav-link">Hello World</router-link>


            </div>
        </div>

    </nav>

        <h1>Vue Router App</h1>


        <div class="container">
            <router-view></router-view>
        </div>
    </div>
</template>
<script>
    export default {}
</script>
