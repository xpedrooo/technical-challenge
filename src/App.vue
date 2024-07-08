<template>
  <div id="app">
    <div class="container">
      <StepsIndicator />
      <div class="main-content">
        <FormContainer />
        <MarketingContainer />
      </div>
      <PhoneNumberComponent />
    </div>
  </div>
</template>

<script>
import StepsIndicator from './components/StepsIndicator.vue';
import FormContainer from './components/FormContainer.vue';
import MarketingContainer from './components/MarketingContainer.vue';
import PhoneNumberComponent from './components/PhoneNumberComponent.vue';

export default {
  name: 'App',
  components: {
    StepsIndicator,
    FormContainer,
    MarketingContainer,
    PhoneNumberComponent
  }
};
</script>

<style>
.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.main-content {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

@media (max-width: 768px) {
  .main-content {
    flex-direction: column;
  }

  .container {
    width: auto;
  }
}
</style>
