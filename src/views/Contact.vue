<template>
  <div class="contact">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">Contact me</h1>
          </v-card>

          <br><br>

          <v-card
            color='transparent'
            height="100%"
            class="lightsaber-pink"
            flat
          >
            <br><br><br>
            <v-card-text class="lightsaber-pink-sm" style="color: white"><i class="fas fa-at"></i> a.renteriavillanueva@gmail.com</v-card-text>
            <v-card-text class="lightsaber-pink-sm" style="color: white"><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/alfredorv/" style="color: white;">alfredorv</a></v-card-text>
            <v-card-text class="lightsaber-pink-sm" style="color: white"><i class="fas fa-phone"></i> +52 477 7500 253</v-card-text>
          </v-card>

        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

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

  a {
    color: white;
    text-decoration: none;
  }
</style>