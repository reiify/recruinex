<template>
  <section class="main__screen">

  <div class="ms-texts">
      <h2 class="mst-h2">Find&Hire Experts <span>for any job</span></h2>
      <p class="mst-p">We help talents meets opportunity and grow</p>
      <button type="submit" class="ms-btn">Contact us</button>
  </div>

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
  gap: 40px;
}

.ms-texts {
  display: flex;
  flex-direction: column;
  gap: 20px;
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
  width: fit-content;
  padding: 0px 54px;
  margin-top: 10px;
  border-radius: 20px;
  border: 2px solid #FFF;
  background: #F68D2C;
}
.ms-btn:hover {
  background: #F38116;
}

.people {
  width: 100%;
  border-radius: 50px;
  background: #00AFA5;
}

/* media */
@media (max-width: 1199.99px) {
  .main__screen {
    flex-wrap: wrap;
    gap: 45px;
  }

  .ms-texts {
    gap: 15px;
  }
}
</style>