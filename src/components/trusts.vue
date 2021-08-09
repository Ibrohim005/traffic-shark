<template>
    <div class="trusts">
        <div class="container">
            <h3 class="trusts__title">
                Нам доверяют
            </h3>
            <div class="d-flex justify-content-center flex-wrap">
                <span class="trust" v-for="(item, index) in trusts" :key="index"> 
                    <img :src="item.icon" alt="Trusts icon">
                </span>
            </div>
            <p class="trusts__text">
                и десятки других популярных компаний
            </p>
        </div>
    </div>
</template>

<script>
export default{
    props:[
        "trusts"
    ]
}
</script>

<style lang="scss" scoped>
    .trusts{
        text-align: center;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 30px;
            line-height: 37px;
            text-transform: uppercase;
            color: #000000;
            margin-bottom: 80px ;
        }
        .trust{
            margin-right: 50px;
            margin-bottom: 50px;
        }
        &__text{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: #939393;
            margin-top: 30px;   
        }
    }
</style>