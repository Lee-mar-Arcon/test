<template>
    <div class="absolute bottom-0 left-0 right-0 z-10 bg-[#181818] border-t border-white/10">
        <div class="flex text-base/5 items-center justify-start px-2 gap-x-2">
            <Icon icon="lets-icons:remote" />
            <div class="flex items-center gap-x-0.5">
                <Icon icon="carbon:close-outline" />
                <span class="text-xs">1</span>
            </div>
            <div class="flex items-center gap-x-0.5">
                <Icon icon="typcn:warning-outline" />
                <span class="text-xs">1</span>
            </div>
            <div class="ml-auto text-[13px] flex gap-x-4 items-center">
                <span>Ln 14, Col 29</span>
                <span>Spaces: 4</span>
                <span>UTF-8</span>
                <span>CRLF</span>
                <span>{ } Vue</span>
                <Icon icon="ri:copilot-line" />
                <Icon icon="codicon:bell-dot" />
            </div>
        </div>
    </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';


</script>

<style lang="scss" scoped></style>