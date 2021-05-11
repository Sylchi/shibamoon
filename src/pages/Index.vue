<template>
  <q-page style="background: linear-gradient(45deg, #050a14, #132e4e 60% 80%, #050a14)">
    <Header />
    <section class="text-center content q-py-lg relative-position font-14" style="z-index: 1">
      <div style="z-index: 10">
        <p class="text-gradient font-25 q-mt-lg">Meme tokens are the new era of fair launched projects.</p>
        <p class="text-gradient font-10">This vibrant ecosystem is growing every day by huge numbers of believers. No VC. No rich man game.</p>
        <p class="text-gradient">Everybody can join shibamoon!</p>
        <p class="text-gradient">Shibamoon - Shimo 1000 trillion initial supply, 500 trillion sent to BSC-Vitalik</p>
        <p class="text-gradient">Set your slippage high because this token burns!</p>
        <p class="text-gradient">4% to liquidity / 4% to holders</p>
        <p class="text-gradient">Absolutely fair launch, any raised BNB goes into pancakeswap LP and will be locked for 101 years in <a href="https://cryptexlock.me/#team" target="_blank">https://cryptexlock.me/#team</a></p>
        <q-btn color="primary" class="q-mt-md" padding="15px 30px">
          <div class="text-gradient">Read more</div>
        </q-btn>
      </div>
      <div class="absolute fit" style="top: 0; z-index: -1; opacity: 0.2; user-select: none">
        <img src="/shiba_logo.png" alt="" style="height: 90%; width: auto; filter: brightness(0.5)">
      </div>
    </section>
    <div style="background: linear-gradient(90deg, transparent, #01f8de, transparent); max-width: 600px; height: 2px" class="q-mx-auto q-mt-xl" />
    <section class="content q-py-xl" id="ecosystem">
      <div class="text-center text-gradient font-30">
        SHIMO - Ecosystem
      </div>
      <div style="border: 1px solid #87ffff; max-width: 1000px" class="q-mt-md q-mx-auto">
        <div style="border: 7px solid #3684b4; background: #051120; line-height: 1.6" class="text-secondary text-uppercase q-px-md q-pt-md font-12 text-center">
          <p>
            Shimo is an experiment in the decentralized community building of string defi apes. Shimo token is our initial token and a bridge to a broader eco-system. It is first cryptocurrency token combining the best of shiba and safemoon.
          </p>
          <p>
            With forever locked liquidity and the tokenomics that will increase liquidity over time, it will outpace any other meme coin.
          </p>
        </div>
      </div>
    </section>
    <section id="buy" class="q-py-xl text-center content">
      <div class="text-center text-gradient font-30">
        How to buy
      </div>
      <div style="background: linear-gradient(90deg, transparent, #01f8de, transparent); max-width: 600px; height: 2px" class="q-mx-auto" />
      <p class="text-gradient q-mt-lg font-14">The only place to buy and sell shimo safely is on pancake swap. You can find links below!</p>
      <div class="row items-center text-center justify-center q-gutter-lg q-mt-md">
        <a href="" target="_blank"><img src="/pcswap.png" alt="" height="70"></a>
        <a href="" target="_blank"><img src="/shiba_logo.png" alt="" height="70"></a>       
      </div>
      <p class="text-gradient font-14 q-mt-md">Other dexs will follow. One day, shimo will also enter ethereum. But right now, vitalik please fix it.</p>
    </section>
    <section id="community" class="text-center flex flex-center" style="min-height: 800px;background-image: url(/moon.png); background-size: cover; background-repeat: no-repeat">
      <div class="content">
        <div class="text-center text-gradient font-30">
          Community
        </div>
        <div style="background: linear-gradient(90deg, transparent, #01f8de, transparent); max-width: 600px; height: 2px" class="q-mx-auto" />
        <p class="text-gradient font-20 q-mt-xl">Shibamoon is community, first.</p>
        <p class="text-gradient font-14 q-mt-lg">Entirely self generated and individuals who have come together - for a purpose - and to realise an impact for the crypto world.</p>
      </div>
    </section>
    <footer style="background: #061f3c;" class="q-py-lg">
      <div class="row content justify-around">
        <div style="max-width: 300px">
          <div class="text-gradient font-20">Shibamoon</div>
          <p class="text-white">The future of fair launced, community led capital controlled projects. Its Us vs the VCs</p>
          <q-btn color="primary" class="q-mt-md" padding="15px 30px">
            <div class="text-gradient">Read more</div>
          </q-btn>
        </div>
        <div class="text-white">
          <div style="color: #59d9ff" class="font-14 q-mt-md">Quick links</div>
          <div class="column q-gutter-sm q-mt-xs">
            <a href="#">Home</a>
            <a href="#ecosystem">Ecosystem</a>
            <a href="#buy">Buy</a>
            <a href="#community">Community</a>
          </div>
        </div>
        <div>
          <div style="color: #59d9ff"  class="font-14 q-mt-md">Newsletter</div>
          <q-input v-model="text" type="text" label="Email address" bg-color="primary" label-color="secondary" dark text-color="white" class="q-mt-md" dense filled style="border-radius: 10px" />
        </div>
      </div>
      <div style="background: linear-gradient(90deg, transparent, #01f8de, transparent); max-width: 600px; height: 2px" class="q-mx-auto q-mt-lg" />
      <p class="text-center text-secondary q-mt-sm">All rights reserved by Shibamoon</p>
    </footer>
  </q-page>
</template>

<script>
import Header from 'components/Header'

export default {
  name: 'PageIndex',
  components: { Header },
  setup(){

    return { }
  }
}
</script>
