<template>
  <div>
    <h1 class="index-header">Welcome to the Organic Coffee Roasters Co.</h1>
    <div class="border-width"></div>
    <img
      src="../assets/companyLogo.png"
      alt="Company Logo"
      class="index-image"
    />
    <h2 class="company-slogan">Earth Makes The Best Taste</h2>
    <p class="mission-state">
      Introducing the pinnacle of coffee perfection: Earth Makes The Best Taste.
      Crafted from the finest beans sourced across the globe, our coffee
      embodies a symphony of flavors that tantalize the palate. Each cup tells a
      story of dedication, from the earth's embrace to the expert hands that
      roast and blend these exceptional beans. With every sip, indulge in a
      sensory adventure that transcends ordinary coffee, awakening your taste
      buds to a harmonious blend of richness and depth. Join us in celebrating a
      brew that stands as a testament to nature's finest offerings, promising an
      unparalleled experience that defines the essence of exceptional coffee.
    </p>
  </div>
</template>

<script>
export default {
  // You can add component-specific logic or data here if needed
};
</script>

<style scoped>
.index-header {
  text-align: center;
  width: auto;
  margin: 90px 90px 10px 90px;
  font-size: 40px;
}

.border-width {
  border: 1px solid rgba(235, 160, 89, 0.4);
  width: 50%;
  margin: 0 auto;
  margin-bottom: 80px;
}

.index-image {
  width: 50%;
  display: block;
  margin: 0 auto;
  border-radius: 50%;
  border: 2px solid #2b3036;
}

.company-slogan {
  text-align: center;
  font-size: 30px;
  font-weight: bold;
  margin: 50px;
}

.mission-state {
  width: 80%;
  text-align: center;
  margin: 0 auto;
  margin-bottom: 50px;
}
</style>
