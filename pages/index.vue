<template>
  <section>
    <header class="home--header">
      <div class="cto--container container px-4">
        <div class="cto--left">
          <h3 class="text-primary">NFTs TICKETING <br>
            <span class="text-base-content">MANAGEMENT SOLUTION</span></h3>
          <p class="text-base-content/80">
            Using our developer toolkits on NEAR, create, Buy and Sell your own NFT Ticket in marketplace. Let's begin creating your collections right away.
          </p>
          <nif-btn :button-type="{ normLink: false }" url="/events"  class="px-12 mr-5 mt-10">
            <i class="isax text-xl isax-designtools mr-2" />
            Explore
          </nif-btn>
          <nif-btn :button-type="{ normLink: false }" url="/mint" class="px-12 mt-10">
            <i class="isax text-xl isax-pen-add mr-2" />
            Create
          </nif-btn>
          <div class="avatar--group mt-10 flex items-center">
            <div class="avatar-group mr-5 -space-x-2">
              <div class="avatar">
                <div class="w-10">
                  <img src="https://placeimg.com/192/192/people" />
                </div>
              </div>
              <div class="avatar">
                <div class="w-10">
                  <img src="https://placeimg.com/192/192/people" />
                </div>
              </div>
              <div class="avatar">
                <div class="w-10">
                  <img src="https://placeimg.com/192/192/people" />
                </div>
              </div>
              <div class="avatar placeholder">
                <div class="w-10 bg-accent-focus text-black">
                  <span class="font-bold">2M</span>
                </div>
              </div>
            </div>
            <div class="">
              <span class="font-extrabold">
                2M+ <br>NFT TICKETS
              </span>
            </div>
          </div>
        </div>
        <div class="cto--right">
          <div class="card--layers">
            <div class="top--ly-card">
              <NifCard class="w-1/2" />
            </div>
            <div class="bottom--ly-card grid grid-cols-2 gap-10">
              <NifCard />
              <NifCard />
            </div>
          </div>
        </div>
      </div>
    </header>
    <main>
      <img class="bg--svg" src="/bg.svg" />
      <section class="home--body">
        <div class="cto--container container px-4 min-h-screen">
          <div class="cat--title flex justify-between items-center">
            <h4 class="text-2xl">Top Stores</h4>
            <nif-btn>
              View All
              <img class="ml-2" src="/arrow-right.svg" alt="">
            </nif-btn>
          </div>
          <top-stores-grid />
          <div class="cat--title mt-20 flex justify-between items-center">
            <h4 class="text-2xl">Browse Event Collections</h4>
            <nif-btn>
              View All
              <img class="ml-2" src="/arrow-right.svg" alt="">
            </nif-btn>
          </div>
          <event-collection-grid />
          <div class="cat--title mt-20 flex justify-between items-center">
            <h4 class="text-2xl">Popular Collections</h4>
            <nif-btn>
              View All
              <img class="ml-2" src="/arrow-right.svg" alt="">
            </nif-btn>
          </div>
          <collection-grid />
          <div class="cat--title mt-20 flex justify-between items-center">
            <h4 class="text-2xl">Trending Now</h4>
            <div class="cat--grid">
              <select class="select w-full">
                <option selected>Most Popular</option>
                <option>Trending</option>
                <option>Downloads</option>
              </select>
              <select class="select w-full">
                <option selected>Category</option>
                <option>Homer</option>
                <option>Marge</option>
              </select>
              <select class="select w-full">
                <option selected>Last 7 days</option>
                <option>Homer</option>
                <option>Marge</option>
              </select>
              <select class="select w-full">
                <option selected>Price Range</option>
                <option>Homer</option>
                <option>Marge</option>
              </select>
            </div>
          </div>
          <event-card-grid />
        </div>
      </section>
    </main>
    <bottom-c-t-o />
  </section>
</template>
<script>
export default {
  colorMode: 'dark',
  mounted() {
    console.log('colormode', this)
  }
}
</script>
