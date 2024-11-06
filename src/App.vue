<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <header class="w-full h-auto py-5 bg-slate-800">
        <div class="container text-center mx-auto">
            <a href="#" class="text-2xl text-white">Temporary Email</a>
        </div>
    </header>

    <div class="w-full h-auto py-5 bg-slate-800">
        <div class="container text-center mx-auto w-2/5">
            <div class="border-dashed border-2 border-slate-700 rounded-lg py-8">
                <h1 class="text-xl text-white font-Roboto_Mono mb-6">Địa chỉ email tạm thời của bạn</h1>
                <div class="flex justify-center">
                    <input type="text" class="h-14 w-96 rounded-full text-slate-50 bg-slate-700 border-none outline-none px-4 py-3 mr-2" readonly />
                    <button class="h-14 w-14 bg-slate-500 rounded-full ml-2 text-2xl hover:bg-slate-600 transition-colors duration-200 ease-in-out">
                        <font-awesome-icon :icon="['fas', 'copy']" />
                    </button>
                </div>
            </div>
            <label class="pt-8 pb-4 block text-sm font-medium">
                Quên thư rác, thư quảng cáo, robot xâm nhập và tấn công. Giữ cho hộp thư của bạn sạch sẽ và an toàn. Dịch vụ mail tạm thời cung cấp địa chỉ email tạm thời, an toàn, mang tính ẩn danh,
                miễn phí và dùng một lần.
            </label>
        </div>
    </div>
    <div class="drop-shadow-md">
        <div class="container text-center bg-white text-black">
            <div class="grid grid-cols-4 gap-4 w-1/2 mx-auto py-5">
                <button class="bg-gray-100 text-slate-600 font-medium hover:bg-slate-600 hover:text-gray-200 transition-colors duration-150 ease-in-out w-40 px-4 py-3 rounded-full drop-shadow-lg">
                    <font-awesome-icon :icon="['fas', 'copy']" class="mr-2" /> Chép
                </button>
                <button class="bg-gray-100 text-slate-600 font-medium hover:bg-slate-600 hover:text-gray-200 transition-colors duration-150 ease-in-out w-40 px-4 py-3 rounded-full drop-shadow-lg">
                    <font-awesome-icon :icon="['fas', 'arrows-rotate']" class="mr-2" /> Làm mới
                </button>
                <button class="bg-gray-100 text-slate-600 font-medium hover:bg-slate-600 hover:text-gray-200 transition-colors duration-150 ease-in-out w-40 px-4 py-3 rounded-full drop-shadow-lg">
                    <font-awesome-icon :icon="['fas', 'pen-to-square']" class="mr-2" /> Thay đổi
                </button>
                <button class="bg-gray-100 text-slate-600 font-medium hover:bg-slate-600 hover:text-gray-200 transition-colors duration-150 ease-in-out w-40 px-4 py-3 rounded-full drop-shadow-lg">
                    <font-awesome-icon :icon="['fas', 'trash']" class="mr-2" /> Xóa
                </button>
            </div>
        </div>
    </div>
</template>
