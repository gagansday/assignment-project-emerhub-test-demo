<template>
  <div>
    <div class="bg-gray-100 text-gray-800 font-medium">
      <div class="container mx-auto">
        <nav class="pt-4">
          <img src="/img/logo.png" class="logo" />
        </nav>
        <div class="mt-10">
          <h1 class="text-4xl font-bold">Register a foreign company in Vietnam</h1>
          <div class="flex">
            <div class="w-2/5">
              <h2 class="text-xl font-bold">Set up a 100% foreign owned company within 30 days</h2>
              <ul class="text-gray-700 text-lg font-semibold">
                <li class="mt-8">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div>Flexible paid up capital and corporate structure</div>
                  </div>
                </li>
                <li class="mt-4">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div>Majority of industries don't require local founder</div>
                  </div>
                </li>
                <li class="mt-4">
                  <div class="flex items-center">
                    <tick-icon></tick-icon>
                    <div>Hire unlimited amount of foreign nationals</div>
                  </div>
                </li>
              </ul>
              <div class="mt-8 font-semibold">
                <div>
                  <label class="block" for="email">Your Email</label>
                  <input
                    class="block mt-1 w-full border-2 border-gray-800 p-3 rounded-lg"
                    type="text"
                    id="email"
                  />
                </div>
                <div class="mt-4">
                  <label class="block" for="business-Activity">Planned Business Activity</label>
                  <input
                    class="block mt-1 w-full border-2 border-gray-800 p-3 rounded-lg"
                    type="text"
                    id="business-Activity"
                  />
                </div>
              </div>
              <div class="ml-4 py-2 text-sm text-gray-700">
                <div class="mt-1">
                  Foreign Ownership :
                  <strong class="text-gray-900 font-bold">Allowed</strong>
                </div>
                <div class="mt-1">
                  Min Capital Required :
                  <strong class="text-gray-900 font-bold">200 Million VND</strong>
                </div>
              </div>
            </div>
            <div class="ml-auto flex items-end">
              <div class="-mt-16">
                <img src="/img/slider-1.png" alt="slider-image" />
              </div>
              <div class="text-gray-700 font-semibold">
                <div class="mb-8">
                  <div>Hayley Bakker</div>
                  <div class="font-semibold text-gray-900">Director, Colibri Growth</div>
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
          <button class="bg-gray-900 text-lg w-full text-white py-3 rounded-lg">Get a Quote</button>
        </div>
        <div class="ml-auto mt-2 mr-8 flex">
          <div class="w-4 h-4 bg-gray-900 rounded-full"></div>
          <div class="w-4 h-4 ml-2 border border-gray-900 rounded-full"></div>
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
