<template>
    <div>

        <router-view></router-view>
        <!-- <welcome-screen></welcome-screen> -->

        <!-- <home></home> -->
        

    </div>    
</template>


<script>
import WelcomeScreen from './components/WelcomScreen.vue';
import Home from './components/Home.vue';

export default({
    components:{
        'home':Home,
        'welcome-screen':WelcomeScreen
    }
    
})
</script>


<style>
@import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');

template,
body {
  font-family: 'Poppins', sans-serif;
  color: #111;
}

</style>