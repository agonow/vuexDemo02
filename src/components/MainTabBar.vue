<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="red">
      <img slot="item-icon" src="../assets/img/tabBar/home.svg" alt="" />
      <img
        slot="item-icon-active"
        src="../assets/img/tabBar/home_active.svg"
        alt=""
      />
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="red">
      <img slot="item-icon" src="../assets/img/tabBar/category.svg" alt="" />
      <img
        slot="item-icon-active"
        src="../assets/img/tabBar/category_active.svg"
        alt=""
      />
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="red">
      <img slot="item-icon" src="../assets/img/tabBar/shopcart.svg" alt="" />
      <img
        slot="item-icon-active"
        src="../assets/img/tabBar/shopcart_active.svg"
        alt=""
      />
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="red">
      <img slot="item-icon" src="../assets/img/tabBar/profile.svg" alt="" />
      <img
        slot="item-icon-active"
        src="../assets/img/tabBar/profile_active.svg"
        alt=""
      />
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>
<script>
import TabBar from "./tabbar/TabBar";
import TabBarItem from "./tabbar/TabBarItem";
export default {
  components: {
    TabBar,
    TabBarItem
  }
};
</script>
<style lang=""></style>
