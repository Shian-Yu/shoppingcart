<script>
import PublicBtn from '@/components/PublicBtn.vue'
import LabelCheck from '@/components/LabelCheck.vue'
import CheckList from '@/components/CheckList.vue'

export default {
  components: {
    PublicBtn,
    LabelCheck,
    CheckList,
  },
  data(){
    return{
      formData:{
        name:'AAA',
        phone:'09123456789',
        address:'台北市',
        email:'abcdedfg@gmail.com',
      }
    }
  },
}
</script>

<template>
  <div class="p-2 text-3xl">購物車確認</div>
  <div>
    <div class="grid grid-cols-4 w-11/12 m-auto justify-center p-2 border-y gap-2 font-bold">
      <div class="text-center">商品圖片</div>
      <div>商品名稱</div>
      <div class="text-center">價錢</div>
      <div class="text-center">數量</div>
    </div>
    <CheckList></CheckList>
    <form action="">
      <LabelCheck :content="'姓名'" required :value-data="formData.name" @update="(value) => formData.name = value"></LabelCheck>
      <LabelCheck :content="'電話'" required :value-data="formData.phone" @update="(value) => formData.phone = value"></LabelCheck>
      <LabelCheck :content="'地址'" required :value-data="formData.address" @update="(value) => formData.address = value"></LabelCheck>
      <LabelCheck :content="'電子信箱'" required :value-data="formData.email" @update="(value) => formData.email = value"></LabelCheck>
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
    </form>
    <div class="flex justify-between px-5 pb-3">
      <PublicBtn :link="'/shoppingcart'" :style="'bg-rose-600'" :content="'回上頁繼續加購'"></PublicBtn>
      <PublicBtn :link="'/shoppingcheck'" :style="'bg-blue-800'" :content="'確認送出'"></PublicBtn>
    </div>
  </div>


</template>

<style></style>