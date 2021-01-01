<template>
  <header class="flex w-full justify-between">
    <nav class="ml-8 flex w-2/3 justify-between items-center">
      <div
        style="color: #1dc6d1"
        class="flex items-center justify-center space-x-3"
      >
        <div
          style="background-color: #1dc6d1"
          class="rounded-full h-8 w-8 flex items-center justify-center"
        >
          <span class="text-white font-bold">J</span>
        </div>
        <a
          href="#"
          style="color: #11bcc7; letter-spacing: 1px"
          class="leading-6 text-base font-bold uppercase"
          >Juicedaily</a
        >
      </div>
      <ul class="flex space-x-12 uppercase text-gray-800">
        <li
          class="h-3"
          style="letter-spacing: 1.5px; mix-blend-mode: normal; opacity: 0.8"
        >
          Browse
        </li>
        <li
          class="h-3"
          style="letter-spacing: 1.5px; mix-blend-mode: normal; opacity: 0.8"
        >
          Trending
        </li>
        <li
          class="h-3"
          style="letter-spacing: 1.5px; mix-blend-mode: normal; opacity: 0.8"
        >
          Contributors
        </li>
        <li
          class="h-3"
          style="letter-spacing: 1.5px; mix-blend-mode: normal; opacity: 0.8"
        >
          Community
        </li>
      </ul>
    </nav>
    <div
      class="w/1-4 search-box h-24 w-24 bg-red-700 flex justify-center items-center"
    >
      <svg
        class="w-6 h-6"
        fill="#FFFFFF"
        viewBox="0 0 20 20"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill-rule="evenodd"
          d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
          clip-rule="evenodd"
        ></path>
      </svg>
    </div>
  </header>
</template>
