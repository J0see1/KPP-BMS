<template>
    <section class="content-head" id="konten">
        <h1>CONTENT</h1>
    </section>
    <section class="content-fotgraf">
        <div class="img-box">
            <img src="../assets/fotgraf_img_1.JPG" alt="Dokumentasi Materi Fotografi" width="500px" />
        </div>
        <div class="txt-box">
            <h2>Fotografi dan<br>Videografi</h2>
            <p>Pada sesi fotografi dan videografi kami mendapatkan materi mengenai dasar-dasar setting kamera, angle kamera, frame size dan camera movement. Kami juga diberi kesempatan untuk mempraktekkan langsung secara hands on.</p>
        </div>
    </section>
    <section class="content-jurnalistik">
        <div class="txt-box">
            <h2>Jurnalistik</h2>
            <p>Beberapa materi yang kami dapatkan mengenai jurnalistik adalah definisi jurnalistik, manfaat jurnalistik, peran-peran dalam jurnalistik, dan juga tips menjadi jurnalis yang baik.</p>
        </div>
        <div class="img-box">
            <img src="../assets/jurnalistik_img_1.JPG" alt="Dokumentasi Materi Fotografi" width="500px" />
        </div>
    </section>
    <section class="content-webdev">
        <div class="img-box">
            <img src="../assets/webdev_img_1.JPG" alt="Dokumentasi Materi Fotografi" width="500px" />
        </div>
        <div class="txt-box">
            <h2>Web Development</h2>
            <p>Web development merupakan bidang yang selalu berkembang, dimana pada materi webdev ini kita dijelaskan mengenai basic dari webdev, rekomendasi tools webdev, dan basic dari vue.js</p>
        </div>
    </section>
    <section class="content-desain">
        <div class="txt-box">
            <h2>Desain</h2>
            <p>Materi-materi yang kami dapatkan diantara lain adalah prinsip desain, unsur desain, dan penerapan desain. Lalu kita juga mendapat cheat sheet desain dari mbak shafira 😁</p>
        </div>
        <div class="img-box">
            <img src="../assets/desain_img_1.JPG" alt="Dokumentasi Materi Fotografi" width="500px" />
        </div>
    </section>
    <section class="content-nulis">
        <div class="img-box">
            <img src="../assets/nulis_img_1.JPG" alt="Dokumentasi Materi Fotografi" width="500px" />
        </div>
        <div class="txt-box">
            <h2>Penulisan</h2>
            <p>Penulisan merupakan hal yang sangat penting bagi kita semua. Sehingga pada materi penulisan BMS ini kami mendapatkan materi mengenai jenis tulisan pada berita, bagian-bagian dalam tulisan, dan aturan penulisan.</p>
        </div>
    </section>
</template>

<style scoped>
* {
    background-color: whitesmoke;
    padding: 0;
    margin: 0;
}
.content-head {
    padding: 40px 0 50px;
    /*border: 1px solid black;*/
}
.content-head h1 {
    text-align: center;
    color: #136f63;
    font-family: Montserrat, sans-serif;
    font-size: 48px;
    font-weight: 800;
    text-shadow: 5px 8px 4px rgba(0, 0, 0, 0.3);
}
.content-fotgraf {
    padding: 50px 90px 100px;
    display: flex;
    justify-content: flex-end;
}
.content-fotgraf .txt-box {
    text-align: right;
}
.content-fotgraf p {
    padding-left: 48px;
}
.content-fotgraf .img-box {
    padding-top: 20px;
}


.content-jurnalistik {
    padding: 50px 90px 100px;
    display: flex;
    justify-content: flex-start;
}
.content-jurnalistik .txt-box {
    padding-top: 42px;
}
.content-jurnalistik p {
    padding-right: 48px;
}


.content-webdev {
    padding: 50px 90px 100px;
    display: flex;
    justify-content: flex-end;
}
.content-webdev .txt-box {
    text-align: right;
}
.content-webdev p {
    padding-left: 48px;
}
.content-webdev .img-box {
    padding-top: 20px;
}


.content-desain {
    padding: 50px 90px 100px;
    display: flex;
    justify-content: flex-end;
}
.content-desain .txt-box {
    padding-top: 42px;
}
.content-desain p {
    padding-right: 56px;
}


.content-nulis {
    padding: 50px 90px 100px;
    display: flex;
    justify-content: flex-end;
}
.content-nulis .txt-box {
    text-align: right;
}
.content-nulis p {
    padding-left: 48px;
}
.content-nulis .img-box {
    padding-top: 20px;
}


.img-box {
    display: inline-flex;
    padding-right: 10px;
}
.img-box img {
    border-radius: 64px;
    box-shadow: 5px 6px 5px rgba(0, 0, 0, 0.25);
}
.txt-box {
    width: 60%;
    font-family: Montserrat, sans-serif;
    display: block;
}
.txt-box h2 {
    font-size: 42px;
    font-weight: 600;
}
.txt-box p {
    padding-top: 20px;
    font-size: 24px;
    font-weight: 200;
}
</style>

<script>

</script>