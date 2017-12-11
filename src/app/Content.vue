<template>
  <div class="section">
    <div class="columns">
      <div class="column is-one-half-tablet">
        <div class="box">
          <div class="icon icon-padding is-large is-pulled-left">
            <i class="fa fa-info fa-5x"></i>
          </div>
          <h2 class="title is-2 heading-padding-top">Welcome!</h2><p class="subtitle is-4">Thanks for taking the time to read up on accessibility.</p>
          <ul>
            <li>University applications is a stressful time period, whether you're disabled or not!</li>
            <li>As a tour guide, you can take a lot of this stress out, even if you've never dealt with someone with a disability before.</li>
            <li>Be different, be prepared! Disabled students have shared these tips with us to help you introduce them to your University.</li>
          </ul>
        </div>
      </div>
      <div class="column is-one-half-tablet">
        <div class="notification is-info">
          <span class="icon is-large is-pulled-right icon-padding">
              <i class="fa fa-home fa-5x"></i>
          </span>
          <h2 class="title is-3">The Small Things</h2><p class="subtitle is-5">Etiquette and Language can make a big difference</p>
          <div class="content">
            <tip></tip>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <h1 class="subtitle is-3">You can help me...</h1>
      <div class="columns">
      <div class="column">
        <div class="notification is-danger">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-deaf fa-5x"></i>
          </span>
          <h2 class="title is-2">Listen</h2><p class="subtitle is-4">Helping Students with Deafness</p>
          <div class="content">
            <tip></tip>
          </div>
          </div>
      </div>
      <div class="column">
        <div class="notification is-success">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-eye-slash fa-5x"></i>
          </span>
          <h2 class="title is-2">See</h2><p class="subtitle is-4">Helping Students with Impaired Vision</p>
          <div class="content">
            <tip></tip>
          </div>
          </div>
      </div>
      <div class="column">
        <div class="notification is-warning">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-wheelchair-alt fa-5x"></i>
          </span>
          <h2 class="title is-2">Move</h2><p class="subtitle is-4">Helping Students who use Wheelchairs</p>
          <div class="content">
            <tip></tip>
          </div>
          </div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
import Tip from './tip.vue';
export default {
  name: "Wish U the Best",
  data() {
    return {
      hello: "i'd wish you the best but you already had it"
    };
  },
  components: {
    Tip
  }
};
</script>
