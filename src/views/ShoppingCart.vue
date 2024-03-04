<template>
  <div class="p-2 text-3xl">購物車確認</div>
  <div>
    <div class="grid grid-cols-6 w-11/12 m-auto justify-center p-2 border-y gap-2 font-bold">
      <div></div>
      <div class="text-center">商品圖片</div>
      <div>商品名稱</div>
      <div class="text-center">價錢</div>
      <div></div>
      <div></div>
    </div>
    <!-- 以下商品清單 -->
    <div class="grid grid-cols-6 w-11/12 m-auto justify-center items-center p-2 border-b gap-2 mb-5">
      <div class="flex justify-center"><input type="checkbox"></div>
      <div class="m-auto max-w-[100px] max-h-[100px]"><img src="https://fakeimg.pl/300/"></div>
      <div class="break-words">Bytecard</div>
      <div class="text-center">$954</div>
      <div>
        <div class="flex h-[35px]">
          <button class="w-1/4 border rounded-l-3xl">-</button>
          <input type="number" class="w-2/4 border text-center" value="1">
          <button class="w-1/4 border rounded-r-3xl">+</button>
        </div>
      </div>
      <div></div>
    </div>
    <!-- 以上商品清單 -->
    <div class="flex flex-col items-end px-5 font-bold mb-4">
      <div class="text-2xl">商品數量: 0</div>
      <div class="text-2xl">商品總金額: $0</div>
    </div>
    <div class="flex justify-between px-5">
      <button class="bg-rose-600 p-2 rounded-lg">回上頁繼續購買</button>
      <button class="bg-blue-800 text-white p-2 rounded-lg">確認購買</button>
    </div>
  </div>


</template>

<style></style>
