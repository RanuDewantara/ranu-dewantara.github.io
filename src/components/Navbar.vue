<template>
  <header class="fixed flex flex-wrap sm:justify-start sm:flex-nowrap z-50 w-full bg-red-700 text-sm">
    <nav class="max-w-[85rem] w-full mx-auto sm:flex sm:items-center sm:justify-between" aria-label="Global">
      <div class="flex items-center justify-between p-2 py-3 md:px-8">
        <a class="flex-none fill-current text-white" href="#">
          <svg height="40" viewBox="0 0 217 80" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink"
            xmlns="http://www.w3.org/2000/svg">
            <defs>
              <path d="M0 0L217 0L217 80L0 80L0 0Z" id="path_1" />
              <use xlink:href="#path_1" transform="translate(0, 5.3600006)" />
            </defs>
            <g id="Text" clip-path="url(#clip_1)" transform="translate(0 -5.3600006)">
              <g transform="translate(4.8499985, 0)" id="RPD">
                <path
                  d="M18.9 72.45L3.15 72.45L3.15 28.35L18.9 28.35L18.9 72.45ZM0 22.05L-12.06 9.45L34.65 9.45L53.55 28.35L44.1 37.8L25.2 37.8L34.65 28.35L28.35 22.05L0 22.05ZM25.2 44.1L25.2 56.7L37.8 56.7L53.55 72.45L72.45 72.45L44.1 44.1L25.2 44.1ZM88.48 72.45L72.73 72.45L72.73 28.35L88.48 28.35L88.48 72.45ZM69.58 22.05L57.34 9.45L104.23 9.45L123.13 28.35L113.68 37.8L94.78 37.8L104.23 28.35L97.93 22.05L69.58 22.05ZM142.4 72.45L142.4 28.35L126.65 28.35L126.65 72.45L142.4 72.45ZM148.7 59.85L161.3 59.85L180.2 40.95L161.3 22.05L123.5 22.05L111.17 9.45L167.6 9.45L199.1 40.95L167.6 72.45L148.7 72.45L148.7 59.85Z" />
              </g>
            </g>
          </svg>
        </a>
        <button type="button"
          class="hs-collapse-toggle p-2 inline-flex justify-center items-center gap-x-2 rounded-lg md:hidden"
          data-hs-collapse="#navbar-image-1" aria-controls="navbar-image-1" aria-label="Toggle navigation">
          <svg class="hs-collapse-open:hidden flex-shrink-0 size-6 text-white" xmlns="http://www.w3.org/2000/svg" width="24"
            height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
            stroke-linejoin="round">
            <line x1="3" x2="21" y1="6" y2="6" />
            <line x1="3" x2="21" y1="12" y2="12" />
            <line x1="3" x2="21" y1="18" y2="18" />
          </svg>
          <svg class="hs-collapse-open:block hidden flex-shrink-0 size-6 text-white" xmlns="http://www.w3.org/2000/svg"
            width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
            stroke-linecap="round" stroke-linejoin="round">
            <path d="M18 6 6 18" />
            <path d="m6 6 12 12" />
          </svg>
        </button>
      </div>
      <div id="navbar-image-1"
        class="hs-collapse hidden overflow-hidden transition-all px-5 duration-300 basis-full grow sm:block">
        <div class="flex flex-col font-semibold uppercase md:gap-5 sm:flex-row sm:items-center font-[Oxanium] sm:justify-end sm:mt-0 text-white">
          <a href="" class="p-5 md:w-28 text-center hover:bg-white hover:text-red-700">Home</a>
          <a href="" class="p-5 md:w-28 text-center hover:bg-white hover:text-red-700">About</a>
          <a href="" class="p-5 md:w-28 text-center hover:bg-white hover:text-red-700">Experience</a>
          <a href="" class="p-5 md:w-28 text-center hover:bg-white hover:text-red-700">Project</a>
          <a href="" class="p-5 md:w-28 text-center hover:bg-white hover:text-red-700">Contact</a>
        </div>
      </div>
    </nav>
  </header>
</template>