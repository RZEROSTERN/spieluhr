<template>
    <div class="bg-black h-screen text-white">
        <h1 class="text-4xl font-bold p-4">Spieluhr</h1>
        <div>
            <div class="xl:py-2">
                <div class="group relative sidebar-item">
                    <a href="#" class="block xl:flex xl:items-center text-center xl:text-left shadow-light xl:shadow-none py-6 xl:py-2 xl:px-4 border-l-4 border-transparent hover:bg-black">
                        <svg class="h-6 w-6 text-white xl:mr-2"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <polyline points="5 12 3 12 12 3 21 12 19 12" />  <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />  <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" /></svg>
                        <div class="text-white text-xs"> Inicio</div>
                    </a>
                </div>
                <div class="group relative sidebar-item">
                    <a href="#" class="block xl:flex xl:items-center text-center xl:text-left shadow-light xl:shadow-none py-6 xl:py-2 xl:px-4 border-l-4 border-transparent hover:bg-black">
                        <svg class="h-6 w-6 text-white xl:mr-2" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <circle cx="10" cy="10" r="7" />  <line x1="21" y1="21" x2="15" y2="15" /></svg>
                        <div class="text-white text-xs">Buscar</div>
                    </a>
                </div>
                <div class="group relative sidebar-item">
                    <a href="#" class="block xl:flex xl:items-center text-center xl:text-left shadow-light xl:shadow-none py-6 xl:py-2 xl:px-4 border-l-4 border-transparent hover:bg-black">
                        <svg class="h-6 w-6 text-white xl:mr-2" viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <rect x="1" y="4" width="22" height="16" rx="2" ry="2" />  <line x1="1" y1="10" x2="23" y2="10" /></svg>
                        <div class="text-white text-xs">Premium</div>
                    </a>
                </div>
                <div class="hidden xl:block font-medium text-gray-300 text-xs px-4 py-2 mt-8">
                    Tu biblioteca
                </div>
                <div class="group relative sidebar-item with-children">
                    <div class="absolute xl:relative hidden xl:block pin-t xl:pin-none w-48 xl:w-auto group-hover:block bg-black z-50 xl:z-auto">
                        <a href="#" class="block text-left font-semibold xl:flex xl:items-center shadow xl:shadow-none py-3 px-3 xl:px-4 border-l-4 border-transparent text-white hover:text-blue-dark text-xs">
                            Creada para ti
                        </a>
                        <a href="#" class="block text-left font-semibold xl:flex xl:items-center shadow xl:shadow-none py-3 px-3 xl:px-4 border-l-4 border-transparent text-white hover:text-blue-dark text-xs">
                            Escuchado recientemente
                        </a>
                        <a href="#" class="block text-left font-semibold xl:flex xl:items-center shadow xl:shadow-none py-3 px-3 xl:px-4 border-l-4 border-transparent text-white hover:text-blue-dark text-xs">
                            Tus Me Gusta
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>