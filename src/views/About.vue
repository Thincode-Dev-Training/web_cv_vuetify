<template>
  <div class="about">
    <v-container>
      <v-row dense>
        <v-col cols=12 class="text-center">

          <v-card
            color="transparent"
            flat
            height="10px"
          >
            <h1 class="lightsaber-pink">About me</h1>
          </v-card>

          <br><br>

          <v-card color='transparent' flat height='350px'>
            <v-carousel
              cycle
              height="100%"
              width="100%"
              hide-delimiters
              interval="2500"
              show-arrows-on-hover
            >
            <v-carousel-item
              v-for="(item,i) in items"
              :key="i"
              :src="item.src"
              reverse-transition="fade-transition"
              transition="fade-transition"
            ></v-carousel-item>
            </v-carousel>
            <br>
            <v-card-text class="lightsaber-pink-md" style="color: white;">I'm a friendly and curious engineer who is always on the move.</v-card-text>
            <v-card-text class="lightsaber-pink-md" style="color: white;">I love electronics, making stuff, programming and ice hockey!</v-card-text>
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
        { src: require('@/assets/programming.jpeg') },
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