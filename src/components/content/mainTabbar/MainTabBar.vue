<!--  -->
<template>
  <tab-bar>
       <tab-bar-item path='/home'>
         <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
         <img slot="item-icon-active" src="~assets/img/tabbar/home_active.svg" alt="">
         <div slot="item-text">首页</div>
       </tab-bar-item>
       <tab-bar-item path='/category'>
         <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
         <img slot="item-icon-active" src="~assets/img/tabbar/category_active.svg" alt="">
         <div slot="item-text">分类</div>
       </tab-bar-item>
       <tab-bar-item path='/cart'>
         <img slot="item-icon" src="~assets/img/tabbar/cart.svg" alt="">
         <img slot="item-icon-active" src="~assets/img/tabbar/cart_active.svg" alt="">
         <div slot="item-text">购物车</div>
       </tab-bar-item>
       <tab-bar-item path='/profile'>
         <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
         <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.svg" alt="">
         <div slot="item-text">我的</div>
       </tab-bar-item>
    </tab-bar>
</template>

<script>
  import TabBar from 'components/common/tabbar/Tabbar'
  import TabBarItem from 'components/common/tabbar/TabBarItem'
//这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
//例如：import 《组件名称》 from '《组件路径》';

export default {
//import引入的组件需要注入到对象中才能使用
components: {
  TabBar,
  TabBarItem
},
name: '',
data() {
//这里存放数据
return {

};
},
//监听属性 类似于data概念
computed: {},
//监控data中的数据变化
watch: {},
//方法集合
methods: {

},
//生命周期 - 创建完成（可以访问当前this实例）
created() {

},
//生命周期 - 挂载完成（可以访问DOM元素）
mounted() {

},
beforeCreate() {}, //生命周期 - 创建之前
beforeMount() {}, //生命周期 - 挂载之前
beforeUpdate() {}, //生命周期 - 更新之前
updated() {}, //生命周期 - 更新之后
beforeDestroy() {}, //生命周期 - 销毁之前
destroyed() {}, //生命周期 - 销毁完成
activated() {}, //如果页面有keep-alive缓存功能，这个函数会触发
}
</script>
<style scoped>
/*@import url(); 引入公共css类 */

</style>