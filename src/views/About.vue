<template>
  <div class="about">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
          >
            <h1>This is an about page</h1>
          </v-card>
          <v-carousel
            cycle
            height="60px"
            width="100%"
            :show-arrows="false"
            hide-delimiters
            interval="2500"
          >
            <v-carousel-item v-for="(item, index) in images" :key="index">
              <v-row class="fill-height" align="center" justify="center">
                <!--<v-img
                class="white--text align-end"
                height="300px"
                src='{{ images }}'
              >
              </v-img> -->
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  data: () => ({
      images: ['Electronics Engineer', 'Telecommunications Engineer', 'Maker', 'Web Developer']
    }),
};
</script>

<style scoped>

  body {

        font-family: 'Roboto', sans-serif;
  }
  .side-nav {
    color: white;
    font-size: 2em;
  }

  .lightsaber-blue{
    color: white;
    text-shadow: 0 0 40px rgb(0, 68, 255);
  }

  .lightsaber-pink{
    color: white;
    font-size: 2em;
    text-shadow: 0 0 5px #ff00dd;
  }

  .lightsaber-pink-sm{
    color: white;
    font-size: 1em;
    text-shadow: 0 0 5px #ff00dd;
  }
</style>