<template>
  <div id="layout-main">
    <top id="component-top"/>
    <Nuxt id="component-Nuxt" />
  </div>
</template>

<style lang="scss">
@import "@/assets/css/global.scss";
</style>

<style lang="scss" scoped>
#layout-main {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
#component-top {
  flex: 0 0 auto;
}
#component-Nuxt {
  flex: 1 0 auto;
}
.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}
.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}
.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}
.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
