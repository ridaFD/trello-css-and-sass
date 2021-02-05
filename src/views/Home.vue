<template>
  <div class="container">
    <Header/>
    <div class="content">
      <Sidebar />
      <main class="hotel-view">
        main
      </main>
    </div>

  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "@/layout/Header.vue";
import Sidebar from "@/components/Sidebar.vue";

export default Vue.extend({
  name: "Home",
  components: {Header, Sidebar}
});
</script>

<style lang="scss" scoped>
.container {
  max-width: 120rem;
  margin: 8rem auto;
  background-color: var(--gray-light-1);
  box-shadow: var(--shadow-dark);
  min-height: 50rem;
}

.content {
  display: flex;
}
.hotel-view {
  background-color: #fff;
  flex: 1;
}
</style>
