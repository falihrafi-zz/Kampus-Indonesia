<template>
    <div id = 'introduction'>
        <div id = 'introduction_tulisan'>
            <h1>Bingung Cari Informasi</h1>
            <h1> Seputar Kuliah ?</h1>
            <h2>Cari Disini Aja!</h2>
            <p>Dapatkan informasi seputar dunia perkuliahan secara</p>
            <p>terupdate dari kami melalui aplikasi kampus indonesia</p>
        </div>

        <div id = 'introduction_gambar'>
            <img src = './resources/computerpicture.png'>
        </div>

        <div id = 'introduction_input'>
            <input type = 'text' placeholder = 'Informasi Seputar Perkuliahan / Cari Kampus' v-on:keyup.enter = "submit" v-model = "inputBaru"/>
        </div>

        <div id = 'introduction_kampusinfo'>
            <div class = "introduction_kampusinfo_box">
                <h1>{{ kampusTerdata }}</h1>
                <p>Jumlah Kampus yang Terdata Saat Ini</p>
            </div>

            <div class = "introduction_kampusinfo_box">
                <h1>{{ kampusTerdaftar }}</h1>
                <p>Jumlah Kampus yang Sudah Terdaftar di Pintara</p>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Introduction',
    data : function(){
        return {
            kampusTerdata : 1045,
            kampusTerdaftar : 113,
            input : [],
            inputBaru : ""
        }
    },
    methods : {
        submit : function(){
            this.input.unshift(this.inputBaru);
            this.inputBaru = "";
        }
    }
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #introduction {
        margin : 2%;
        margin-top : 4%;
        font-family : 'Quicksand', sans-serif;
    }

    #introduction_tulisan {
        margin-left : 5%;
        width : 50%;
        display : inline-block;
    }

    #introduction_tulisan h1 {
        font-size : 290%;
        margin : 0%;
        font-weight : 600;
    }

    #introduction_tulisan h2 {
        font-size : 230%;
        margin-top : 2%;
        margin-bottom : 2%;
        font-weight : 400;
    }

    #introduction_tulisan p {
        font-size : 130%;
        margin : 0%;
    }

    #introduction_gambar {
        width : 40%;
        display : inline-block;
    }

    #introduction_gambar img {
        height : 55%;
        width : 55%;
        margin-left : 25%;
    }

    #introduction_input {
        text-align : center;
        margin : 3%;
    }

    #introduction_input input{
        text-align : center;
        font-size : 100%;
        font-weight : 300;
        padding : 17px;
        width : 45%;
        border: 1px solid #000000;
        border-radius: 30px;
    }

    #introduction_kampusinfo {
        display : flex;
        width : 50%;
        text-align : center;
        margin-left : 25%;
        margin-top : 5%;
        border: 1px solid rgba(0, 0, 0, .2);
        border-radius : 10px;
    }

    .introduction_kampusinfo_box {
        width : 50%;
    }

    .introduction_kampusinfo_box h1 {
        color : black;
    }

    .introduction_kampusinfo_box p {
        color : black;
        font-size : 120%;
    }
</style>

