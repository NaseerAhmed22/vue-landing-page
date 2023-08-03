<template>
    <div class=" text-gray-100 py-4 px-6 md:flex justify-between items-center container mx-auto sm:px-3 md:px-5 lg:px-5  xl:px-5">
        <div class="flex items-center cursor-pointer">
            <span class="flex items-center text-green-500 text-xl mr-1">
                <img src="../assets/image/logo.png" class="border-2 rounded-full" alt="">
                <h1 class="font-bold text-xl hover:text-green-500 duration-300 ml-2">LAWYER</h1>
            </span>
        </div>
        <span class="md:hidden absolute right-6 top-7 cursor-pointer text-4xl text-black">
            <i :class="[open ? 'bi bi-x' : 'bi bi-filter-left']" @click="menuOpen"></i>
        </span>
        <ul
            class="md:flex md:items-center md:px-0 px-6 md:pb-0 bg-white pb-10 md:static absolute text-black md:w-auto w-full top-17 duration-700 ease-in " :class="[open ? 'left-0' : 'left-[-100%]']">
            <li class="md:mx-5 md:my-0 my-6">
                <a  href="#contact" class="text-base font-normal hover:text-green-500 duration-300">CONTACT</a>
            </li>
            <li class="md:mx-5 md:my-0 my-6">
                <a  href="#testimonials" class="text-base font-normal hover:text-green-500 duration-300">TESTIMONIALS</a>
            </li>
            <li class="md:mx-5 md:my-0 my-6">
                <a  href="#about" class="text-base font-normal hover:text-green-500 duration-300">ABOUT</a>
            </li>
            <li class="md:mx-5 md:my-0 my-6">
                <a  href="#terms" class="text-base font-normal hover:text-green-500 duration-300">TERMS</a>
            </li>
        </ul>
    </div>
</template>
<script>

export default {
    name: 'Nav',
    data() {
        return {
            open: false
        }
    },

    methods: {
        menuOpen() {
            this.open = !this.open
        },

    }

}
</script>

<style></style>