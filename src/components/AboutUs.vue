<template>
  <section class="about-us">
    <h2 class="au-h2">About us</h2>

    <div class="au-content">
        <div class="au-txt">
            <p>
                Our young recruitment agency offering
                a fresh and innovative approach
                to bridging the gap between
                employers and IT specialists in Ukraine.
            </p>
            <p>
                We believe that building strong
                relationships is the foundation of
                successful recruitment. We foster trust,
                transparency, and open communication with
                both clients and candidates throughout
                the entire process. 
            </p>
        </div>

        <div class="advantages">
            <div class="adv-container">
                <div class="adv-content">
                    <h2 class="advantages-h2">1600</h2>
                    <p class="advantages-p">Filled vacancies</p>
                </div>
                <div class="adv-content">
                    <h2 class="advantages-h2">13 000</h2>
                    <p class="advantages-p">Developers in our database</p>
                </div>
            </div>

            <div class="adv-container">
                <div class="adv-content">
                    <h2 class="advantages-h2">1500</h2>
                    <p class="advantages-p">Trained specialists</p>
                </div>
                <div class="adv-content">
                    <h2 class="advantages-h2">5</h2>
                    <p class="advantages-p">Years in IT recruitment</p>
                </div>
            </div>
        </div>
        
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.about-us {
    padding: 50px 120px 80px 40px;
    border-radius: 50px;
    background: #2F0899;
}

.au-h2 {
    font-family: Poppins;
    font-size: 70px;
    font-style: normal;
    font-weight: 600;
    line-height: 120px;
    color: #FFF;
}

.au-content {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
}

.au-txt {
    /* font styles */
    font-family: Poppins;
    font-style: normal;
    font-size: 24px;
    font-weight: 300;
    line-height: 34px;
    color: #FFF;

    /* container styles */
    display: flex;
    flex-direction: column;
    row-gap: 25px;
    max-width: 42vw;
}
.au-txt p:nth-child(2) { /* второй параграф */
    max-width: 37vw;
}

.advantages {
    display: flex;
    flex-wrap: wrap;
    column-gap: 64px;
}
.adv-container {
    display: flex;
    flex-direction: column;
    row-gap: 40px;
}
.adv-content {
    display: flex;
    flex-direction: column;
    row-gap: 20px;
}

.advantages-h2 {
    font-family: Poppins;
    font-style: normal;
    font-weight: 600;
    font-size: 70px;
    line-height: 34px;
    color: #FFF;
}
.advantages-p {
    font-family: Poppins;
    font-size: 24px;
    font-style: normal;
    font-weight: 300;
    color: #FFF;
    width: 145px;
}
</style>