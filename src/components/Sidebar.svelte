<script>
    import { onMount } from 'svelte';
  </script>
  
  <style>
    .sidebar {
        min-width: 310px;
      display: flex;
      flex-direction: column;
      /* height: calc(100vh - 40px); */
      background-color: #fff;
      padding: 20px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1), 0 10px 20px rgba(0, 0, 0, 0.1);
      margin: 20px;
      border-radius: 8px;
      position: relative;
      z-index: 10;
    }
    .menu-item {
      padding: 10px 0;
      color: #333;
    }
    .locked {
      color: #aaa;
      pointer-events: none;
    }
  </style>
  
  <div class="sidebar">
    <div class="header mb-4">
      <h1 class="text-2xl font-bold">CloudChat AI</h1>
    </div>
    <hr class="border-gray-200 mb-4">
    <div class="menu-item mb-4">
      <h2 class="flex items-center text-xl font-semibold">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-5 h-5 mr-2">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M9 16h6M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
        Chat UI
      </h2>
    </div>
    <nav class="flex-1">
      <a href="#" class="menu-item block">Other Pages</a>
      <a href="#" class="menu-item block">Prompt Page</a>
      <a href="#" class="menu-item block">Register</a>
      <a href="#" class="menu-item block">Sign in</a>
      <hr class="border-gray-200 my-4">
      <a href="#" class="menu-item block locked">Admin Pages</a>
      <a href="#" class="menu-item block locked">All Templates</a>
      <a href="#" class="menu-item block locked">New Template</a>
      <a href="#" class="menu-item block locked">Edit Template</a>
      <a href="#" class="menu-item block locked">Users Overview</a>
    </nav>
    <div class="flex items-center mt-4">
      <img src="https://via.placeholder.com/40" alt="User Picture" class="rounded-full">
      <div class="ml-2">
        <p class="text-sm font-semibold">Name Surname</p>
        <button class="bg-red-500 text-white rounded-full p-2 mr-2">Logout</button>
      </div>
    </div>
  </div>
  