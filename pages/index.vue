<template>
  <div class>
    <div class="landingpage landingpage__image">
      <div>
        <h1 class="text-white text-3xl font-bold text-center">Hi, I'm Faris.</h1>
        <!-- <img src="~/assets/img/sketch.png" alt=""> -->
      </div>
    </div>
    <section id="section2">
      <div class="flex flex-1 m-4">
        <div id="left">
          <div class="flex">
            <div class="card-black">
              Skills
            </div>
            <div>
              <div class="card-black">
                Logos
              </div>
              <div class="card-black">
                More about me
              </div>
            </div>
          </div>
          <div class="card-black">
            <div>Experiences</div>
          </div>
        </div>
        <div id="right">
          <div class="card-black">
            <h2>Hello</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A reprehenderit libero in quos. Ab placeat esse omnis eaque ea fuga modi. Similique, doloremque! Cupiditate omnis eum, harum est quibusdam officiis!</p>
          </div>
          <div class="card-black mt-3">
              <div></div>
              <div></div>
              <div></div>
              <h2>Projects</h2>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style>
.landingpage{
    padding: 20rem 2.25em !important;
    background-position: center;
    background-size: cover;
    width: 100%;
}
.landingpage__image{
  background-image: url("~/assets/img/bg-main.png");
}
.card-black{
  @apply p-8 border-4 border-black rounded-3xl m-4;
}

</style>
