<template>
  <section class="tickets--body">
    <header
      class="page--header tickets flex flex-col justify-center container items-center"
    >
      <div class="container flex flex-col justify-center">
        <img
          src="https://placeimg.com/400/225/arch"
          class="ticket--img"
          alt="Ticket Image"
        />
      </div>
    </header>
    <main>
      <section class="ticket--details mt-12">
        <div class="container">
          <div class="ticket--data sticky top-0">
            <div class="card">
              <div class="card-body">
                <h2 class="card-title">The Big Spring</h2>
                <div class="divider my-3"></div>
                <div class="form-control w-full">
                  <label class="label px-0">
                    <span class="label-text">Price</span>
                    <span class="label-text-alt">2 / 24 Available</span>
                  </label>
                  <div class="near--data flex font-bold items-center">
                    <i class="cf cf-near mr-2"></i>
                    2.29 NEAR ($ 6,227.15)
                  </div>
                </div>
                <p>Ends In:</p>
                <div
                  class="uk-grid-small uk-child-width-auto sale--countdown"
                  uk-grid
                  uk-countdown="date: 2022-10-17T19:37:28+00:00"
                >
                  <div>
                    <div class="uk-countdown-number uk-countdown-days"></div>
                    <div
                      class="uk-countdown-label uk-margin-small uk-text-center uk-visible@s"
                    >
                      Days
                    </div>
                  </div>
                  <div>
                    <div class="uk-countdown-number uk-countdown-hours"></div>
                    <div
                      class="uk-countdown-label uk-margin-small uk-text-center uk-visible@s"
                    >
                      Hours
                    </div>
                  </div>
                  <div>
                    <div class="uk-countdown-number uk-countdown-minutes"></div>
                    <div
                      class="uk-countdown-label uk-margin-small uk-text-center uk-visible@s"
                    >
                      Minutes
                    </div>
                  </div>
                  <div>
                    <div class="uk-countdown-number uk-countdown-seconds"></div>
                    <div
                      class="uk-countdown-label uk-margin-small uk-text-center uk-visible@s"
                    >
                      Seconds
                    </div>
                  </div>
                </div>
                <div class="form-control mt-2 w-full relative">
                  <b-field label="Quantity" class="primary-btns relative">
                    <b-numberinput :placeholder="2"></b-numberinput>
                  </b-field>
                </div>
                <div class="w-full flex justify-center mt-12">
                  <nif-btn>Buy with NEAR </nif-btn>
                </div>
              </div>
            </div>
          </div>
          <div class="ticket--data sticky top-0">
            <div class="card">
              <div class="card-body">
                <b-tabs class="block w-full">
                  <b-tab-item label="About">
                    <div class="form-control w-full">
                      <label class="label">
                        <span class="label-text">Ticket Name</span>
                      </label>
                      <input
                        type="text"
                        disabled
                        value="The Big Spring"
                        class="input bg-base-100/10 w-full"
                      />
                    </div>
                    <div class="form-control mt-2 w-full">
                      <label class="label">
                        <span class="label-text">Ticket Description</span>
                      </label>
                      <textarea
                        disabled
                        rows="3"
                        class="textarea bg-base-100/10"
                      >
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          </textarea
                      >
                    </div>
                    <div class="grid grid-cols-2 gap-4">
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Store</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="Near.Niftiqet.testnet"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Created By</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="Obani.testnet"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Owner</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="Obani.testnet"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Minted Ticket</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="24"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Listed Nft Tickets</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="1"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Token ID</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="#2"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Type</span>
                        </label>
                        <input
                          type="text"
                          disabled
                          value="Image"
                          class="input bg-base-100/10 w-full"
                        />
                      </div>
                      <div class="form-control mt-2 w-full">
                        <label class="label">
                          <span class="label-text">Price Category</span>
                        </label>
                        <select class="select w-full" disabled>
                          <option disabled selected>VIP</option>
                          <option>Homer</option>
                        </select>
                      </div>
                    </div>
                    <h3 class="mt-5">Splits</h3>
                    <div class="divider my-3"></div>
                    <div class="info--grid">
                      <div class="royalties">
                        <div class="info--stuf">
                          <div class="inf--circ"></div>
                          <span>Forever Royalties</span>
                          <div class="inf--size">0%</div>
                        </div>
                        <div class="line--rule"></div>
                      </div>
                      <div class="split">
                        <div class="info--stuf">
                          <div class="inf--circ"></div>
                          <span>Split Values</span>
                          <div class="inf--size">0%</div>
                        </div>
                        <div class="line--rule"></div>
                      </div>
                      <div class="market">
                        <div class="info--stuf">
                          <div class="inf--circ"></div>
                          <span>Market</span>
                          <div class="inf--size">0%</div>
                        </div>
                        <div class="line--rule"></div>
                      </div>
                    </div>
                  </b-tab-item>
                  <b-tab-item label="Details">
                    <div class="form-control w-full">
                      <label class="label">
                        <span class="label-text">Transation ID</span>
                      </label>
                      <input
                        type="text"
                        disabled
                        value="0x91a6dF52aA476378198422C922178560a5400E43"
                        class="input bg-base-100/10 w-full"
                      />
                    </div>
                    <div class="form-control mt-2 w-full">
                      <label class="label">
                        <span class="label-text">Ticket ID</span>
                      </label>
                      <input
                        type="text"
                        disabled
                        value="ip7TBJuBu5syNihxnkwumVFGxthSx7JxdJFHCul74PY:ehapa.Niftiqet2.testnet"
                        class="input bg-base-100/10 w-full"
                      />
                    </div>
                    <div class="form-control mt-2 w-full">
                      <label class="label">
                        <span class="label-text">Contract</span>
                      </label>
                      <input
                        type="text"
                        disabled
                        value="Obani.testnet"
                        class="input bg-base-100/10 w-full"
                      />
                    </div>
                    <div class="form-control mt-2 w-full">
                      <label class="label">
                        <span class="label-text">Storage Gateway</span>
                      </label>
                      <input
                        type="text"
                        disabled
                        value="Obani.testnet"
                        class="input bg-base-100/10 w-full"
                      />
                    </div>
                  </b-tab-item>
                </b-tabs>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="more--events">
        <div class="cto--container container px-4 my-12">
          <event-card />
          <event-card />
          <event-card />
        </div>
      </section>
    </main>
  </section>
