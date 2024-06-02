<script>
   
</script>

<div class="sidebar w-79">
    <div class="header mb-4">
        <h1 class="text-2xl text-center"><b>CLOUDCHAT</b> AI</h1>
    </div>
    <hr class="border-gray-200 mb-4 w-full" />
    <div class="menu-item mb-4">
        <h2 class="flex items-center justify-center text-xl font-semibold ">
            <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="w-5 h-5 mr-2"
            >
                <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M8 12h.01M12 12h.01M16 12h.01M9 16h6M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
            </svg>
            Chat UI
        </h2>
    </div>
    <nav class="flex-1">
        <ul class="space-y-2">
            <li>
                <a href="#" class="menu-item block text-center">Other Pages</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center">Prompt Page</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center">Register</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center">Sign in</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center locked">Admin Pages</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center locked">All Templates</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center locked">New Template</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center locked">Edit Template</a>
            </li>
            <li>
                <a href="#" class="menu-item block text-center locked">Users Overview</a>
            </li>
        </ul>
    </nav>
    <div class="flex items-center p-2 mt-4 shadow-md rounded-2xl">
        <img
            src="https://via.placeholder.com/40"
            alt="User Picture"
            class="rounded-full"
        />
        <div class="flex-1 flex justify-center items-center">
            <h3 class="text-md font-semibold">Name Surname</h3>
        </div>
        <button class="rounded-full w-10 h-10 flex items-center justify-center border-solid border-gray border-2 ml-2">
            <i class="fa-solid fa-arrow-right-from-bracket" style="color: #161c27;"></i>
        </button>
    </div>
</div>

<style>
    .sidebar {
        display: flex;
        flex-direction: column;
        background-color: #fff;
        padding: 20px;
        box-shadow:
            0 10px 20px rgba(0, 0, 0, 0.1),
            0 10px 20px rgba(0, 0, 0, 0.1);
        margin: 20px;
        border-radius: 8px;
        position: relative;
        z-index: 10;
    }
    .menu-item {
        padding: 10px 0;
        color: #333;
        text-align: center; 
    }
    .locked {
        color: #aaa;
        pointer-events: none;
    }
</style>
