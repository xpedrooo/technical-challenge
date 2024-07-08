<template>
  <div class="steps-indicator">
    <div class="step active">1</div>
    <div class="step">2</div>
  </div>
</template>

<script>
export default {
  name: 'StepsIndicator'
};
</script>

<style>
.steps-indicator {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.step {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background-color: #ddd;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
}

.step.active {
  background-color: #007bff;
  color: white;
}
</style>
