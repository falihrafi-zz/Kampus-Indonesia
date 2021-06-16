<template>
    <div id = 'lokasikampus'>
        <div id = 'lokasikampus_judul'>
            Lokasi Kampus Terpopuler
        </div>

        <div id = 'lokasikampus_namakota'>
            <div class = 'lokasikampus_namakota_layer'>
                <div id = 'lokasikampus_namakota_layer_kota_jakarta'>
                    Jakarta
                </div>

                <div id = 'lokasikampus_namakota_layer_kota_surabaya'>
                    Surabaya
                </div>

                <div id = 'lokasikampus_namakota_layer_kota_yogyakarta'>
                    Yogyakarta
                </div>

                <div id = 'lokasikampus_namakota_layer_kota_bandung'>
                    Bandung
                </div>
            </div>

            <div class = 'lokasikampus_namakota_layer'>
                <div id = 'lokasikampus_namakota_layer_kota_medan'>
                    Medan
                </div>
    
                <div id = 'lokasikampus_namakota_layer_kota_semarang'>
                    Semarang
                </div>
    
                <div id = 'lokasikampus_namakota_layer_kota_malang'>
                    Malang
                </div>
    
                <div id = 'lokasikampus_namakota_layer_kota_bali'>
                    Bali
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'LokasiKampus'
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #lokasikampus {
        margin : 2%;
        margin-top : 8%;
        font-family : 'Quicksand', sans-serif;
    }

    #lokasikampus_judul {
        text-align : center;
        font-size : 230%;
        font-weight : 400;
    }

    #lokasikampus_namakota {
        margin-top : 2%;
        margin-left : 10%;
    }

    .lokasikampus_namakota_layer {
        display : flex;
    }

    #lokasikampus_namakota_layer_kota_jakarta {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/jakarta.jpeg)
    }

    #lokasikampus_namakota_layer_kota_surabaya {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/surabaya.jpg)
    }

    #lokasikampus_namakota_layer_kota_yogyakarta {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/yogyakarta.jpg)
    }

    #lokasikampus_namakota_layer_kota_bandung {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/bandung.jpg)
    }

    #lokasikampus_namakota_layer_kota_medan {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/medan.jpg)
    }

    #lokasikampus_namakota_layer_kota_semarang {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/semarang.jpg)
    }

    #lokasikampus_namakota_layer_kota_malang {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/malang.jpg)
    }

    #lokasikampus_namakota_layer_kota_bali {
        display : inline-block;
        text-align : center;
        width : 13%;
        padding : 40px;
        border-radius : 10px;
        margin : 1%;
        font-size : 140%;
        font-weight : 900;
        color : white;
        background-size : cover;
        background-image : url(./resources/bali.png)
    }
</style>

