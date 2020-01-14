<template>
  <div class="languages">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">Languages</h1>
          </v-card>

          <br><br><br><br><br><br><br><br><br>

          <v-card
            color='transparent'
            class="lightsaber-pink"
            flat
          >

            <v-row
              class="fill-height"
              align="center"
              justify="center"
            >
              <v-carousel
                cycle
                height="90%"
                width="100%"
                hide-delimiters=false
                interval="2500"
                show-arrows-on-hover
              >
                <v-carousel-item>
                  <img src="https://www.countryflags.io/ca/flat/64.png">
                  <img src="https://www.countryflags.io/us/flat/64.png">
                  <img src="https://www.countryflags.io/gb/flat/64.png">
                  <img src="https://www.countryflags.io/au/flat/64.png">
                  <img src="https://www.countryflags.io/ie/flat/64.png">
                  <img src="https://www.countryflags.io/nz/flat/64.png">
                  <p>Fluent English</p>
                </v-carousel-item>

                <v-carousel-item>
                  <img src="https://www.countryflags.io/mx/flat/64.png">
                  <img src="https://www.countryflags.io/es/flat/64.png">
                  <img src="https://www.countryflags.io/co/flat/64.png">
                  <img src="https://www.countryflags.io/ar/flat/64.png">
                  <img src="https://www.countryflags.io/pe/flat/64.png">
                  <p>Native Spanish</p>
                </v-carousel-item>

                <v-carousel-item>
                  <img src="https://www.countryflags.io/fr/flat/64.png">
                  <img src="https://www.countryflags.io/de/flat/64.png">
                  <img src="https://www.countryflags.io/it/flat/64.png">
                  <p>More coming soon!</p>
                </v-carousel-item>
              </v-carousel>
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'about',
  data: () => ({
      images: ['@/assets/hockey.jpg', '@/assets/programming.jpeg'],
      items: [
        { src: "https://www.countryflags.io/ca/flat/64.png" },
          { src: require('@/assets/electronics.jpg') },
          { src: require('@/assets/welding.jpg') },
          { src: require('@/assets/hockey.jpg') }
        ]
    }),
};
</script>

<style scoped>

  h1 {
    font-family: 'Montserrat', sans-serif;
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

  .lightsaber-pink-md{
    color: white;
    font-size: 1.8em;
    text-shadow: 0 0 5px #ff00dd;
  }
</style>