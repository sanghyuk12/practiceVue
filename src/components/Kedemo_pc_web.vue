<template>
  <div id="all_wrap">

    <!-- [s] top -->
    <div class="header">
    <div id="top_wrap">
      <div class="fix">
        <div class="top_section_box">
          <div class="logo_box">
            <img class="img-time-matters" :src="require(`../assets/img/layout/top_logo.png`)">
          </div>
          <div class="lnk_box">
            <div class="lnk_topbox">
              <ul>
                  <li><a href="javascript:;" onclick="login()">로그인</a></li>
                  <li><a href="javascript:;" onclick="join()">회원가입</a></li>
                <li><a href="javascript:;">고객센터</a></li>
              </ul>
            </div>
          </div>
          <div class="top_menu_box">
            <ul>
              <li id="mainTab" class="on"><a href="<c:url value='/front/main/main.do' />">홈</a></li>
              <li id="tb"><a href="#" onclick="goTb()">항공권 예매</a></li>
              <li id="mm"><a href="#" onclick="goMm()">나의 마일리지</a></li>
              <li id="mr"><a href="#" onclick="goMr()">나의 예약내역</a></li>
              <li id="mf" class="last"><a href="#" onclick="goMf()">나의 가족</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- [e] top -->
    </div>
    <!-- [s] bottom -->
    <div class="footer">
    <div id="footer_wrap">
      <div class="term_meet">
        <div class="term">
          <a href="#" class="first">개인정보 취급방침</a>
          <a href="#">이용약관</a>
        </div>
      </div>

      <div class="footer_box">
        <div class="footer_lnk_box">
          <p class="copy"><span>이원정보기술</span><br/>(우) 13494 경기도 성남시 분당구 판교역로 231 H스퀘어 S동 811호0</p>
          <p class="copy">COPYRIGHT (C) E1. ALL RIGHTS RESERVED.</p>
        </div>
      </div>
    </div>
    </div>
    <!-- [e] bottom -->
  </div>
</template>

<script>

export default {
  name: 'Kedemo_pc_web',
  props: {
    msg: String
  }

}
</script>

<style scoped src="../assets/css/style.css">

</style>