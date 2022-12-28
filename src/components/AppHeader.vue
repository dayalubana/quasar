<template>
  <div class="header">
    <div>
      <img src="@/assets/map.svg" alt="" />
    </div>
    <div>Reserve Parking</div>
    <div class="bell">
      <img src="@/assets/bell.svg" alt="" />
    </div>
    <div class="notify-count">
      <p class="notifications">12</p>
    </div>
    <div>
      <img src="@/assets/avatar.svg" alt="" />
    </div>
    <div>
      <div class="user">
        <div>Brooklyn Simmons</div>
        <div>brooklyn@simmons.com</div>
      </div>
    </div>
    <div>
      <img src="@/assets/3dots.svg" alt="" />
    </div>
  </div>
</template>
<style scoped>
.header {
  margin: 10px 20px 0 20px;
  display: flex;
  justify-content: end;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 20px;
}
.notifications {
  width: 28px;
  height: 22px;
  background: #fb5d64;
  border-radius: 24px;
  color: #ffffff;
  padding-left: 5px;
}
.user {
  display: flex;
  flex-direction: column;
}
.bell {
  padding-top: 5px;
}
.notify-count {
  padding-top: 15px;
  margin-left: -5px;
}
</style>