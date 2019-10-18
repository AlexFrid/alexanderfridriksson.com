<template>
  <v-app>
    <v-container fill-height justify="center">
      <v-card 
        width="400" 
        class="mx-auto" 
        elevation="5"
        >
        <v-img
        class="white--text align-end"
        height="300px"
        src="..\assets\myProfilePicture.jpg"
        >
        <v-card-title>
          <h1 style="font-size: 1.96rem!important;">Alexander Fridriksson</h1>
        </v-card-title>
        <v-card-subtitle class="white--text">
        I help people save time and make better decisions
        </v-card-subtitle>
        </v-img>
        <v-card-text>
          <p>*Imagine I wrote something meaningful about myself*</p>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions class="justify-space-around" >
          <v-btn  
          icon 
          color="primary"
          href="mailto:post@alexanderfridriksson.com"
          >
            <v-icon>fa-envelope</v-icon>
          </v-btn>
          <v-btn  
          icon 
          color="#1da1f2"
          href="https://twitter.com/Datastorydesign"
          >
            <v-icon>fab fa-twitter</v-icon>
          </v-btn>
          <v-btn  
          icon 
          color="#0e76a8"
          href="https://www.linkedin.com/in/alexanderfridriksson/"
          >
            <v-icon>fab fa-linkedin</v-icon>
          </v-btn>
          <v-btn  
          icon 
          color="black"
          href="https://github.com/AlexFrid"
          >
            <v-icon>fab fa-github</v-icon>
          </v-btn>
          <v-btn  
          icon 
          color="primary"
          href="https://public.tableau.com/profile/alexander.fridriksson#!/"
          >
            <v-img
            height="24px"
            width="24px"
            src="..\assets\tableauIcon.svg"></v-img>
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'cv',
  data: () => ({
    //
  }),
};
</script>
