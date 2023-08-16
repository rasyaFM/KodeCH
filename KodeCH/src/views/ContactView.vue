<template>
  <v-app id="contact" font-family="Montserrat">
    <NavBar/>
    <v-container fluid>
      <div class="ground">
        <div class="head">
          <!--Banner -->
          <v-img class="head" src="contactban.jpg" cover>
            <v-col cols="6" class="mt-6">
                  <div class="title">
                    <h1>Ada pertanyaan atau masukan untuk Kode Creative Hub?</h1>
                    <br>
                    <v-btn class="btn mt-8">
                      Hubungi Kami
                    </v-btn>
                  </div>
            </v-col>
          </v-img>
          <!--Banner Done-->
        </div>
      </div>
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
  name: "ContactUsView",
  components: {
    NavBar,
    FooterView
},
});
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');
#contact {
  padding: 0 0 0 0;
  height: max-content;
  width: 100%;
}
.ground{
  height: 900px;
}
.head {
  position: relative;
  margin-top: 70px;
  margin-left: 30px;
  width: 1200px;
  height: 600px;
}
.title{
  position: relative;
  text-align: center;
  margin-top: 160px;
  margin-left: 260px;  
  font-size: 22px;
  font-weight: 700;
  font-style: normal;
  line-height: 48px;
  letter-spacing: -0.4px;
  width: 650px;
  height: 150px;
  color: white;
  
}
.btn{
  background-color: transparent;
  color: white;
  outline :white;
  
}

</style>
