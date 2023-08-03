<template>
    <div>
        <div class="back py-[100px] overflow-hidden">
            <h2
                class="text-[#fff] text-3xl sm:text-5xl text-center  font-[900] leading-[34px] sm:leading-[64px] tracking-[0.24px]">
                Some count that matters</h2>
            <p class="text-[#fff] text-lg leading-[32px] text-center tracking-[0.5px]">Our achievement in the journey
                depicted in numbers</p>
            <div class="flex items-center justify-center flex-col sm:flex-row mt-5">
                <div class=" sm:border-r-2 px-[5px] sm:px-[50px] ">
                    <h1 class="text-2xl sm:text-5xl font-[800] text-[#fff] leading-[64px] text-center">30</h1>
                    <p class="text-[#fff] text-lg text-center">Clients</p>
                </div>
                <div class=" sm:border-r-2   px-[5px] sm:px-[50px] ">
                    <h1 class="text-2xl sm:text-5xl font-[800] text-[#fff] leading-[64px] text-center">300+</h1>
                    <p class="text-[#fff] text-lg text-center">Taken business legalities</p>
                </div>
                <div class="px-[5px] sm:px-[50px]">
                    <h1 class="text-2xl sm:text-5xl font-[800] text-[#fff] leading-[64px] text-center">8</h1>
                    <p class="text-[#fff] text-center text-lg">Years of Journey</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Count'
}
</script>
<style scoped>
.back {
    background-image: url(../assets/image/BG.png);
    height: 380px;
}

@media(max-width:640px) {
    .back {
        height: auto;
    }
}
</style>