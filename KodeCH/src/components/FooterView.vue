<template>
      <v-footer
            color="surface"
            height="250"
            class="">
            <v-card
            color="surface"
            padding="150px 60px"
            elevation="0"
            >
            <v-card-title>
                <h3 class=" font-weight-bold">Kode Creative Hub</h3>
            </v-card-title>
            <v-card-subtitle>
                <br>
                <h4 class=" font-weight-bold">Depok Town Square, paling atas (Lantai 2,
                <br>Level Mezanin) Area Foodcourt, Jl. Margonda Raya No.1,
                <br>Kemiri Muka, Kecamatan Beji, Kota Depok,
                <br>Jawa Barat 16424
                <br>
                (021) 72739662 </h4>
            </v-card-subtitle>
            </v-card>
            <v-spacer></v-spacer>
            <v-card
            color="surface"
            elevation="0" >
                <v-card-title class="d-flex flex-row mb-13 pointer" style="padding: 5px 15px;">
                    <v-btn width="30px" style="margin:7px; padding: 5px 5px;" href="https://web.facebook.com/"><img src="Facebook.png"></v-btn>
                    <v-btn width="30px" style="margin:7px; padding: 5px 5px;" href="https://wa.me/0895328705586"><img src="Whatsapp.png"></v-btn>
                    <v-btn width="30px" style="margin:7px; padding: 5px 5px;" href="https://www.linkedin.com/"><img src="Linkedin.png"></v-btn>
                    <v-btn width="30px" style="margin:7px; padding: 5px 5px;" href="https://www.instagram.com"><img src="Instagram.png"></v-btn>
                </v-card-title>
                <br>
                <v-card-subtitle 
                class="d-flex flex-row mb-0"
                padding="5px 10px">
                    &copy; <strong>Kode Creative Hub`</strong> {{ new Date().getFullYear() }}
                </v-card-subtitle>
            </v-card>
        </v-footer>
</template>

<script>
export default {

}
</script>

<style>

.v-btn{
    min-width: 0;
}
</style>