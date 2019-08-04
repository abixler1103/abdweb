<script>
  export let segment;
</script>

<div class="bg-adb-pink h-2">&nbsp;</div>
<nav class="flex items-center justify-between flex-wrap bg-adb-teal p-6">

  <div class="flex items-center flex-shrink-0 text-white mr-6">
    <a href="/">
      <img
        class="h-10"
        src="/abd_logo_transparent.png"
        alt="Ashley Bixler Design Logo" />
    </a>

    <span class="font-semibold text-xl tracking-tight">
      Ashley Bixler Design
    </span>

  </div>
  <div class="block lg:hidden">
    <button
      class="flex items-center px-3 py-2 border rounded text-teal-200
      border-teal-400 hover:text-white hover:border-white">
      <svg
        class="fill-current h-3 w-3"
        viewBox="0 0 20 20"
        xmlns="http://www.w3.org/2000/svg">
        <title>Menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
      </svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
      <a
        href="/about"
        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white
        mr-4">
        About Me
      </a>
    </div>
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
</nav>
