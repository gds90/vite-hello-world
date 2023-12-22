<script>
import AppTitle from './appTitle.vue';
export default {
    components: {
        AppTitle,
    }
}
</script>
<template lang="">
    <div class="jumbotron mb-4 d-flex align-items-center">
        <div class="container-fluid">
          <h1 class="display-5 fw-bold"><AppTitle /></h1>
        </div>
    </div>
</template>
<style>
.jumbotron {
    background-image: url('https://s3.amazonaws.com/codecademy-content/projects/junction/bg.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 60vh;
    color: #fff;
}

h1 {
    opacity: 0.9;
}
</style>