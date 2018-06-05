<template>
    <div class="web-right-buttons">
        <div><a class="button button--primary" href="">  开始免费试用</a></div>
        <ul class="support--navigation">
            <li class="navigation--tier-one sign-in--wrap">
            <a class="navigation--item" href="javascript:;">登录</a>
            </li>
        </ul>
    </div>
</template>
<style lang="scss" scoped>
@import url("../css/button.scss");
$mobileViewWidth: 767px;

.web-right-buttons {
  display: none;
}

.navigation--item {
  color: #616161;
  cursor: pointer;
  display: block;
  font-size: 14px;
  font-weight: 400;
  line-height: 16px;
  margin-bottom: 0;
  padding: 20px;
  position: relative;
  width: 100%;
}

.button {
    float: left;
    font-size: 14px;
    line-height: 36px;
    min-height: 36px;
    padding: 0 16px;
}

@media (min-width: $mobileViewWidth) {
  .topbar {
    .web-right-buttons {
      display: flex;
      position: absolute;
      align-items: center;
      right: 0;
    }
  }
}
</style>

