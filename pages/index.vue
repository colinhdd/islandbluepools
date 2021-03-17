<template>

<div>   
    <div class="video-section">
      <div class="video-container">
         <v-img style="height: 100vh" src="https://res.cloudinary.com/colinhdd/image/upload/v1615919200/IMG_7972_1_lwaktt.jpg"></v-img>
      </div>

<div class="site-content pa-6 rounded">

<v-row no-gutters  justify-md="start" justify="center" align="center">
  <v-col cols="4" md="auto">
   <div class="d-flex justify-content-center"> <v-img width="250px" src="https://res.cloudinary.com/colinhdd/image/upload/v1615926444/Logo-01_gnj1sf.png"></v-img></div> 
  </v-col>
      <v-col cols="4" md="auto">
   <div class="d-flex justify-content-center"> <v-img width="250px" src="https://res.cloudinary.com/colinhdd/image/upload/v1615927087/CEO_Logo-01_hin6qj.png"></v-img></div> 
  </v-col>
    <v-col cols="4" md="auto">
   <div class="d-flex justify-content-center"> <v-img width="250px" src="https://res.cloudinary.com/colinhdd/image/upload/v1615926446/Peek-A-Paradise_Official_-Title-01_pjj2ra.png"></v-img></div> 
  </v-col>
</v-row>

   
<p class="headline font-weight-bold">Be the CEO of your Life!</p>

        
<v-btn width="50%" x-large color="purple darken-1" class="white--text text-capitalize" target="blank" href="https://qapp.live/res/22253/213695?source=web">Get Started</v-btn>

<v-btn text width="50%" x-large color="purple darken-1" class="text-capitalize" target="blank" href="https://qapp.live/res/10527/213695?source=mobile">Learn More</v-btn>

</div>

    </div>


   
</div>
   

</template>

<script>


export default {

  data: () => ({
      items: [
        { text: '1 876 869 4889', icon: 'mdi-phone' },
        { text: '1 876 513 7894', icon: 'mdi-phone' },
        { text: 'islandbluepools@gmail.com', icon: 'mdi-email' },
        { text: '62, 8 Shortwood Rd, Kingston', icon: 'mdi-map-marker' },
      ],
    }),

}
</script>

<style scoped>

.video-section {
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
}

.site-content {
  background-color: #fff;
  text-align: center;
  z-index: 1;
  opacity: 0.8;
}

.video-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
}

</style>
