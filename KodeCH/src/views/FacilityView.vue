<template>
  <v-app id="facility" font-family="Montserrat">
    <NavBar/>
    <v-container fluid>
      <v-col cols="16" id="page">
        <div class="pre" elevation="3">
          <v-row>
            <v-col cols="6" sm="4">
              <!-- Card 1 -->
              <v-card class="mx-auto" max-width="500">
                <v-img class="text-white align-end" src="facility(1).png" height="500px" cover>
                  <v-card-title class="card1">Co-Working<br>Space</v-card-title>
                </v-img>
              </v-card>
            </v-col>
            <v-col cols="6" sm="4">
              <!-- Card 2 -->
              <v-card class="mx-auto" max-width="500">
                <v-img class="text-white align-end" src="facility(3).png" height="500px" cover>
                  <v-card-title class="card2">Event &<br>Meetings</v-card-title>
                </v-img>
              </v-card>
            </v-col>
            <v-col cols="6" sm="4">
              <!-- Card 3 -->
              <v-card class="mx-auto" max-width="500">
                <v-img class="text-white align-end" src="facility(5).png" height="500px" cover>
                  <v-card-title class="card3">Virtual Office<br>& Legal</v-card-title>
                </v-img>
              </v-card>
            </v-col>
          </v-row>
          <br/>
          <v-btn class="button1 text-white" color="orange">
            Pelajari Selengkapnya
          </v-btn>
        </div>
      </v-col>
      <!-- About -->
      <v-col cols="3" class="describe1 mt-6">
        <v-row>
          <v-col cols="3" sm="2">
            <div class="name">
              <v-img src="Facility(2).png" width="450px"></v-img>
            </div>
          </v-col>
          <v-col cols="3" sm="6">
            <div class="info">
              <p class="text-grey">Fasilitas 1</p>
              <h1 class="text-orange">Co-working Space</h1>
              <p class="fasiltext1"> Ruangan yang luas dengan pemandangan metropolitan yang siap menjadi tempat untuk aktivitas produktifmu.</p>
              <div class="desc2">
                <!-- Card 1 -->
                <v-row>
                  <v-col cols="3" sm="4">
                    <br/>
                    <p class="fasiltext2">Detail Fasilitas :</p>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Co-working Space</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Meeting</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                      <p style="font-weight: 300;">Harian</p>
                    </div>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 750 Ribu</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 5 Juta</p>
                      <p style="font-weight: 300;">IDR 6 Juta</p>
                      <p style="font-weight: 300;">IDR 12 Juta</p>
                    </div>
                  </v-col>
                </v-row>
                <v-btn class="button2 text-white" color="orange">
                      Pesan Sekarang
                  </v-btn>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="3" class="describe2 mt-6">
        <v-row>
          <v-col cols="3" sm="2">
            <div class="name">
              <v-img src="Facility(4).png"></v-img>
            </div>
          </v-col>
          <v-col cols="3" sm="6">
            <div class="info">
              <p class="text-grey">Fasilitas 2</p>
              <h1 class="text-orange">Event & Meetings</h1>
              <p class="fasiltext1"> Banyak pilihan ruangan untuk acara ataupun rapat yang bisa disesuaikan dengan jumlah peserta.</p>
              <div class="desc2">
                <!-- Card 1 -->
                <v-row>
                  <v-col cols="3" sm="4">
                    <br/>
                    <p class="fasiltext2">Detail Fasilitas :</p>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Event</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Meeting</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Class Room</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                      <p style="font-weight: 300;">Harian</p>
                      <p style="font-weight: 300;">Bulanan</p>
                    </div>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 750 Ribu</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 5 Juta</p>
                      <p style="font-weight: 300;">IDR 6 Juta</p>
                      <p style="font-weight: 300;">IDR 12 Juta</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                    </div>
                  </v-col>
                </v-row>
                <v-btn class="button2 text-white" color="orange">
                      Pesan Sekarang
                </v-btn>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="3" class="describe3 mt-6">
        <v-row>
          <v-col cols="3" sm="2">
            <div class="name">
              <v-img src="Facility(6).png"></v-img>
            </div>
          </v-col>
          <v-col cols="3" sm="6">
            <div class="info">
              <p class="text-grey">Fasilitas 1</p>
              <h1 class="text-orange">Virtual Office & Legal</h1>
              <p class="fasiltext1"> Kantor fisik ataupun virtual tersedia untuk kamu yang punya perusahaan, organisasi atau komunitas.</p>
              <div class="desc2">
                <!-- Card 1 -->
                <v-row>
                  <v-col cols="3" sm="4">
                    <br/>
                    <p class="fasiltext2">Detail Fasilitas :</p>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Virtual Office</p>
                      <p style="font-weight: 300;">Harian</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <p class="fasiltext2">Legal</p>
                      <p style="font-weight: 300;">Harian</p>
                    </div>
                  </v-col>
                  <v-col cols="3" sm="4">
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 50 Ribu</p>
                    </div>
                    <div class="isi">
                      <br/>
                      <br/>
                      <p style="font-weight: 300;">IDR 5 Juta</p>
                    </div>
                  </v-col>
                </v-row>
                <v-btn class="button2 text-white" color="orange">
                      Pesan Sekarang
                  </v-btn>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <!-- About Done -->
    </v-container>
    <FooterView />
  </v-app>
</template>
  
<script>
  import {
    defineComponent
  } from "vue";
  import NavBar from "../components/NavBar.vue";
  import FooterView from "../components/FooterView.vue";
  // Components
  //import HelloWorld from '../components/HelloWorld.vue';
  export default defineComponent({
    name: "FacilityView",
    components: {
      NavBar,
      FooterView
    },
  });
</script>
<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');
  #facility {
    padding: 5px 0 10px 0;
    height: max-content;
  }
  .pre {
    margin-top: 70px;
    width: 100%;
    height: 600px;
    text-align: center;
    font-feature-settings: "half" on;
    padding: 0px 80px;
  }
  .describe1 {
    height: 520px;
  }
  .describe2 {
    height: 850px;
  }
  .describe3 {
    height: 500px;
  }
  .name {
    position: relative;
    display: block;
    margin-left: 75px;
    margin-top: 5px;
    width: 360px;
    height: 360px;
  }
  .desc1 {
    width: 500px;
  }
  .info {
    position: relative;
    display: block;
    margin-left: 450px;
    margin-top: 5px;
    width: 600px;
    height: 700px;
  }
  .fasiltext1 {
    font-size: 20px;
    letter-spacing: -0.2px;
    font-feature-settings: 'haln' on;
    font-weight: 500;
  }
  .fasiltext2 {
    font-size: 20px;
    letter-spacing: -0.2px;
    font-feature-settings: 'haln' on;
    font-weight: 500;
  }
  .isi{
    font-size: 20px;
  }
  .desc2 {
    width: 620px;
  }
  .button1 {
    width: 360px;
    border-radius: 0;
  }
  .button2 {
    margin-top: 25px;
    height: 30px;
    width: 250px;
    border-radius: 0;
  }
  .card1,
  .card2,
  .card3 {
    margin-bottom: 80px;
    font-weight: 700;
    font-size: 28px;
    letter-spacing: -0.2px;
    line-height: 32px;
    align-items: flex-end;
    display: flex;
    text-shadow: 0px 3px 3px rgba(0, 0, 0, 15);
  }
  .card1{
    margin-left: 100px;
  }
  .card2{
    margin-left: 110px;
  }
  .card3{
    margin-left: 110px;
  }
</style>
  