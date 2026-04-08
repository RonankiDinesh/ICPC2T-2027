<template>
  <div class="col-xl-8 col-md-12">
    <div class="row mt-2 mb-5 pb-3 mx-2">
      <div class="card card-body mb-5">

        <!-- Main Heading -->
        <h2 class="font-weight-bold mt-3">
          <strong>Advisory Board Members (Tentative)</strong>
        </h2>
        <hr class="red title-hr" />

        <!-- International Advisory Board -->
        <h3 class="mt-4"><strong>International Advisory Board Members</strong></h3>
        <hr class="red title-hr" />
        <p class="article">
          <span>Prof. Bikash Pal, Imperial College London</span><br />
          <span>Prof. Ayman El-Refaie, Marquette University, USA</span><br />
          <span>Prof. Sanjib Panda, National University of Singapore, Singapore</span><br />
          <span>Prof. Frede Blaabjerg, Aalborg University, Denmark</span><br />
          <span>Prof. Jih-Sheng (Jason) Lai, Virginia Tech, USA</span><br />
          <span>Prof. Akshay Rathore, National University of Singapore, Singapore</span><br />
          <span>Prof. Ramesh Bansal, University of Pretoria, South Africa</span><br />
          <span>Prof. Vinod Khadkikar, Khalifa University of Science & Technology, UAE</span><br />
          <span>Prof. Kashem Muttaqi, University of Wollongong, Australia</span><br />
          <span>Prof. Biplab Sikdar, National University of Singapore, Singapore</span><br />
          <span>Dr. Brij N. Singh, John Deere Inc, USA</span><br />
        </p>

        <!-- National Advisory Board -->
        <h3 class="mt-4"><strong>National Advisory Board Members</strong></h3>
        <hr class="red title-hr" />
        <p class="article">
          <span>Prof. Bijay Ketan Panigrahy, IIT Delhi</span><br />
          <span>Prof. Sukumar Mishra, IIT(ISM) Dhanbad</span><br />
          <span>Prof. Bidyadhar Subudhi, NIT Warangal</span><br />
          <span>Prof. Manisha Dubey, MANIT Bhopal</span><br />
          <span>Prof. Rajesh Kumar Nema, MANIT Bhopal</span><br />
          <span>Prof. Savita Nema, MANIT Bhopal</span><br />
          <span>Prof. Jyoti Singhi, MANIT Bhopal</span><br />
          <span>Prof. Ram Bilas Pachori, IIT Indore</span><br />
          <span>Prof. Kiran Kumar Pattanaik, IITM Gwalior</span><br />
          <span>Prof. Durgesh Kumar Mishra, SAIT Indore</span><br />
          <span>Prof. Sanjeev Singh, MANIT Bhopal</span><br />
        </p>

      </div>

      <div id="comments" class="comments-area"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Advisory_Committee",
};
</script>

<style scoped>
.article {
  line-height: 1.8;
  font-family: sans-serif;
}

h3 {
  font-weight: 600;
}

.title-hr {
  margin-bottom: 15px;
}
</style>