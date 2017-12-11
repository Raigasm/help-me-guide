<template>
  <div class="help-me-guide-root">
    <help-me-header></help-me-header>
    <help-me-content></help-me-content>
    <help-me-footer></help-me-footer>
  </div>
</template>

<script>
import HelpMeHeader from './Header.vue';
import HelpMeFooter from './Footer.vue';
import HelpMeContent from './Content.vue';

export default {
  name: "Wish U the Best",
  data() {
    return {
      hello: "i'd wish you the best but you already had it"
    };
  },
  components: {
    HelpMeHeader,
    HelpMeFooter,
    HelpMeContent
  }
};
</script>
