<template>
  <div class="how-it-works pb-6 sm:hidden">
    <div class="flex justify-center">
      <HomeToggleButton is-mobile class="mt-16" />
    </div>

    <div class="w-11/12 sm:w-11/12 lg:w-9/12 flex justify-between sm:justify-center items-center m-auto mt-16 mb-4">
      <div class="w-6/12">
        <div class="mb-4">
          <div class="mr-0 m-auto step-box">1</div>
          <h6 class="text-sm font-medium text-right leading-5">Select your timeframe or destination</h6>
          <p class="text-[11px] text-right">
            Choose your pickup location and the time range/duration that you’ll need a driver for
          </p>
        </div>
        <div class="mb-4">
          <div class="mr-0 m-auto step-box">2</div>
          <h6 class="text-sm font-medium text-right leading-5">Book a driver</h6>
          <p class="text-[11px] text-right">GetDriva will match you with the nearest driver</p>
        </div>
        <div class="mb-4">
          <div class="mr-0 m-auto step-box">3</div>
          <h6 class="text-sm font-medium text-right leading-5">Pay when service is rendered</h6>
          <p class="text-[11px] text-right">Pay the driver the accumulated fee either by cash or card</p>
        </div>
        <div class="mb-4">
          <div class="mr-0 m-auto step-box">4</div>
          <h6 class="text-sm font-medium text-right leading-5">Rate your driver</h6>
          <p class="text-[11px] text-right">
            Rate your driver according to the service rendered, you can also leave a review about your ride
          </p>
        </div>
      </div>

      <nuxt-img class="w-5/12" src="/images/how-screenshot.png" />

      <!--      <div class="w-4/12">
        <div class="mb-40">
          <div class="ml-0 m-auto step-box">2</div>
          <h6 class="text-sm md:text-base font-medium text-left leading-5 mb-2">Book a driver</h6>
          <p class="text-xs text-left">GetDriva will match you with the nearest driver</p>
        </div>

        <div>
          <div class="ml-0 m-auto step-box">4</div>
          <h6 class="text-sm md:text-base font-medium text-left leading-5 mb-2">Rate your driver</h6>
          <p class="text-xs text-left">
            Rate your driver according to the service rendered, you can also leave a review about your ride
          </p>
        </div>
      </div>-->
    </div>
  </div>
</template>

<style lang="scss" scoped>
.how-it-works {
  background-color: rgba(255, 233, 219, 0.38);
  .step-box {
    @apply flex justify-center items-center;
    @apply w-10 h-10 lg:w-16 lg:h-[60px] rounded-lg lg:rounded-[15px] bg-primary-500;
    @apply mb-2 text-2xl text-white font-semibold;
  }
}
</style>