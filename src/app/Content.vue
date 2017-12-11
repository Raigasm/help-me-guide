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
            <div class="box">I’m “Disabled”, not “‘differently-abled”!</div>
<div class="box">I’m a <em>"person with a disability”</em> not a <em>“‘disabled person”</em></div>
<div class="box">I don’t make a big deal out of my disability, so you shouldn’t either!</div>
<div class="box">Please don’t pet, feed or otherwise distract my service animal without permission!</div>
<div class="box">Not everyone with a disability wishes to discuss it or its limitations. - Don’t probe unnecessarily.</div>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <h1 class="subtitle is-3">Can you help me...</h1>
      <div class="columns">
      <div class="column">
        <div class="notification is-danger">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-deaf fa-5x"></i>
          </span>
          <h2 class="title is-2">Listen?</h2><p class="subtitle is-4">Helping Students with Deafness</p>
          <div class="content">
            <div class="box">Need attention? Tap on my shoulder or wave your hand.</div>
<div class="box">Can’t sign? Write notes.</div>
<div class="box">Look directly at me while speaking.  Don’t obscure your mouth.</div>
<div class="box">Talk directly to me, not my interpreter.</div>
<div class="box">Speak in a normal speed and tone.</div>
<div class="box">Please don’t stand in front of a light source!</div>
<div class="box">Please check I understand, even if I’m nodding my head.</div>
<div class="box">Try to be expressive in your body language, gestures and facial expressions.</div>
<div class="box">Do not attempted to finish my sentences or words.</div>
          </div>
          </div>
      </div>
      <div class="column">
        <div class="notification is-success">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-eye-slash fa-5x"></i>
          </span>
          <h2 class="title is-2">See?</h2><p class="subtitle is-4">Helping Students with Impaired Vision</p>
          <div class="content">
            <div class="box">Feel free to use words like “see” and “look”!</div>
<div class="box">Please give me very explicit and specific directions.</div>
<div class="box">I might appreciate your arm or elbow when you’re leading me.</div>
<div class="box">It’s great when you help me find the back of a chair when I’m sitting down.</div>
<div class="box">Please be as descriptive as you can!</div>
<div class="box">Thanks for keeping the environment safe by removing every cones/signs and other obstacles!</div>
          </div>
          </div>
      </div>
      <div class="column">
        <div class="notification is-warning">
          <span class="icon is-large is-pulled-right icon-padding">
            <i class="fa fa-wheelchair-alt fa-5x"></i>
          </span>
          <h2 class="title is-2">Move Around?</h2><p class="subtitle is-4">Helping Students who use Wheelchairs</p>
          <div class="content">
            <div class="box">If we’re having a long conversation, please bring yourself to my eye-level.</div>
<div class="box">My chair is part of my personal space; hands off!</div>
<div class="box">Ask me before giving assistance and please take “No” for an answer.</div>
<div class="box">Help me look out for steps or insufficiently wide doors.</div>
<div class="box">We use words like “run” or “walk” too!</div>
<div class="box">Please speak to me, not my attendant.</div>
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
