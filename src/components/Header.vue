<template>
    <div id = "header">
        <img src = './resources/logokampusindonesia.jpg'>
        <a>Beranda</a>
        <a>Fitur</a>
        <a>Hubungi Kami</a>
        <a>Blog</a>
        <a>Masuk</a>
        <a>Daftar</a>
    </div>
</template>


<script>
export default {
    name: 'Header'
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #header {
        font-family : 'Quicksand', sans-serif;
        display : flex;
        width : 100%;
    }

    #header a {
        display : inline-block;
        text-align : center;
        font-size : 120%;
        margin-right : 1%;
        margin-left : 1%;
        margin-top : 2%;
        margin-bottom : 1%;
        font-weight : 300;
        color : #696969;
        cursor : pointer;
    }

    #header a:hover {
        color : #000000;
    }

    #header img {
        height : 14%;
        width : 14%;
        margin-left : 5%;
    }
</style>
