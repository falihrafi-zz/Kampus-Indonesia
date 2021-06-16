<template>
    <div id = 'rekomendasi'>
        <div id = 'rekomendasi_carikampuslain'>
            <h2>Website Untuk Mencari Informasi Seputar Kuliah</h2>
            <p>Dapatkan informasi seputar dunia perkuliahan secara terupdate dari kami melalui aplikasi Kampus Indonesia</p>
            <a href = "#"><button id = 'rekomendasi_carikampuslain_button'>Cari Kampus Lainnya</button></a>
        </div>

        <div id = 'rekomendasi_kampusterbaik'>
            <div id = 'rekomendasi_kampusterbaik_boxatas'>
                <div id = 'rekomendasi_kampusterbaik_boxatas_tulisan1'>Rekomendasi Kampus Terbaik</div>
                <button id = 'rekomendasi_kampusterbaik_boxatas_button'>Lihat Kampus Lain ></button>
            </div>

            <div id = 'rekomendasi_kampusterbaik_boxbawahfull'>
                <div class = 'rekomendasi_kampusterbaik_boxbawah'>
                    <img src = './resources/brawijaya.jpg'>
                    <div class = 'rekomendasi_kampusterbaik_boxbawah_akreditasi'>Akreditasi : A</div>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_namauniv'>Universitas Brawijaya</p>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_status'>Negeri</p>
                    <a href = "#"><button class = 'rekomendasi_kampusterbaik_boxbawah_lihatdetail'>Lihat Detail</button></a>
                </div>

                <div class = 'rekomendasi_kampusterbaik_boxbawah'>
                    <img src = './resources/ugm.jpg' style = 'height : 153px'>
                    <div class = 'rekomendasi_kampusterbaik_boxbawah_akreditasi'>Akreditasi : A</div>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_namauniv'>Universitas Gadjah Mada</p>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_status'>Negeri</p>
                    <a href = "#"><button class = 'rekomendasi_kampusterbaik_boxbawah_lihatdetail'>Lihat Detail</button></a>
                </div>

                <div class = 'rekomendasi_kampusterbaik_boxbawah'>
                    <img src = './resources/itb.jpg' style = 'height : 153px'>
                    <div class = 'rekomendasi_kampusterbaik_boxbawah_akreditasi'>Akreditasi : A</div>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_namauniv' style = 'font-size : 112%'>Institut Teknologi Bandung</p>
                    <p class = 'rekomendasi_kampusterbaik_boxbawah_status'>Negeri</p>
                    <a href = "#"><button class = 'rekomendasi_kampusterbaik_boxbawah_lihatdetail'>Lihat Detail</button></a>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Rekomendasi'
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #rekomendasi {
        margin : 2%;
        margin-top : 8%;
        display : flex;
        font-family : 'Quicksand', sans-serif;
    }

    #rekomendasi_carikampuslain {
        width : 33%;
        display : inline-block;
        border-radius : 10px;
        background-color :#3388ff;
    }

    #rekomendasi_carikampuslain h2 {
        font-size : 180%;
        font-weight : 500;
        margin-left : 5%;
        margin-right : 22%;
        margin-bottom : 14%;
        color : white;
    }

    #rekomendasi_carikampuslain p {
        font-size : 130%;
        margin-left : 5%;
        margin-right : 10%;
        color : white;
    }

    #rekomendasi_carikampuslain_button {
        font-size : 100%;
        font-weight : 300;
        border-radius : 10px;
        background-color : white;
        text-align : center; 
        width : 90%;
        margin-left : 5%;
        margin-bottom : 5%;
        padding : 15px;
        border : none;
    }

    #rekomendasi_carikampuslain_button:hover {
        background-color : #33aaff;
        cursor : pointer;
    }

    #rekomendasi_kampusterbaik {
        width : 65%;
        margin-left : 1%;
        display : inline-block;
        border-radius : 10px;
    }

    #rekomendasi_kampusterbaik_boxatas {
        display : flex;
        margin : 2%;
        margin-top : 0%;
    }

    #rekomendasi_kampusterbaik_boxatas_tulisan1 {
        display : inline-block;
        font-size : 150%;
        font-weight : 700;

    }

    #rekomendasi_kampusterbaik_boxatas_button {
        display : inline-block;
        font-size : 70%;
        font-weight : 300;
        margin-top : 2%;
        margin-left : 35%;
        border-radius : 20px;
        padding : 5px;
        border : none;
    }

    #rekomendasi_kampusterbaik_boxatas_button:hover {
        cursor : pointer;
    }

    #rekomendasi_kampusterbaik_boxbawahfull {
        display : flex;
    }

    .rekomendasi_kampusterbaik_boxbawah {
        border-radius : 10px;
        width : 33%;
        display : inline-block;
        margin-left : 1%;
        margin-right : 1%;
        border: 1px solid rgba(0, 0, 0, .2);
    }

    .rekomendasi_kampusterbaik_boxbawah img {
        max-width : 90%;
        max-height : 50%;
        border-radius : 10px;
        margin : 5%;
        margin-top : 2%;
    }

    .rekomendasi_kampusterbaik_boxbawah_akreditasi {
        border-radius : 8px;
        border : 1px solid #000000;
        width : 45%;
        display : inline-block;
        text-align : center;
        margin-left : 40%;
        padding : 5px;
        background : #000077;
        color : white;
        font-weight : 600;
    }

    .rekomendasi_kampusterbaik_boxbawah_namauniv {
        font-size : 120%;
        margin-left : 3%;
        color : #000077;
        font-weight : 700;
        margin-bottom : 0%;
    }

    .rekomendasi_kampusterbaik_boxbawah_status {
        font-size : 100%;
        margin-left : 3%;
        color : #000077;
        font-weight : 400;   
        margin-top : 0%;
    }

    .rekomendasi_kampusterbaik_boxbawah_lihatdetail {
        font-size : 90%;
        font-weight : 300;
        font-weight : 600;
        border-radius : 10px;
        background-color : #000077;
        color : white;
        text-align : center; 
        width : 90%;
        margin-left : 5%;
        margin-bottom : 5%;
        padding : 12px;
        border : none;
        cursor : pointer;
    }
</style>

