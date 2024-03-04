<script>
export default{
  props:{
    valueData:{
      type:String,
      default:'',
    },
    content:{
      type:String,
      default:'',
    },
    type:{
      type:String,
      default:'text',
    },
    required:Boolean,
  },
  emits:['update'],
  data(){
    return{
      newValue:this.valueData,
    };
  },
  watch:{
    newValue:{
      handler(newValue){
        this.$emit('update',newValue)
      }
    }
  }
};
</script>

<template>
    <div class="flex flex-col w-11/12 m-auto gap-2 mb-4 text-xl">
        <label for="name" class="font-bold">{{ content }}<span v-show="required" class="text-rose-700">*</span></label>
        <input v-model="newValue" class="w-full border-2 rounded-md" type="text" required>
    </div>
</template>