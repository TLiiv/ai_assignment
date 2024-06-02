<script>

</script>

<style>
    .background-icon {
      position: absolute;
      top: 30%;
      left: 50%;
      z-index: -1;
      font-size: 30rem; 
      color: rgba(251, 251, 255,0.5); 
    }
  </style>


<div class="w-full h-screen flex flex-col items-center justify-between flex-grow-1">
    
    <div class="background-icon">
        <i class="fas fa-icon">&#xf0e7;</i> 
      </div>
  <!-- GPT buttons and dropdown -->
  <div class="p-4 space-y-4">
    <!-- GPT buttons -->
    <div class="inline-flex rounded-md shadow-sm" >
      <button type="button" class="inline-flex items-center w-40 h-16 px-4 py-2 text-m font-bold shadow-2xl text-gray-900 hover:text-purple-700 rounded-xl focus:z-10 focus:ring-2 ">
        <span class="icon-circle bg-purple-200 text-purple-900 mr-2 inline-flex justify-center items-center rounded-full w-10 h-10 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-purple-100  to-purple-400">
            <i class="fas fa-icon">&#xf0e7;</i> 
          </span>
        GPT-3.5
      </button>
      <button type="button" class="inline-flex items-center w-40 h-16 px-4 py-2 text-m font-bold shadow-2xl text-gray-900 hover:text-purple-700 rounded-xl focus:z-10 focus:ring-2 ">
        <span class="icon-circle bg-purple-200 text-purple-900 mr-2 inline-flex justify-center items-center rounded-full w-10 h-10 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-purple-100  to-purple-400">
            <i class="fas fa-icon">&#xf0e7;</i> 
          </span>
        GPT-4
      </button>
    </div>
    
    <!-- Dropdown -->
    <div class="flex justify-center">
      <button id="dropdownDefaultButton" data-dropdown-toggle="dropdown" class="text-gray   focus:ring-1 focus:outline-none focus:ring-purple-100 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center   " type="button">No plugins enabled <svg class="w-2.5 h-2.5 ms-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
        </svg>
      </button>
      
      <!-- Dropdown menu -->
      <div id="dropdown" class="z-10 hidden bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700">
          <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownDefaultButton">
            <li>
              <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Plugin</a>
            </li>
          </ul>
      </div>
    </div>
  </div>
  
  <!-- Submit button and textarea -->
  <div class="flex flex-row items-center p-4 w-4/5 justify-between flex-grow-1">
    <textarea class="flex-grow h-12 px-4 border rounded-full overflow-hidden resize-none" placeholder="Send a message"></textarea>
    <button class="ml-2 w-40 h-12 text-white rounded-full px-6 py-2 text-sm bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-purple-700 to-purple-900 shadow-lg shadow-purple-600">
        Submit
    </button>
      </div>
</div>



