<template>
  <section class="section">
    <h2 class="title is-2 has-text-centered">Meet the Robots</h2>
    <div class="card-container">

      <card
        title="Hoverbot"
        date="2021-09-16"
        img="/robots/hoverbot.svg"
        >Gravity is for plebs. All the cool kids hover.</card>

      <card
        title="The Gymnast"
        date="2021-09-16"
        img="/robots/twirly.svg"
        >It says it can beat Simone Biles, but I think it's lying.</card>

      <card
        title="Not Armando"
        date="2021-06-22"
        img="/robots/arm-mobile.svg"
      >It's a robot arm, but it's not <i>that</i> robot arm.</card>

      <card
        title="WALL⋅E"
        date="2021-06-22"
        img="/robots/wall-e.svg"
      >Looking for Eve. And also your trash.</card>

      <card
        title="Just a Drone"
        date="2021-06-22"
        img="/robots/drone-camera.svg"
      >Definitely not a government surveillance drone.</card>

      <card
        title="Clamper"
        date="2021-06-22"
        img="/robots/the-clamps.svg"
      >Soft fingers can't hurt you like clamps can.</card>

      <card
        title="Unicycle"
        date="2021-06-22"
        img="/robots/mono-wheel.svg"
      >Only has one wheel. Still has one more wheel than you.</card>

      <!-- <card
        title="Copper Giant"
        date="2021-08-09"
        img="/robots/iron-giant.svg"
        >For legal reasons, this giant is not iron.</card>

      <card
        title="ALIEN"
        date="2021-08-09"
        img="/robots/alien.svg"
        >I AM AN ALIEN. I AM DEFINITELY NOT A ROBOT.</card>

      <card
        title="Pokebot"
        date="2021-08-09"
        img="/robots/pokebot.svg"
        >We automated the capture of Pokemon. Sorry, Ash.</card>

      <card
        title="Buff Bot"
        date="2021-08-09"
        img="/robots/buffbot.svg"
      >I don't go to the gym. I'm just naturally built this way.</card>

      <card
        title="Disco"
        date="2021-08-09"
        img="/robots/alert-bot.svg"
      >This head is full of RGB LEDs, and these arms have 7 DOFs.</card>

      <card
        title="Treaded"
        date="2021-08-09"
        img="/robots/treaded.svg"
      >I said <i>treaded</i> not <i>dreaded</i>. You're too afraid of the imminent robot apocalypse.</card>

      <card
        title="Bluebot"
        date="2021-08-09"
        img="/robots/bluebot.svg"
      >Bespoke, locally produced robots with mass appeal.</card> -->
    </div>
  </section>
</template>

<script>
import Card from "~/components/Card";

export default {
  name: "HomePage",

  components: {
    Card,
  },
};
</script>
