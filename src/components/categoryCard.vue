<template>
  <div>
    <div class="card">
      <div class="categoryCard">
        <div class="category">
          <p class="categoryName">Work</p>
          <p>...</p>
        </div>
        <p class="hours">32hrs</p>
        <p class="spentTime">Last-week - 32hrs</p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "categoryCard",
  props: {
    categoryName: String,
  },
};
</script>


<style scoped>
.categoryCard {
    padding: 30px;
    text-align: left;
  width: 180px;
  height: 115px;
  border-radius: 20px;
  background-color: #1d204b;
  position: relative;
}

.category {
    display: flex;
    justify-content: space-between;
    padding-bottom: 20px;
    color: white;
    padding-bottom: 15px;
}

.categoryName {
    font-weight: bold;
}

.hours {
    font-size: 50px;
    color: white;
}

.spentTime {
    color: white;
}

.card {
  padding-top: 40px;
  margin-left: 23px;
  position: relative;
  z-index: -1;
  height: 170px;
  background-color: #fe8b64;
  border-radius: 20px;
}

p {
  margin: 0;
}
</style>