<template>
  <div
  >

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img :src="img" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <p class="title is-4">{{ title }}</p>
        <p class="subtitle is-6 has-text-grey">Posted on: <time :datetime="date">{{ datetime_str }}</time></p>
        <p><slot></slot></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    date: {
      type: String,
      required: true,
    },
    img: {
      type: String,
    },
  },
  computed: {
    datetime_str: function () {
      // Adding time fixes a weird JS date/time issue that makes it possibly a day off
      var date = new Date(this.date + "T00:00:00");
      return date.toDateString();
    },
  },
};
</script>
