<template>
  <div>
    <section class="hero is-primary is-large">
      <div class="hero-body has-text-centered">
        <p class="title is-1">
          Robot Scavenger Hunt
        </p>
        <p class="subtitle">
          Find all the robots before time runs out.
        </p>
      </div>
    </section>

    <section class="main-content has-background-light	">
      <div class="container is-max-desktop">
        <section class="section">
            <p class="title is-2 has-text-centered">The Challenge</p>

            <p>See if you can find all of the robot decals hidden around the new Science and Engineering Complex. Unsurprisingly, they've concentrated themselves around the robotics labs on the fourth floor. New ones may appear soon!</p>

            <p>Why do you want to find them all before time runs out? Who knows! No, seriously, I have no idea. Someone please tell me.</p>
        </section>
      </div>

      <div class="container">
        <Nuxt />

      </div>
    </section>

    <footer class="footer">
      <div class="content has-text-centered">
        <p><strong>Robot Scavenger Hunt</strong> by <a href="https://juliaebert.com">Julia Ebert</a>, a division of Teebert Industries.</p>
        <p>Header image source: <a href="https://unsplash.com/photos/MECKPoKJYjM">Arseny Tugolev, Unsplash</a></p>
        <p>&copy; 2021</p>
      </div>
    </footer>

  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: "Home",
          icon: "home",
          to: { name: "index" },
        },
        {
          title: "Inspire",
          icon: "lightbulb",
          to: { name: "inspire" },
        },
      ],
    };
  },
};
</script>
