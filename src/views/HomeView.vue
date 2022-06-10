<template>
  <div class="components">
    <userCard />
    <div>
      <categoryCard />
    </div>
  </div>
</template>


<script>
// @ is an alias to /src
import userCard from "@/components/userCard.vue";
import categoryCard from "@/components/categoryCard.vue";

export default {
  name: "HomeView",
  components: {
    userCard,
    categoryCard
  },
};
</script>

<style>
  .components {
    display: flex;
  }
</style>