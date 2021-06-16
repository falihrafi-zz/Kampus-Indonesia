<template>
    <div id = "fitur">
        <div id = 'fitur_judul'>
            Fitur Yang Tersedia Di Kampus Indonesia
        </div>

        <div id = "fitur_listfitur">
            <div class = "fitur_listfitur_layer">
                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/book.jpg">
                    <p>Kampus</p>
                </div>

                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/beasiswa.png" style = 'margin-top : 10%'>
                    <p style = 'margin-top : 12%'>Beasiswa</p>
                </div>

                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/seminar.png" style = 'max-width : 75%; max-height : 75%; margin-top : 15%'>
                    <p style = 'margin-top : 5%; font-size : 140%'>Seminar dan Workshop</p>
                </div>
            </div>

            <div class = "fitur_listfitur_layer">
                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/lomba.png" style = 'max-width : 73%; max-height : 73%; margin-top : 18%'>
                    <p style = 'margin-top : 8%'>Lomba</p>
                </div>

                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/lowongan.png" style = 'max-width : 70%; max-height : 70%; margin-top : 17%'>
                    <p style = 'margin-top : 10%'>Lowongan</p>
                </div>

                <div class = 'fitur_listfitur_layer_box'>
                    <img src = "./resources/utbk.png" style = 'max-width : 80%; max-height : 80%; margin-top : 15%'>
                    <p style = 'margin-top : 2%'>UTBK</p>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Fitur'
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #fitur {
        margin : 2%;
        margin-top : 8%;
        font-family : 'Quicksand', sans-serif;
    }

    #fitur_judul {
        text-align : center;
        font-size : 180%;
        font-weight : 500;
    }

    #fitur_listfitur {
        margin-top : 2%;
        margin-left : 7%;
    }

    .fitur_listfitur_layer {
        display : flex;
    }

    .fitur_listfitur_layer_box {
        display : inline-block;
        text-align : center;
        width : 25%;
        margin : 3%;
        margin-top : 0%;
    }

    .fitur_listfitur_layer_box img {
        max-width : 100%;
        max-height : 100%;
    }

    .fitur_listfitur_layer_box p {
        margin-top : 0%;
        font-size : 150%;
        font-weight : 500;
    }

    .fitur_listfitur_layer_box:hover {
        border-radius : 10px;
        border: 1px solid rgba(0, 0, 0, .2);
        cursor : pointer;
        width : 25%;
    }
</style>


