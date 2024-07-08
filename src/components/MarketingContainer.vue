<template>
  <div class="diagonal-background">
    <div class="content">
      <h1>Why Should You?</h1>
      <ul>
        <li>USP 1</li>
        <li>USP 2</li>
        <li>USP 3</li>
      </ul>
      <div class="tips-container">
    <div class="icon">
      <img src="lightbulb.png" alt="Tips Icon">
    </div>
    <div class="tips-text">
      Tips: password must be at least 8 characters and contain at least 1 capital letter and 1 number
    </div>
  </div>
      <div class="trustpilot">
        <img src="trustpilot.png" alt="Trustpilot rating">
      </div>
    </div>
    <div class="image-container">
      <img src="person.png" alt="Person pointing" class="person-image">
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyComponent'
}
</script>

<style scoped>
.diagonal-background {
  background: linear-gradient(-20deg, #FFC100 0%, #FFC100 40%, #FFE6BE 36%);
  min-height: 100vh;
  padding: 20px;
  border-radius: 8px;
}

.tips-container {
  background-color: #fff;
  border: 1px solid #ffd79c;
  border-radius: 10px;
  padding: 15px 20px;
  display: flex;
  align-items: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.icon {
  margin-right: 10px;
}

.icon img {
  width: 24px;
  height: 24px;
}

.tips-text {
  font-size: 14px;
  color: #333;
}

.icon {
  margin-right: 10px;
}

.trustpilot {
  margin-top: 20px;
  text-align: left;
}

.image-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.person-image {
  max-width: 100%;
  height: auto;
}
</style>
