<template>
  <div class="skills">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">My skills</h1>
          </v-card>

          <br><br><br><br>

          <v-container>
            <v-row>
              <v-col>
                <p class="lightsaber-pink">Circuit design</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="80"
                  color="pink"
                >
                  80%
                </v-progress-circular>
              </v-col>
              <v-col>
                <p class="lightsaber-pink">PCB layout</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="85"
                  color="pink"
                >
                  85%
                </v-progress-circular>
              </v-col>
              <v-col>
                <p class="lightsaber-pink">Web Development</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="60"
                  color="pink"
                >
                  60%
                </v-progress-circular>
              </v-col>
            </v-row>
            <v-row>
              <v-col>
                <p class="lightsaber-pink">Programming</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="80"
                  color="pink"
                >
                  80%
                </v-progress-circular>
              </v-col>
              <v-col>
                <p class="lightsaber-pink">Project Management</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="65"
                  color="pink"
                >
                  65%
                </v-progress-circular>
              </v-col>
              <v-col>
                <p class="lightsaber-pink">Team Work</p>
                <v-progress-circular
                  :rotate="360"
                  :size="80"
                  :width="8"
                  :value="100"
                  color="pink"
                >
                  100%
                </v-progress-circular>
              </v-col>
            </v-row>

          </v-container>
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