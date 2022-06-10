<template>
  <div class="cardUser">
    <div class="cardBottom">
      <div class="cardTop">
        <img
          src="../../public/images/image-jeremy.png"
          alt=""
          class="userAvatar"
        />
        <p class="reportedFor">Report for</p>
        <p class="userName">
          Jeremy <br />
          Robson
        </p>
      </div>
      <div class="divTimeSlot">
        <a href="">Daily</a>
        <a href="">Weekly</a>
        <a href="">Monthly</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "userCard",
};
</script>

<style scoped>
.cardUser {
  width: 230px;
  height: 420px;
  border-radius: 20px;
  text-align: left;
  font-family: "Rubik", sans-serif;
}

/* style pour le haut de la card */

.cardTop {
  height: 70%;
  padding: 30px;
  margin: 0;
  background-color: #5746ea;
  border-radius: 20px;
}

.userAvatar {
  width: 65px;
  border: solid 2px white;
  border-radius: 50%;
  margin-bottom: 30px;
}

.reportedFor {
  color: #9992fd;
  font-size: 15px;
  margin: 0;
}

.userName {
  margin: 0;
  color: white;
  font-size: 35px;
}

/* Style pour le bas de la card */

.cardBottom {
  width: 100%;
  background-color: #1d204b;
  height: 100%;
  border-radius: 20px;
  display: flex;
  flex-direction: column;
}

.divTimeSlot {
    padding-inline: 30px;
    padding-block: 20px;
    display: flex;
    flex-direction: column;
}

.divTimeSlot a {
    padding-block: 10px;
    width: 25%;
    color: white;
    text-decoration: none;
}

a:hover {
  color: #5746ea;
}
</style>