<template>
  <v-app id="about" font-family="Montserrat">
    <NavBar></NavBar>
    <v-container fluid>
      <div class="head">
        <!--Banner Home -->
            <v-img src="Maskgroup.jpg" ></v-img>
          
          <!-- Banner Home DONE -->
      </div>
      <!-- About -->
      <v-col cols="16" class="mt-12" id="describe">
          <v-row>
            <v-col cols="3" sm="3">
              <div class="name">
                <h1 class="text-orange">Berkumpul, Bekerja, Bercerita <br/> Bersama di Kode Creative Hub</h1>
                <div class="desc1" style="line-height: 28px; font-style: normal;">
                  <br>
                  <p style="font-size: 20px;"><strong style="font-size: 22px;">Kode Creative Hub berdiri sejak **** dibangun oleh **** dan diakuisisi oleh **** pada ****</strong>
                  <br>
                  <br>
                  Kode Creative Hub merupakan wadah berkumpulnya komunitas bisnis dan startup Anda.
                  Kami menyediakan tempat strategis untuk pengadaan event, training, kelas dan meeting. Selain itu
                  kami juga menyediakan coworking space, virtual office, private office, dan jasa legalitas untuk bisnis dan usaha Anda.
                  </p>
                </div>
              </div>
            </v-col>
            <v-col cols="3" sm="3">
              <div class="info">
                <h1>Orang-orang dibalik </h1>
                <h1 class="text-orange">Kode Creative Hub</h1>
                <div class="desc2">
                <!-- Card 1 -->
                  <v-row>
                    <v-col cols="3" sm="4">
                      <v-card
                        max-width="180px"
                        elevation="0"
                      >
                        <v-img
                          src="Maskgroupkiri.png" class="Card1" height="200px" cover
                        >
                        </v-img>
                        <v-card-title style="font-size: 18px;">Hwang Ye-Ji</v-card-title>
                        <v-card-text>
                          <p>Owner</p>
                        </v-card-text>
                      </v-card>
                    </v-col>
                    <v-col cols="3" sm="4">
                      <v-card
                        max-width="180px"
                        elevation="0"
                      >
                        <v-img
                          src="Maskgrouptengah.png" class="Card2" height="200px" cover
                        >
                        </v-img>
                        <v-card-title style="font-size: 18px;">Rosseanne Park</v-card-title>
                        <v-card-text>
                          <p>Marketing</p>
                        </v-card-text>
                      </v-card>
                    </v-col>
                    <v-col cols="3" sm="4">
                      <v-card
                        max-width="180px"
                        elevation="0"
                      >
                        <v-img
                          src="Maskgroupkanan.png" class="Card3" height="200px" cover
                        >
                        </v-img>
                        <v-card-title style="font-size: 18px;">Seoul In Ah</v-card-title>
                        <v-card-text>
                          <p>Front Officer</p>
                        </v-card-text>
                      </v-card>
                    </v-col>
                  </v-row>    
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
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";

// Components
//import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: "AboutView",
  components: {
    NavBar,
    FooterView
},
});
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');
#about {
  padding: 0 0 0 0;
  height: max-content;
  width: 100%;
}

.head {
  position: relative;
  height: 400px;
  margin-top: 70px;
  margin-left: auto;
}


.name {
  position: relative;
  display: block;
  margin-left: 45px;
  margin-top: 5px;
  width: 550px;
  height: 550px;
  
}

.desc1{
  width: 500px;
}

.info{
  position: relative;
  display: block;
  margin-left: 300px;
  margin-top: 5px;
  width: 620px;
  height: 450px;
}
.desc2{
  width: 620px;
}

.Card1,
.Card2,
.Card3{
  margin-top: 20px;
  font-size: 20px;
  letter-spacing: -0,2px;
  line-height: 28px;
  align-items: flex-end;
  display: flex; 
}

</style>
