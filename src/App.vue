<template>
    <div id="app">
        <Header></Header>
        <Introduction></Introduction>
        <Rekomendasi></Rekomendasi>
        <LokasiKampus></LokasiKampus>
        <Fitur></Fitur>
        <Footer></Footer>
    </div>
</template>


<script>
import Header from './components/Header.vue'
import Introduction from './components/Introduction.vue'
import Rekomendasi from './components/Rekomendasi.vue'
import LokasiKampus from './components/LokasiKampus.vue'
import Fitur from './components/Fitur.vue'
import Footer from './components/Footer.vue'

export default {
    name: 'App',
    components : {
        Header,
        Introduction,
        Rekomendasi,
        LokasiKampus,
        Fitur,
        Footer
    }
}
</script>


<style>

</style>
