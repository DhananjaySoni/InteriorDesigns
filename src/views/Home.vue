<template>
    <div>
        <home />
        <Footer />
    </div>
</template>

<script>
import home from '../components/home';
import Footer from '../components/footer';
export default {
    components:{
        home,
        Footer
    }
}
</script>

<style scoped>
*{
  background: url(/images/bg-home.webp) fixed no-repeat;
  background-size: cover;
  color:#fff;
}
</style>