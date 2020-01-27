<template>
  <div>
    <div class="bg-gray-2 text-font-primary font-medium">
      <div class="container mx-auto">
        <nav class="pt-4">
          <img src="/img/logo.png" class="logo" />
        </nav>
        <div class="mt-10">
          <h1 class="text-h1 font-extrabold">Register a foreign company in Vietnam</h1>
          <div class="flex">
            <div class="w-2/5 mt-5">
              <h3 class="text-h3 font-bold">Set up a 100% foreign owned company within 30 days</h3>
              <ul class="text-gray-700 text-li">
                <li class="mt-6">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div
                      class="leading-relaxed text-secondary"
                    >Flexible paid up capital and corporate structure</div>
                  </div>
                </li>
                <li class="mt-4">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div
                      class="leading-relaxed text-secondary"
                    >Majority of industries don't require local founder</div>
                  </div>
                </li>
                <li class="mt-4">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div
                      class="leading-relaxed text-secondary"
                    >Hire unlimited amount of foreign nationals</div>
                  </div>
                </li>
              </ul>
              <div class="mt-8 font-semibold">
                <div>
                  <label class="block font-lg text-secondary" for="email">Your Email</label>
                  <input
                    class="block mt-1 w-full border-2 border-primary p-3 rounded-lg"
                    type="text"
                    id="email"
                  />
                </div>
                <div class="mt-4">
                  <label
                    class="block font-lg text-secondary"
                    for="business-Activity"
                  >Planned Business Activity</label>
                  <input
                    class="block mt-1 w-full border-2 border-primary p-3 rounded-lg"
                    type="text"
                    id="business-Activity"
                  />
                </div>
              </div>
              <div class="ml-4 py-2 text-sm text-font-gray">
                <div class="pt-1">
                  Foreign Ownership :
                  <strong class="text-primary font-semibold">Allowed</strong>
                </div>
                <div class="pt-1">
                  Min Capital Required :
                  <strong class="text-primary font-semibold">200 Million VND</strong>
                </div>
              </div>
            </div>
            <div class="ml-auto flex items-end">
              <div>
                <img src="/img/hailey.png" alt="slider-image" />
              </div>
              <div class="text-gray-700 text-sm text-font-gray-1">
                <div class="mb-8">
                  <div>Hayley Bakker</div>
                  <div class="font-semibold">Director, Colibri Growth</div>
                  <div>Vietnam</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto">
      <div class="flex">
        <div class="w-2/5 -mt-6">
          <button class="bg-primary text-li w-full text-white py-3 rounded-lg">Get a Quote</button>
        </div>
        <div class="ml-auto mt-2 mr-8 flex">
          <div class="w-4 h-4 bg-primary rounded-full"></div>
          <div class="w-4 h-4 ml-2 border border-primary rounded-full"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TickIcon from "./TickIcon";
export default {
  name: "Hero",
  components: {
    TickIcon
  }
};
</script>

<style>
</style>
