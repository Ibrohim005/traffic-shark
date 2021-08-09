<template>
    <div class="regist">
        <div class="container">
            <h3 class="regist__title">
                Работать с нами это
            </h3>
            <div class="regist-cards">
                <div class="row">
                    <div class="col-6 col-md-4" v-for="(item, index) in regists" :key="index">
                        <div class="regist-card">
                            <span v-html="item.icon"></span>
                            <p class="regist-card__text">
                                {{ item.text }}
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <button class="button button_outline-green">Регистрация</button>
        </div>
    </div>
</template>

<script>
export default {
    name:'regist',

    props: [
        "regists"
    ]
}
</script>

<style lang="scss" scoped>
    .regist{
        text-align: center;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 30px;
            line-height: 37px;
            text-transform: uppercase;
            color: #000000;
            margin-bottom: 80px;
        }
        &-card{
            margin-bottom: 80px;
            &__text{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 300;
                font-size: 20px;
                line-height: 23px;
                color: #000000;
                margin-top: 30px;
            }
        }
    }
</style>