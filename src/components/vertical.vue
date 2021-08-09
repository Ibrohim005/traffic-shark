<template>
    <div class="vertical">
        <div class="container">
            <h3 class="vertical__title">
                Топовые вертикали
            </h3>
            <div class="vertical-cards">
                <div class="row">
                    <div class="col-lg-4 col-sm-6 col-12" v-for="(item, index) in verticals" :key="index">
                        <div class="vertical-card">
                            <span class="vertical-card__icon" v-html="item.icon"></span>
                            <h5 class="vertical-card__title">
                                {{ item.title }}
                            </h5>
                            <p class="vertical-card__text">
                                {{ item.text }}
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'vertical',

    props: [
        "verticals"
    ]
}
</script>

<style lang="scss" scoped>
    .vertical{
        padding: 80px 0;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 30px;
            line-height: 37px;
            text-transform: uppercase;
            color: #000000;
            text-align: center;
        }
        &-card{
            height: 350px;
            margin-bottom: 30px;
            background: #FFFFFF;
            box-shadow: 0px 20px 80px rgba(0, 0, 0, 0.08);
            border-radius: 8px;
            background: url('../assets/Group 39.png') no-repeat;
            padding: 40px;
            &__icon{
                margin-bottom: 87px;
                display: inline-block;
            }
            &__title{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 900;
                font-size: 20px;
                line-height: 25px;
                color: #000000;
                margin-bottom: 10px;
            }
            &__text{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 300;
                font-size: 14px;
                line-height: 16px;
                color: #000000;
            }
        }
    }
    @media screen and (max-width: 768px){
        .vertical-card{
            background-image: url('../assets/Group 40.png');
        }
    }
</style>