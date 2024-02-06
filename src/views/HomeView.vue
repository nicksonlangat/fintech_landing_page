<template>
<main class="h-screen text-white font-base bg-gradient-to-r from-[#7a53e9] via-[#a558d0] to-[#d15cb6]">
    <div class="mx-auto container">
        <div class="mx-2 lg:mx-0 flex justify-between items-center">
            <h1 class="text-xl font-extrabold mt-5">Grove</h1>
            <div class="hidden lg:flex gap-5 mt-5">
                <a href="" class="hover:underline transition-all duration-300">Features</a>
                <a href="" class="hover:underline transition-all duration-300">About</a>
                <a href="" class="hover:underline transition-all duration-300">Customers</a>
                <a href="" class="hover:underline transition-all duration-300">FAQ</a>
            </div>
            <div class="hidden lg:flex gap-5 items-center">
                <a href="" class="mt-5 hover:underline transition-all duration-300">Our Demo</a>
                <button class="py-2 mt-5 bg-white text-black rounded-full px-6">Join Beta</button>
            </div>
            <span class="mt-5 lg:hidden">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>

            </span>
        </div>
        <div class="mx-2 lg:mx-0 lg:mt-20 grid lg:grid-cols-2 gap-10">
            <div>
                <div class="border py-1.5 mt-10 rounded-full w-5/6 lg:w-1/2 flex items-center gap-4 pl-4 text-xs">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-sparkles" width="20" height="20" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M16 18a2 2 0 0 1 2 2a2 2 0 0 1 2 -2a2 2 0 0 1 -2 -2a2 2 0 0 1 -2 2zm0 -12a2 2 0 0 1 2 2a2 2 0 0 1 2 -2a2 2 0 0 1 -2 -2a2 2 0 0 1 -2 2zm-7 12a6 6 0 0 1 6 -6a6 6 0 0 1 -6 -6a6 6 0 0 1 -6 6a6 6 0 0 1 6 6z" /></svg>
                    Announcing our 1M seed round funding
                </div>
                <h1 class="lg:text-6xl text-4xl font-extrabold mt-10">The money app that just works</h1>

                <p className="mt-5 text-gray-300">
                    Step up your financial game with Grove and start living the right way and with lots of control over your money!
                </p>
                <div class="mt-10 flex text-xs lg:text-base gap-5">
                    <button class="border py-2 w-2/3 lg:w-full flex gap-3 rounded-xl px-4 items-center">

                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-appstore" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M12 12m-9 0a9 9 0 1 0 18 0a9 9 0 1 0 -18 0" />
                            <path d="M8 16l1.106 -1.99m1.4 -2.522l2.494 -4.488" />
                            <path d="M7 14h5m2.9 0h2.1" />
                            <path d="M16 16l-2.51 -4.518m-1.487 -2.677l-1 -1.805" /></svg>
                        Get it on App Store</button>
                    <button class="bg-white text-black w-2/3 lg:w-full py-2 flex gap-3 rounded-xl px-4 items-center">

                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-google-play" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M4 3.71v16.58a.7 .7 0 0 0 1.05 .606l14.622 -8.42a.55 .55 0 0 0 0 -.953l-14.622 -8.419a.7 .7 0 0 0 -1.05 .607z" />
                            <path d="M15 9l-10.5 11.5" />
                            <path d="M4.5 3.5l10.5 11.5" /></svg>
                        Get it on Play Store</button>
                </div>
                <div>
                    <div class="flex flex-col lg:flex-row mt-10 gap-3 items-center">
                        <div class=" flex -space-x-4 rtl:space-x-reverse">
                            <img src="../assets/images/1.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                            <img src="../assets/images/2.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                            <img src="../assets/images/3.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                            <img src="../assets/images/4.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                            <img src="../assets/images/5.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                            <img src="../assets/images/6.png" class="h-12 w-12  lg:h-16 lg:w-16" alt="">
                        </div>
                        <p class="text-gray-300">Over 20k delighted customers!</p>
                    </div>
                </div>
            </div>
           <div class="hidden lg:block">
            
                <img class="rounded-xl mt-10" src="https://cdn.dribbble.com/userupload/12881563/file/original-8a1f6276702fc7f48965253ed4800f7c.jpg?resize=3200x2400" alt="">
            
           </div>
        </div>
    </div>
</main>
</template>
