<template>
    <div>
        <!-- 顶部返回开始-->
        <mt-header fixed title="">
            <router-link to="/me" slot="left" style="color:black">
            <mt-button icon="back"></mt-button>
            </router-link>
        </mt-header>
        <!-- 顶部返回结束-->
        <!--  内容区域开始-->
        <div class="lets">
            <div >
                <span class="letse">超市消费券
                    <div class="letsea">
                        <span>有效日期至2020.09.22</span>
                    </div>
                </span>
                <span class="letsed">￥9
                     <div class="letsea">
                        <span>满15可用</span>
                    </div>
                </span>
            </div>
            <div class="letsdes">
                <span class="letsdf">限商品现价+包装费满15元使用，限非到店自取订单，本账户商家首单，超市便利，医药健康，商品专售，水果商家使用，限本账户使用，不可转用</span>
            </div>
        </div>
        <!--  内容区域结束-->

    </div>
</template>
<style scoped>
    .lets{
    margin-top: 50px;
    margin-left: 20px;
    width: 90%;
    height: 150px;
    background-color: aliceblue;

    }
    .letse{
        position: absolute;
        padding: 20px;
        font-size:24px;
        color: red;
    }
    .letsed{
        position: absolute;
        padding: 20px;
        font-size: 24px;
        margin-left: 70%;
        color: red;
    }
    .letsea{
        margin-top: 5px;
        color: black;
        font-size: 10px;
    }
    .letsdes{
        margin-left: 10px;
        width: 80%;
        font-size: 12px;
        color: rgba(124, 118, 118, 0.87);
        /* font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; */
        position: absolute;
        margin-top: 100px;
    }
</style>