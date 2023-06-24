<template>
    <div class="flex h-screen">
      <aside class="bg-white-100 w-1/8 p-4">
        <div class=" mb-8 text-4xl font-semibold Poppins">
        <span class="underline decoration-1 hover:text-blue-400">APPOINTER</span>
      </div>
        <nav>
          <ul>
            <li class="mb-4">
              <a class="flex items-center" href="/index">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="15px" width="15px">
                    <rect x="48" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="48" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="48" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="288" width="176" height="176" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span class="hover:text-blue-400">DASHBOARD</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="15px" width="15px">
                    <rect fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" x="48" y="80" width="416" height="384" rx="48"/><circle cx="296" cy="232" r="24"/><circle cx="376" cy="232" r="24"/><circle cx="296" cy="312" r="24"/><circle cx="376" cy="312" r="24"/><circle cx="136" cy="312" r="24"/><circle cx="216" cy="312" r="24"/><circle cx="136" cy="392" r="24"/><circle cx="216" cy="392" r="24"/><circle cx="296" cy="392" r="24"/><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" stroke-linecap="round" d="M128 48v32M384 48v32"/><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" d="M464 160H48"/>
                </svg>
                <span class="hover:text-blue-400">APPOINTMENTS</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="15px" width="15px">
                    <rect x="32" y="112" width="448" height="352" rx="48" ry="48" fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32"/><path d="M144 112V80a32 32 0 0132-32h160a32 32 0 0132 32v32M256 208v160M336 288H176" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span class="hover:text-blue-400">DOCTORS</span>
              </a>
            </li>
            <li class="mb-4">
              <a class="flex items-center" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="15px" width="15px">
                    <path d="M262.29 192.31a64 64 0 1057.4 57.4 64.13 64.13 0 00-57.4-57.4zM416.39 256a154.34 154.34 0 01-1.53 20.79l45.21 35.46a10.81 10.81 0 012.45 13.75l-42.77 74a10.81 10.81 0 01-13.14 4.59l-44.9-18.08a16.11 16.11 0 00-15.17 1.75A164.48 164.48 0 01325 400.8a15.94 15.94 0 00-8.82 12.14l-6.73 47.89a11.08 11.08 0 01-10.68 9.17h-85.54a11.11 11.11 0 01-10.69-8.87l-6.72-47.82a16.07 16.07 0 00-9-12.22 155.3 155.3 0 01-21.46-12.57 16 16 0 00-15.11-1.71l-44.89 18.07a10.81 10.81 0 01-13.14-4.58l-42.77-74a10.8 10.8 0 012.45-13.75l38.21-30a16.05 16.05 0 006-14.08c-.36-4.17-.58-8.33-.58-12.5s.21-8.27.58-12.35a16 16 0 00-6.07-13.94l-38.19-30A10.81 10.81 0 0149.48 186l42.77-74a10.81 10.81 0 0113.14-4.59l44.9 18.08a16.11 16.11 0 0015.17-1.75A164.48 164.48 0 01187 111.2a15.94 15.94 0 008.82-12.14l6.73-47.89A11.08 11.08 0 01213.23 42h85.54a11.11 11.11 0 0110.69 8.87l6.72 47.82a16.07 16.07 0 009 12.22 155.3 155.3 0 0121.46 12.57 16 16 0 0015.11 1.71l44.89-18.07a10.81 10.81 0 0113.14 4.58l42.77 74a10.8 10.8 0 01-2.45 13.75l-38.21 30a16.05 16.05 0 00-6.05 14.08c.33 4.14.55 8.3.55 12.47z" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                </svg>
                <span class="hover:text-blue-400">SETTINGS</span>
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
        <input type="search" id="default-search" class="flex justify-between py-2 px-10 text-sm text-gray-900 border border-blue-100 rounded-lg bg-gray-50 focus:ring-blue-100 focus:border-blue-100 dark:bg-gray-100 dark:border-blue-300 dark:placeholder-gray-400 dark:text-black dark:focus:ring-blue-200 dark:focus:border-blue-200" placeholder="Search" required>
    </div>
</form>

<div class="p-8">
    <h2 class="font-semibold text-2xl">Welcome (patient name)!</h2>
</div>
<div class="flex flex-wrap justify-center mt-10">

<!-- card 1 Appointment -->
<div class="p-4 max-w-sm">
  <h2 class="text-black text-lg font-medium">Today's Appointments</h2>
    <div class="flex rounded-lg h-full bg-blue-400 p-8 flex-col">
        <div class="flex items-center mb-3">
        </div>
        <div class="flex flex-col justify-between flex-grow">
            <p class="leading-relaxed text-base text-white">Lorem ipsum dolor sit amet. In quos laboriosam non
                neque eveniet 33 nihil molestias. Rem perspiciatis iure ut laborum inventore et maxime amet.
            </p>
        </div>
    </div>
</div>

<!-- card 3 Records-->
<div class="p-4 max-w-sm">
  <h2 class="text-black text-lg font-medium">Appointment History</h2>
    <div class="flex rounded-lg h-full bg-blue-400 p-8 flex-col">
        <div class="flex items-center mb-3">
        </div>
        <div class="flex flex-col justify-between flex-grow">
            <p class="leading-relaxed text-base text-white">Lorem ipsum dolor sit amet. In quos laboriosam non
                neque eveniet 33 nihil molestias. Rem perspiciatis iure ut laborum inventore et maxime amet.</p>
        </div>
    </div>
</div>
</div>

<ul class="absolute top-0 right-0 h-13 w-13 gap-2 max-w-[280px]">

<li>
    <details class="group">

        <summary
            class="flex items-center justify-between gap-2 p-2 font-medium marker:content-none hover:cursor-pointer">
            <span class="flex gap-2">
                <img class="w-6 h-6 rounded-lg"
                    src=""
                    alt="">

                <span>
                    patients acc
                </span>
            </span>
            <svg class="w-5 h-5 text-gray-500 transition group-open:rotate-90" xmlns="http://www.w3.org/2000/svg"
                width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z">
                </path>
            </svg>
        </summary>

        <article class="px-4 pb-4">

            <ul class="flex flex-col gap-4 pl-2 mt-4">
                <form action="">
                  <li class="hover:text-blue-400">
                    <a href="/newAppointment">
                    <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="18" width="18">
                    <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M256 112v288M400 256H112"/>
                  </svg>
                    New Appointment</a></li>
                </form>
                <form action="" method="POST">
                    <li class="hover:text-blue-400"><svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512" height="18" width="18">
                      <path d="M304 336v40a40 40 0 01-40 40H104a40 40 0 01-40-40V136a40 40 0 0140-40h152c22.09 0 48 17.91 48 40v40M368 336l80-80-80-80M176 256h256" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
                    </svg>
                    Logout
                    </li>
                </form>

            </ul>

        </article>

    </details>
</li>
</ul>
      </main>
    </div>
  </template>

<script>
export default {
  layout: 'vertical-dashboard',
}
</script>