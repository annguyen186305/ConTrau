<template>
  <div>
    <p>{{mota }}</p>
    Trâu aasfafa(còn gọi là trâu nước) là một loài động vật thuộc họ Trâu bò (Bovidae), phân bộ Nhai lại (Ruminantia), nhóm sừng rỗng (Cavicornes), bộ Guốc chẵn (Actiodactyla), lớp Thú có vú (Mammalia). Chúng sống hoang dã ở Nam Á, Đông Nam Á, miền bắc Úc
    <ConNghe duongdan="https://png.pngtree.com/png-vector/20230902/ourmid/pngtree-cute-cow-cartoon-clipart-png-image_9637644.png"/>
    <ConNghe duongdan="https://png.pngtree.com/png-vector/20230902/ourmid/pngtree-cute-cow-cartoon-clipart-png-image_9637644.png"/>
    <ConNghe duongdan="https://cly.1cdn.vn/2021/02/09/hinh-minh-hoa.jpg"/>
  </div>
</template>

<script>
import ConNghe from "@/components/ConNghe.vue";

export default {
  name: 'ConTrau',
  props: {
      mota: String
  },
  components :{
    ConNghe
  }
}
</script>

<style scoped>

</style>