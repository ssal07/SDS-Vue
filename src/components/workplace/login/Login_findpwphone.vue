<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery findid">
        <!-- header -->
        <div id="header">
          <button type="button" class="btn only prev"><span class="ico">이전</span></button>
          <p class="font_19"></p>
        </div>
        <!-- //header -->
        
        <div id="content" class="etc">
          <div class="cell">
            <div class="inner">
                <h1 class="h-tit1">핸드폰 번호로 찾기</h1>

                <!-- list -->
                <ul class="ulList type1">
                    <li>
                        <strong class="label-tit">아이디</strong>
                        <input type="text" class="input" placeholder="아이디 입력">
                    </li>
                    <li>
                        <strong class="label-tit">이름</strong>
                        <input type="text" class="input" placeholder="이름 입력">
                    </li>
                    <li>
                        <strong class="label-tit">휴대전화</strong>
                        <input type="text" class="input" placeholder="‘-‘ 없이 숫자만 입력">
                    </li>
                </ul>
                <!-- // list -->
            </div>
          </div>
        </div>

        <!-- floating button -->
        <div class="fixBtmBtn">
            <ul>
                <li><button type="button" class="btn md clr1">확인</button></li>
            </ul>
        </div>
        <!-- //floating button -->

        
      </div>
      <!-- //container --> 
        
      
    </div>
    <!-- //wrap -->

</template>

<script>
export default {
  name: 'Login_findpwphone',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
    }
  },
  /* vue function */
  methods: {
  }
}
</script>
