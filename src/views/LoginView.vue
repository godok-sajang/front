<template lang="">
  <div class="login">
    <div class="login__title">어서 오세요, 리뷰어님!</div>
    <input
      class="login__input"
      type="text"
      placeholder="아이디를 입력하세요"
    >
    <input
      class="login__input"
      type="text"
      placeholder="비밀번호를 입력하세요"
    >
    <button class="login__button" type="button">
      로그인
    </button>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="scss">
.login {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.login__title {
  font-size: 1.5rem;
  margin-bottom: 1.75rem;
}

.login__input {
  width: 20rem;
  height: 3rem;
  margin-bottom: 0.5rem;
  padding-left: 0.75rem;
  border-radius: 0.5rem;
  border: 1px solid $normal-gray;
  font-size: 1rem;
}

.login__button {
  width: 20rem;
  height: 3rem;
  border-radius: 0.5rem;
  font-size: 1rem;
  background-color: $black;
  margin-top: 1.75rem;
  color: $white;
}
</style>
