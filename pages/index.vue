<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        alt-coins.eu: to the moon !
      </h1>
      <div class="links">
        <a
          href="https://coinmarketcap.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Visit CoinMarketCap for the live charts of all coins
        </a>
        <a
          href="https://www.reddit.com/r/CryptoCurrency/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Share your experience on reddit...
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.links {
  padding-top: 15px;
}
</style>
