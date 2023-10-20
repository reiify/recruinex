<template>
  <section class="services">

    <div class="services__texts">
        <h2 class="services__title">Our <span>services</span></h2>
        <p class="services__info">
            We take pride in our
            expertise in the Ukrainian IT
            sector, allowing us to tap
            into the country's rich talent
            pool and connect businesses with
            highly skilled individuals who possess
            the right technical know-how,
            as well as the necessary
            soft skills to excel in their roles.
        </p>
    </div>
    <div class="services__advantages">
        <div class="services__advantages-content">
            <div class="services__advantages-transfer">
                <img src="../assets/recruitment.svg" alt="recruitment icon">
                <h3 class="services__advantages-title">IT recruitment in Ukraine</h3>
            </div>
            <div class="sat-texts">
                <p class="satt-info">
                    Recruitment of both technical and
                    non-technical specialists in IT.
                </p>
                <p class="satti-before">
                    full cycle of recruitment
                </p>
            </div>
        </div>
        <div class="services__advantages-content">
            <div class="services__advantages-transfer">
                <img src="../assets/interview.svg" alt="interview icon">
                <h3 class="services__advantages-title">Technical interview</h3>
            </div>
            <div class="sat-texts">
                <p class="satt-info">
                    We will provide a top-level
                    specialist to evaluate the candidate's
                    technical skills and help your
                    company make the best choice.
                </p>
            </div>
        </div>
        <div class="services__advantages-content">
            <div class="services__advantages-transfer">
                <img src="../assets/relocation.svg" alt="relocation icon">
                <h3 class="services__advantages-title">Relocation support</h3>
            </div>
            <div class="sat-texts">
                <p class="satt-info">
                    Relocation of technical specialists from
                    Ukraine to your worldwide offices.
                </p>
                <p class="satti-before">
                    visa
                </p>
                <p class="satti-before">
                    bureaucratic procedures
                </p>
                <p class="satti-before">
                    assistance with accommodation
                </p>
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
.services {
    display: flex;
    flex-direction: column;
    gap: 60px;
}

.services__title {
    font-family: Poppins;
    font-size: 70px;
    font-weight: 600;
    font-style: normal;
    line-height: 120px;
    color: #010B23;
}
.services__title span {
    color: #2F0899;
}

.services__info {
    font-family: Poppins;
    font-size: 24px;
    font-weight: 300;
    font-style: normal;
    line-height: 34px;
    color: #010B23;
}

.services__advantages {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 40px;
}

.services__advantages-content {
    /* box styles */
    border-radius: 50px;
    background: #FFF;
    box-shadow: 0px 2px 4px 0px rgba(54, 54, 54, 0.15);

    /* box content styles */
    display: flex;
    flex-direction: column;
    gap: 16px;
    padding: 25px 20px;
}

.services__advantages-transfer {
    display: flex;
    align-items: center;
    gap: 22px;
}

.sat-texts {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
}

.satt-info {
    font-family: Poppins;
    font-size: 20px;
    font-weight: 300;
    font-style: normal;
    line-height: normal;
    color: #010B23;
}

.satti-before {
    font-family: Poppins;
    font-size: 20px;
    font-weight: 300;
    font-style: normal;
    line-height: normal;
    color: #010B23;
    transform: translateX(22px);
}
.satti-before::before {
    content: '';
    position: absolute;
    transform:translateY(50%);
    left: -22px;
    width: 15px;
    height: 15px;
    border-radius: 100%;
    background-color: #F68D2C;
}
</style>