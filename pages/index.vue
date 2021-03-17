<template>

<div>   
    <div class="video-section">
      <div class="video-container">
         <video autoplay loop muted src="https://res.cloudinary.com/colinhdd/video/upload/v1615265617/PoolDay_zl5r2z.mp4"></video>
      </div>

<div class="site-content pa-3 rounded">

<v-row justify-md="start" justify="center" align="center">
  <v-col cols="6" md="4">
   <div class="d-flex justify-content-center"> <v-img width="350px" src="https://res.cloudinary.com/colinhdd/image/upload/v1615265489/IBP_Logo_Full_Transparent_t6hwdy.png"></v-img></div> 
  </v-col>
  <v-col cols="auto" >
     <p class="ma-0 display-1 text--primary mt-n12 mt-md-0">Island Blue Pools</p>   
  </v-col>
</v-row>

   
<p>We help you learn to swim quickly and with confidence</p>

        
<v-btn width="50%" x-large color="primary" class="text-capitalize" target="blank" href="https://form.jotform.com/210708471092856">Get Started</v-btn>

<v-btn text width="50%" x-large color="primary" class="text-capitalize" target="blank" href="https://beta.oneshapp.com/islandbluepools">Shop Swim Gear</v-btn>

</div>

    </div>

    <v-container>

      <v-row justify="center">
        <v-col cols="12" md="4">

                <v-card height="500">
                   <v-img
      height="250"
      src="https://res.cloudinary.com/colinhdd/image/upload/v1615596126/jeff-dunham-fq673rUxrsQ-unsplash_bchdyy.jpg"
    ></v-img>

                  <v-card-text>
      <p class="display-1 text--primary">
      Experience Swift Results
      </p>
      <div class="text--primary">
       Our knowledgeable and
professional team of trained
swim coaches will guide you
through the basics of
swimming, which will
increase your confidence in
the water and ensure you
experience results in the
first few lessons
      </div>
    </v-card-text>

       

      </v-card>

        </v-col>

        <v-col cols="12" md="4">

                <v-card height="500">

                   <v-img
      height="250"
      src="https://res.cloudinary.com/colinhdd/image/upload/v1615596122/claude-piche-EHKRwpuQ0ts-unsplash_af30il.jpg"
    ></v-img>

                  <v-card-text>
      <p class="display-1 text--primary">
      Have Fun While Learning
      </p>
      <div class="text--primary">
     We want you to enjoy
yourselves while learning to
swim, so we incorporate fun
activities into our lessons.
Water exercises is also a
great way to work on your
fitness.
      </div>
    </v-card-text>


        


      </v-card>

        </v-col>

        <v-col cols="12" md="4">

                <v-card height="500">

                                     <v-img
      height="250"
      src="https://res.cloudinary.com/colinhdd/image/upload/v1615592866/bg2_lyruhv.jpg"
    ></v-img>

                  <v-card-text>
      <p class="display-1 text--primary">
        Advanced Swimming
      </p>
      <div class="text--primary">
Having mastered the basics
our aim is to continue
working with you to bring
you to an intermediate and
eventually an advanced
level where you may even
swim competitively as part
of a swim club if you
choose.
      </div>
    </v-card-text>


      


      </v-card>

        </v-col>
      </v-row>



    </v-container>

     <a target="blank" href="https://form.jotform.com/210708471092856" class="title d-block py-6 my-6 text-decoration-none text-center">Join Our Learn To Swim Programme</a>

     <div style="background-color: #fff" class="text-center">
       <p class="display-1 text--primary mb-0 px-md-16 mx-md-12 mt-16">
       Island Blue Pools
      </p>
     <p class="px-md-16 mx-md-12">Our vision is to provide a platform for every Jamaican to learn how to swim. </p>
<v-row no-gutters justify="center" align="center" >
    <v-col cols="12" md="4"  class="mr-md-8">
    <div>
      <v-img style="border-radius: 5px;" src="https://res.cloudinary.com/colinhdd/image/upload/v1615593660/drew-dau-GA2sc8nIOsk-unsplash_rasqdk.jpg"></v-img>
    </div>
  </v-col>
  <v-col cols="12" md="4">
    <p class="text-left container">
  Approximately 15% of Jamaicans can swim, which is a relatively small number for a country surrounded by water. The
team at Island Blue Pools is focused on changing this statistic, and believe the quality of our
instruction, affordability and passion for swimming will drive us forward to achieve our vision.
</p>
  </v-col>
</v-row>

<v-row no-gutters justify="center" align="center">
      <v-col cols="12" md="4" order-md="2">
    <div>
      <v-img style="border-radius: 5px;" src="https://res.cloudinary.com/colinhdd/image/upload/v1615593206/bg3_1_bgheq8.jpg"></v-img>
    </div>
  </v-col>

  <v-col cols="12" md="4" order-md="1">
  <p class="text-left container">
At Island Blue Pools we have developed learn to swim curriculums for all age groups, ranging
from toddlers to senior citizens. Swimmers have been amazed by the results they achieve while
participating in our programme. We are happy to have helped swimmers overcome their fear of
drowning and their own doubts to be able to swim with confidence. 
        </p>
  </v-col>
</v-row>





    </div>






    <div class="text-center pa-md-12 ma-md-12 pa-3 ma-3">
    <p class="display-1 text--primary ma-0">
      Contact Us
    </p>

<p class="mb-md-12">Contact us to get started quickly and with confidence.</p>
    <v-row dense justify="center" align="center">
<v-col cols="6" md="2"><div>
  <v-img contain src="https://res.cloudinary.com/colinhdd/image/upload/v1615594642/Copy_of_Iphone_Mockup_Imessage_Instagram_Story_wxvl6f.png"></v-img>
  </div>
  </v-col>
      <v-col cols="auto">
        <v-list>
    <v-list-item-group
        v-model="selectedItem"
        color="primary"
      >
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          link
        >
          <v-list-item-icon>
            <v-icon v-text="item.icon"></v-icon>
          </v-list-item-icon>
          <v-list-item-content class="text-left">
            <v-list-item-title v-text="item.text"></v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-item-group>
    </v-list>
      </v-col>

      <v-col cols="12">
        <div>
              <v-btn fab depressed x-large><v-icon x-large>mdi-facebook</v-icon></v-btn>
    <v-btn fab depressed x-large href="https://www.instagram.com/islandbluepoolsja/" target="blank"><v-icon x-large>mdi-instagram</v-icon></v-btn>
        </div>
      </v-col>
     
    </v-row>

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
