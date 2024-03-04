<template>
    <div class="p-2 text-3xl">購物車確認</div>
    <div>
      <div class="grid grid-cols-4 w-11/12 m-auto justify-center p-2 border-y gap-2 font-bold">
        <div class="text-center">商品圖片</div>
        <div>商品名稱</div>
        <div class="text-center">價錢</div>
        <div class="text-center">數量</div>
      </div>
      <!-- 以下商品清單 -->
      <div class="grid grid-cols-4 w-11/12 m-auto justify-center items-center p-2 border-b gap-2 mb-5">
        <div class="m-auto max-w-[100px] max-h-[100px]"><img src="https://fakeimg.pl/300/"></div>
        <div class="break-words">Bytecard</div>
        <div class="text-center">$954</div>
        <div class="text-center">1</div>
      </div>
      <!-- 以上商品清單 -->
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="name" class="font-bold">姓名</label>
        <input class="w-full border-2 rounded-md" type="text">
      </div>
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="phone" class="font-bold">電話</label>
        <input class="w-full border-2 rounded-md" type="text">
      </div>
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="address" class="font-bold">地址</label>
        <input class="w-full border-2 rounded-md" type="text">
      </div>
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="email" class="font-bold">電子信箱</label>
        <input class="w-full border-2 rounded-md" type="email">
      </div>
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="pay" class="font-bold">付款方式</label>
        <div class="flex gap-2 text-lg">
            <input type="radio" id="pay1"><label for="pay1">信用卡</label><br>
            <input type="radio" id="pay2"><label for="pay2">貨到付款</label>
        </div>
      </div>
      <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="delivery" class="font-bold">運送方式</label>
        <div class="flex gap-2 text-lg">
            <input type="radio" id="delivery1"><label for="delivery1">宅配</label><br>
            <input type="radio" id="delivery2"><label for="delivery2">超商取貨</label>
        </div>
      </div>
      <div class="flex flex-col items-end px-5 mb-5 font-bold">
        <div class="text-2xl">商品數量: 0</div>
        <div class="text-2xl">商品總金額: $0</div>
      </div>
      <div class="flex justify-between px-5">
        <button class="bg-rose-600 p-2 rounded-lg">回上頁繼續加購</button>
        <button class="bg-blue-800 text-white p-2 rounded-lg">確認送出</button>
      </div>
    </div>
  
  
  </template>
  
  <style></style>
  