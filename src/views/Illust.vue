
  <template>
  <h1>Illust</h1>
  <p>主に好きな人たちの似顔絵を描いています</p>
  <div class="container">
    <div class="slider">
      <carousel>
        <slide v-for="slide in 3" :key="slide">
          <img v-bind:src="require(`../assets/illust/` + slide + `.png`)" />
        </slide>
        <template #addons>
          <navigation />
        </template>
      </carousel>
    </div>
    <div class="section__request">
      <h2>■Request</h2>
      <p>
        <a
          href="
https://narilyn.base.shop"
          >Narilyn</a
        >似顔絵のデータ販売をはじめてみました！
      </p>
      <p>
        <a
          href="
https://instagram.com/yzuesm_"
          >Instagram</a
        >ここにもイラストを載せています
      </p>
    </div>
  </div>
</template>
<style scoped>
.slider {
  margin: 150px;
}
</style>
<script>
import "vue3-carousel/dist/carousel.css";
import { Carousel, Navigation, Slide } from "vue3-carousel";

export default {
  name: "App",

  components: {
    Carousel,
    Slide,
    Navigation,
  },
};
</script>
