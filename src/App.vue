<script setup lang="ts"></script>

<template>
  <div class="container">
    <h1>El abuelo que canta</h1>
    <div class="flex">
      <iframe
        src="https://www.youtube.com/embed/ZUr5STk_12Q?si=i-VhOJkFZA01VgIQ"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
        class="video"
      ></iframe>

      <div class="lyrics">
        <div class="letra">
          Desde lejos, desde lejos oigo <br />
          El canto enamorado de un pájaro <br />
          Desde lejos, desde lejos oigo <br />
          El canto enamorado de un pájaro <br />
        </div>

        <div class="letra">
          Ese pájaro es mi abuelo <br />
          Es mi abuelo que canta, canta enamorado <br />
          Ese pájaro es mi abuelo <br />
          Es mi abuelo que canta, canta enamorado <br />
        </div>

        <div class="letra">
          Canta canta canta <br />
          Canta canta canta <br />
          Canta canta canta <br />
          Canta canta canta <br />
        </div>

        <div class="letra">
          Águila, águila aguilé <br />
          Águila, águila<br />
          Águila águila aguilé <br />
          Águila, águila águila <br />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Add your scoped CSS styles here */

.container {
  font-family: Arial, Helvetica, sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 1em;
}

.letra {
  margin-bottom: 1em;
}

h1 {
  font-size: 1em;
  margin-bottom: 1em;
}

.lyrics {
  margin-top: 1em;
}

/* Styling for the video */
.video {
  width: 100%; /* Make the video take up the full width of its container */
}

/* Your existing media query styles */

@media screen and (min-width: 600px) {
  h1 {
    font-size: 2em;
  }

  .letra {
    font-size: 1.2em;
  }

  .flex {
    display: flex;
    flex-direction: column;
    gap: 2em;
    align-items: center;
  }

  /* Increase the size of the video on desktop */
  .video {
    width: 80%; /* Adjust the percentage as needed */
  }
}
</style>
