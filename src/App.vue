<template>
  <div>
    <FinalRecovery/>
   <PageForm/>
  </div>

</template>

<script>
// import CreateForm from './components/Login/CreateForm.vue';
// import RegForm from './components/Regestration/RegForm.vue';
 import PageForm from './components/MainPage/PageForm.vue';
// import Recovery from './components/Login/RecoveryForm.vue';
// import FinalRecovery from './components/Login/FinalRecovery.vue'
// import RecoveryText from './components/Login/RecoveryText.vue'
export default {
  name: "app",
  components: {
  //  CreateForm,
  //  RegForm,
   PageForm,
  // Recovery
 // RecoveryText
//  FinalRecovery
  },
};
</script>

<style>
@media (min-width: 552px) {
  .modal-content {
    min-width: 500px;
    margin-right: 10%;
  }
}
@media (min-width: 458px) {
  .modal-content {
    min-width: 360px;
    margin-right: 10%;
  }
}
</style>
