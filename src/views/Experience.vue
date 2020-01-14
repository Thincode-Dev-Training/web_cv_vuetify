<template>
  <div class="experience">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">My experience</h1>
          </v-card>

          <br><br>

          <v-container>
            <v-row>
              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/udelas.jpg"
                  >
                    <v-card-title style="color: white;">Teacher at La Salle University</v-card-title>
                  </v-img>
                  <p>Currently, I teach at La Salle University about electronics. Generally speaking, I focus on hardware design and prototyping. My goal is to leave a footprint on the students so they can create a better future for all of us!</p>
                </v-card>
              </v-col>

              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/rubycode.jpg"
                  >
                    <v-card-title>Web Developer at Thincode</v-card-title>
                  </v-img>
                  <p>I'm also a Web Developer at Thincode, at my hometown León, Guanajuato in México. Here I use my knowledge on Ruby on Rails and other frameworks such as Bootstrap and Vue to create websites. One major project is the migration of a big old Rails 1 application to Rails 5!</p>
                </v-card>
              </v-col>
            </v-row>

            <v-row>
              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/proto.jpg"
                  >
                    <v-card-title>Freelance</v-card-title>
                  </v-img>
                  <p>Yes, I'm a freelance too! From hardware to web applications or other engineering services, I'm ready for action! You can expect a high quality service from me with a great customer service.</p>
                </v-card>
              </v-col>

              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/tower.jpg"
                  >
                    <v-card-title>RF Engineer</v-card-title>
                  </v-img>
                  <p>In the past, I've worked as an RF engineer, wokring at heights and servicing telecommunication systems for cell phone networks and dedicated internet services. In other words: I'm not afraid of hard work!</p>
                </v-card>
              </v-col>
            </v-row>

            <v-row>
              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/horno.jpg"
                  >
                    <v-card-title>Design Engineer</v-card-title>
                  </v-img>
                  <p>As a design engineer, I developed electronic control systems for shoe machinery as well as intermediate mechanical designs for the projects. Combining these two main areas, I'm now capable of creating machines and solutions for the industry!</p>
                </v-card>
              </v-col>

              <v-col cols=6>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/ni.jpeg"
                  >
                    <v-card-title>Functional Test Engineer</v-card-title>
                  </v-img>
                  <p>At last but not least, I have experience working and designing functional test equipment for PCBs. During that time I became the leader of the Functional Test and In Circuit Test areas, that means that I'm more than capable of leading teams!</p>
                </v-card>
              </v-col>
            </v-row>

            <v-row>
                <v-card color='transparent' class="lightsaber-pink-sm">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="@/assets/pink-pcb.jpg"
                  >
                    <v-card-title>Give me a shout!</v-card-title>
                  </v-img>
                  <p>If you wish to know more about my experience or to talk about projects, just get in touch!</p>
                </v-card>
            </v-row>
          </v-container>

          <br><br>
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
    font-size: 1.3em;
    text-shadow: 0 0 5px #ff00dd;
  }

  .lightsaber-pink-md{
    color: white;
    font-size: 1.8em;
    text-shadow: 0 0 5px #ff00dd;
  }
</style>