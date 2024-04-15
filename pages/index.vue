<script setup>

const form = reactive({
    data: {
        username: "",
        password: ""
    },
});

</script>

<template>
    <NuxtLayout>
        <div class="w-full h-screen flex justify-center items-center">
            <div class="w-[616px] bg-basegray flex flex-col justify-center items-center shadow-xl p-5">
                <div class="flex flex-col text-[27px]">
                    <label for="">Username</label>
                    <input v-model="form.data.username" type="text"
                        class="w-[453.65px] h-[57.57px] bg-white rounded-[10px] shadow-inner border border-black mb-8 px-3" />
                </div>
                <div class="flex flex-col text-[27px]">
                    <label for="">Password</label>
                    <input v-model="form.data.password" type="password"
                        class="w-[453.65px] h-[57.57px] bg-white rounded-[10px] shadow-inner border border-black mb-8 px-3" />
                </div>

                <div class="flex items-center justify-center ">
                    <button class="w-[164px] h-[63px] text-white rounded-lg shadow bg-red-600 text-[30px] mt-4"> <NuxtLink to="/dashboard" 
                       >
                        Log - in
                    </NuxtLink > 
                </button>
                </div>


                <NuxtLink class="text-[19px] text-content">Forgot Password?</NuxtLink>

                <p class="text-[19px] text-primary">Register for new employee</p>
            </div>
        </div>
    </NuxtLayout>
</template>
