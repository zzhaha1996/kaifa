<template>
    <div>
        <div>
            <span>企业画像</span>
            <ul>
                <li @click="showxinxi">
                        <img src="../../../assets/qiyexinxi.png" alt="">
                         <span>企业信息</span>
                </li>
                <li @click="showweizhi">
                        <img src="../../../assets/hedaojianguan.png" alt="">
                        <span>空间位置</span>
                </li>
                <li @click="showjingying">
                        <img src="../../../assets/jingyingguanli.png" alt="">
                        <span>生产经营</span>
                </li>
                <li @click="showjiandu">
                        <img src="../../../assets/hedaojianguan.png" alt="">
                        <span>环保监管</span>
                </li>
                <li @click="showpaifang">
                       <img src="../../../assets/wuranyuan.png" alt="">
                       <span>污染排放</span>
                </li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    name: 'CompanyInfoNew',
   data(){
       return{

       }
   },
   methods: {
       showxinxi(id){
           this.$router.push({ name: 'companyInfoNewInfo'})
       },
       showweizhi(){
           this.$router.push({ name: 'companyInfoNewInfoWzhi'})
       },
       showjingying(){
           this.$router.push({ name: 'companyInfoNewJingying'})
       },
       showjiandu(){
           this.$router.push({ name: 'companyInfoNewHuanbao' })
       },
       showpaifang(){
           this.$router.push({ name: 'companyInfoNewWupan' })
       }
      
      
    }
}
</script>
<style scoped>

</style>


