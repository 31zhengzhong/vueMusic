<template>
  <div class="hello">
    <div class="Pahang">
      <div class="Pahang_div">
            <span class="Pahang_back" @click="$router.back()">
              <img src="../Paihang/imges/back.png" alt="">
            </span>
        <span class="Pahang_P">
               <p>MyMusic</p>
            </span>
        <span class="Pahang_fen">
              <img src="../Paihang/imges/xiala.png" alt="">
            </span>
      </div>
    </div>
    <div class="Songs_tabs">
      <ul>
        <li><div ><span >最爱</span></div></li>
        <li><div><span>收藏</span></div></li>
        <li><div><span>随声听</span></div></li>
      </ul>
    </div>
    <div class="Songs_body">
      <div class="Songs_body_div">
        <div class="Songs_body_A">
          <ul class="Songs_body_AUL">
            <!--<li class="Songs_body_AULI" v-for="items in 8">-->
              <!--<div class="Songs_body_AULI_a">-->
                <!--<img src="https://cdn.dribbble.com/users/912872/screenshots/4186388/dri_teaser.png" alt="">-->
              <!--</div>-->
              <!--<div class="Songs_body_AULI_b">-->
                <!--<h4>喜欢你</h4>-->
                <!--<p>黄家驹《beyond》</p>-->
              <!--</div>-->
              <!--<div class="Songs_body_AULI_c">-->
                <!--<span><img src="../Songs/imgs/xingShi.png" alt="">BonusTrack</span>-->
              <!--</div>-->
            <!--</li>-->
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {

    data () {
      return {

      }
    },
    methods:{

    },
    created(){

    }
  }
</script>
<style scoped>
  .active{
    box-shadow: 0 0 .5rem #f4f4f4;
    border-radius: 20%;

  }
  .hello{
    position: fixed;
    width: 100%;
    height: 100%;
    background-color: #ffffff;
  }
  .Pahang{
    width: 100%;
    height:2.3rem;
    border-bottom: .05rem solid #e8e8e8;
  }
  .Pahang_div{
    height: 100%;
    width: 100%;
    background-color: rgba(249, 249, 249, 0.07);
  }
  .Pahang_div img{
    height: 1.2rem;
    width:1.2rem;

  }
  .Pahang_back{
    float: left;
    margin-left: .4rem;
    margin-top: .4rem;
  }
  .Pahang_P{
    display: block;
    width: 80%;
    height:2rem;
    margin: 0 auto;
    font-size: .5rem;
    text-align: center;
    line-height: 2rem;
    float: left;
  }
  .Pahang_fen{
    float: right;
    margin-right:.2rem ;
    margin-top: .4rem;
  }
  /**/
  .Songs_tabs{
    width: 100%;
    height: 2rem;
    border-bottom: .02rem solid #f9f9f9;
    background-color: rgb(255, 89, 101);
  }
  .Songs_tabs ul{
    width: 100%;
    height: 100%;
    display:flex;

  }
  .Songs_tabs ul li{
    width: 25%;
    height: 100%;
    text-align: center;
  }
  .Songs_tabs ul li div{
    width: 50%;
    height: 3rem;
    margin: 0 auto;
    line-height:2.5rem;

  }
  .Songs_tabs ul li div span{
    width:100%;
    color: #f7f7f7;
    font-size: .5rem;
    font-weight: 700;
  }
  /**/
  .Songs_body{
    position: fixed;
    width: 100%;
    height: 85%;
    background-color: #f4f4f4;

  }
  .Songs_body_div{
    width: 100%;
    height: 100%;
  }
  .Songs_body_A{
    width: 100%;
    height: 100%;
  }
  .Songs_body_AULI{
    width: 100%;
    height: 3.4rem;
    border-bottom: .05rem solid #a0ff90;
    overflow: hidden;
  }
  .Songs_body_AULI_a{
    float: left;
  }
  .Songs_body_AULI_a img{
    padding: .3rem;
    width: 2.8rem;
    height: 2.8rem;
    border-radius: .6rem;
  }
  .Songs_body_AULI_b{
    padding: .3rem;
    float: left;
    font-size: .7rem;
  }
  .Songs_body_AULI_c{
    padding: .3rem;
    float: left;
    height: 100%;
    border: .03rem solid #000000;
  }
</style>
