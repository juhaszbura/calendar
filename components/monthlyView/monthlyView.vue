<template>
    <div class="text-gray-700">
        <!-- Component Start -->
        <div class="flex flex-grow w-screen h-screen overflow-auto">

            <div class="flex flex-col flex-grow">
                <!-- Header -->
                <div class="flex items-center mt-4">
                    <div class="flex ml-6">
                        <button>
                            <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
                            </svg>
                        </button>
                        <button>
                            <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                            </svg>
                        </button>
                    </div>
                    <h2 class="ml-2 text-xl font-bold leading-none">September, 2020</h2>
                </div>
                <!-- Name of week days -->
                <div class="grid grid-cols-7 mt-4">
                    <div class="pl-1 text-sm">hétfő</div>
                    <div class="pl-1 text-sm">kedd</div>
                    <div class="pl-1 text-sm">szerda</div>
                    <div class="pl-1 text-sm">csütrötök</div>
                    <div class="pl-1 text-sm">péntek</div>
                    <div class="pl-1 text-sm">szombat</div>
                    <div class="pl-1 text-sm">vasárnap</div>
                </div>
                <!-- Days -->
                <div class="grid flex-grow w-full h-auto grid-cols-7 grid-rows-5 gap-px pt-px mt-1 bg-gray-200">
                    <div class="relative flex flex-col bg-white group">
                        <span class="mx-2 my-1 text-xs font-bold">1 September</span>
                        <div class="flex flex-col px-1 py-1 overflow-auto">
                            <button class="flex items-center flex-shrink-0 h-5 px-1 text-xs hover:bg-gray-200">
                                <span class="flex-shrink-0 w-2 h-2 border border-gray-500 rounded-full"></span>
                                <span class="ml-2 font-light leading-none">08:30</span>
                                <span class="ml-2 font-medium leading-none truncate">An unconfirmed event</span>
                            </button>
                            <button class="flex items-center flex-shrink-0 h-5 px-1 text-xs hover:bg-gray-200">
                                <span class="flex-shrink-0 w-2 h-2 bg-gray-500 rounded-full"></span>
                                <span class="ml-2 font-light leading-none">14:15</span>
                                <span class="ml-2 font-medium leading-none truncate">A confirmed event</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Component End  -->
    </div>
</template>

<script>
export default {
    name: "monthlyView"
}
</script>