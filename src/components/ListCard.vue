<script>

</script>

<template>
    <!-- 以下商品頁面2 -->
    <div class="flex flex-wrap w-11/12 m-auto justify-center">
        <div class="grid grid-cols-6 w-full m-auto justify-center p-2 border-y gap-2 font-bold">
            <div class="text-center">商品圖片</div>
            <div>商品名稱</div>
            <div class="text-center">商品描述</div>
            <div class="text-center">價錢</div>
            <div></div>
            <div></div>
        </div>
        <!-- 以下商品清單 -->
        <div class="grid grid-cols-6 w-full m-auto justify-center items-center p-2 border-b gap-2">
            <div class="m-auto max-w-[200px] max-h-[200px]"><img src="https://fakeimg.pl/300/"></div>
            <div class="break-words">Bytecard</div>
            <div class="break-words">mmunization not carried out because of caregiver refusal</div>
            <div class="text-center">$954</div>
            <div>
                <div class="flex h-[35px]">
                    <button class="w-1/4 border rounded-l-3xl">-</button>
                    <input type="number" class="w-2/4 border text-center" value="1">
                    <button class="w-1/4 border rounded-r-3xl">+</button>
                </div>
                <div class="text-center bg-blue-300 text-white rounded-3xl text-sm"><i
                        class="fa-solid fa-cart-shopping relative"></i>加入購物車</div>
            </div>
            <div></div>
        </div>
        <!-- 以上商品清單 -->
    </div>
</template>