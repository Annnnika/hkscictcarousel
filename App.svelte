<script>
  import Button from "./Button.svelte";
  import Carousel from "./Carousel.svelte";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
  .slide-content img {
    height: 50vh;
  }
</style>

<main>
	<h1>Hello CodeSandbox</h1>
	<h2>Start editing to see some magic happen!</h2>
	<Button />
  <br>
  <br>
  <Carousel perPage="1">
    <div class="slide-content">
      <img alt="1" src="https://kb.rspca.org.au/wp-content/uploads/2018/11/golder-retriever-puppy.jpeg">
    </div>
    <div class="slide-content">
      <img alt="2" src="https://www.guidedogs.org/wp-content/uploads/2019/11/website-donate-mobile.jpg">
    </div>
    <div class="slide-content">
      <img alt="3" src="https://cdn.cnn.com/cnnnext/dam/assets/201030094143-stock-rhodesian-ridgeback-super-tease.jpg">
    </div>
    <div class="slide-content">
      <img alt="4" src= "https://live-production.wcms.abc-cdn.net.au/52bb7802a388c3c53cc78bbdd181fbc7?impolicy=wcms_crop_resize&cropH=838&cropW=1489&xPos=0&yPos=120&width=862&height=485">
    </div>
  </Carousel>
</main>