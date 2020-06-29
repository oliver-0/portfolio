<template>
  <header>
    <div id="brand">
      <img id="profile-image" src="@/assets/images/profileimage.jpg">
      <div id="name-box">
        <div id="name">OLIVER DAVIES</div>
        <div id="title">WEB / UI DEVELOPER</div>
      </div>
    </div>
    <div>Nav</div>
  </header>
</template>

<script>
export default {
  name: 'top',
}
</script>

<style lang="scss" scoped>
@import "@/assets/css/variables.scss";
header {
  background-color: rgb(30, 30, 30);
  color: rgb(246, 245, 243);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 5px 20px;
}
#brand {
  display: flex;
  justify-content: space-between;
  align-items: center;
  #profile-image {
    height: 50px;
    width: 50px;
    border-radius: 50%;
    border: 2px solid $accent;
  }
  #name-box {
    margin: 5px 5px 5px 10px;
    #name {
      font-family: 'Titillium Web', sans-serif;
      font-size: 1.5rem;
      font-weight: 600;
      line-height: 1.2;
    }
    #title {
      font-family: 'Rubik', sans-serif;
      font-style: italic;
      font-weight: 400;
      font-size: 0.73rem;
      color: $accent-secondary;
    }
  }
}
</style>