<script>
  var src = "ashleybw.png";

  function imgOut() {
    src = "ashleybw.png";
  }

  function imgOver() {
    src = "ashleycolor.jpg";
  }
</script>

<div class="bg-adb-pink h-2">&nbsp;</div>
<div class="flex mt-2 px-4">
  <div class="w-2/3 ">
    <a href="/">
      <img src="/abd_logo_transparent.png" alt="Ashley Bixler Design Logo" />
    </a>
  </div>

  <div class="w-1/2">
    <a href="/ashley_bixler_resume_2019.pdf">
      <button
        class="hover:bg-yellow-400 hover:text-adb-teal rounded inline-flex
        items-center bg-adb-teal text-white text-sm font-bold py-2 px-8
        border-gray-500 shadow-outline">
        <svg
          class="fill-current w-4 h-4 mr-2"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20">
          <path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z" />
        </svg>
        <span>Download Resume</span>
      </button>
    </a>
  </div>
</div>

<div class="flex flex-col font-sans">
  <div class="flex">
    <div class="flex-1 text-left px-4 py-1 m-1">
      <p
        class="text-9xl text-left font-serif text-adb-teal leading-tight
        tracking-widest font-hairline">
        Let's
        <u>design</u>
        the future together.
      </p>
      <p class="text-4xl text-left text-adb-pink font-black mt-4">
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

  <div
    class="flex bg-repeat bg-center p-10 mt-4 bg-transparent"
    style="background-image: url('./glamorous.svg'); background-color: #d6144e;
    opacity: 0.5;">
    <div class="w-1/3 h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img class="w-full" src="hp_web.png" alt="Website screenshot" />
        <div class="px-6 py-4 bg-white">
          <div class="font-bold text-xl mb-2">Web</div>
          <p class="text-gray-700 text-base">
            Web applications that deliver results.
          </p>
        </div>
        <div class="px-6 py-4 bg-white">
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
    <div class="w-1/3 h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img class="w-full" src="hp_logo.png" alt="Logo screenshot" />
        <div class="px-6 py-4 bg-white">
          <div class="font-bold text-xl mb-2">Identity</div>
          <p class="text-gray-700 text-base">Crafting unique brands.</p>
        </div>
        <div class="px-6 py-4 bg-white">
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

    <div class="w-1/3 h-auto flex-1">
      <div class="max-w-sm rounded overflow-hidden shadow-lg">
        <img
          class="w-full"
          src="hp_mobile.png"
          alt="Mobile application screenshot" />
        <div class="px-6 py-4 bg-white">
          <div class="font-bold text-xl mb-2">Mobile</div>
          <p class="text-gray-700 text-base">
            Functional mobile user interface design.
          </p>
        </div>
        <div class="px-6 py-4 bg-white">
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
<div class="flex items-center h-auto p-8 bg-adb-teal text-sm font-bold">

  <div class="flex bg-adb-teal text-white text-lg font-bold p-6">
    <div>
      <svg
        class="fill-current w-4 h-4 text-adb-yellow text-left"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20">
        <path
          d="M10 20a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm2-2.25a8 8 0 0 0
          4-2.46V9a2 2 0 0 1-2-2V3.07a7.95 7.95 0 0 0-3-1V3a2 2 0 0 1-2 2v1a2 2
          0 0 1-2 2v2h3a2 2 0 0 1 2 2v5.75zm-4 0V15a2 2 0 0 1-2-2v-1h-.5A1.5 1.5
          0 0 1 4 10.5V8H2.25A8.01 8.01 0 0 0 8 17.75z" />
      </svg>
      <br />
      <svg
        class="fill-current text-adb-yellow w-4 h-4 mt-2"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20">
        <path
          d="M20 18.35V19a1 1 0 0 1-1 1h-2A17 17 0 0 1 0 3V1a1 1 0 0 1 1-1h4a1 1
          0 0 1 1 1v4c0 .56-.31 1.31-.7 1.7L3.16 8.84c1.52 3.6 4.4 6.48 8
          8l2.12-2.12c.4-.4 1.15-.71 1.7-.71H19a1 1 0 0 1 .99 1v3.35z" />
      </svg>
    </div>
    <div>
      &nbsp;
      <a href="mailto:ashley@ashleybixlerdesign.com">
        ashley@ashleybixlerdesign.com
      </a>
      <br />
      &nbsp;&nbsp;
      <br />
      <span class="mt-4">+1 415 654 4517</span>
    </div>

  </div>

  <div class="flex-2 text-white ml-64">
    <img
      class="fill-current text-adb-yellow bg-adb-yellow mt-2"
      src="georgia.png"
      alt="State of Georgia"
      width="50"
      height="80" />
    <span class="text-gray-100 text-sm uppercase">Made in Georgia</span>
    <br />
    <br />
    &copy; 2019 Ashley Bixler Design LLC
  </div>

</div>
