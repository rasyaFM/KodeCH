<template>
    <NavBar></NavBar>
    <v-form class="content" v-model="valid">
        <v-container fluid>
            <div class="page">
                <h1 class="judul text-orange">Halaman Pemesanan</h1>
                <p class="judul">Silakan lengkapi data berikut untuk melanjutkan proses pemesanan. Pesanan akan segera diproses oleh admin kami.</p>
                <v-row>
                    <v-col cols="12" sm="5">
                        <p class="title">Data Diri</p>
                        <p class="title2">Nama Kamu</p>
                        <v-text-field class="are-a"  v-model="placeholder" single-line label="Nama Depan"></v-text-field>
                        <v-text-field class="are-a" v-model="placeholder" label="Nama Belakang"></v-text-field>
                        <br/>
                        <p class="title2">Email</p>
                        <v-text-field class="are-a" v-model="placeholder" label="Email"></v-text-field>
                        <br/>
                        <p class="title2">Nomor Telepon</p>
                        <v-text-field class="are-a" v-model="placeholder" label="Nomor Telepon"></v-text-field>
                    </v-col>
                    <v-col cols="12" sm="5">
                        <p class="title3">Pesanan</p>
                        <p class="title4">Fasilitas</p>
                        <v-row class="fasilbox">
                            <!--Fasilitas-->
                            <v-col cols="3" sm="7">
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Co-working Space</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Meeting</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                    <p style="font-weight: 300;">Harian</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Event</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Meeting</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Class Room</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                    <p style="font-weight: 300;">Harian</p>
                                    <p style="font-weight: 300;">Bulanan</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Virtual Office</p>
                                    <p style="font-weight: 300;">Harian</p>
                                </div>
                                <div class="isi1">
                                    <br/>
                                    <p class="fasiltext2">Legal</p>
                                    <p style="font-weight: 300;">Harian</p>
                                </div>
                            </v-col>
                            <!--Biaya-->
                            <v-col cols="3" sm="5">
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 750 Ribu</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 5 Juta</p>
                                    <p style="font-weight: 300;">IDR 6 Juta</p>
                                    <p style="font-weight: 300;">IDR 12 Juta</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 750 Ribu</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 5 Juta</p>
                                    <p style="font-weight: 300;">IDR 6 Juta</p>
                                    <p style="font-weight: 300;">IDR 12 Juta</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 50 Ribu</p>
                                </div>
                                <div class="isi2">
                                    <br/>
                                    <br/>
                                    <p style="font-weight: 300;">IDR 5 Juta</p>
                                </div>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
                <v-btn class="button text-white" color="orange">
                        Pesan Sekarang
                </v-btn>
            </div>
        </v-container>
    </v-form>
    <FooterView></FooterView>    
</template>

<script>

import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";

    export default defineComponent({
        name: "HomeView",
        components: {
            NavBar,
            FooterView
        },
        data() {
            return {
                textFields: []
            }
        },
        methods: {
            add() {
                this.textFields.push({
                    label1: "foo",
                    value1: "",
                    label2: "bar",
                    value2: ""
                })
            },
            remove(index) {
                this.textFields.splice(index, 1)
            }
        }
    });
</script>
<style>
.content{
    position: relative;
    padding: 5px 0 15px 0;
    width: 100%;
    
    height: 1200px;
}
.page{
    position: relative;
    width: 60%;
    height: 1200px;
    left: 275px;
}
.judul{
    position: relative;
    text-align: center;
    width: 500px;
    margin-left: 150px;
}
.title{
    margin-top: 50px;
    margin-left: 100px;
    font-size: 20px;
}
.title2{
    font-weight: 300;
    margin-left: 100px;
    font-size: 20px;
}
.title3{
    margin-top: 50px;
    margin-left: 60px;
    font-size: 20px;
}
.title4{
    font-weight: 300;
    margin-left: 60px;
    font-size: 20px;
}
.are-a{
    margin-left: 100px;
    margin-top: 5px;
    width: 250px;
}
.isi1{
    font-size: 14px;
    margin-left: 60px;
}
.isi2{
    font-size: 14px;
    text-align: right;
    width: 140px;
}
.button{
    position: relative;
    text-align: center;
    width: 300px;
    height: 20px;
    background-color: yellow;
    margin-left: 200px;
    margin-top: 40px;
}
</style>