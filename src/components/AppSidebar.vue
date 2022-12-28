<template>
  <div class="logo">
    <div>
      <img src="@/assets/logo.svg" alt="" />
    </div>
    <div class="logoname">Parksmart</div>
  </div>
</template>
<style scoped>
.logo{
    padding: 0 15px 0 15px;
    margin-top: 40px;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 8px;
}
.logoname {
  font-family: "Inter";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 120%;
  color: #ffffff;
  flex: none;
  order: 1;
  flex-grow: 0;
}
</style>