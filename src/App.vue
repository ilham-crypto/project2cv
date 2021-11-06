<template>
  <div id="app" class="container">
    <div class="row py-4">
      <project-9 />
    </div>
    <br /><br />
    <div>
      <project-2 />
    </div>
  </div>
</template>

<script>
import Project9 from "./components/Project9.vue";
import Project2 from "./components/Project2.vue";

export default {
  name: "app",
  components: {
    Project9,
    Project2,
  },
};
</script>