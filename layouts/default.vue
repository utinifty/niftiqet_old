<template>
  <div>
    <nav-bar />
    <Nuxt />
    <nif-footer />
  </div>
</template>

<script>
import { useStore } from "@/store";

export default {
  name: 'DefaultLayout',
  setup () {
    const store = useStore()

    return { store }
  },
  async mounted () {
    await this.store.setupWallet()
  }
}
</script>
<style lang="scss">
.bg--svg {
  position: absolute;
  top: 0;
  right: 0;
  filter: contrast(80.1) blur(.1px) brightness(60%);
  //background: hsl(var(--b2)) url(/bg.png);
  width: 50%;
  height: auto;
  //opacity: .2;
  object-fit: cover;
  object-position: right top;
  opacity: .7;
}
.home--header {
  min-height: 100vh;
  position: relative;
  padding: 50px 0;
  & > * {
    position: relative;
    z-index: 2;
    &.sticky {
      z-index: 3;
    }
  }
  .cto--container {
    min-height: calc(100vh - 6rem);
    width: 100%;
    display: flex;
    align-items: center;
    .cto--left {
      width: 50%;
      padding-right: 30px;
      h3 {
        font-size: 2.3rem;
        font-weight: 700;
        margin-bottom: 1.5rem;
      }
      p {
        font-size: 1.3rem;
      }
    }
    .cto--right {
      width: 50%;
      padding-left: 30px;
      height: 100%;
      .top--ly-card {
        display: flex;
        justify-content: center;
        position: relative;
        z-index: 2;
      }
      .bottom--ly-card {
        margin-top: -75px;
        position: relative;
      }
    }
  }
}
</style>
