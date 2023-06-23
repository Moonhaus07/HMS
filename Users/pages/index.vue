<template>
    <div class="flex h-screen">
      <aside class="bg-white-100 w-1/4 p-4">
        <div class=" mb-8 text-4xl font-semibold Poppins">
        <span class="underline decoration-1">APPOINTER</span>
      </div>
        <nav>
          <ul>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="25px" width="25px">
                    <rect x="48" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="48" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span>DASHBOARD</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="25px" width="25px">
                    <rect fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" x="48" y="80" width="416" height="384" rx="48"/><circle cx="296" cy="232" r="24"/><circle cx="376" cy="232" r="24"/><circle cx="296" cy="312" r="24"/><circle cx="376" cy="312" r="24"/><circle cx="136" cy="312" r="24"/><circle cx="216" cy="312" r="24"/><circle cx="136" cy="392" r="24"/><circle cx="216" cy="392" r="24"/><circle cx="296" cy="392" r="24"/><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" stroke-linecap="round" d="M128 48v32M384 48v32"/><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" d="M464 160H48"/>
                </svg>
                <span>APPOINTMENTS</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="25px" width="25px">
                    <rect x="32" y="112" width="448" height="352" rx="48" ry="48" fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32"/><path d="M144 112V80a32 32 0 0132-32h160a32 32 0 0132 32v32M256 208v160M336 288H176" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span>DOCTORS</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="25px" width="25px">
                    <path d="M262.29 192.31a64 64 0 1057.4 57.4 64.13 64.13 0 00-57.4-57.4zM416.39 256a154.34 154.34 0 01-1.53 20.79l45.21 35.46a10.81 10.81 0 012.45 13.75l-42.77 74a10.81 10.81 0 01-13.14 4.59l-44.9-18.08a16.11 16.11 0 00-15.17 1.75A164.48 164.48 0 01325 400.8a15.94 15.94 0 00-8.82 12.14l-6.73 47.89a11.08 11.08 0 01-10.68 9.17h-85.54a11.11 11.11 0 01-10.69-8.87l-6.72-47.82a16.07 16.07 0 00-9-12.22 155.3 155.3 0 01-21.46-12.57 16 16 0 00-15.11-1.71l-44.89 18.07a10.81 10.81 0 01-13.14-4.58l-42.77-74a10.8 10.8 0 012.45-13.75l38.21-30a16.05 16.05 0 006-14.08c-.36-4.17-.58-8.33-.58-12.5s.21-8.27.58-12.35a16 16 0 00-6.07-13.94l-38.19-30A10.81 10.81 0 0149.48 186l42.77-74a10.81 10.81 0 0113.14-4.59l44.9 18.08a16.11 16.11 0 0015.17-1.75A164.48 164.48 0 01187 111.2a15.94 15.94 0 008.82-12.14l6.73-47.89A11.08 11.08 0 01213.23 42h85.54a11.11 11.11 0 0110.69 8.87l6.72 47.82a16.07 16.07 0 009 12.22 155.3 155.3 0 0121.46 12.57 16 16 0 0015.11 1.71l44.89-18.07a10.81 10.81 0 0113.14 4.58l42.77 74a10.8 10.8 0 01-2.45 13.75l-38.21 30a16.05 16.05 0 00-6.05 14.08c.33 4.14.55 8.3.55 12.47z" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span>SETTINGS</span>
              </a>
            </li>
          </ul>
        </nav>
      </aside>
      <main class="bg-gray-100 flex-1 p-4">    
<form>   
    <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
    <div class="relative">
        <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
            <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
        </div>
        <input type="search" id="default-search" class="flex justify-between py-2 px-10 text-sm text-gray-900 border border-gray-100 rounded-lg bg-gray-50 focus:ring-gray-100 focus:border-gray-100 dark:bg-gray-100 dark:border-gray-100 dark:placeholder-gray-400 dark:text-black dark:focus:ring-gray-100 dark:focus:border-gray-100" placeholder="Search" required>
    </div>
</form>

<div class="p-8">
    <h2 class="font-semibold text-2xl">Welcome Mr. Patient!</h2>
</div>
<div class="mx-4">
    <h3 class="font-semibold">Upcoming Appointments</h3>
</div>
<div class="grid grid-cols-3 gap-4 p-4">
    <div class="bg-white rounded-lg shadow-md p-4">
      <h2 class="text-lg font-semibold">acc info here</h2>
      <p>patient info here</p>
    </div>
    <div class="mx-4">
    <h3 class="font-semibold">Doctors</h3>

    <div class="bg-white rounded-lg shadow-md p-4">
      <h2 class="text-lg font-semibold">doc info here</h2>
      <p>docs info here</p>
    </div>
    </div>
    </div>
    <div class="mx-4">
    <h3 class="font-semibold">Appointment Records</h3>
</div>
    <div class="bg-white rounded-lg shadow-md p-4">
      <h2 class="text-lg font-semibold">records here</h2>
      <p>info here</p>
    </div>
      </main>
    </div>
  </template>

<script>
export default {
  layout: 'vertical-dashboard',
}
</script>