<template>
  <div id="app">
    <div class="np-icons">
      <div class="np-icon-ib">
        <FacebookIcon :svgColor="facebookColor" />
      </div>
      <div class="np-icon-ib">
        <TwitterIcon :svgColor="twitterColor" />
      </div>
      <div class="np-icon-ib">
        <InstagramIcon :svgColor="instagramColor" />
      </div>
      <div class="np-icon-ib">
        <BehanceIcon :svgColor="behanceColor" />
      </div>
    </div>
    <div class="np-icon-color-picker">
      <label for="favcolor">Select facebook color</label>
      <input
        v-model="facebookColor"
        type="color"
        id="favcolor"
        name="favcolor"
        value="#4267B2"
      />
    </div>
    <div class="np-icon-color-picker">
      <label for="favcolor">Select twitter color</label>
      <input
        v-model="twitterColor"
        type="color"
        id="favcolor"
        name="favcolor"
        value="#1DA1F2"
      />
    </div>
    <div class="np-icon-color-picker">
      <label for="favcolor">Select instagram color</label>
      <input
        v-model="instagramColor"
        type="color"
        id="favcolor"
        name="favcolor"
        value="#f000ff"
      />
    </div>
    <div class="np-icon-color-picker">
      <label for="favcolor">Select behance color</label>
      <input
        v-model="behanceColor"
        type="color"
        id="favcolor"
        name="favcolor"
        value="#053eff"
      />
    </div>
    <div class="np-credits">www.nightprogrammer.com</div>
  </div>
</template>
<script>
import FacebookIcon from "./../assets/facebook";
import TwitterIcon from "./../assets/twitter";
import InstagramIcon from "./../assets/instagram";
import BehanceIcon from "./../assets/behance";

export default {
  name: "App",
  data() {
    return {
      facebookColor: "#4267B2",
      twitterColor: "#1DA1F2",
      instagramColor: "#f000ff",
      behanceColor: "#053eff",
    };
  },
  components: {
    FacebookIcon,
    TwitterIcon,
    InstagramIcon,
    BehanceIcon,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.np-icons {
  padding-bottom: 12px;
}
.np-icon-ib {
  display: inline-block;
  padding-right: 12px;
}
.np-credits {
  font-size: 12px;
  padding-top: 14px;
}
</style>
