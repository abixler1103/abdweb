<script>
  var src = "ashleybw.png";

  function imgOut() {
    src = "ashleybw.png";
  }

  function imgOver() {
    src = "ashleycolor.jpg";
  }
</script>

<br />
<div class="min-h-screen flex flex-col font-sans">
  <div class="flex">
    <div class="flex-1 text-left px-1 py-1 m-1">
      <p class="text-9xl text-left font-serif text-adb-teal">
        Let's
        <i>design</i>
        the future together.
      </p>
      <p class="text-5xl text-left font-sans text-adb-pink text-bold">
        While delivering impactful business results.
      </p>
    </div>
    <div class="flex-1 text-right pl-12 px-1 py-1 m-1">
      <img
        id="ashley"
        class="shadow-2xl rounded-lg ashley"
        {src}
        width="400"
        alt="Ashley Bixler"
        on:mouseover={imgOver}
        on:mouseout={imgOut} />

    </div>
  </div>

  <br />
  <br />

  <div class="flex bg-white text-gray-800 p-10">
    <div class="w-1/3 bg-white h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img class="w-full" src="hp_web.png" alt="Website screenshot" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Web</div>
          <p class="text-gray-700 text-base">
            Web applications that deliver results.
          </p>
        </div>
        <div class="px-6 py-4">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #web
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #mockups
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700">
            #recipe
          </span>
        </div>
      </div>
    </div>
    <div class="w-1/3 bg-white h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img class="w-full" src="hp_logo.png" alt="Logo screenshot" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Identity</div>
          <p class="text-gray-700 text-base">Crafting unique brands.</p>
        </div>
        <div class="px-6 py-4">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #logo
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #marketing
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700">
            #identity
          </span>
        </div>
      </div>
    </div>

    <div class="w-1/3 bg-white h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img
          class="w-full"
          src="hp_mobile.png"
          alt="Mobile application screenshot" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Mobile</div>
          <p class="text-gray-700 text-base">
            Functional mobile user interface design.
          </p>
        </div>
        <div class="px-6 py-4">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #mobile
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700 mr-2">
            #uiux
          </span>
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm
            font-semibold text-gray-700">
            #onthego
          </span>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- FOOTER -->
<div class="flex bg-adb-teal text-sm font-bold p-2">
  <div class="flex-1 text-left px-2 py-2 m-2 text-adb-yellow">
    <div
      class="rounded inline-flex items-center bg-adb-teal text-yellow text-sm
      font-bold py-2 px4">
      <svg
        class="fill-current w-4 h-4 mr-2"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20">
        <path
          d="M10 20a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm2-2.25a8 8 0 0 0
          4-2.46V9a2 2 0 0 1-2-2V3.07a7.95 7.95 0 0 0-3-1V3a2 2 0 0 1-2 2v1a2 2
          0 0 1-2 2v2h3a2 2 0 0 1 2 2v5.75zm-4 0V15a2 2 0 0 1-2-2v-1h-.5A1.5 1.5
          0 0 1 4 10.5V8H2.25A8.01 8.01 0 0 0 8 17.75z" />
      </svg>
      <span>
        <a href="mailto:ashley@ashleybixlerdesign.com">
          ashley@ashleybixlerdesign.com
        </a>
      </span>
    </div>
    <br />
    <div
      class="rounded inline-flex items-center bg-adb-teal text-yellow text-sm
      font-bold py-2 px4">
      <svg
        class="fill-current w-4 h-4 mr-2"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20">
        <path
          d="M20 18.35V19a1 1 0 0 1-1 1h-2A17 17 0 0 1 0 3V1a1 1 0 0 1 1-1h4a1 1
          0 0 1 1 1v4c0 .56-.31 1.31-.7 1.7L3.16 8.84c1.52 3.6 4.4 6.48 8
          8l2.12-2.12c.4-.4 1.15-.71 1.7-.71H19a1 1 0 0 1 .99 1v3.35z" />
      </svg>
      <span>+1 415 654 4517</span>
    </div>
  </div>
  <div class="flex-1 text-adb-yellow text-left">
    <img
      class="bg-adb-yellow"
      src="georgia.png"
      alt="State of Georgia"
      width="50"
      height="80" />
    <p class="opacity-75">Lovingly crafted in Atlanta, GA</p>
    &copy; 2019 Ashley Bixler Design LLC
  </div>
</div>
