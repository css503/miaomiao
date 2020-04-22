<template>
    <div id="main">
       <Header title="我的喵喵"/>
        <div id="content">
            <Login />
        </div>
       <TabBar />
    </div>
</template>
<script>
//引入header和tabbar组件,@表示src目录
import Header from '@/components/Header';
import TabBar from '@/components/TabBar';
import Login from '@/components/Login';
export default {
    name:'Mine',
     components:{
        Header,
        TabBar,
        Login
    }
}
</script>
<style>

</style>