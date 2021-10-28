<template>
  <div id="app">
    <!-- <div>
      <input v-model="num1" />
    </div>
    <div>
      <input v-model="num2" />
    </div>
    <div>
      {{result}}
    </div> -->
    <!-- <div v-for="item,i in items" :key="i">
      {{ fillter(item)}}
    </div> -->
    <!-- <button @click="display()">
      Click Me!
    </button> -->
    <!-- <div :style="{'font-size' : x +'px'}">
        {{message}}
    </div>
    <button @click="change()">
      Click to change position
    </button>
    <button @click="changePX()">
      Click to change PX
    </button> -->
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      // items :[
      //   1000,
      //   2000,
      //   3000
      // ],
      // message : 'Hello mew',
      // Active : true,
      // x : 100,
      // Active1 :true
     
    };
  },
  watch: {
    // message(value){
    //   return console.log(value)
    // }

  },
  computed: {
    //เรียกใช้ไม่ต้องมี ( ) เป็นการUpdate
    // result(){
    //   return Number(this.num1)+Number(this.num2)
    // }
  },
  created() {
    //ทำงานเกือบแรกสุด ทำงานตั้งแต่ยังสร้างเว็บไม่เสร็จ
    // console.log("Created Functions");
  },
  mounted() {
    // ทำงานหลังสร้างเว็บเสร็จ เป็นการเรียกใช้ใหม่ทุกครั้ง
    // console.log("Mounted Functions");
  },
  methods:{
    //เรียกใช้ต้องมี ( )
    // fillter(value){
    //   return value.toLocaleString()
    // }
    // display(){
    //   return this.message = "Hello Fia"
    // }
    // change(){
    //   this.Active = !this.Active
    // },
    // changePX(){
    //   this.Active1 = !this.Active1
    // }
  }
};
</script>

<style  scoped>
/* .ter {
  text-align: center;
  
} */
</style>
