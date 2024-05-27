<script>

</script>

<template>
  <div class="wrraper">
    <header>
      <img alt="logo">

      <ul class="header-items-info">
        <li>Геймплей</li>
        <li>Персонажи</li>
        <li>Локация</li>
        <li>Lore</li>
      </ul>

      <div class="bascet">
        <img alt="bascet">
        <div class="bascet-info">
           <p>Корзина</p>
           <p>0 Р</p>
        </div>
      </div>
    </header>
  </div>
</template>

<style scoped>
.wrraper{
  width: 100%;
  height: 100px;
  display: flex;
  justify-content: center;
}
header {
  width: 90%;
  height: 80%;
  border:1px solid black;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.header-items-info {
  text-decoration: none;
  display: flex;
  justify-content: space-between;
}

.header-items-info li {
  list-style-type: none;
  margin-right: 50px;
}

.bascet{
  display: flex;
}
</style>