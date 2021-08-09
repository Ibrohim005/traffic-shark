<template>
    <div class="partners">
        <div class="container">
            <h3 class="partners__title">
                Еженедельные выплаты <span>от $100</span>
            </h3>
            <p class="partners__text">
                На удобную для вас платежную систему из перечисленных ниже
            </p>
            <div class="row">
                <div class="col-xl-2 col-md-3 col-sm-4 col-6 offset-xl-1">
                    <img src="../assets/partner1.png" alt="">
                </div>
                <div class="col-xl-2 col-md-3 col-sm-4 col-6">
                    <img src="../assets/partner2.png" alt="">
                </div>
                <div class="col-xl-2 col-md-3 col-sm-4 col-6"> 
                    <img src="../assets/partner3.png" alt="">
                </div>
                <div class="col-xl-2 col-md-3 col-sm-4 col-6">
                    <img src="../assets/partner4.png" alt="">
                </div>
                <div class="col-1 offset-xl-0 offset-md-4 offset-sm-2 offset-3">
                    <img src="../assets/partner5.png" alt="">
                </div>
                <div class="col-1 offset-xl-0 offset-md-2 offset-sm-2 offset-4">
                    <img src="../assets/partner6.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .partners{
        text-align: center;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 30px;
            line-height: 37px;
            text-transform: uppercase;
            color: #000000;
            span{
                color: #2E9ADB;
            }
        }
        &__text{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: #939393;
            margin: 20px 0 78px;
        }
    }
</style>