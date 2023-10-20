<template>
  <section class="main__screen">

  <div class="ms-texts">
      <h2 class="mst-h2">Find&Hire Experts <span>for any job</span></h2>
      <p class="mst-p">We help talents meets opportunity and grow</p>
    </div>
    <button class="ms-btn">Contact us</button>

  <img src="../assets/mainScreen.png" alt="people" class="people">

  </section>
</template>

<script>
export default {

}
</script>

<style>
.main__screen {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.mst-h2 {
  color: #363636;
  font-family: Poppins;
  font-size: 70px;
  font-style: normal;
  font-weight: 600;
  line-height: 80px;
}
.mst-h2 span {
  color: #2F0899;
}

.mst-p {
  color: #363636;
  font-family: Poppins;
  font-size: 24px;
  font-style: normal;
  font-weight: 300;
  line-height: 34px;
}

.ms-btn {
  /* text */
  color: #FFF;
  text-align: center;
  font-family: Poppins;
  font-size: 30px;
  font-style: normal;
  font-weight: 500;
  line-height: 60px;

  /* button */
  display: inline-flex;
  padding: 0px 54px;
  margin-top: 30px;
  border-radius: 20px;
  border: 2px solid #FFF;
  background: #F68D2C;
}
.ms-btn:hover {
  background: #F38116;
}

.people {
  border-radius: 50px;
  background: #00AFA5;
}
</style>