</template>

<script>
export default {
  name: 'index',
}
</script>

<style lang="scss">
.tickets--body {
  padding-top: 120px;
  .page--header.tickets {
    &:before {
      background: #0e333f;
      border-radius: 12px;
    }
    .ticket--img {
      border-radius: 16px;
      height: 300px;
      width: 300px;
      object-fit: cover;
    }
  }
}
.ticket--details {
  .container {
    display: grid;
    grid-template-columns: 1.3fr 2.3fr;
    grid-gap: 20px;
  }
}
.more--events {
  .container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
  }
}
.tabs li.is-active a {
  border-bottom-color: hsl(var(--p)) !important;
  color: hsl(var(--p)) !important;
}
.info--grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
  & > div {
    justify-content: center;
    align-items: center;
    flex-direction: column;
    span {
      flex-basis: calc(100% - 40px);
    }
    .line--rule {
      height: 10px;
      border-radius: 10px;
      width: 100%;
      margin-top: 10px;
    }
    .inf--size {
      background: rgba(75, 75, 75, 0.67);
      padding: 5px 8px;
      margin-top: 10px;
      border-radius: 10px;
    }
    &.royalties {
      .inf--circ {
        background: #ed215e;
      }
      .line--rule {
        background: #ed215e;
      }
    }
    &.split {
      .inf--circ {
        background: #67d2e1;
      }
      .line--rule {
        background: #67d2e1;
      }
    }
    &.market {
      .inf--circ {
        background: #bfc1be;
      }
      .line--rule {
        background: #bfc1be;
      }
    }
    .info--stuf {
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8rem;
      padding: 20px;
      background: hsla(var(--b1) / 0.3);
      border-radius: 12px;
      flex-wrap: wrap;
      .inf--circ {
        width: 20px;
        height: 20px;
        border-radius: 50%;
        margin-right: 20px;
      }
    }
  }
}
.sale--countdown {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 20px;

  & > div {
    .uk-countdown-number {
      background: hsla(var(--p) / 0.5);
      padding: 1rem;
      font-size: unset;
      border-radius: 12px;
      span {
        color: #fafafa;
        font-size: 3rem;
      }
    }
  }
}
.control.plus {
}
</style>
