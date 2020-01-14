<template>
  <div class="education">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">My education</h1>
          </v-card>

          <br><br>

          <v-card
            color='transparent'
            height="100%"
            class="lightsaber-pink"
            flat
          >
            <br><br>
            <v-img
              class="white--text align-end"
              src="@/assets/delasalle_Blanco.png"
            >
            </v-img>
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
</style>