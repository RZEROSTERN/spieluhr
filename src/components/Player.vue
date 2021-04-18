<template>
    <div class="bg-gray-700 text-white grid grid-cols-12 h-18">
        <div class="col-span-2 flex justify-start items-center">
            <div class="px-12">
                <p class="font-bold text-sm">Le Song</p>
                <p class="text-xs text-gray-400">Le Artist</p>
            </div>
        </div>
        <div class="col-span-8 grid grid-rows-2">
            <div>
                <PlayerControllers />
            </div>
            <div class="flex justify-center items-center h-2 mt-4">
                <PlayerSeeker />
            </div>
        </div>
        <div class="flex justify-end items-center col-span-2">
            <svg class="h-6 w-6 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z"/>
            </svg>
            <VolumeSeeker />
        </div>
    </div>
</template>
<script>
import PlayerSeeker from './PlayerSeeker.vue'
import PlayerControllers from './PlayerControllers.vue'
import VolumeSeeker from './VolumeSeeker.vue'

export default {
    components: {PlayerSeeker, PlayerControllers, VolumeSeeker}
}
</script>