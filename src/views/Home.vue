<template>
  <v-container>

  <v-img
    class="white--text align-end"
    height="300px"
    src="@/assets/purple-pcb.jpeg"
  >
  </v-img>

    <v-row dense>
      <v-col cols=11>
        <v-card
          color="transparent"
          flat
        >

          <br>
          <br>
          <br>

          <h1 class="text-center lightsaber float-amimation lightsaber-pink-lg"><i class="fas fa-code"></i>  Alfredo Rentería Villanueva  <i class="fas fa-code"></i></h1>

          <br>

          <v-carousel
            cycle
            height="60px"
            :show-arrows="false"
            hide-delimiters
            interval="2500"
          >
            <v-carousel-item v-for="(item, index) in captions" :key="index">
              <v-row class="fill-height" align="center" justify="center">
                <span class="lightsaber-pink">{{ item }}</span>
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  data: () => ({
      captions: ['Electronics Engineer', 'Telecommunications Engineer', 'Maker', 'Web Developer']
    }),
};
</script>

<style scoped>
  .side-nav {
    color: white;
    font-size: 2em;
  }

  .lightsaber{
    color: white;
    text-shadow: 0 0 100px white;
  }
  .lightsaber-blue{
    color: white;
    text-shadow: 0 0 40px rgb(0, 68, 255);
  }

  .lightsaber-pink{
    color: white;
    font-size: 2em;
    text-shadow: 0 0 5px #ff00dd;
    font-family: 'Montserrat', sans-serif;
  }

  .lightsaber-pink-lg{
    color: white;
    font-size: 3em;
    text-shadow: 0 0 5px #ff00dd;
    font-family: 'Montserrat', sans-serif;
  }

</style>