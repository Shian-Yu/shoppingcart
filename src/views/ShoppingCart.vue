<script>
import CartCard from '@/components/CartCard.vue';
import PublicBtn from '@/components/PublicBtn.vue'

export default{
  components:{
    CartCard,
    PublicBtn,
  },
}
</script>
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
    <CartCard></CartCard>
    <div class="flex flex-col items-end px-5 font-bold mb-4">
      <div class="text-2xl">商品數量: 0</div>
      <div class="text-2xl">商品總金額: $0</div>
    </div>
    <div class="flex justify-between px-5">
      <PublicBtn :link="'/'" :style="'bg-rose-600'" :content="'回上頁繼續購買'"></PublicBtn>
      <PublicBtn :link="'/shoppingcheck'" :style="'bg-blue-800'" :content="'確認購買'"></PublicBtn>
    </div>
  </div>


</template>

<style></style>
