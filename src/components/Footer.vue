<template>
    <div id = "footer">
        <div id = "infoperusahaan">
            <div id = "infoperusahaan_definisi">
                <h1>Kampus Indonesia</h1>
                <p>Kami merupakan perusahaan di bidang informasi seputar dunia perkuliahan yang memberikan informasi secara
                    terupdate dan dapat dipercaya sepenuhnya
                </p>
                <h1>PT Inspirasi Mandiri Nusantara</h1>
                <p>Kec. Lowokwaru, Kota Malang, Jawa Timur</p>
            </div>

            <div class = "infoperusahaan_kontak">
                <img src = "./resources/telpon.png" class = infoperusahaan_kontak_image>
                <p>021 3425 2885</p>
            </div>

            <div class = "infoperusahaan_kontak">
                <img src = "./resources/email.png" class = infoperusahaan_kontak_image style = 'width : 7%; height : 20%'>
                <p>info@kampusindonesia.co.id</p>
            </div>
        </div>

        <div id = "infoperusahaan_signup">
            <h1>Stay Connected</h1>
            <p>Ayok gabung bersama kami !!</p>
            <input type = 'text' placeholder = 'Email Address'>
            <button>Sign up</button>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Footer'
}
</script>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

    #footer {
        background-image : url(./resources/footerbackground.jpg);
        display : flex;
        font-family : 'Quicksand', sans-serif;
    }

    #infoperusahaan {
        width : 50%;
        margin-left : 3%;
        display : inline-block;
    }

    #infoperusahaan_definisi {
        margin : 2%;
    }

    #infoperusahaan_definisi h1 {
        color : white;
        font-weight : 500;
        margin-bottom : 0%;
    }

    #infoperusahaan_definisi p {
        color : white;
        margin-bottom : 0%;
        margin-top: 0%;
    }

    .infoperusahaan_kontak {
        display : flex;
        margin : 2%;
    }

    .infoperusahaan_kontak p {
        color : white;
        display : inline-block;
        margin-left : 2%;
    }

    .infoperusahaan_kontak_image {
        width : 7%;
        height : 7%;
        border-radius : 10px;
    }

    #infoperusahaan_signup {
        margin : 1%;
        margin-left : 10%;
        display : inline-block;
        width : 30%;
    }

    #infoperusahaan_signup h1 {
        color : white;
    }

    #infoperusahaan_signup p {
        color : white;
    }

    #infoperusahaan_signup input {
        width : 50%;
        height : 10%;
    }

    #infoperusahaan_signup button {
        height : 12%;
    }
</style>
