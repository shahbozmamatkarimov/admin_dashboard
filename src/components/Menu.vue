<template>
    <nav class="flex bg-[#343E59] z-50 pt-5 pb-3 justify-between items-center mb-10 text-white fixed">
        <h1 class="text-3xl font-medium py-1">
            <slot></slot>
        </h1>
        <div class="flex items-center gap-5 text-xl">
            <router-link to="/"><i class="bx bxs-dashboard"></i></router-link>
            <router-link to="/profile"><i class="bx bxs-user-circle "></i></router-link>
            <router-link to="/messages"><i class="bx bxs-chat"></i></router-link>
            <img class="h-10 w-10 border-2 rounded-full" src="https://i.ibb.co/PQ4mRtC/myphoto-Round.png" alt="img">
        </div>
    </nav>
</template>

<script setup></script>

<style lang="scss" scoped></style>