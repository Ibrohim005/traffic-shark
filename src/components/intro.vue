<template>
    <div class="intro">
        <div class="container">
            <Particles
                class="particles"
                id="tsparticles"
                :particlesInit="particlesInit"
                :particlesLoaded="particlesLoaded"
                :options="option"
        />
            <h1 class="intro__title">
                Мобильная партнерская сеть
            </h1>
            <p class="intro__text">
                Только рабочие офферы от прямых рекламодателей
            </p>
            <div class="intro-cards d-flex align-items-center">
                <div class="intro-card">
                    <h3 class="intro-card__title">
                        300+
                    </h3>
                    <p class="intro-card__text">
                        офферов по всему миру
                    </p>
                </div>
                <div class="intro-card">
                    <h3 class="intro-card__title">
                        70+
                    </h3>
                    <p class="intro-card__text">
                        активных рекламодателей
                    </p>
                </div>
                <div class="intro-card">
                    <h3 class="intro-card__title">
                        6 лет
                    </h3>
                    <p class="intro-card__text">
                        в аффилейт маркетинге
                    </p>
                </div>
                <div class="intro-card intro-card-last-child">
                    <h3 class="intro-card__title">
                        10.000+
                    </h3>
                    <p class="intro-card__text">
                        конверсий в день
                    </p>
                </div>
            </div>
            <div class="intro-details d-flex align-items-center">
                <div class="intro-detail">
                    <p class="intro-detail__text">
                        Я пользователь соцсетей, блогер, владелец сайта или арбитражник и хочу сотрудничать с топовыми мировыми брендами.
                    </p>
                    <button class="button button_blue">веб-мастерам
                        <span class="button__icon">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0)">
                                <path d="M10.553 19.7709L10.5538 19.7702L14.6163 15.688C14.9206 15.3821 14.9195 14.8875 14.6136 14.5831C14.3078 14.2787 13.8131 14.2799 13.5088 14.5857L10.7813 17.3265L10.7813 0.78125C10.7813 0.349765 10.4315 -1.92866e-07 10 -2.11727e-07C9.56852 -2.30588e-07 9.21875 0.349765 9.21875 0.78125L9.21875 17.3264L6.49125 14.5857C6.18688 14.2799 5.69223 14.2787 5.38641 14.5831C5.08051 14.8875 5.07945 15.3822 5.38375 15.688L9.44625 19.7702L9.44699 19.7709C9.75238 20.0769 10.2486 20.0759 10.553 19.7709Z" fill="white"/>
                                </g>
                                <defs>
                                <clipPath id="clip0">
                                <rect width="20" height="20" fill="white" transform="translate(20) rotate(90)"/>
                                </clipPath>
                                </defs>
                            </svg>
                        </span>
                    </button>
                </div>
                <div class="intro-detail">
                    <p class="intro-detail__text">
                        Я владелец компании или маркетолог и хочу привлечь новых клиентов и увеличить продажи с помощью онлайн-рекламы.
                    </p>
                    <button class="button button_green">рекламодателю
                        <span class="button__icon">
                            <svg width="20" height="10" viewBox="0 0 20 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M19.7709 4.44699C19.7706 4.44676 19.7704 4.44648 19.7702 4.44625L15.688 0.383747C15.3821 0.0794115 14.8875 0.0805441 14.5831 0.386403C14.2787 0.692224 14.2799 1.18687 14.5857 1.49125L17.3265 4.21875H0.78125C0.349766 4.21875 0 4.56851 0 5C0 5.43148 0.349766 5.78125 0.78125 5.78125H17.3264L14.5857 8.50875C14.2799 8.81312 14.2788 9.30777 14.5831 9.61359C14.8875 9.91949 15.3822 9.92054 15.688 9.61625L19.7702 5.55375C19.7704 5.55351 19.7706 5.55324 19.7709 5.55301C20.0769 5.24762 20.0759 4.75137 19.7709 4.44699Z" fill="white"/>
                            </svg>
                        </span>
                    </button>
                </div>
            </div>
        </div>
    </div>
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
    .particles{
        position:absolute;
        top: 0;
        width: 100%;
        height: 100%;
        left: 0;
    }
    .intro{
        position: relative;
        background-image: url('../assets/up_bg.png');
        text-align: center;
        padding: 171px 0 80px;
        &__title{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 900;
            font-size: 60px;
            line-height: 75px;
            text-transform: uppercase;
           color: #FFFFFF;
        }
        &__text{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: #FFFFFF;
        }
        &-cards{
            margin-top: 100px;
        }
        &-card{
            width: 100%;
            padding: 31px 0 51px;
            border-right: 2px solid rgba(255, 255, 255, 0.25);
            &-last-child{
                border-right: none !important;
            }
            &__title{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 800;
                font-size: 40px;
                line-height: 49px;
                color: #FFFFFF;
            }
            &__text{
                font-style: normal;
                font-weight: 500;
                font-size: 16px;
                line-height: 19px;
                color: #FFFFFF;
            }
        }
        &-details{
            background: #FFFFFF;
            border-radius: 8px;
            box-shadow: 0px 20px 80px rgba(0, 0, 0, 0.08);
            .intro-detail{
                padding: 58px 50px;
                &:first-child{
                border-right: 2px solid #F3F3F3;
                }
                &__text{
                    font-family: Gilroy;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 16px;
                    line-height: 24px;
                    color: #000000;
                    margin-bottom: 32px;
                }
            }
        }
    }
    @media(max-width: 992px){
        .intro{
            &-details{
                flex-wrap: wrap;
            }
            &-detail:first-child{
                border-right: none !important;
                border-bottom: 1px solid #F3F3F3;
            }
            &-cards{
                flex-wrap: wrap;
            }
            &-card{
                flex-basis: 50%;
                border-right: none;
                &:first-child{
                    border-right: 2px  solid rgba(255, 255, 255, 0.25) !important;
                    border-bottom: 2px  solid rgba(255, 255, 255, 0.25) !important;
                }
                &:last-child{
                    border-left: 2px  solid rgba(255, 255, 255, 0.25) !important;
                    border-top: 2px  solid rgba(255, 255, 255, 0.25) !important;
                }
            }
        }
    }
    @media screen and (max-width: 475px){
        .intro{  
            padding: 32px 0;
            &__title{
                font-weight: 900;
                font-size: 32px;
                line-height: 40px;
                margin-bottom: 10px;
                text-transform: uppercase;
            }
            &__text{
                margin-bottom: 32px;
                font-weight: 500;
                font-size: 16px;
                line-height: 19px;
                color: #FFFFFF;
            }
            &-detail{
                padding: 20px 16px !important;
                &__text{
                    font-size: 13px !important;
                    line-height: 20px !important;
                    margin-bottom: 16px !important;
                }
            }
        }
    }
</style>