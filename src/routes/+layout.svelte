<script>
    import "../app.css"; 
</script>
  

  <nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded drop-shadow-md">
    <div class="container flex flex-wrap items-center justify-between mx-auto">
      <a href="/" class="flex items-center">
          <span class="self-center text-xl font-semibold whitespace-nowrap">Almost Blog</span>
      </a>
      <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200" aria-controls="navbar-default" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-4 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white">
          <li>
            <a href="daily" class="block py-2 pl-3 pr-4 text-gray-700 rounded p-0">Daily Digest</a>
          </li>
          <li>
            <a href="design" class="block py-2 pl-3 pr-4 text-gray-700 rounded p-0">Design Tools</a>
          </li>
          <li>
            <a href="tutorials" class="block py-2 pl-3 pr-4 text-gray-700 rounded">Tutorials</a>
          </li>
          <li>
            <a href="newsletter"class="block py-2 pl-3 pr-3 text-white bg-gray-700 rounded text-center">Subscribe</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  
<body class="bg-gray-100">
  <slot />
</body>


