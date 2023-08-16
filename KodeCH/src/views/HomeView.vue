<template>
    <v-app id="home" font-family="Montserrat">
      <NavBar/>
      <v-container fluid>
        <div class="head">
          <!--Banner Home -->
            <v-col cols="6" class="mt-6">
              <div class="title" >
                <h1 class="text-black">Berkumpul, Bekerja, <br/>Bercerita Bersama di</h1>
                <h1 class="text-orange">Kode Creative Hub</h1>
                <br>
                <p class="text-grey-#686869">Nikmati lingkungan kerja yang <br/> produktif bersama kode creative hub</p>
                <br>
                <v-btn class="text-white mt-8" color="orange">
                  Pelajari Selengkapnya
                </v-btn>
              </div>
            </v-col>
            <!-- Banner Home DONE -->
            <!-- Vector Banner Home -->
            <v-row>
              <v-col cols="4">
                <div class="asset1">
                  <img src="Asset3.png">
                </div>
              </v-col>
              <v-col cols="6">
                <div class="asset2">
                  <img src="Asset1.png">
                </div>
              </v-col>
              <v-col cols="6">
                <div class="asset3">
                  <img src="Asset4.png">
                </div>
              </v-col>
              <v-col cols="5">
                <div class="asset4">
                  <img src="Asset2.png">
                </div>
              </v-col>
            </v-row>
        </div>
        <!-- About -->
        <v-col cols="12" class="mt-16" id="about">
          <div>
            <v-row>
              <v-col cols="3" sm="3">
                <div class="name">
                  <h2>Tentang Kode <br/> Creative Hub</h2>
                </div>
              </v-col>
              <v-col cols="3" sm="3">
                <div class="info">            
                <p class="text-grey-#686869">
                  Kode Creative Hub merupakan wadah berkumpulnya komunitas bisnis dan startup Anda.
                  Kami menyediakan tempat strategis untuk pengadaan event, training, kelas dan meeting. Selain itu
                  kami juga menyediakan coworking space, virtual office, private office, dan jasa legalitas untuk bisnis dan usaha Anda.
                  <button class="text-orange">
                  Pelajari lebih lanjut.
                  </button>
                </p>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <!-- About Done -->
        <!-- Facility -->
        <v-col cols="12" id="page">
          <div class="pre" elevation="3">
            <v-row>
              <v-col cols="6" sm="4">
                <!-- Card 1 -->
                <v-card
                  class="mx-auto"
                  max-width="250"
                >
                  <v-img
                    src="Card1.jpg" height="200px" cover
                    class="text-white align-end"
                  >
                    <v-card-title class="card1">Co-Working <br>Space</v-card-title>
                  </v-img>
              
                  <v-card-text>
                    <div>Ruangan yang luas dengan pemandangan metropolitan yang siap menjadi tempat untuk aktivitas produktifmu</div>
                  </v-card-text>
              
                  <v-card-actions>
                    <v-btn
                      color="orange"
                      text
                    >
                      Baca Selengkapnya
                    </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <v-col cols="6" sm="4">
                <!-- Card 2 -->
                <v-card
                  class="mx-auto"
                  max-width="250"
                >
                  <v-img
                    class="text-white align-end" 
                    src="Card2.jpg" height="200px" cover
                  >
                    <v-card-title class="card2">Event & <br>Meetings</v-card-title>
                  </v-img>
              
                  <v-card-text>
                    <div>Banyak pilihan ruangan untuk acara ataupun rapat yang bisa disesuaikan dengan jumlah peserta</div>
                  </v-card-text>
              
                  <v-card-actions>
                    <v-btn
                      color="orange"
                      text
                    >
                      Baca Selengkapnya
                    </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <v-col cols="6" sm="4">
                <!-- Card 3 -->
                <v-card
                  class="mx-auto"
                  max-width="250"
                >
                  <v-img
                    class="text-white align-end"
                    src="Card3.jpg" height="200px" cover
                  >
                    <v-card-title class="card3">Virtual Office <br>& Legal</v-card-title>
                  </v-img>
                  
                  <v-card-text>
                    <div>Kantor fisik ataupun virtual tersedia untuk kamu yang punya perusahaan, organisasi atau komunitas</div>
                  </v-card-text>
              
                  <v-card-actions>
                    <v-btn
                      color="orange"
                      text
                    >
                      Baca Selengkapnya
                    </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <!--Facility DONE-->
        <!--Terpercaya oleh-->
        <v-col cols="12" class="mt-16">
          <div class="hire">
            <h3 class="text-black">Terpercaya oleh</h3>
            <br>
            <img src="Frame 2.png"/>
          </div>
        </v-col>
        <!--Terpercaya oleh DONE-->
        <!-- Testimonial-->
        <v-col class="testi">
          <v-carousel hide-delimiter-background="0" class="testimoni" :show-arrows="false" height="300">
            <v-carousel-item class="carousel1">
              <v-row>
                <v-col cols="12" sm="3">
                  <img src="jennie.png" class="jen1">
                </v-col>
                <v-col cols="12" sm="4">
                  <span class="text-caption1">
                    <h4>Kode Creative Hub menyediakan private room untuk membantuku fokus dalam bekerja! tempatnya cukup mudah diakses, dan ada banyak tempat jajan disekitar kode hehe.
                        <br/><br/><br/>
                        <button class="text-orange">
                        Kim Jennie, Artist
                        </button>
                    </h4>
                  </span>
                </v-col>
              </v-row>
            </v-carousel-item>
            <v-carousel-item class="carousel2">
              <v-row>
                <v-col cols="12" sm="3">
                  <img src="jennie.png" class="jen2">
                </v-col>
                <v-col cols="12" sm="4">
                  <span class="text-caption2">
                    <h4>Kode Creative Hub menyediakan private room untuk membantuku fokus dalam bekerja! tempatnya cukup mudah diakses, dan ada banyak tempat jajan disekitar kode hehe.
                        <br/><br/><br/>
                        <button class="text-orange">
                        Kim Jennie, Artist
                        </button>
                    </h4>
                  </span>
                </v-col>
              </v-row>
            </v-carousel-item>
            <v-carousel-item class="carousel3">
              <v-row>
                <v-col cols="12" sm="3">
                  <img src="jennie.png" class="jen3">
                </v-col>
                <v-col cols="12" sm="4">
                  <span class="text-caption3">
                    <h4>Kode Creative Hub menyediakan private room untuk membantuku fokus dalam bekerja! tempatnya cukup mudah diakses, dan ada banyak tempat jajan disekitar kode hehe.
                        <br/><br/><br/>
                        <button class="text-orange">
                        Kim Jennie, Artist
                        </button>
                    </h4>
                  </span>
                </v-col>
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-col>
        <!-- Testimonial DONE -->
      </v-container>
      <FooterView />
    </v-app>
  </template>
  
  <script>
  import { defineComponent } from "vue";
  import NavBar from "../components/NavBar.vue";
  import FooterView from "../components/FooterView.vue";
  
  // Components
  //import HelloWorld from '../components/HelloWorld.vue';
  
  export default defineComponent({
    name: "HomeView",
    components: {
      NavBar,
      FooterView
  },
  });
  </script>
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');
  #home {
    padding: 5px 0 10px 0;
    height: max-content;
  }
  
  .head {
    position: relative;
    text-align: center;
    padding: 20px;
    margin-bottom: 10px;
    height: 300px;
    width: 100%;
    color: surface;
  }
  .title{
    position: absolute;
    margin-top: 70px;
    margin-left: 480px;  
    font-size: large;
    height: 150px;
  }
  
  .asset1{
    position: relative;
    margin-left: 50px;
    margin-top: 10px;
  }
  .asset2{
    position: relative;
    margin-left: 450px;
    margin-top: 20px;
  }
  .asset3{
    position: relative;
    margin-left: 50px;
    margin-top: 10px;
  }
  .asset4{
    position: relative;
    margin-left: 290px;
    margin-top: -80px;
  }
  .name {
    position: relative;
    display: block;
    margin-left: 325px;
    margin-top: 215px;
    width: 500px;
    height: 150px;
  }
  .info{
    position: relative;
    display: block;
    margin-left: 175px;
    margin-top: 220px;
    width: 425px;
    height: 150px;
  }
  .pre {
    margin-top: 100px;
    width: 100%;
    height: 200px;
    text-align: left;
    font-feature-settings: "half" on;
    padding: 0px 250px;
    
  }
  .card1,.card2,.card3{
    font-weight: 700;
    font-size: 24px;
    letter-spacing: -0.2px;
    line-height: 32px;
    align-items: flex-end;
    display: flex;
    text-shadow: 0px 3px 3px rgba(0, 0, 0, 15);
  }
  .hire {
    position: relative;
    width: 100%;
    height: 200px;
    padding: 0 200px;
    background-color: surface;
    margin-top: 175px;
    text-align: center;
    margin-bottom: 15px;
    font-size: medium;
  }
  
  .testi{
    height: 300px;
    margin-bottom: 100px;
  }
  .testimoni{
    position: relative;
    width: 100%;
    padding: 50 50px;
    text-align: center;
    margin-bottom: 15px;
    font-size: medium;
  }
  
  .carousel1,.carousel2,.carousel3{
    position: absolute;
    height: 100px;
  }
  .jen1,.jen2,.jen3{
    position: absolute;
    margin-left: 150px;
    border-radius: 25px;
  }
  .text-caption1,.text-caption2,.text-caption3{
    position: absolute;
    text-align: left;
    margin-top: 50px;
    width: 500px;
  }
  .text-caption1,.text-caption2,.text-caption3 :hover{
    color: none;
  }
  
  </style>