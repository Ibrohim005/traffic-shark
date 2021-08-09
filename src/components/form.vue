<template>
    <form class="form">
        <div class="container">
            <Particles
                class="particles"
                id="tsparticles"
                :particlesInit="particlesInit"
                :particlesLoaded="particlesLoaded"
                :options="option"
        />
            <h3 class="form__title">
                Остались вопросы? Готовы ответить!
            </h3>
            <div class="row">
                <div class="col-md-8 col-12 offset-md-2">
                    <input type="text" class="form__input" placeholder="Ваше имя">
                    <input type="text" class="form__input" placeholder="Ваши контакты">
                    <input type="text" class="form__input" placeholder="Ваше предложение">
                    <button class="button">
                        написать нам
                    </button>
                </div>
            </div>
        </div>
    </form>
</template>

<script>

export default{
    name:'Intro',
    data (){
        return{
        option : {
            background: {
            color: {
                value: ''
            }
            },
            fpsLimit: 60,
            interactivity: {
            detectsOn: 'canvas',
            events: {
                onClick: {
                enable: true,
                mode: 'push'
                },
                onHover: {
                enable: true,
                mode: 'repulse'
                },
                resize: true
            },
            modes: {
                bubble: {
                distance: 400,
                duration: 2,
                opacity: 0.8,
                size: 40
                },
                push: {
                quantity: 4
                },
                repulse: {
                distance: 200,
                duration: 0.4
                }
            }
            },
            particles: {
            color: {
                value: '#ffffff'
            },
            links: {
                color: '#ffffff',
                distance: 150,
                enable: true,
                opacity: 0.5,
                width: 1
            },
            collisions: {
                enable: true
            },
            move: {
                direction: 'none',
                enable: true,
                outMode: 'bounce',
                random: false,
                speed: 6,
                straight: false
            },
            number: {
                density: {
                enable: true,
                value_area: 800
                },
                value: 80
            },
            opacity: {
                value: 0.5
            },
            shape: {
                type: 'circle'
            },
            size: {
                random: true,
                value: 5
            }
            },
            detectRetina: true
        }
        }
    }
}
</script>

<style lang="scss" scoped>
    .form{
        text-align: center;
        background: linear-gradient(195.2deg, #2E9ADB 10.68%, #55B570 89.32%);
        padding: 215px 0 70px;
        width: 100%;
        position: relative;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 30px;
            line-height: 37px;
            color: #FFFFFF;
            margin-bottom: 40px;
        }
        &__input{
            background: #FFFFFF;
            border-radius: 40px;
            padding: 28px 30px;
            width: 100%;
            border: none;
            outline: none;
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: rgb(126, 126, 126);
            margin-bottom: 20px;
        &::placeholder{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: rgba(126, 126, 126, 0.5);
            }
        }
    }
    .particles{
        position: absolute;
        top: 0;
        left: 0;
        z-index: 12;
    }
    @media screen and (max-width: 768){
        .button{
            width: 100% !important;
        }
    }
</style>