<template>
    <div class="bg-gray-100">
        <h6 class="text-center">A P P O I N T M E N T</h6>
        <p class="text-center font-semibold">Consult with our Experts</p>

        <div class="p-5">
    <div class="mt-2">
        <div class="flex flex-col md:flex-row border-b border-gray-200 pb-4 mb-4">
            <div class="flex-1 flex flex-col md:flex-row">
                <div class="w-full flex-1 mx-2">
                    <div class="my-2 p-1 bg-white flex border border-gray-200 rounded">
                        <input placeholder="Choose Medical department" class="p-1 px-2 appearance-none outline-none w-full text-gray-800 "> </div>
                </div>
            <select id="Doctors" input placeholder="Choose your Doctor" class="flex-1 flex flex-col md:flex-row my-2 p-1 bg-white flex border border-gray-200 rounded">
                <option value="" selected disabled>Choose your Doctor</option>
            </select>
            </div>
        </div>

        <div class="p-5">
            <div class="mt-2">
                <div class="flex flex-col md:flex-row border-b border-gray-200 pb-4 mb-4">
                    <div class="flex-1 flex flex-col md:flex-row">
                        <div class="w-full flex-1 mx-2">
                            <div class="my-2 p-1 bg-white flex border border-gray-200 rounded">
                                <input placeholder="Enter your name" class="p-1 px-2 appearance-none outline-none w-full text-gray-800">
                            </div>
                        </div>
                        <div class="w-full flex-1 mx-2">
                            <div class="my-2 p-1 bg-white flex border border-gray-200 rounded">
                                <input placeholder="Email Adress" class="p-1 px-2 appearance-none outline-none w-full text-gray-800"> 
                            </div>
                        </div>
                        <div>
                </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="w-full flex-1 mx-2">
            <div class="my-2 p-1 bg-white flex border border-gray-200 rounded">
                <input type="tel" id="phone" class="p-1 px-2 appearance-none outline-none w-full text-gray-800" placeholder="Enter Phone number" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>
        </div>
            </div>
            <div class="w-full flex-1 mx-2">
                <div class="my-2 p-1 bg-white flex border border-gray-200 rounded">
                    <div class="relative mb-3" data-te-datepicker-init data-te-input-wrapper-init>
                    <input type="text" class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[1.6] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 peer-focus:text-primary data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-neutral-200 dark:placeholder:text-neutral-200 dark:peer-focus:text-primary [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0" placeholder="Select a date" />
                <label for="floatingInput" class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[1.6] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[0.9rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[0.9rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Select a date</label>
            </div>
                </div>
                <div class="relative" id="timepicker-inline-12" data-te-input-wrapper-init> 
                    <input type="text" class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[1.6] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 peer-focus:text-primary data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-neutral-200 dark:placeholder:text-neutral-200 dark:peer-focus:text-primary [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0" id="form2" />
                <label for="form2" class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[1.6] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[0.9rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[0.9rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Select a time</label>
</div>
            </div>

    </div>
        </div>
            </div>
        <div class="flex flex-col md:flex-row">
            <div class="w-64 mx-2 font-bold h-6 mt-3 text-gray-800"></div>
            <div class="flex-1 flex flex-col md:flex-row">
                <button class="text-sm  mx-2 w-32  focus:outline-none flex justify-center px-4 py-2 rounded font-bold cursor-pointer hover:bg-blue-400 hover:text-teal-100 bg-blue-100 text-white-600 border duration-200 ease-in-out border-blue-200 transition">Confirm Appointment</button>
            </div>
        </div>
</template>
