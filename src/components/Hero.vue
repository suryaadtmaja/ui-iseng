<template>
  <section
    class="h-screen w-full flex items-center hero bg-no-repeat bg-center justify-end"
    style="background-image: url('/img/hero.png')"
  >
    <div class="container mx-auto">
      <div class="flex justify-end">
        <div class="max-w-lg flex flex-col space-y-6">
          <div
            class="cursor-pointer badge flex px-2 py-2 items-center max-w-md"
          >
            <div class="flex space-x-4">
              <button
                style="
                  color: #4e9aa9;
                  font-size: 9px;
                  letter-spacing: 1px;
                  line-height: 9px;
                "
                class="bg-white uppercase px-2 py-2"
              >
                new recipe
              </button>
              <p style="color: #4e9aa9">Delicious fruit juice combinations</p>
              <svg
                class="w-6 h-6"
                fill="#4e9aa9"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
          </div>
          <h3
            style="
              font-style: normal;
              font-weight: 600;
              letter-spacing: -2px;
              line-height: 95px;
              font-size: 85px;
            "
          >
            Simple and Tasty Juice Recipes
          </h3>
          <p class="text-gray-400">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.badge {
  background-color: rgba(78, 154, 169, 0.15);
}

.badge:hover {
  box-shadow: 1px 1px #4e9aa9, 2px 2px #4e9aa9, 3px 3px #4e9aa9;
  transition: all 0.3s ease;
}
</style>
