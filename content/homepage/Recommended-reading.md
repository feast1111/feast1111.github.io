---
title: "Recommended reading"
weight: 99
header_menu: true
---
<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
}

.grid-item {
  display: flex;
  flex-direction: column;
}

.grid-item h2 {
  margin-bottom: auto; /* Pushes everything else to the bottom */
}

.grid-item img {
  width: 100%;
  align-self: start; /* Aligns the image to the top of the flex item */
  margin-top: auto; /* Ensures the image is pushed to the bottom of the flex container if there's space */
}
</style>

<div class="grid-container">
  <div class="grid-item">
    <h2>1. Why We Get Sick: T
he Hidden Epidemic at the Root of Most Chronic Disease--and How to Fight It </h2>
    <img src="../images/Whyweget.jpg" alt="">
  </div>
  <div class="grid-item">
    <h2>2. Wheat Belly (Revised and Expanded Edition): Lose the Wheat, Lose the Weight, and Find Your Path Back to Health</h2>
    <img src="../images/Wheatbelly.jpg" alt="">
  </div>
  <!-- Additional items here -->
</div>