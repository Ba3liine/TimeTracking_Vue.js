<template>
  <div>
    <userCard />
  </div>
</template>


<script>
// @ is an alias to /src
import userCard from "@/components/userCard.vue";

export default {
  name: "HomeView",
  components: {
    userCard,
  },
};
</script>