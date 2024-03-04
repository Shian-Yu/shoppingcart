<script>
</script>

<template>
  <main>
    <div class="p-2 text-3xl">商品列表</div>
    <div class="flex gap-3 justify-end px-3 mb-3">
      <i class="fa-solid fa-table-cells-large"></i>
      <i class="fa-solid fa-list"></i>
    </div>
    <!-- 以下商品頁面1 -->
    <div class="flex flex-wrap w-11/12 m-auto gap-4 justify-center">
      <!-- 以下商品card -->
      <div class="flex flex-col w-1/6 min-w-[150px] min-h-[550px] rounded-xl border overflow-hidden ">
        <img src="https://fakeimg.pl/300/">
        <div class="md-5">
          <h2 class="my-4">Bytecard</h2>
          <p class="my-4 break-words">Immunization not carried out because of caregiver refusal</p>
          <p class="my-5">價格: 954</p>
        </div>
        <div class="flex-grow"></div>
        <div class="flex">
          <div>數量：</div>
          <div class="flex h-[35px]">
            <button class="w-1/4 border rounded-l-xl">-</button>
            <input type="number" class="w-2/4 border text-center" value="1">
            <button class="w-1/4 border rounded-r-xl">+</button>
          </div>
        </div>
        <div class="text-center bg-blue-300 text-white"><i class="fa-solid fa-cart-shopping relative"></i>加入購物車</div>
      </div>
      <!-- 以上商品card -->
    </div>
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
          <div class="text-center bg-blue-300 text-white rounded-3xl"><i class="fa-solid fa-cart-shopping relative"></i>加入購物車</div>
        </div>
        <div></div>
      </div>
      <!-- 以上商品清單 -->
    </div>
  </main>
</template>
