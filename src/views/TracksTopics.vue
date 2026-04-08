<template>
  <div class="col-xl-8 col-md-12">
    <!-- Post -->
    <div class="row mt-2 mb-5 pb-3 mx-2">
      <!-- Card -->
      <div class="card card-body mb-5">
        
        <h2 class="font-weight-bold mt-3">
          <strong>Conference Tracks/Topics</strong>
        </h2>

        <hr class="title-hr" />

        <p>
          Papers are invited in the following areas of interest, but not limited to:
        </p>

        <!-- ✅ Updated Tracks List -->
        <ul class="tracks-list">
          <li><strong>T1:</strong> Power System Operation, Monitoring and Control</li>
          <li><strong>T2:</strong> Power System Protection, Relaying and Automation</li>
          <li><strong>T3:</strong> Power Electronics, Drives and Control Applications</li>
          <li><strong>T4:</strong> Renewable Energy Systems and Grid Integration</li>
          <li><strong>T5:</strong> Electricity Markets, Policy and Regulatory Frameworks</li>
          <li><strong>T6:</strong> Smart Grids, Data Analytics and Cyber Security</li>
          <li><strong>T7:</strong> Demand Side Management, Demand Response and Energy Efficiency</li>
          <li><strong>T8:</strong> Electric Vehicles, Charging Infrastructure and Vehicle-to-Grid (V2G)</li>
          <li><strong>T9:</strong> Grid Flexibility, Resilience and Reliability Enhancement</li>
          <li><strong>T10:</strong> High Voltage Engineering, Insulation and Power System Equipment</li>
          <li><strong>T11:</strong> Energy Storage Systems (BESS, Hydrogen Storage, Hybrid Storage)</li>
          <li><strong>T12:</strong> Microgrids, Nanogrids and Distributed Energy Resources (DERs)</li>
          <li><strong>T13:</strong> AI, ML and Digital Twins in Power Systems</li>
          <li><strong>T14:</strong> WAMS, PMU Applications and IoT in Power Systems</li>
          <li><strong>T15:</strong> Quantum Computing, Advanced Optimization and Next-Generation Power System Analytics</li>
        </ul>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TracksTopics",
};
</script>

<style scoped>
/* 🔥 Title line */
.title-hr {
  border: 2px solid #ffffff;
  width: 500px;
  margin-left: 0;
}

/* 🔥 Tracks List Styling */
.tracks-list {
  list-style: none;
  padding-left: 0;
}

.tracks-list li {
  background: #f5f9ff;
  margin-bottom: 10px;
  padding: 12px 15px;
  border-left: 4px solid #87acee;
  border-radius: 6px;
  transition: 0.3s;
  text-align: justify;
}

/* ✨ Hover effect */
.tracks-list li:hover {
  background: #e3efff;
  transform: translateX(5px);
}
</style>