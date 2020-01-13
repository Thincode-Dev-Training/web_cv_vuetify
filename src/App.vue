<template>
  <v-app style="background-color: transparent;" class="fill-height bottom-gradient">

    <v-card>
      <v-navigation-drawer
        app
        permanent
        right
        color='rgba(128, 16, 255, 0.3)'
        height="100%"
        width="300px"
        :src="require('@/assets/neon-pcb.jpg')"
        expand-on-hover
      >
        <v-list-item>
          <v-list-item two-line>
            <v-list-item-avatar
              size=60
            >
              <img src="@/assets/me.jpeg">
            </v-list-item-avatar>

            <v-list-item-content>
              <h1 class="lightsaber-pink">ARV</h1>
            </v-list-item-content>

          </v-list-item>
        </v-list-item>

        <v-divider></v-divider>

          <v-list nav>
            <v-list-item link to="/">
              <v-list-item-icon>
                <i class="fas fa-home lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md">Home</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/about">
              <v-list-item-icon>
                <i class="fas fa-robot lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">About me</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/experience">
              <v-list-item-icon>
                <i class="far fa-building lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Experience</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/education">
              <v-list-item-icon>
                <i class="fas fa-graduation-cap lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Education</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/skills">
              <v-list-item-icon>
                <i class="fas fa-hiking lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Skills</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/languages">
              <v-list-item-icon>
                <i class="fas fa-language lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Languages</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/blog">
              <v-list-item-icon>
                <i class="fas fa-laptop-code lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Blog</v-list-item-title>
            </v-list-item>

            <v-list-item link to="/contact">
              <v-list-item-icon>
                <i class="fas fa-user-alt lightsaber-pink"></i>
              </v-list-item-icon>
              <v-list-item-title class="lightsaber-pink-md" style="text-decoration: none; color: white">Contact</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-navigation-drawer>
    </v-card>

    <v-content>
      <router-view/>
    </v-content>

    <br>
    <br>
    <br>

    <v-footer
      color="transparent"
      absolute
    >
      <v-col class="text-center">
        <div class="lightsaber-pink-sm">Alfredo Rentería Villanueva &copy; {{ new Date().getFullYear() }}</div>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
  export default {
    name: 'App',

    components: {
    },

    data: () => ({
      //
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

  .lightsaber-pink-md{
    color: white;
    font-size: 1.4em;
    text-shadow: 0 0 5px #ff00dd;
  }
</style>
