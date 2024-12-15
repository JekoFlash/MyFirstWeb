<script>
export default {
  name: "UnderBar",
  data() {
    return {
      message: "Footer จ้า",
    };
  },
};
</script>

<template>
  <div class="section">
    <div class="footer-container">
      <div class="grid-container">
        <div>
          <p>GRAVITY TEAM</p>
          <ul style="margin-top: 1rem;">
            <li style="margin-bottom: 10px;"><p>About Us</p></li>
            <li><p>Work with Us</p></li>
          </ul>
        </div>
        <div>
          <img
            src="../assets/logo-light.png.png"
            alt="GravityTeam"
            style="width: 180px; height: 41.81px"
          />
        </div>
      </div>
      <div class="flex-container">
        <p>Terms of Use & Privacy Poilcy</p>
        <p>©2022 Gravity Team. All Rights Reserved</p>
      </div>
    </div>
  </div>
</template>

<style>
.footer-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  width: 1728px;
  height: 205px;
}
.grid-container {
  display: grid;
  justify-content: space-between;
  grid-template-columns: auto auto;
  width: 1450px;
  height: 126px;
}
.flex-container {
  display: flex;
  justify-content: space-between;
  width: 1450px;
  height: 19px;
}
</style>
